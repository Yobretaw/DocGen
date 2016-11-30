```csharp
namespace ProductsApp.Controllers
{
    public class ProductsController : ApiController
    {
        Product[] products = new Product[] 
        { 
            new Product { Id = 1, Name = "Tomato Soup", Category = "Groceries", Price = 1 }, 
            new Product { Id = 2, Name = "Yo-yo", Category = "Toys", Price = 3.75 }, 
            new Product { Id = 3, Name = "Hammer", Category = "Hardware", Price = 16.99 } 
        };

        public IHttpActionResult GetProduct(int id)
        {
            var product = products.FirstOrDefault((p) => p.Id == id);
            if (product == null)
            {
                return NotFound();
            }
            return Ok(product);
        }
        
        public IEnumerable<Product> GetAllProducts()
        {
            return products;
        }
    }
}
```


```csharp
namespace ProductsApp.Models
{
    public class Product
    {
        public int Id { get; set; }
        public string Name { get; set; }
        public string Category { get; set; }
        public decimal Price { get; set; }
    }
}
```

```csharp
namespace ProductsApp
{
    public static class WebApiConfig
    {
        public static void Register(HttpConfiguration config)
        {
            // Web API routes
            config.MapHttpAttributeRoutes();
            config.Routes.MapHttpRoute(
                name: "DefaultApi",
                routeTemplate: "api/{controller}/{id}",
                defaults: new { id = RouteParameter.Optional }
            );
        }
    }
}
```



```csharp
namespace Fabric.ResourceProvider.NetworkingService.Controllers
{
    public class LogicalSubnetResourceController : ApiController
    {
        public IHttpActionResult GetLogicalSubnet(string logicSubnetName)
        {
            ...
        }
    }
}
```


```powershell
PS C:\> Import-Module AzureStackFabricResourceProvider.psm1
PS C:\> Get-LogicalSubnet -LogicalSubnetName "f8f67956-3906-4303-94c5-09cf91e7e311"

Id         : /subscriptions/B6940E9A-5969-41EC-B6B1-C3575D19F067/resourceGroups/s
             ystem/providers/Microsoft.Fabric.Admin/fabricLocations/local/logical
             Networks/f8f67956-3906-4303-94c5-09cf91e7e311
Name       : f8f67956-3906-4303-94c5-09cf91e7e311
Type       : Microsoft.Fabric.Admin/fabricLocations/logicalNetworks
Location   : local
Tags       : {}
Properties : Microsoft.AzureStack.FabricResourceProvider.ClientModel.LogicalNetwo
             rk

```


```csharp
var networkingServiceHost = new ServiceHost<NetworkingService<InProcDependencySet>>(config, baseUrl);

/* Start server */
Task.Run(async() => await networkingServiceHost.Start()).Wait();

/* Extract HttpConfiguration via reflection */
var httpConfig = networkingServiceHost
    .GetPrivateField("serviceLifecycle")
    .GetPrivateField("host")
    .GetProperty<HttpConfiguration>("HttpConfiguration");

/* Call SwaggerGen to generate Swagger spec */
var swaggerSpec = new SwaggerGen(httpConfig).GenerateSwagger();
...
```

```csharp
public static void Register(HttpConfiguration config)
{
    config.MapHttpAttributeRoutes();
    config.Routes.MapHttpRoute(
        name: "DefaultApi",
        routeTemplate: "api/{controller}/{id}",
        defaults: new { id = RouteParameter.Optional }
    );
    
    ...
    
    var swaggerSpec = new SwaggerGen(config).GenerateSwagger();
    ...
}
```


```csharp
    public class NetworkingServiceSetup
    {
        public NetworkingServiceSetup(HttpConfiguration config)
        {
            // Configure the formatters so we don't output XML
            config.Formatters.ConfigureDefaultResourceProviderFormatters();
            
            ...
            
            /* Call SwaggerGen */
            `**`var swaggerSpec = new SwaggerGen(config).GenerateSwagger();`**`
            ...
        }
    }
```


```csharp
public class LogicalSubnetResourceController : ApiController
{
    public IHttpActionResult GetLogicalSubnet(string logicSubnetName)
    {
        ...
    }
}

public class LogicalSubnetResourceController : ApiController
{
    [ResponseType(typeof(LogicalSubnet))]
    public IHttpActionResult GetLogicalSubnet(string logicSubnetName)
    {
        ...
    }
}
```

```json
{
  "swagger": "2.0",
  "info": { "title": "ProductAPI" },
  "host": "localhost:9000",
  "schemes": [ "http" ],
  "paths": {
    "/api/product/{id}": {
      "get": {
        "tags": [ "Product" ],
        "operationId": "Product_GetProduct",
        "consumes": [],
        "produces": [ "application/json" ],
        "parameters": [
          {
            "name": "id",
            "in": "path",
            "required": true,
            "type": "string"
          }
        ],
        "responses": {
          "200": {
            "description": "OK",
            "schema": {
              "ref": "#/definitions/Product"
            }
          }
        }
      }
    }
  },
  "definitions": {
    "Product": {
      "type": "object",
      "properties": {
        "Id":       { "type": "integer" },
        "Name":     { "type": "string"  },
        "Category": { "type": "string"  },
        "Price":    { "type": "number"  }
      }
    }
  }
}

```

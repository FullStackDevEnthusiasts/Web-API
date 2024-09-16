### API Documentation  
51. **How do you document a Web API using Swagger?**  
   - Use `Swashbuckle` NuGet package to generate Swagger docs.
   - Automatically generates API documentation from code.
   - Provides an interactive UI to test API endpoints.
   - Customize descriptions, response types, and examples.

52. **What are the benefits of API documentation?**  
   - Improves understanding for developers using the API.
   - Provides clear instructions on how to use each endpoint.
   - Allows for easier maintenance and updates.
   - Facilitates automated testing with interactive tools like Swagger.

53. **How can you customize Swagger UI in ASP.NET Core?**  
   - Modify Swagger options in the `Startup.cs` or `Program.cs`.
   - Add custom themes, logos, and colors to match branding.
   - Include more detailed descriptions, XML comments, and examples.
   - Define custom operation filters to modify behavior.

54. **What is OpenAPI, and how does it relate to Swagger?**  
   - OpenAPI is a specification for describing REST APIs.
   - Swagger is a toolset for generating OpenAPI documentation.
   - OpenAPI defines how API endpoints should behave and be documented.
   - Swagger implements the specification, making it easier to create docs.

55. **How do you version API documentation?**  
   - Create separate Swagger docs for each API version.
   - Use `SwaggerDoc` method to specify versioned routes.
   - Maintain backward compatibility by serving multiple versions.
   - Clearly indicate deprecations and updates in the documentation.

### Advanced Topics  
56. **What is middleware, and how do you create custom middleware?**  
   - Middleware are components that handle HTTP requests and responses.
   - Custom middleware can be created by implementing `RequestDelegate`.
   - Add logic for tasks like logging, authentication, or request validation.
   - Register middleware in the `Configure` method using `app.Use`.

57. **Explain the concept of API gateways.**  
   - API gateways act as a single entry point for multiple services.
   - They handle routing, rate limiting, security, and load balancing.
   - Examples include Ocelot and Azure API Management.
   - Useful in microservices architecture to simplify client interactions.

58. **How do you manage state in a stateless Web API?**  
   - Use session tokens, cookies, or JWT to maintain user sessions.
   - Store state in databases, caches (Redis), or external systems.
   - Web APIs should remain stateless; state management should be external.
   - Stateless APIs scale better and are easier to maintain.

59. **What are background services in ASP.NET Core?**  
   - Services that run asynchronously in the background of an application.
   - Use `IHostedService` or `BackgroundService` to implement them.
   - Ideal for tasks like sending emails or processing data.
   - Register in `Program.cs` to start them when the application runs.

60. **How do you implement health checks in a Web API?**  
   - Use the `Microsoft.Extensions.Diagnostics.HealthChecks` package.
   - Configure endpoints to report the health status of services.
   - Use built-in checks for database connections, external services, etc.
   - Health checks are useful for monitoring and auto-scaling in production.

### Design Patterns  
61. **What design patterns are commonly used in .NET applications?**  
   - **Singleton:** Ensures only one instance of a service is created.
   - **Repository:** Abstracts database logic, improving testability.
   - **Factory:** Creates objects without exposing instantiation logic.
   - **Dependency Injection:** Decouples components by injecting dependencies.

62. **Explain the Repository pattern in the context of EF Core.**  
   - The Repository pattern abstracts data access logic.
   - Encapsulates EF Core DbContext logic in a separate class.
   - Improves maintainability and testability of data access code.
   - Example: `IRepository<T>` interface with methods like `GetAll`, `Add`.

63. **How does the Unit of Work pattern work?**  
   - Manages multiple database operations as a single transaction.
   - Coordinates the work of multiple repositories.
   - Ensures data consistency by committing or rolling back changes.
   - Example: Using a single `DbContext` instance to manage all operations.

64. **What is the CQRS pattern?**  
   - **Command Query Responsibility Segregation** separates reads and writes.
   - Queries only retrieve data, while commands modify state.
   - Helps optimize performance by scaling reads and writes independently.
   - Commonly used in microservices and event-driven architectures.

65. **How do you apply the Dependency Injection pattern?**  
   - Register services in the `IServiceCollection` in `Program.cs`.
   - Inject dependencies through constructors or methods.
   - Promotes loose coupling and better testability.
   - Example: `public MyController(IMyService service)` injects `IMyService`.

Next set when you're ready!
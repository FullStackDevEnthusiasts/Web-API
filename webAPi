Here are 20 questions with concise, bullet-point answers:

### General .NET Core Questions
1. **What is .NET 6, and what are its key features?**
   - Cross-platform.
   - Unified development model.
   - Performance optimizations.
   - Minimal APIs support.

2. **Explain the differences between .NET Core and .NET Framework.**
   - .NET Core is cross-platform, .NET Framework is Windows-only.
   - .NET Core is modular.
   - Improved performance in .NET Core.
   - .NET Core supports modern workloads (cloud, IoT).

3. **What is the purpose of the `Program.cs` and `Startup.cs` in .NET 6?**
   - `Program.cs` integrates Startup functionality.
   - Simplified startup configuration.
   - Supports minimal APIs.
   - Entry point for application configuration.

4. **How does dependency injection work in .NET 6?**
   - Built-in DI container.
   - Register services in `IServiceCollection`.
   - Resolve dependencies via constructors.
   - Supports transient, scoped, and singleton lifetimes.

### ASP.NET Core Web API
5. **What is a Web API, and how does it differ from a web application?**
   - API exposes data/services over HTTP.
   - Stateless communication.
   - No UI, unlike web apps.
   - Often used for integration with other systems.

6. **How do you create a RESTful API using ASP.NET Core?**
   - Use controllers with `[ApiController]`.
   - Map routes to actions.
   - Use HTTP verbs (GET, POST, etc.).
   - Return JSON data.

7. **What are HTTP verbs, and how are they used in Web APIs?**
   - GET: retrieve data.
   - POST: create data.
   - PUT: update data.
   - DELETE: remove data.

8. **How can you implement versioning in a Web API?**
   - Use URL versioning (`/api/v1/`).
   - Query string versioning.
   - Header-based versioning.
   - Use `ApiVersion` attribute.

### Entity Framework Core
9. **What is Entity Framework Core, and how does it differ from EF 6?**
   - Cross-platform, EF 6 is Windows-only.
   - EF Core is lightweight.
   - Improved performance.
   - Supports migrations and LINQ.

10. **Explain the Code First and Database First approaches in EF Core.**
    - Code First: model classes to DB schema.
    - Database First: DB schema to model classes.
    - Code First is more flexible for changes.
    - Use migrations for schema updates.

11. **What are DbContext and DbSet in EF Core?**
    - `DbContext`: database session handler.
    - `DbSet`: represents a collection of entities.
    - Query, add, update, delete data.
    - Tied to the database lifecycle.

12. **How do you handle relationships in EF Core?**
    - One-to-one: foreign key in dependent table.
    - One-to-many: foreign key on the "many" side.
    - Many-to-many: join table.
    - Configure using `Fluent API` or `Data Annotations`.

### Security
13. **How do you secure a Web API using JWT authentication?**
    - Validate JWT tokens on API requests.
    - Use middleware for token validation.
    - Store user claims in JWT.
    - Sign tokens with secret keys.

14. **What is claims-based authorization?**
    - Users have claims that define permissions.
    - Claims represent user data (e.g., roles).
    - Policies enforce claims-based access.
    - Used with JWT and OAuth.

15. **How do you protect sensitive data in a Web API?**
    - Use HTTPS.
    - Encrypt sensitive data.
    - Secure appsettings with user secrets.
    - Apply input validation.

16. **What are the best practices for securing a Web API?**
    - Use HTTPS always.
    - Implement authentication/authorization.
    - Validate inputs against injections.
    - Enable CORS properly.

### Testing
17. **How do you unit test a Web API in .NET 6?**
    - Use `xUnit` or `NUnit`.
    - Mock dependencies using `Moq`.
    - Test controller actions.
    - Validate HTTP status codes and responses.

18. **What is the role of mocking in testing?**
    - Simulate external dependencies.
    - Isolate system behavior.
    - Create fake data for tests.
    - Use libraries like `Moq`.

### Performance
19. **What are some techniques to improve the performance of a Web API?**
    - Implement caching.
    - Use response compression.
    - Optimize database queries.
    - Leverage async/await for non-blocking I/O.

20. **How do you implement caching in ASP.NET Core?**
    - Use in-memory cache (`IMemoryCache`).
    - Response caching for static content.
    - Redis for distributed caching.
    - Cache API responses based on request.
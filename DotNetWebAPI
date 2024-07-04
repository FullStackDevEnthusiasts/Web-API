1. How does the ASP.NET application respond when a user requests a URL from a browser?
   - The request is routed to the appropriate controller.
   - The controller processes the request and interacts with the model.
   - The controller returns a view or data (for API) to the user.

2. Can you explain attribute routing?
   - Uses attributes to define routes directly on controller actions.
   - Provides more control over URIs.
   - Example: `[Route("api/products/{id}")]`.

3. Can you explain the steps to implement web API versioning?
   - Use URL path versioning (`/api/v1/products`).
   - Query string versioning (`/api/products?version=1`).
   - Header versioning (custom header like `api-version: 1.0`).
   - Media type versioning (accept header like `application/vnd.myapi.v1+json`).

4. How do you consume an external API/test API in an MVC application?
   - Use `HttpClient` to make API calls.
   - Configure the API endpoint and necessary headers.
   - Handle responses and errors appropriately.
   - Use dependency injection for `HttpClient`.

5. Have you worked with action filters in ASP.NET Web API, and if so, how do you handle error exceptions, caching, and custom filters?
   - Yes, action filters can handle cross-cutting concerns.
   - For error exceptions: Use `ExceptionFilterAttribute` for global exception handling.
   - For caching: Implement custom caching logic in `ActionFilterAttribute`.
   - For custom filters: Create custom attributes inheriting from `ActionFilterAttribute`.

6. Can you explain what action filters are used for in ASP.NET Web API?
   - Execute code before or after action methods.
   - Handle cross-cutting concerns like logging, caching, and error handling.
   - Customizable for specific actions or controllers.

7. How do you handle exceptions and caching in ASP.NET Web API using action filters?
   - Exceptions: Implement `ExceptionFilterAttribute` to catch and handle exceptions globally.
   - Caching: Use `OutputCacheAttribute` for caching responses or create custom caching logic in `ActionFilterAttribute`.

8. Describe some best practices for writing stored procedures in SQL Server, especially regarding subqueries and cursors.
   - Avoid using cursors; use set-based operations instead.
   - Use indexed views or temporary tables for complex subqueries.
   - Parameterize queries to prevent SQL injection.
   - Optimize for performance with proper indexing and query planning.
   - Keep procedures modular and maintainable.

9. How would you handle authentication and authorization in a web application consuming APIs?
   - Use OAuth or OpenID Connect for authentication.
   - Implement token-based authentication (JWT).
   - Use role-based or policy-based authorization.
   - Secure API endpoints with proper authentication and authorization.

10. Have you worked with API OpenID Connect?
    - Yes, used for handling authentication and authorization.
    - Integrates with identity providers for secure login.
    - Supports token issuance for accessing APIs.

11. What types of APIs have you worked with, particularly in setting them up for third-party interactions?
    - RESTful APIs using HTTP/HTTPS.
    - SOAP-based services with WSDL.
    - Implemented OAuth for third-party integrations.
    - Designed and documented APIs for external consumption.

12. How would you ensure application performance, both at the database level and application level?
    - Database level: Optimize queries, use indexing, and avoid unnecessary joins.
    - Application level: Implement caching, use asynchronous programming, and minimize server round-trips.
    - Monitor performance using tools like SQL Profiler and Application Insights.
    - Perform load testing and optimize based on results.

13. Can you discuss your experience with RESTful services?
    - Designed and implemented RESTful APIs.
    - Followed REST principles: statelessness, resource-based URIs, and proper use of HTTP methods.
    - Implemented error handling, versioning, and documentation.
    - Consumed RESTful APIs using `HttpClient` and handled responses.

14. How do you handle global exception handling in your applications?
    - Implement a global exception filter (`ExceptionFilterAttribute`).
    - Use middleware in ASP.NET Core for centralized exception handling.
    - Log exceptions using logging frameworks (e.g., Serilog, NLog).
    - Provide user-friendly error messages and proper status codes.

15. How do you implement rate limiting in a Web API?
    - Use middleware to track request counts per client.
    - Implement rate limiting policies (e.g., requests per minute).
    - Return appropriate status codes (e.g., 429 Too Many Requests).
    - Use third-party libraries like `AspNetCoreRateLimit`.

16. Can you explain the differences between RESTful and SOAP-based services?
    - RESTful: Uses HTTP, lightweight, resource-based URIs, JSON/XML payloads.
    - SOAP: Protocol-based, uses XML, supports WS-* standards, more rigid structure.
    - REST is more flexible and widely used for web services.
    - SOAP offers built-in error handling and standardized security.

17. How do you secure a Web API?
    - Implement HTTPS to encrypt data.
    - Use OAuth2 or OpenID Connect for authentication.
    - Implement token-based authentication (JWT).
    - Validate input to prevent injection attacks.
    - Use API gateways for additional security layers.

18. What are the benefits and drawbacks of using API Gateways?
    - Benefits: Centralized management, security, rate limiting, load balancing, analytics.
    - Drawbacks: Adds complexity, single point of failure, potential performance bottleneck.
    - Useful for managing microservices architecture.

19. Can you explain the concept of middleware in ASP.NET Core?
    - Middleware: Software components that process HTTP requests/responses.
    - Used for logging, authentication, exception handling, and more.
    - Configured in the request pipeline.
    - Can be custom or built-in.

20. How do you handle large file uploads in a Web API?
    - Configure maximum request size in settings.
    - Use streaming to handle large files.
    - Implement chunked uploads for better reliability.
    - Validate file types and sizes for security.

21. How do you document a Web API, and what tools do you use?
    - Use tools like Swagger/OpenAPI for automatic documentation.
    - Annotate API methods with XML comments.
    - Provide examples and usage instructions.
    - Generate interactive API documentation.

22. How do you test Web APIs, and what tools do you prefer for automated testing?
    - Use Postman or Insomnia for manual testing.
    - Implement unit tests with frameworks like xUnit or NUnit.
    - Use tools like RestSharp for integration testing.
    - Implement continuous testing with CI/CD pipelines.

23. Can you explain the CORS policy and how to configure it in a Web API?
    - CORS: Cross-Origin Resource Sharing, controls resource access from different origins.
    - Configure CORS in middleware to allow specific origins, methods, and headers.
    - Use `[EnableCors]` attribute for specific controllers or actions.
    - Ensure security by limiting allowed origins.

24. How do you handle versioning in a RESTful API?
    - Use URL path versioning (`/api/v1/resource`).
    - Implement query string versioning (`?version=1`).
    - Use header versioning (`api-version: 1.0`).
    - Maintain backward compatibility.

25. How do you manage API throttling and rate limiting in a high-traffic application?
    - Implement middleware to track request counts.
    - Use distributed caches like Redis to store rate limiting data.
    - Apply rate limiting policies to ensure fair usage.
    - Monitor and adjust limits based on application performance.

26. **How do you document a Web API, and what tools do you use?**
    - Use tools like Swagger/OpenAPI for automatic documentation.
    - Annotate API methods with XML comments.
    - Provide examples and usage instructions.
    - Generate interactive API documentation.

27. **How do you test Web APIs, and what tools do you prefer for automated testing?**
    - Use Postman or Insomnia for manual testing.
    - Implement unit tests with frameworks like xUnit or NUnit.
    - Use tools like RestSharp for integration testing.
    - Implement continuous testing with CI/CD pipelines.

28. **Can you explain the CORS policy and how to configure it in a Web API?**
    - CORS: Cross-Origin Resource Sharing, controls resource access from different origins.
    - Configure CORS in middleware to allow specific origins, methods, and headers.
    - Use `[EnableCors]` attribute for specific controllers or actions.
    - Ensure security by limiting allowed origins.

29. **How do you handle versioning in a RESTful API?**
    - Use URL path versioning (`/api/v1/resource`).
    - Implement query string versioning (`?version=1`).
    - Use header versioning (`api-version: 1.0`).
    - Maintain backward compatibility.

30. **How do you manage API throttling and rate limiting in a high-traffic application?**
    - Implement middleware to track request counts.
    - Use distributed caches like Redis to store rate limiting data.
    - Apply rate limiting policies to ensure fair usage.
    - Monitor and adjust limits based on application performance.

31. **How do you handle authentication and authorization in a web application consuming APIs?**
    - Use OAuth or OpenID Connect for authentication.
    - Implement token-based authentication (JWT).
    - Use role-based or policy-based authorization.
    - Secure API endpoints with proper authentication and authorization.

32. **Have you worked with API OpenID Connect?**
    - Yes, used for handling authentication and authorization.
    - Integrates with identity providers for secure login.
    - Supports token issuance for accessing APIs.

33. **What types of APIs have you worked with, particularly in setting them up for third-party interactions?**
    - RESTful APIs using HTTP/HTTPS.
    - SOAP-based services with WSDL.
    - Implemented OAuth for third-party integrations.
    - Designed and documented APIs for external consumption.

34. **How would you ensure application performance, both at the database level and application level?**
    - Database level: Optimize queries, use indexing, and avoid unnecessary joins.
    - Application level: Implement caching, use asynchronous programming, and minimize server round-trips.
    - Monitor performance using tools like SQL Profiler and Application Insights.
    - Perform load testing and optimize based on results.

35. **Can you discuss your experience with RESTful services?**
    - Designed and implemented RESTful APIs.
    - Followed REST principles: statelessness, resource-based URIs, and proper use of HTTP methods.
    - Implemented error handling, versioning, and documentation.
    - Consumed RESTful APIs using `HttpClient` and handled responses.

36. **How do you handle global exception handling in your applications?**
    - Implement a global exception filter (`ExceptionFilterAttribute`).
    - Use middleware in ASP.NET Core for centralized exception handling.
    - Log exceptions using logging frameworks (e.g., Serilog, NLog).
    - Provide user-friendly error messages and proper status codes.

37. **Describe some best practices for writing stored procedures in SQL Server, especially regarding subqueries and cursors.**
    - Avoid using cursors; use set-based operations instead.
    - Use indexed views or temporary tables for complex subqueries.
    - Parameterize queries to prevent SQL injection.
    - Optimize for performance with proper indexing and query planning.
    - Keep procedures modular and maintainable.

38. **How do you consume an external API/test API in an MVC application?**
    - Use `HttpClient` to make API calls.
    - Configure the API endpoint and necessary headers.
    - Handle responses and errors appropriately.
    - Use dependency injection for `HttpClient`.

39. **Have you worked with action filters in ASP.NET Web API, and if so, how do you handle error exceptions, caching, and custom filters?**
    - Yes, action filters can handle cross-cutting concerns.
    - For error exceptions: Use `ExceptionFilterAttribute` for global exception handling.
    - For caching: Implement custom caching logic in `ActionFilterAttribute`.
    - For custom filters: Create custom attributes inheriting from `ActionFilterAttribute`.

40. **Can you explain what action filters are used for in ASP.NET Web API?**
    - Execute code before or after action methods.
    - Handle cross-cutting concerns like logging, caching, and error handling.
    - Customizable for specific actions or controllers.

41. **How do you handle exceptions and caching in ASP.NET Web API using action filters?**
    - Exceptions: Implement `ExceptionFilterAttribute` to catch and handle exceptions globally.
    - Caching: Use `OutputCacheAttribute` for caching responses or create custom caching logic in `ActionFilterAttribute`.

42. **How do you implement middleware in ASP.NET Core?**
    - Middleware components are added in the `Startup` class.
    - Use `app.UseMiddleware<YourMiddleware>()` to add custom middleware.
    - Middleware can handle requests, responses, or both.
    - Order of middleware matters; it processes requests in the order they are added.

43. **How do you implement rate limiting in ASP.NET Core?**
    - Use middleware to track request counts per client.
    - Implement rate limiting policies (e.g., requests per minute).
    - Return appropriate status codes (e.g., 429 Too Many Requests).
    - Use third-party libraries like `AspNetCoreRateLimit`.

44. **How do you handle large file uploads in ASP.NET Core?**
    - Configure maximum request size in `Startup` class.
    - Use streaming to handle large files.
    - Implement chunked uploads for better reliability.
    - Validate file types and sizes for security.

45. **How do you document an ASP.NET Core Web API, and what tools do you use?**
    - Use Swagger/OpenAPI for automatic documentation.
    - Annotate API methods with XML comments.
    - Provide examples and usage instructions.
    - Generate interactive API documentation.

46. **How do you test an ASP.NET Core Web API, and what tools do you prefer for automated testing?**
    - Use Postman or Insomnia for manual testing.
    - Implement unit tests with frameworks like xUnit or NUnit.
    - Use tools like RestSharp for integration testing.
    - Implement continuous testing with CI/CD pipelines.

47. **Can you explain the CORS policy in ASP.NET Core and how to configure it?**
    - CORS: Cross-Origin Resource Sharing, controls resource access from different origins.
    - Configure CORS in middleware to allow specific origins, methods, and headers.
    - Use `[EnableCors]` attribute for specific controllers or actions.
    - Ensure security by limiting allowed origins.

48. **How do you handle versioning in an ASP.NET Core Web API?**
    - Use URL path versioning (`/api/v1/resource`).
    - Implement query string versioning (`?version=1`).
    - Use header versioning (`api-version: 1.0`).
    - Maintain backward compatibility.

49. **How do you manage API throttling and rate limiting in ASP.NET Core for a high-traffic application?**
    - Implement middleware to track request counts.
    - Use distributed caches like Redis to store rate limiting data.
    - Apply rate limiting policies to ensure fair usage.
    - Monitor and adjust limits based on application performance.

50. **How do you secure an ASP.NET Core Web API?**
    - Implement HTTPS to encrypt data.
    - Use OAuth2 or OpenID Connect for authentication.
    - Implement token-based authentication (JWT).
    - Validate input to prevent injection attacks.
    - Use API gateways for additional security layers.

51. **How do you handle global exception handling in ASP.NET Core?**
    - Use middleware for centralized exception handling.
    - Implement a global exception filter (`ExceptionFilterAttribute`).
    - Log exceptions using logging frameworks (e.g., Serilog, NLog).
    - Provide user-friendly error messages and proper status codes.

52. **What are the benefits and drawbacks of using API Gateways in ASP.NET Core?**
    - Benefits: Centralized management, security, rate limiting, load balancing, analytics.
    - Drawbacks: Adds complexity, single point of failure, potential performance bottleneck.
    - Useful for managing microservices architecture.

53. **Can you explain the concept of middleware in ASP.NET Core?**
    - Middleware: Software components that process HTTP requests/responses.
    - Used for logging, authentication, exception handling, and more.
    - Configured in the request pipeline.
    - Can be custom or built-in.

54. **How do you document a Web API in ASP.NET Core, and what tools do you use?**
    - Use tools like Swagger/OpenAPI for automatic documentation.
    - Annotate API methods with XML comments.
    - Provide examples and usage instructions.
    - Generate interactive API documentation.

55. **How do you test a Web API in ASP.NET Core, and what tools do you prefer for automated testing?**
    - Use Postman or Insomnia for manual testing.
    - Implement unit tests with frameworks like xUnit or NUnit.
    - Use tools like RestSharp for integration testing.
    - Implement continuous testing with CI/CD pipelines.

56. **How do you implement rate limiting in a Web API using ASP.NET Core?**
    - Use middleware to track request counts per client.
    - Implement rate limiting policies (e.g

., requests per minute).
    - Return appropriate status codes (e.g., 429 Too Many Requests).
    - Use third-party libraries like `AspNetCoreRateLimit`.

57. **How do you handle large file uploads in a Web API using ASP.NET Core?**
    - Configure maximum request size in `Startup` class.
    - Use streaming to handle large files.
    - Implement chunked uploads for better reliability.
    - Validate file types and sizes for security.

58. **How do you document a Web API using ASP.NET Core, and what tools do you use?**
    - Use Swagger/OpenAPI for automatic documentation.
    - Annotate API methods with XML comments.
    - Provide examples and usage instructions.
    - Generate interactive API documentation.

59. **How do you test a Web API using ASP.NET Core, and what tools do you prefer for automated testing?**
    - Use Postman or Insomnia for manual testing.
    - Implement unit tests with frameworks like xUnit or NUnit.
    - Use tools like RestSharp for integration testing.
    - Implement continuous testing with CI/CD pipelines.

60. **Can you explain the CORS policy in a Web API using ASP.NET Core and how to configure it?**
    - CORS: Cross-Origin Resource Sharing, controls resource access from different origins.
    - Configure CORS in middleware to allow specific origins, methods, and headers.
    - Use `[EnableCors]` attribute for specific controllers or actions.
    - Ensure security by limiting allowed origins.

61. **How do you handle versioning in a Web API using ASP.NET Core?**
    - Use URL path versioning (`/api/v1/resource`).
    - Implement query string versioning (`?version=1`).
    - Use header versioning (`api-version: 1.0`).
    - Maintain backward compatibility.

62. **How do you manage API throttling and rate limiting in a high-traffic application using ASP.NET Core?**
    - Implement middleware to track request counts.
    - Use distributed caches like Redis to store rate limiting data.
    - Apply rate limiting policies to ensure fair usage.
    - Monitor and adjust limits based on application performance.

63. **How do you secure a Web API using ASP.NET Core?**
    - Implement HTTPS to encrypt data.
    - Use OAuth2 or OpenID Connect for authentication.
    - Implement token-based authentication (JWT).
    - Validate input to prevent injection attacks.
    - Use API gateways for additional security layers.

64. **How do you handle global exception handling in a Web API using ASP.NET Core?**
    - Use middleware for centralized exception handling.
    - Implement a global exception filter (`ExceptionFilterAttribute`).
    - Log exceptions using logging frameworks (e.g., Serilog, NLog).
    - Provide user-friendly error messages and proper status codes.

65. **What are the benefits and drawbacks of using API Gateways in a Web API using ASP.NET Core?**
    - Benefits: Centralized management, security, rate limiting, load balancing, analytics.
    - Drawbacks: Adds complexity, single point of failure, potential performance bottleneck.
    - Useful for managing microservices architecture.

66. **Can you explain the concept of middleware in a Web API using ASP.NET Core?**
    - Middleware: Software components that process HTTP requests/responses.
    - Used for logging, authentication, exception handling, and more.
    - Configured in the request pipeline.
    - Can be custom or built-in.

67. **How do you document a Web API in ASP.NET Core, and what tools do you use?**
    - Use tools like Swagger/OpenAPI for automatic documentation.
    - Annotate API methods with XML comments.
    - Provide examples and usage instructions.
    - Generate interactive API documentation.

68. **How do you test a Web API in ASP.NET Core, and what tools do you prefer for automated testing?**
    - Use Postman or Insomnia for manual testing.
    - Implement unit tests with frameworks like xUnit or NUnit.
    - Use tools like RestSharp for integration testing.
    - Implement continuous testing with CI/CD pipelines.

69. **How do you implement rate limiting in a Web API using ASP.NET Core?**
    - Use middleware to track request counts per client.
    - Implement rate limiting policies (e.g., requests per minute).
    - Return appropriate status codes (e.g., 429 Too Many Requests).
    - Use third-party libraries like `AspNetCoreRateLimit`.

70. **How do you handle large file uploads in a Web API using ASP.NET Core?**
    - Configure maximum request size in `Startup` class.
    - Use streaming to handle large files.
    - Implement chunked uploads for better reliability.
    - Validate file types and sizes for security.

71. **Can you explain dependency injection in ASP.NET Core?**
    - A design pattern to achieve Inversion of Control (IoC).
    - ASP.NET Core has built-in support for dependency injection.
    - Configure services in `Startup.ConfigureServices`.
    - Inject dependencies via constructor or method injection.

72. **How do you configure logging in ASP.NET Core?**
    - Use built-in logging providers (Console, Debug, EventSource, etc.).
    - Configure logging in `appsettings.json` or `Startup.Configure`.
    - Use third-party logging libraries like Serilog or NLog.
    - Inject `ILogger` into controllers or services.

73. **What is the role of `IHostedService` in ASP.NET Core?**
    - Represents background tasks.
    - Implement `IHostedService` for long-running operations.
    - Register hosted services in `Startup.ConfigureServices`.
    - Used for tasks like processing messages, running scheduled jobs.

74. **How do you handle session state in ASP.NET Core?**
    - Configure session middleware in `Startup.Configure`.
    - Store session data in-memory, distributed cache, or database.
    - Use `ISession` interface to read and write session data.
    - Set session expiration policies.

75. **What is the purpose of the `IConfiguration` interface in ASP.NET Core?**
    - Provides access to configuration settings.
    - Supports multiple configuration sources (JSON, XML, environment variables).
    - Inject `IConfiguration` into services or controllers.
    - Use configuration sections for structured data.

76. **How do you implement localization in ASP.NET Core?**
    - Use localization middleware and services.
    - Define resource files for different languages.
    - Inject `IStringLocalizer` or `IHtmlLocalizer` for localized strings.
    - Configure supported cultures in `Startup.Configure`.

77. **What are tag helpers in ASP.NET Core MVC?**
    - Components that enable server-side code to create and render HTML elements.
    - Provide a clean and readable syntax for Razor views.
    - Built-in tag helpers for forms, links, and other HTML elements.
    - Custom tag helpers can be created by implementing `TagHelper`.

78. **How do you use ViewComponents in ASP.NET Core MVC?**
    - Small reusable components for rendering partial views.
    - Create by deriving from `ViewComponent` class.
    - Invoke in views using `@Component.InvokeAsync`.
    - Useful for encapsulating logic and markup.

79. **What is SignalR and how do you use it in ASP.NET Core?**
    - A library for adding real-time web functionality.
    - Supports WebSockets, Server-Sent Events, and Long Polling.
    - Configure SignalR in `Startup.Configure` and `Startup.ConfigureServices`.
    - Use hubs to handle client-server communication.

80. **How do you implement health checks in ASP.NET Core?**
    - Use built-in health check middleware.
    - Configure health checks in `Startup.ConfigureServices`.
    - Define custom health check logic by implementing `IHealthCheck`.
    - Expose health check endpoints for monitoring.

81. **What is Blazor and how does it fit into ASP.NET Core?**
    - A framework for building interactive web UIs using C# instead of JavaScript.
    - Two hosting models: Blazor Server and Blazor WebAssembly.
    - Integrates with ASP.NET Core for backend services.
    - Enables full-stack development with .NET.

82. **How do you manage static files in ASP.NET Core?**
    - Use static files middleware in `Startup.Configure`.
    - Serve files from `wwwroot` directory.
    - Configure caching for static files.
    - Use `FileResult` to return static files from controllers.

83. **How do you implement background tasks in ASP.NET Core?**
    - Use hosted services (`IHostedService`).
    - Use `BackgroundService` as a base class for long-running tasks.
    - Register services in `Startup.ConfigureServices`.
    - Use `Task.Delay` for periodic tasks.

84. **What is the purpose of the `IActionResult` interface in ASP.NET Core MVC?**
    - Represents the result of an action method.
    - Provides various result types (e.g., `ViewResult`, `JsonResult`, `StatusCodeResult`).
    - Enables flexible and consistent responses.
    - Simplifies testing of controller actions.

85. **How do you handle form validation in ASP.NET Core MVC?**
    - Use data annotation attributes on model properties.
    - Implement server-side validation with `ModelState`.
    - Use client-side validation with jQuery Validate.
    - Customize validation logic by implementing `IValidatableObject` or custom attributes.

86. **What are Razor Pages and how do they differ from MVC?**
    - A page-based programming model for ASP.NET Core.
    - Encapsulates model, view, and controller logic in a single file.
    - Uses `@page` directive to define page routes.
    - Simplifies development for page-focused applications.

87. **How do you use gRPC in ASP.NET Core?**
    - A high-performance RPC framework.
    - Define service contracts using `.proto` files.
    - Generate server and client code using gRPC tools.
    - Configure gRPC services in `Startup.ConfigureServices`.

88. **What is the difference between AddScoped, AddTransient, and AddSingleton in ASP.NET Core?**
    - `AddScoped`: Creates a new instance per request.
    - `AddTransient`: Creates a new instance every time it's requested.
    - `AddSingleton`: Creates a single instance for the application's lifetime.
    - Choose based on the desired lifetime and usage.

89. **How do you use `IOptions` in ASP.NET Core?**
    - Provides a way to manage configuration settings.
    - Bind configuration sections to POCO classes.
    - Inject `IOptions<T>` or `IOptionsMonitor<T>` for accessing settings.
    - Use `IOptionsSnapshot<T>` for request-scoped options.

90. **How do you configure URL rewriting and redirection in ASP.NET Core?**
    - Use URL rewriting middleware.
    - Configure rules for rewriting and redirection.
    - Use built-in `RewriteOptions` for common scenarios.
    - Custom rules can be implemented using `IRule`.

91. **How do you handle user secrets in ASP.NET Core?**
    - Use Secret Manager tool for development secrets.
    - Store secrets in a secure location, like Azure Key Vault for production.
    - Access secrets through `IConfiguration`.
    - Ensure secrets are not included in source control.

92. **What is `HttpClientFactory` and why should you use it in ASP.NET Core?**
    - A factory for creating `HttpClient` instances.
    - Provides centralized configuration and lifecycle management.
    - Avoids common issues like socket exhaustion.
    - Supports Polly for resilience and transient fault handling.

93. **How do you implement request logging in ASP.NET Core?**
    - Use middleware to log incoming requests and responses.
    - Integrate logging frameworks (Serilog, NLog).
    - Log relevant request data (headers, path, body).
    - Ensure sensitive data is not logged.

94. **How do you handle long-running requests in ASP.NET Core?**
    - Use asynchronous programming with `async` and `await`.
    - Implement background processing with hosted services.
    - Use `Task.Run` for offloading work to background threads.
    - Optimize response times with proper load balancing.

95. **What are some common security best practices for ASP.NET Core applications?**
    - Use HTTPS for all communications.
    - Validate and sanitize user inputs.
    - Implement proper authentication and authorization.
    - Regularly update and patch dependencies.
    - Use security tools for vulnerability scanning.

96. **How do you manage configuration in ASP.NET Core?**
    - Use multiple configuration sources (JSON, XML, environment variables).
    - Access configuration settings via `IConfiguration`.
    - Support different environments (Development, Staging, Production).
    - Use `Options` pattern for structured settings.

97. **What is the role of the `Configure` method in ASP.NET Core?**
    - Sets up the request processing pipeline.
    - Configure middleware components.
    - Define routes and endpoints.
    - Implement exception handling.

98. **How do you handle file uploads in ASP.NET Core?**
    - Use `IFormFile` for reading uploaded files.
    - Configure request limits for file size.
    - Save files to the server or cloud storage.
    - Validate file types and sizes for security.

99. **How do you implement caching in ASP.NET Core?**
    - Use in-memory caching for quick access.
    - Use distributed caching for scaling (Redis, SQL Server).
    - Apply caching strategies (absolute expiration, sliding expiration).
    - Implement output caching for response caching.

100. **How do you handle concurrency in ASP.NET Core?**
    - Use asynchronous programming to improve scalability.
    - Implement locking mechanisms for critical sections.
    - Use optimistic concurrency control with EF Core.
    - Handle race conditions and ensure data consistency.

101. **How do you create custom middleware in ASP.NET Core?**
    - Implement `IMiddleware` or create a middleware class with `InvokeAsync` method.
    - Register middleware in `Startup.Configure`.
    - Process requests and responses within the middleware.
    - Chain middleware components for complex processing.

102. **What is the purpose of `IApplicationBuilder` in ASP.NET Core?**
    - Used to configure the request pipeline.
    - Register middleware components.
    - Define routes and endpoints.
    - Implement application-wide settings.

103. **How do you handle cross-cutting concerns in ASP.NET Core?**
    - Use middleware for logging, authentication, error handling.
    - Implement action filters for validation, authorization.
    - Utilize dependency

 injection for service reuse.
    - Encapsulate shared logic in reusable components.

104. **How do you implement globalization and localization in ASP.NET Core?**
    - Configure localization middleware.
    - Use resource files for different languages.
    - Set up culture-specific formatting.
    - Enable dynamic language switching.

105. **How do you deploy an ASP.NET Core application to Azure?**
    - Use Azure App Service for web hosting.
    - Configure deployment settings in Azure portal.
    - Use CI/CD pipelines for automated deployments.
    - Monitor application with Azure Application Insights.

### State Management  
96. **What is the difference between session state and application state?**  
   - **Session State:** Stores user-specific data across requests for a single user session.
   - **Application State:** Stores data shared across all users and sessions.
   - Session state is typically stored in-memory or in distributed caches.
   - Application state is often static and global, such as configuration settings.

97. **How do you implement distributed caching in a Web API?**  
   - Use a distributed cache provider like **Redis** or **Memcached**.
   - Configure caching in `Startup.cs` using `services.AddStackExchangeRedisCache()` or similar.
   - Cache data with expiration policies to balance performance and freshness.
   - Example: `await _cache.SetAsync("key", data, options);`.

98. **What are the options for managing state in a stateless application?**  
   - Use **token-based authentication** (e.g., JWT) to maintain session state.
   - Store user preferences or session data in a **distributed cache**.
   - Employ **client-side storage** (e.g., cookies or local storage) for certain data.
   - Implement **state management** in frameworks (e.g., Blazor's `CircuitHandler`).

99. **How can you use Redis for caching in ASP.NET Core?**  
   - Install **StackExchange.Redis** package for Redis integration.
   - Configure Redis in `Startup.cs` with `services.AddStackExchangeRedisCache()`.
   - Use `IDistributedCache` interface for caching operations.
   - Example: `await _cache.SetStringAsync("key", "value");`.

100. **Explain the role of cookies in state management.**  
   - **Cookies** store data on the client-side, sent with each request.
   - Commonly used for **session identifiers** and user preferences.
   - **Secure** cookies are used for sensitive information, marked with `Secure` and `HttpOnly` flags.
   - Example: `Response.Cookies.Append("cookieName", "cookieValue", options);`.

### User Interface  
101. **How can you create a SPA (Single Page Application) with .NET 6?**  
   - Use frameworks like **Angular**, **React**, or **Vue.js** integrated with ASP.NET Core.
   - Serve the SPA using the `wwwroot` folder or via an external server.
   - Use `dotnet new` templates for SPA applications.
   - Example: Create a project using `dotnet new angular` or `dotnet new react`.

102. **What are Blazor components, and how do they work?**  
   - **Blazor components** are reusable UI elements in Blazor applications.
   - Components use **Razor syntax** (.razor files) to define HTML and C# logic.
   - Can be either **server-side** or **WebAssembly**-based (client-side).
   - Example: `<MyComponent />` is used in Razor pages or other components.

103. **How do you connect a .NET Web API to a front-end framework like Angular or React?**  
   - Use **HTTP client** in the front-end to make API requests.
   - Configure **CORS** in the Web API to allow requests from the front-end.
   - Define **API endpoints** in the Web API and consume them in the front-end code.
   - Example: Use `HttpClient` in Angular to call Web API endpoints.

104. **What are the benefits of using Razor Pages?**  
   - Simplified model-view-controller (MVC) pattern with page-focused coding.
   - Directly integrates HTML and C# code, improving productivity.
   - Supports routing, data binding, and validation easily.
   - Ideal for single-page scenarios or small to medium-sized web applications.

105. **How do you implement server-side rendering in ASP.NET Core?**  
   - Use **Razor Pages** or **ASP.NET Core MVC** for server-side rendering.
   - Render HTML on the server and send it to the client for faster initial load.
   - Integrate with client-side frameworks for dynamic content.
   - Example: Use `@await Html.PartialAsync("PartialViewName")` in Razor Pages.

### Localization  
106. **How do you implement localization in an ASP.NET Core application?**  
   - Use **resource files** (.resx) for storing localized strings.
   - Configure localization services in `Startup.cs` using `services.AddLocalization()`.
   - Use **IStringLocalizer** to access localized strings in controllers and views.
   - Example: `localizer["WelcomeMessage"]` retrieves the localized message.

107. **What are the advantages of using resource files for localization?**  
   - Separates text from code, simplifying localization management.
   - Supports multiple languages through different resource files.
   - Easily update localized strings without changing application logic.
   - Facilitates collaboration with translators for content updates.

108. **How can you change the culture of a Web API dynamically?**  
   - Use middleware to set the culture based on request data (e.g., headers or query parameters).
   - Configure `CultureInfo` and `RequestLocalizationOptions` in `Startup.cs`.
   - Example: Set culture with `Thread.CurrentThread.CurrentCulture = new CultureInfo("fr-FR");`.

109. **What is the role of middleware in localization?**  
   - Middleware can intercept requests and set culture based on request information.
   - Handles culture selection, applying it to the current thread or context.
   - Ensures localized content is served according to user preferences or settings.
   - Example: Use `app.UseRequestLocalization()` to apply localization settings.

110. **How do you support multiple languages in your API responses?**  
   - Include **localized strings** in API responses based on user preferences or request headers.
   - Use resource files to manage translations for different languages.
   - Implement a mechanism to detect and apply the user's language settings.
   - Example: Return `localizedResponse["greeting"]` based on the requested culture.

Next set when you're ready!
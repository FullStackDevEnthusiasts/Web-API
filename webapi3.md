### Entity Framework Core
21. **What is Entity Framework Core, and how does it differ from EF 6?**  
   - Lightweight, cross-platform ORM.
   - EF Core supports LINQ queries, migrations, etc.
   - EF Core does not support all features of EF 6 (e.g., lazy loading by default).
   - More modular and better performance.

22. **Explain the Code First and Database First approaches in EF Core.**  
   - **Code First**: Define model classes, EF generates database schema.
   - **Database First**: Generate model classes from an existing database.
   - Code First is ideal for new projects.
   - Database First fits legacy database integration.

23. **How do you create a migration in EF Core?**  
   - Use `Add-Migration` in the Package Manager Console.
   - Apply with `Update-Database`.
   - Migrations track database changes.
   - Can be reverted using `Remove-Migration`.

24. **What are DbContext and DbSet in EF Core?**  
   - `DbContext`: Main class for database interactions.
   - `DbSet<T>`: Represents a collection of entities in the context.
   - `DbContext` manages querying, saving, etc.
   - Can configure relationships and transactions.

25. **How do you handle relationships in EF Core (one-to-one, one-to-many, many-to-many)?**  
   - One-to-One: Use `HasOne` and `WithOne`.
   - One-to-Many: Use `HasOne` and `WithMany`.
   - Many-to-Many: Use `HasMany` and `WithMany`.
   - Relationships defined via navigation properties.

26. **What is lazy loading, and how do you enable it in EF Core?**  
   - Loads related data when accessed, not upfront.
   - Enabled by adding the `Microsoft.EntityFrameworkCore.Proxies` package.
   - Use `.UseLazyLoadingProxies()` in `DbContext`.
   - Improves performance by deferring data loading.

27. **How can you implement data seeding in EF Core?**  
   - Pre-populate database with initial data.
   - Use `ModelBuilder.Entity().HasData()` in `OnModelCreating`.
   - Define the data in migrations.
   - Ensures consistent data for testing/development.

28. **What are query filters in EF Core?**  
   - Global filters applied to queries.
   - Example: Soft-deletes (filtering out deleted records).
   - Define in `OnModelCreating` with `HasQueryFilter()`.
   - Automatically applies to all queries.

29. **Explain the use of asynchronous programming in EF Core.**  
   - Supports `async/await` for non-blocking operations.
   - Use methods like `SaveChangesAsync()` or `ToListAsync()`.
   - Improves scalability by releasing the thread during I/O operations.
   - Ideal for web applications with high concurrency.

30. **How do you implement transactions in EF Core?**  
   - Use `BeginTransaction()` for manual transactions.
   - Call `Commit()` or `Rollback()` based on success/failure.
   - Transactions group multiple operations.
   - Ensures data consistency.

### Security
31. **How do you implement authentication and authorization in a .NET 6 Web API?**  
   - Use `Identity` for user management.
   - JWT tokens for stateless authentication.
   - Authorization via roles/claims.
   - Secure endpoints using `[Authorize]` attribute.

32. **What is ASP.NET Core Identity, and how is it used?**  
   - Framework for user authentication and authorization.
   - Supports user registration, login, roles, and claims.
   - Integrated with JWT authentication.
   - Easily customizable for user data.

33. **Explain the role of claims-based authorization.**  
   - Claims represent user attributes.
   - Used to authorize based on user data (e.g., roles, permissions).
   - Implemented using `[Authorize(Policy = "PolicyName")]`.
   - Fine-grained control over access.

34. **How do you protect sensitive data in a Web API?**  
   - Use HTTPS for secure communication.
   - Store secrets in environment variables or Azure Key Vault.
   - Encrypt sensitive fields (e.g., passwords) using hashing.
   - Implement data protection for cookies/tokens.

35. **What are the best practices for securing a Web API?**  
   - Use HTTPS and SSL certificates.
   - Implement JWT-based authentication.
   - Validate input to prevent injection attacks.
   - Apply rate-limiting to prevent DDoS.

Let me know if you'd like more!
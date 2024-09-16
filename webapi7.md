### Cloud and Microservices  
81. **What is a microservices architecture?**  
   - Decomposes a large application into smaller, independent services.
   - Each service focuses on a single business capability.
   - Services communicate via lightweight protocols like HTTP or messaging queues.
   - Increases scalability, flexibility, and ease of deployment.

82. **How do you implement communication between microservices?**  
   - Use **HTTP-based REST APIs** for synchronous communication.
   - Use **message brokers** like RabbitMQ, Azure Service Bus for asynchronous communication.
   - Implement **gRPC** for low-latency, high-performance inter-service communication.
   - Ensure services are loosely coupled to allow independent scaling.

83. **What are the advantages of using a cloud platform for hosting .NET applications?**  
   - **Scalability:** Scale resources dynamically based on demand.
   - **Availability:** High availability with redundancy and failover options.
   - **Cost-efficiency:** Pay-as-you-go pricing models.
   - **Integrated services:** Use cloud-based databases, storage, and messaging queues.

84. **How can you manage configuration in a cloud environment?**  
   - Use **environment variables** for sensitive data.
   - Leverage **Azure App Configuration** or **AWS Parameter Store** for centralized management.
   - Use **Key Vaults** to securely store secrets and API keys.
   - Employ **config maps** in containerized applications for dynamic configurations.

85. **What role does Kubernetes play in microservices deployment?**  
   - Manages containerized applications and services.
   - Handles automatic scaling, load balancing, and service discovery.
   - Manages deployment rollouts and rollbacks.
   - Provides self-healing by restarting failed containers automatically.

### Event-Driven Architecture  
86. **What is event-driven architecture?**  
   - Services communicate through events, which trigger reactions in other services.
   - Loose coupling of services as they react to events asynchronously.
   - Event producers and consumers do not need to know each other.
   - Ideal for building scalable, distributed systems.

87. **How do you implement event sourcing in a .NET application?**  
   - Use **EventStore** or similar event storage systems.
   - Store state changes as a sequence of events rather than directly updating the database.
   - Rebuild entity state by replaying events.
   - Each event is immutable and provides a full audit trail of changes.

88. **What are message queues, and how are they used in .NET?**  
   - A **message queue** allows services to communicate asynchronously.
   - **Producers** send messages to the queue, and **consumers** process them.
   - Examples: RabbitMQ, Azure Service Bus, and Amazon SQS.
   - Useful for decoupling services and handling spikes in traffic.

89. **Explain the role of RabbitMQ or Azure Service Bus in microservices.**  
   - Both are **message brokers** used for asynchronous communication.
   - RabbitMQ supports messaging patterns like pub/sub, routing, and priority queues.
   - Azure Service Bus provides features like dead-letter queues and topic-based routing.
   - Ensures reliability by managing message delivery even if services are temporarily unavailable.

90. **How do you handle eventual consistency in distributed systems?**  
   - Use **sagas** or **compensation patterns** to manage transactions across services.
   - Implement **eventual consistency** by accepting temporary inconsistencies.
   - Employ **message queues** to retry operations until success.
   - Use **event sourcing** to reconcile state asynchronously.

### Dependency Management  
91. **How do you manage NuGet packages in a .NET application?**  
   - Use **NuGet Package Manager** in Visual Studio or the **dotnet CLI**.
   - Define dependencies in the `.csproj` file or `packages.config`.
   - Use **version ranges** to ensure compatibility with future package updates.
   - Use **private NuGet feeds** for internal packages (e.g., Azure Artifacts).

92. **What is the purpose of `global.json` in .NET projects?**  
   - Locks the project to a specific **.NET SDK version**.
   - Ensures consistent SDK versions across development machines and CI/CD pipelines.
   - Useful for managing multiple .NET SDKs on the same machine.
   - Example: `"version": "6.0.100"` in `global.json` specifies .NET 6 SDK.

93. **How do you create and publish a NuGet package?**  
   - Create a `.nuspec` file or configure package details in `.csproj`.
   - Use `dotnet pack` to generate the NuGet package.
   - Publish using `dotnet nuget push` or through the NuGet gallery.
   - Follow semantic versioning and include proper metadata like descriptions and authors.

94. **Explain the difference between a library and an application in .NET.**  
   - **Library:** Reusable code packaged as a **DLL** that can be referenced by multiple projects.
   - **Application:** A complete executable that runs independently.
   - Libraries promote code reuse across projects.
   - Examples: A class library (.dll) vs. a console application (.exe).

95. **How do you handle versioning of dependencies?**  
   - Use **NuGet version ranges** to allow updates within a specified range.
   - Specify **floating versions** (e.g., `1.0.*`) to auto-update minor versions.
   - Pin exact versions for stability in production environments.
   - Use dependency management tools like **Dependabot** for automatic updates.

Next set is ready when you are!
# SpringBoot

1) Coffeemaker :- 
A simple Spring-based Java application demonstrating dependency injection, bean scopes, and lifecycle callbacks.

Features - 
- Defines a `CoffeeMachine` interface with multiple implementations:
  - `EspressoMachine` (singleton scope)
  - `LatteMachine` (prototype scope)
- `CafeService` uses a `CoffeeMachine` to serve coffee.
- Demonstrates usage of Spring annotations: `@Component`, `@Scope`, `@Autowired`, `@Qualifier`, `@PostConstruct`, and `@PreDestroy`.
- Manual configuration using `AppConfig` and Java-based context initialization.

Project Structure - 
- `src/main/java/com/example/coffeemaker/`
  - `CoffeemakerApplication.java`: Main class to run the application.
  - `AppConfig.java`: Spring configuration and component scanning.
  - `CoffeeMachine.java`: Interface for coffee machines.
  - `EspressoMachine.java`: Singleton bean implementation.
  - `LatteMachine.java`: Prototype bean implementation.
  - `CafeService.java`: Service that uses a coffee machine.
 

2) Demo :- 
A simple Spring Boot application demonstrating RESTful APIs, JPA, H2 database, and basic security.






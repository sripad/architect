# Architecture Patterns

 1. Software Architecture Patterns
 2. [Enterprise Architecture Patterns](https://www.amazon.in/Patterns-Enterprise-Application-Architecture-Addison-Wesley-ebook/dp/B008OHVDFM)
 3. Application architecture patterns
    1. Monolith
       1. References
           1. https://microservices.io/patterns/monolithic.html
           
    2. Microservices
       1. References
           1. https://microservices.io/patterns/microservices.html
           
       2. Decomposition 
           1. [Decompose by business capability](https://microservices.io/patterns/decomposition/decompose-by-business-capability.html)
           2. [Decompose by subdomain](https://microservices.io/patterns/decomposition/decompose-by-subdomain.html)
           3. [Self-contained service](https://microservices.io/patterns/decomposition/self-contained-service.html)
           4. [Service per team](https://microservices.io/patterns/decomposition/service-per-team.html)
           
       3. Refactoring to microservices - convert monlith as microservices
           1. [Strangler application](https://microservices.io/patterns/refactoring/strangler-application.html)
               - How do you migrate a legacy monolithic application to a microservice architecture?
               - The strangler application consists of two types of services. 
                    - First, there are services that implement functionality that previously resided in the monolith. 
                    - Second, there are services that implement new features. 
               - The latter are particularly useful since they demonstrate to the business the value of using microservices.
           2. [Anti-corruption layer](https://microservices.io/patterns/refactoring/anti-corruption-layer.html)
                    - How do you prevent a legacy monolith’s domain model from polluting the domain model of a new service.
           3. [Strategy 1 – Stop Digging](https://www.nginx.com/blog/refactoring-a-monolith-into-microservices/#Strategy-1&nbsp;%E2%80%93-Stop-Digging)
           4. [Strategy 2 – Split Frontend and Backend](https://www.nginx.com/blog/refactoring-a-monolith-into-microservices/#Strategy-2&nbsp;%E2%80%93-Split-Frontend-and-Backend)
           5. [Strategy 3 – Extract Services](https://www.nginx.com/blog/refactoring-a-monolith-into-microservices/#Strategy-3&nbsp;%E2%80%93-Extract-Services)
                    
       3. Data management
           1. [Database per service](https://microservices.io/patterns/data/database-per-service.html)
               1. [The FTGO application and the Database per service pattern](https://chrisrichardson.net/post/microservices/patterns/data/2019/07/15/ftgo-database-per-service.html)
           2. [Shared database](https://microservices.io/patterns/data/shared-database.html)
           3. [Saga](https://microservices.io/patterns/data/saga.html)
           4. [API Composition](https://microservices.io/patterns/data/api-composition.html)
           5. [CQRS](https://microservices.io/patterns/data/cqrs.html)
           6. [Domain event](https://microservices.io/patterns/data/domain-event.html)
           7. [Event sourcing](https://microservices.io/patterns/data/event-sourcing.html)
           
       4. Transactional messaging
           1. [Transactional outbox](https://microservices.io/patterns/data/transactional-outbox.html)
           2. [Transaction log tailing](https://microservices.io/patterns/data/transaction-log-tailing.html)
           3. [Polling publisher](https://microservices.io/patterns/data/polling-publisher.html)
          
       5. Testing
           1. [Service Component Test](https://microservices.io/patterns/testing/service-component-test.html)
           2. [Consumer-driven contract test](https://microservices.io/patterns/testing/service-integration-contract-test.html)
           3. [Consumer-side contract test](https://microservices.io/patterns/testing/consumer-side-contract-test.html)
           
       6. Deployment patterns
           1. [Multiple service instances per host](https://microservices.io/patterns/deployment/multiple-services-per-host.html)
           2. [Service instance per host](https://microservices.io/patterns/deployment/single-service-per-host.html)
           3. [Service instance per VM](https://microservices.io/patterns/deployment/service-per-vm.html)
           4. [Service instance per Container](https://microservices.io/patterns/deployment/service-per-container.html)
           5. [Serverless deployment](https://microservices.io/patterns/deployment/serverless-deployment.html)
           6. [Service deployment platform](https://microservices.io/patterns/deployment/service-deployment-platform.html)
           
       7. Cross cutting concerns
           1. [Microservice chassis]()
           2. [Service Template]()
           3. [Externalized configuration]()
           
       8. Communication style
           1. [Remote Procedure Invocation](https://microservices.io/patterns/communication-style/rpi.html)
           2. [Messaging](https://microservices.io/patterns/communication-style/messaging.html)
           3. [Domain-specific protocol](https://microservices.io/patterns/communication-style/domain-specific.html)
           4. [Idempotent Consumer](https://microservices.io/patterns/communication-style/idempotent-consumer.html)
           
       9. External API
           1. [API gateway](https://microservices.io/patterns/apigateway.html)
               1. https://www.nginx.com/blog/building-microservices-using-an-api-gateway/
           2. [Backend for front-end](https://microservices.io/patterns/apigateway.html#variation-backends-for-frontends)

       10. Service discovery
           1. [Client-side discovery](https://microservices.io/patterns/client-side-discovery.html)
           2. [Server-side discovery](https://microservices.io/patterns/server-side-discovery.html)
           3. [Service registry](https://microservices.io/patterns/service-registry.html)
           4. [Self registration](https://microservices.io/patterns/self-registration.html)
           5. [3rd party registration](https://microservices.io/patterns/3rd-party-registration.html)
           6. References
               - https://www.nginx.com/blog/service-discovery-in-a-microservices-architecture/

       11. Reliability
           1. [Circuit Breaker (Handling Partial Failures)](https://microservices.io/patterns/reliability/circuit-breaker.html)
              1. https://spring.io/guides/gs/circuit-breaker/
              2. https://martinfowler.com/bliki/CircuitBreaker.html
              3. https://github.com/Netflix/Hystrix
              
       12. Security
           1. [Access Token](https://microservices.io/patterns/security/access-token.html)
       
       13. [Observability
           1. [Log aggregation](https://microservices.io/patterns/observability/application-logging.html)
           2. [Application metrics](https://microservices.io/patterns/observability/application-metrics.html)
           3. [Audit logging](https://microservices.io/patterns/observability/audit-logging.html)
           4. [Distributed tracing](https://microservices.io/patterns/observability/distributed-tracing.html)
           5. [Exception tracking](https://microservices.io/patterns/observability/exception-tracking.html)
           6. [Health check API](https://microservices.io/patterns/observability/health-check-api.html)
           7. [Log deployments and changes](https://microservices.io/patterns/observability/log-deployments-and-changes.html)
           
       14. UI patterns
           1. [Server-side page fragment composition](https://microservices.io/patterns/ui/server-side-page-fragment-composition.html)
           2. [Client-side UI composition](https://microservices.io/patterns/ui/client-side-ui-composition.html)
       
       15. References
           1. [FTGO Application](https://github.com/microservices-patterns/ftgo-application)
           2. [Eventuate](https://eventuate.io/)
 3. Cloud Native Architecture/Design Patterns



 #### References
 * Books
    - Patterns of Enterprise Application Architecture : https://www.amazon.in/Patterns-Enterprise-Application-Architecture-Addison-Wesley-ebook/dp/B008OHVDFM

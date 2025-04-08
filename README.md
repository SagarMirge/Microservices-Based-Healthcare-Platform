# Microservices-Based-Healthcare-Platform
Designed and implemented a full-featured microservices-based Patient Management System using Spring Boot, gRPC, Kafka, and Docker, simulating real-world healthcare infrastructure with robust inter-service communication, secure authentication, and CI/CD readiness.

Key Highlights:

Microservices Architecture: Developed multiple Spring Boot services (patient-service, billing-service, auth-service, analytics-service) communicating via gRPC and Kafka for scalable and decoupled communication.

gRPC Integration: Defined and consumed Protocol Buffers for efficient, low-latency communication between services (e.g., Patient to Billing Service).

Apache Kafka: Implemented asynchronous event-driven communication using Kafka producers/consumers; serialized messages using Protobuf.

Authentication & Security: Built an auth-service with JWT-based authentication, password hashing, and secure user validation integrated via API Gateway filters.

API Gateway: Centralized request routing and authentication with Spring Cloud Gateway, implementing request filtering, exception handling, and OpenAPI documentation.

Database Integration: Used PostgreSQL for persistent storage, configured schema/data via SQL migrations; employed in-memory H2 for local dev/testing.

Docker & Containerization: Containerized all services with Docker, including Kafka brokers, PostgreSQL, and Auth-service, orchestrated using Docker Compose.

Testing: Wrote unit and integration tests (JUnit, Mockito) for key functionalities including login, token validation, and patient data flows.

Cloud Readiness: Simulated AWS infrastructure deployment using LocalStack and CloudFormation, including MSK, ECS, VPC, RDS, and API Gateway services.

CI/CD Mindset: Applied best practices for clean architecture, separation of concerns, and logging for observability and debugging.

-------------------
Tools & Tech: Spring Boot, gRPC, Kafka, Protobuf, JWT, PostgreSQL, Docker, LocalStack, AWS CLI, Spring Security, Spring Data JPA, OpenAPI/Swagger, JUnit, IntelliJ HTTP Client


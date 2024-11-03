
# Observability Project

![image](https://github.com/user-attachments/assets/4c735e69-cb06-4055-a555-8255095c52d8)

This project focuses on implementing observability across a microservices-based architecture, leveraging tools like OpenTelemetry, Prometheus, Grafana, and Kafka to create an end-to-end observability setup.

## Project Structure

- **adservice**: Ad service in Python
- **checkoutservice**: Checkout in Java
- **frontend**: UI frontend in TypeScript
- **frontendproxy**: Go-based proxy for frontend services
- **imageprovider**: Image provider microservice in JavaScript
- **kafka**: Message broker setup
- **productcatalogservice**: Product catalog service
- **prometheus**: Prometheus setup for metrics
- **recommendationservice**: Recommendation service

## Key Highlights

### Microservices Architecture
This project includes multiple microservices in Python, Java, Go, and JavaScript, highlighting multi-language interoperability in a microservices setup.

### Distributed Tracing with OpenTelemetry
Each service is instrumented for distributed tracing, offering insights into inter-service communication and request flows.

### Metrics and Monitoring
Prometheus captures service metrics, which are visualized in Grafana. This setup provides comprehensive monitoring, alerting, and observability capabilities.

### Logging
Centralized logging with aggregation supports efficient troubleshooting across all services, essential for maintaining production-ready microservices.

### Scalable Infrastructure with Docker and Kubernetes
All services are containerized and deployed in Kubernetes, enabling scalability and demonstrating DevOps proficiency in container orchestration.

### Message Broker Integration (Kafka)
Kafka is integrated as a message broker, enabling asynchronous communication between services—a common and effective pattern in distributed systems.

## Technologies Used

- **Programming Languages**: Python, Java, Go, JavaScript
- **Observability Tools**: OpenTelemetry, Prometheus, Grafana
- **Containerization and Orchestration**: Docker, Kubernetes
- **Messaging**: Kafka

## Overall Impact
This project exemplifies end-to-end observability within a diverse microservices ecosystem, showcasing industry-standard tools and practices to boost service reliability, scalability, and maintainability.

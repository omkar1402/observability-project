
# Observability Project

![image](https://github.com/user-attachments/assets/4c735e69-cb06-4055-a555-8255095c52d8)
![image](https://github.com/user-attachments/assets/dada0ed3-8c0f-4fd5-a427-e601958a2515)

This project focuses on implementing observability across a microservices-based architecture, leveraging tools like OpenTelemetry, Prometheus, Grafana, and Kafka to create an end-to-end observability setup.

## Project Structure

- **adservice**: Ad service in Java
- **checkoutservice**: Checkout in Go
- **frontend**: UI frontend in TypeScript
- **frontendproxy**: frontend services in C++
- **imageprovider**: Image provider microservice in C++
- **kafka**: Message broker setup
- **productcatalogservice**: Product catalog service in Go
- **prometheus**: Prometheus setup for metrics
- **recommendationservice**: Recommendation service in Python

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

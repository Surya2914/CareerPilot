# CareerPilot – Microservices-Based Job Portal

CareerPilot is a full-stack job portal application built using React, Java, Spring Boot and a microservices architecture. It provides a platform for job seekers to explore job opportunities and manage job applications through a distributed backend system.

## Architecture

flowchart TD
    A[React Frontend] --> B[API Gateway]
    B --> C[User Service]
    B --> D[Job Service]
    B --> E[Application Service]
    B --> F[Notification Service]
    B --> G[Analytics Service]

## Tech Stack

### Frontend
- React
- JavaScript
- Vite

### Backend
- Java 17
- Spring Boot
- Spring Security
- REST APIs
- Spring Cloud Gateway

### Database
- MySQL
- Spring Data JPA
- Hibernate

### Tools
- Git & GitHub
- Postman
- VS Code

## Microservices

| Service | Description | Repository |
|---|---|---|
| Frontend | React-based user interface | [careerpilot-frontend](https://github.com/Surya2914/careerpilot-frontend) |
| API Gateway | Routes requests to backend services | [careerpilot-api-gateway](https://github.com/Surya2914/careerpilot-api-gateway) |
| User Service | User registration and authentication | [careerpilot-user-service](https://github.com/Surya2914/careerpilot-user-service) |
| Job Service | Job management and job listing APIs | [careerpilot-job-service](https://github.com/Surya2914/careerpilot-job-service) |
| Application Service | Job application management | [careerpilot-application-service](https://github.com/Surya2914/careerpilot-application-service) |
| Notification Service | Notification management | [careerpilot-notification-service](https://github.com/Surya2914/careerpilot-notification-service) |
| Analytics Service | Analytics-related APIs | [careerpilot-analytics-service](https://github.com/Surya2914/careerpilot-analytics-service) |

## Project Structure

CareerPilot
├── Frontend
├── API Gateway
├── User Service
├── Job Service
├── Application Service
├── Notification Service
└── Analytics Service
```

## Project Status

- [x] Frontend development
- [x] User Service
- [x] Job Service
- [x] Application Service
- [x] Notification Service
- [x] Analytics Service
- [x] API Gateway
- [x] GitHub repository setup

## Author

Developed as a full-stack microservices-based project using Java and React.

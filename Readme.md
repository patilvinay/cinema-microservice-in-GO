# Cinemas Microservice in Go (Project) (You are in Step-4)

This project consist of the following components:

```
.
├── cinemas-db
├── deploy
│   ├── docker-compose
│   ├── hashicorp
│   │   ├── deployment-files
│   └── readme.md
├── movie-service
├── notification-service (new)
└── payment-service
```

# How to use this project

This project has several components and deployment strategies, so please follow the instructions defined below in order to spin up this project.

- [Initialize Environment with Hashicorp Vagrant] please see step-6 and onwards.

- **[Run microservices with Docker Compose]**(./deploy/docker-compose) \
it only deploys the microservices in docker containers locally and it is best for debugging the applications.
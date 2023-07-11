<h2 align="center">NestJS Prisma Postgresql Starter Kit</h2>

🚀 A quick and comprehensive nestjs starter kit powered by Prisma, PostgreSQL, and Swagger, perfect for backend rookies to rapidly construct a robust backend server.

I'm looking forward to a great nestjs starter kit or template which can help me quickly figure out how to build a real world backend server, then I found this blog: https://www.prisma.io/blog/nestjs-prisma-rest-api-7D056s1BmOL0, and implement it.

It's a good starter kit for backend rookies like me, to combine db like postgresql, ORM like prisma, Api doc like swagger together,  also with many concepts in backend like dto, entity and so on.

## Features

- 💼 Basic REST API implemented, ideal for starting any project.
- 🎛 Input validation and transformation to ensure data integrity.
- 🚦 Error handling for better fault tolerance.
- 📜 Swagger for generating and maintaining excellent API documentation.
- 🌐 Relation data handling made easy.
- 🔐 Built-in authentication using Passport and passport-jwt.
- 🏗 Structured around well-established best practices, which helps to maintain code quality even in larger projects.
- ⏰ Save time by avoiding boilerplate code, so you can focus on what matters: your business logic.
- 🔄 Encourages agile development: easy to refactor and expand as your project evolves.


## Setup and Run
```shell
npm install
docker-compose up -d
npx prisma migrate dev
npm run start:dev
```

### Concepts Used
- Contoller
- Service
- Module
- DTO
- Entity
- Pipes
- Guards
- Interceptors
- Decorators
- Providers
- Exception Filters

### Stack
- NestJS as a core framework.
- Prisma as an ORM.
- PostgreSQL for the database.
- Swagger for API documentation.
- Passport and passport-jwt for authentication.
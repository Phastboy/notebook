<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [**NestJS Mastery: From Beginner to Advanced**](#nestjs-mastery-from-beginner-to-advanced)
- [**Chapter 1: Introduction to NestJS and Prerequisites**](#chapter-1-introduction-to-nestjs-and-prerequisites)
  - [**1.1 Introduction to NestJS**](#11-introduction-to-nestjs)
    - [**What is NestJS?**](#what-is-nestjs)
    - [**Key Features of NestJS**](#key-features-of-nestjs)
    - [**Why Use NestJS?**](#why-use-nestjs)
    - [**Comparing NestJS with Express, Fastify, and Others**](#comparing-nestjs-with-express-fastify-and-others)
  - [**1.2 Prerequisites**](#12-prerequisites)
    - [**JavaScript & TypeScript Basics**](#javascript--typescript-basics)
    - [**Node.js and Package Managers (npm, pnpm, yarn)**](#nodejs-and-package-managers-npm-pnpm-yarn)
    - [**Setting Up Development Tools**](#setting-up-development-tools)
  - [**🛠️ Mini Project: Environment Setup**](#-mini-project-environment-setup)
  - [**✅ Learning Outcomes**](#-learning-outcomes)
- [**Chapter 2: Getting Started with NestJS**](#chapter-2-getting-started-with-nestjs)
  - [**2.1 Installing NestJS CLI**](#21-installing-nestjs-cli)
    - [**Step 1: Install the NestJS CLI**](#step-1-install-the-nestjs-cli)
    - [**Step 2: Verify the Installation**](#step-2-verify-the-installation)
  - [**2.2 Creating a NestJS Project**](#22-creating-a-nestjs-project)
    - [**Step 1: Generate a New Project**](#step-1-generate-a-new-project)
    - [**Step 2: Explore the Project Structure**](#step-2-explore-the-project-structure)
  - [**2.3 Exploring the Project Structure**](#23-exploring-the-project-structure)
    - [**Key Files and Folders**](#key-files-and-folders)
  - [**🛠️ Mini Project: First NestJS API**](#-mini-project-first-nestjs-api)
    - [**Task**](#task)
  - [**✅ Learning Outcomes**](#-learning-outcomes-1)
- [**Chapter 3: Core Concepts of NestJS**](#chapter-3-core-concepts-of-nestjs)
  - [**3.1 Modules**](#31-modules)
    - [**What Are Modules?**](#what-are-modules)
    - [**Creating a Module**](#creating-a-module)
    - [**Key Properties of a Module**](#key-properties-of-a-module)
  - [**3.2 Controllers**](#32-controllers)
    - [**Creating a Controller**](#creating-a-controller)
    - [**Handling Routes**](#handling-routes)
  - [**3.3 Services**](#33-services)
    - [**Creating a Service**](#creating-a-service)
    - [**Adding Business Logic**](#adding-business-logic)
  - [**3.4 Providers & Dependency Injection**](#34-providers--dependency-injection)
    - [**What Are Providers?**](#what-are-providers)
    - [**Injecting a Service into a Controller**](#injecting-a-service-into-a-controller)
  - [**🛠️ Mini Project: Todo API**](#-mini-project-todo-api)
    - [**Task**](#task-1)
  - [**✅ Learning Outcomes**](#-learning-outcomes-2)
- [**Chapter 4: Middleware, Guards, Interceptors & Pipes**](#chapter-4-middleware-guards-interceptors--pipes)
  - [**4.1 Middleware**](#41-middleware)
    - [**Built-in vs Custom Middleware**](#built-in-vs-custom-middleware)
    - [**Creating Custom Middleware**](#creating-custom-middleware)
    - [**Applying Middleware**](#applying-middleware)
  - [**4.2 Guards**](#42-guards)
    - [**Creating a Guard**](#creating-a-guard)
    - [**Applying a Guard**](#applying-a-guard)
  - [**4.3 Interceptors**](#43-interceptors)
    - [**Creating an Interceptor**](#creating-an-interceptor)
    - [**Applying an Interceptor**](#applying-an-interceptor)
  - [**4.4 Pipes**](#44-pipes)
    - [**Built-in Pipes**](#built-in-pipes)
    - [**Creating a Custom Pipe**](#creating-a-custom-pipe)
    - [**Applying a Pipe**](#applying-a-pipe)
  - [**🛠️ Mini Project: Authenticated Todo API**](#-mini-project-authenticated-todo-api)
    - [**Task**](#task-2)
  - [**✅ Learning Outcomes**](#-learning-outcomes-3)
- [**Chapter 5: Databases & ORM - MongoDB & PostgreSQL with Prisma**](#chapter-5-databases--orm---mongodb--postgresql-with-prisma)
  - [**5.1 Introduction to Databases**](#51-introduction-to-databases)
    - [**SQL vs NoSQL**](#sql-vs-nosql)
  - [**5.2 Using MongoDB with Mongoose**](#52-using-mongodb-with-mongoose)
    - [**Step 1: Install Dependencies**](#step-1-install-dependencies)
    - [**Step 2: Configure MongoDB Connection**](#step-2-configure-mongodb-connection)
    - [**Step 3: Define a Schema**](#step-3-define-a-schema)
    - [**Step 4: Create a Model**](#step-4-create-a-model)
    - [**Step 5: Use the Model in a Service**](#step-5-use-the-model-in-a-service)
  - [**5.3 Using PostgreSQL with Prisma**](#53-using-postgresql-with-prisma)
    - [**Step 1: Install Prisma**](#step-1-install-prisma)
    - [**Step 2: Configure PostgreSQL Connection**](#step-2-configure-postgresql-connection)
    - [**Step 3: Define Models**](#step-3-define-models)
    - [**Step 4: Generate and Migrate the Database**](#step-4-generate-and-migrate-the-database)
    - [**Step 5: Use Prisma in a Service**](#step-5-use-prisma-in-a-service)
  - [**🛠️ Mini Project: Task Manager API**](#-mini-project-task-manager-api)
    - [**Task**](#task-3)
  - [**✅ Learning Outcomes**](#-learning-outcomes-4)
- [**Chapter 6: Authentication & Authorization**](#chapter-6-authentication--authorization)
  - [**6.1 Setting Up JWT Authentication**](#61-setting-up-jwt-authentication)
    - [**Step 1: Install Required Packages**](#step-1-install-required-packages)
    - [**Step 2: Create an Auth Module**](#step-2-create-an-auth-module)
    - [**Step 3: Configure JWT**](#step-3-configure-jwt)
    - [**Step 4: Implement User Registration and Login**](#step-4-implement-user-registration-and-login)
    - [**Step 5: Create Login and Registration Endpoints**](#step-5-create-login-and-registration-endpoints)
  - [**6.2 Role-Based Access Control**](#62-role-based-access-control)
    - [**Step 1: Define Roles**](#step-1-define-roles)
    - [**Step 2: Create a Roles Guard**](#step-2-create-a-roles-guard)
    - [**Step 3: Create a Roles Decorator**](#step-3-create-a-roles-decorator)
    - [**Step 4: Apply the Roles Guard**](#step-4-apply-the-roles-guard)
  - [**🛠️ Mini Project: Secure User API**](#-mini-project-secure-user-api)
    - [**Task**](#task-4)
  - [**✅ Learning Outcomes**](#-learning-outcomes-5)
- [**Chapter 7: API Documentation with Swagger**](#chapter-7-api-documentation-with-swagger)
  - [**7.1 Setting Up Swagger**](#71-setting-up-swagger)
    - [**Step 1: Install Swagger**](#step-1-install-swagger)
    - [**Step 2: Configure Swagger**](#step-2-configure-swagger)
    - [**Step 3: Explore the Swagger UI**](#step-3-explore-the-swagger-ui)
  - [**7.2 Documenting Your API**](#72-documenting-your-api)
    - [**Documenting Controllers and Routes**](#documenting-controllers-and-routes)
    - [**Documenting DTOs**](#documenting-dtos)
    - [**Documenting Authentication**](#documenting-authentication)
  - [**🛠️ Mini Project: Documenting Task Manager API**](#-mini-project-documenting-task-manager-api)
    - [**Task**](#task-5)
  - [**✅ Learning Outcomes**](#-learning-outcomes-6)
- [**Chapter 8: Testing with Jest**](#chapter-8-testing-with-jest)
  - [**8.1 Introduction to Testing**](#81-introduction-to-testing)
    - [**Types of Tests**](#types-of-tests)
    - [**Why Test?**](#why-test)
  - [**8.2 Getting Started with Jest**](#82-getting-started-with-jest)
    - [**Step 1: Install Jest**](#step-1-install-jest)
    - [**Step 2: Write Your First Test**](#step-2-write-your-first-test)
    - [**Step 3: Run the Test**](#step-3-run-the-test)
  - [**8.3 Writing Unit Tests**](#83-writing-unit-tests)
    - [**Example: Testing a Function**](#example-testing-a-function)
    - [**Key Concepts**](#key-concepts)
  - [**8.4 Writing Integration Tests**](#84-writing-integration-tests)
    - [**Example: Testing a Module**](#example-testing-a-module)
  - [**8.5 Testing in NestJS**](#85-testing-in-nestjs)
    - [**Step 1: Write Unit Tests for a Service**](#step-1-write-unit-tests-for-a-service)
    - [**Step 2: Write Integration Tests for a Controller**](#step-2-write-integration-tests-for-a-controller)
  - [**🛠️ Exercises**](#-exercises)
  - [**🛠️ Mini Project: Test-Driven Development**](#-mini-project-test-driven-development)
    - [**Task**](#task-6)
  - [**✅ Learning Outcomes**](#-learning-outcomes-7)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

---
# **NestJS Mastery: From Beginner to Advanced**

This course is designed to take you from **zero to hero** in NestJS, covering everything from **basic concepts** to **advanced features**, with **hands-on projects** for each chapter.

---

# **Chapter 1: Introduction to NestJS and Prerequisites**

## **1.1 Introduction to NestJS**

### **What is NestJS?**
NestJS is a progressive, TypeScript-first framework for building efficient and scalable server-side applications. It is built on top of Node.js and combines elements of Object-Oriented Programming (OOP), Functional Programming (FP), and Functional Reactive Programming (FRP).

NestJS provides an out-of-the-box application architecture that allows developers to create highly testable, scalable, and maintainable applications. It supports both RESTful and GraphQL APIs, and it can be used to build microservices, real-time applications, and even full-stack apps.

---

### **Key Features of NestJS**
1. **Modular Architecture**: NestJS encourages the use of modules to organize code into reusable and maintainable components.
2. **TypeScript Support**: Built with TypeScript, NestJS provides strong typing and improved developer productivity.
3. **Dependency Injection**: NestJS uses a powerful Dependency Injection (DI) system to manage dependencies and improve testability.
4. **Extensibility**: NestJS is highly extensible, allowing integration with libraries like Express, Fastify, and more.
5. **Built-in Support for Microservices**: NestJS makes it easy to build microservices with support for various transport layers (e.g., TCP, Redis, MQTT).
6. **WebSockets and Real-Time Communication**: NestJS provides first-class support for WebSockets, enabling real-time communication.
7. **Testing**: NestJS integrates seamlessly with testing frameworks like Jest, making it easy to write unit and integration tests.

---

### **Why Use NestJS?**
- **Scalability**: NestJS is designed to handle large-scale applications with ease.
- **Developer Experience**: The framework’s architecture and tooling make it a joy to work with.
- **Community and Ecosystem**: NestJS has a growing community and a rich ecosystem of plugins and libraries.
- **Flexibility**: It supports multiple architectural patterns, including REST, GraphQL, and microservices.
- **Enterprise-Ready**: NestJS is a great choice for building enterprise-grade applications due to its robust architecture and TypeScript support.

---

### **Comparing NestJS with Express, Fastify, and Others**
| **Framework** | **Pros** | **Cons** |
|---------------|----------|----------|
| **NestJS**    | - Built-in architecture <br> - TypeScript-first <br> - Dependency Injection <br> - Scalable and testable | - Steeper learning curve <br> - Heavier than Express/Fastify |
| **Express**   | - Lightweight <br> - Minimalistic <br> - Large ecosystem | - No built-in structure <br> - Lack of TypeScript support out of the box |
| **Fastify**   | - Extremely fast <br> - Low overhead <br> - Plugin-based architecture | - Smaller ecosystem compared to Express <br> - Less opinionated |
| **Koa**       | - Modern and lightweight <br> - Async/await support | - Smaller community <br> - Less structure |

---

## **1.2 Prerequisites**

### **JavaScript & TypeScript Basics**
Before diving into NestJS, you should have a solid understanding of JavaScript and TypeScript. Key concepts to know include:
- **JavaScript**: Variables, functions, objects, arrays, promises, async/await, and ES6+ features.
- **TypeScript**: Types, interfaces, classes, decorators, and generics.

---

### **Node.js and Package Managers (npm, pnpm, yarn)**
NestJS is built on Node.js, so you need to have Node.js installed. You should also be familiar with package managers like npm, pnpm, or yarn for managing dependencies.

---

### **Setting Up Development Tools**
To get started with NestJS, you’ll need the following tools:
1. **VS Code**: A lightweight but powerful code editor with excellent TypeScript support.
2. **Postman**: For testing APIs.
3. **Git**: For version control.
4. **Terminal**: Familiarity with command-line tools is essential.

---

## **🛠️ Mini Project: Environment Setup**

1. Install Node.js
2. Create a simple typescript project.

---

## **✅ Learning Outcomes**
By the end of this chapter, you should be able to:
1. Explain what NestJS is and why it’s useful.
2. Compare NestJS with other backend frameworks.
3. Set up your development environment for NestJS.
4. Understand the prerequisites required to follow this course.

---

# **Chapter 2: Getting Started with NestJS**

## **2.1 Installing NestJS CLI**
The NestJS Command Line Interface (CLI) is a powerful tool that helps you scaffold and manage NestJS projects. It simplifies tasks like creating modules, controllers, and services.

### **Step 1: Install the NestJS CLI**
To install the CLI globally, run the following command:
```bash
npm install -g @nestjs/cli
```

### **Step 2: Verify the Installation**
Once installed, verify the CLI by running:
```bash
nest --version
```
This will display the installed version of the NestJS CLI.

---

## **2.2 Creating a NestJS Project**
With the CLI installed, you can now create a new NestJS project.

### **Step 1: Generate a New Project**
Run the following command to create a new project:
```bash
nest new my-nestjs-app
```
The CLI will prompt you to choose a package manager (npm, yarn, or pnpm). Select your preferred option.

### **Step 2: Explore the Project Structure**
After the project is created, navigate into the project directory:
```bash
cd my-nestjs-app
```

---

## **2.3 Exploring the Project Structure**
A newly generated NestJS project has the following structure:

```
my-nestjs-app/
├── src/
│   ├── app.controller.ts
│   ├── app.module.ts
│   ├── app.service.ts
│   └── main.ts
├── test/
│   ├── app.e2e-spec.ts
│   └── jest-e2e.json
├── .eslintrc.js
├── .prettierrc
├── nest-cli.json
├── package.json
├── tsconfig.build.json
└── tsconfig.json
```

### **Key Files and Folders**
1. **`src/` Directory**: Contains the application’s source code.
   - `app.controller.ts`: Defines the basic routes for your application.
   - `app.module.ts`: The root module of the application.
   - `app.service.ts`: Contains the business logic for your application.
   - `main.ts`: The entry point of the application. It bootstraps the NestJS app.

2. **Configuration Files**:
   - `tsconfig.json`: TypeScript configuration file.
   - `package.json`: Lists project dependencies and scripts.
   - `.eslintrc.js`: ESLint configuration for code linting.
   - `.prettierrc`: Prettier configuration for code formatting.

---

## **🛠️ Mini Project: First NestJS API**
### **Task**
1. Create a new NestJS project using the CLI.
2. Explore the generated project structure.
3. Modify the `app.controller.ts` file to create a new route that returns a custom message (e.g., `"Hello, NestJS!"`).
4. Run the application and test the new route using a browser or Postman.

---

## **✅ Learning Outcomes**
By the end of this chapter, you should be able to:
1. Install the NestJS CLI and create a new project.
2. Understand the structure of a NestJS application.
3. Run a NestJS server and test basic routes.

---

# **Chapter 3: Core Concepts of NestJS**

## **3.1 Modules**
Modules are the building blocks of a NestJS application. They help organize the application into cohesive units of functionality.

### **What Are Modules?**
A module is a class annotated with the `@Module()` decorator. It encapsulates related components, such as controllers, services, and other providers.

### **Creating a Module**
To create a module, use the NestJS CLI:
```bash
nest generate module <module-name>
```
For example, to create a `users` module:
```bash
nest generate module users
```
This will generate a `users.module.ts` file with the following structure:
```typescript
import { Module } from '@nestjs/common';

@Module({})
export class UsersModule {}
```

### **Key Properties of a Module**
The `@Module()` decorator accepts the following properties:
- **`controllers`**: Controllers that belong to this module.
- **`providers`**: Services and other providers that belong to this module.
- **`imports`**: Other modules that this module depends on.
- **`exports`**: Providers that should be available to other modules.

---

## **3.2 Controllers**
Controllers are responsible for handling incoming HTTP requests and returning responses.

### **Creating a Controller**
To create a controller, use the NestJS CLI:
```bash
nest generate controller <controller-name>
```
For example, to create a `users` controller:
```bash
nest generate controller users
```
This will generate a `users.controller.ts` file with the following structure:
```typescript
import { Controller } from '@nestjs/common';

@Controller('users')
export class UsersController {}
```

### **Handling Routes**
Controllers use decorators to define routes and handle HTTP methods. For example:
```typescript
import { Controller, Get, Post, Body, Param } from '@nestjs/common';

@Controller('users')
export class UsersController {
  @Get()
  findAll(): string {
    return 'This action returns all users';
  }

  @Post()
  create(@Body() user: any): string {
    return 'This action adds a new user';
  }

  @Get(':id')
  findOne(@Param('id') id: string): string {
    return `This action returns user #${id}`;
  }
}
```

---

## **3.3 Services**
Services are responsible for handling business logic and data access.

### **Creating a Service**
To create a service, use the NestJS CLI:
```bash
nest generate service <service-name>
```
For example, to create a `users` service:
```bash
nest generate service users
```
This will generate a `users.service.ts` file with the following structure:
```typescript
import { Injectable } from '@nestjs/common';

@Injectable()
export class UsersService {}
```

### **Adding Business Logic**
Services are where you implement the core functionality of your application. For example:
```typescript
import { Injectable } from '@nestjs/common';

@Injectable()
export class UsersService {
  private users = [];

  findAll() {
    return this.users;
  }

  create(user: any) {
    this.users.push(user);
    return user;
  }

  findOne(id: number) {
    return this.users.find(user => user.id === id);
  }
}
```

---

## **3.4 Providers & Dependency Injection**
Dependency Injection (DI) is a design pattern that NestJS uses to manage dependencies between components.

### **What Are Providers?**
Providers are classes that can be injected into other components. They are annotated with the `@Injectable()` decorator.

### **Injecting a Service into a Controller**
To use a service in a controller, inject it via the constructor:
```typescript
import { Controller, Get } from '@nestjs/common';
import { UsersService } from './users.service';

@Controller('users')
export class UsersController {
  constructor(private readonly usersService: UsersService) {}

  @Get()
  findAll() {
    return this.usersService.findAll();
  }
}
```

---

## **🛠️ Mini Project: Todo API**
### **Task**
1. Create a `todos` module using the NestJS CLI.
2. Generate a `todos` controller and service.
3. Implement the following endpoints:
   - `GET /todos`: Returns all todos.
   - `POST /todos`: Creates a new todo.
   - `GET /todos/:id`: Returns a single todo by ID.
4. Use the `TodosService` to manage the list of todos in memory.

---

## **✅ Learning Outcomes**
By the end of this chapter, you should be able to:
1. Create and organize modules in a NestJS project.
2. Implement controllers to handle HTTP requests.
3. Use services to manage business logic.
4. Understand and apply Dependency Injection in NestJS.

---

# **Chapter 4: Middleware, Guards, Interceptors & Pipes**

## **4.1 Middleware**
Middleware functions are executed before a request reaches the route handler. They can be used for tasks like logging, request validation, or modifying the request/response objects.

### **Built-in vs Custom Middleware**
NestJS provides built-in middleware for common tasks, but you can also create custom middleware.

### **Creating Custom Middleware**
To create custom middleware, use the `@Injectable()` decorator and implement the `NestMiddleware` interface:
```typescript
import { Injectable, NestMiddleware } from '@nestjs/common';
import { Request, Response, NextFunction } from 'express';

@Injectable()
export class LoggerMiddleware implements NestMiddleware {
  use(req: Request, res: Response, next: NextFunction) {
    console.log(`Request URL: ${req.url}`);
    next();
  }
}
```

### **Applying Middleware**
Middleware can be applied globally or to specific routes. To apply middleware globally, use the `configure()` method in the `AppModule`:
```typescript
import { Module, MiddlewareConsumer } from '@nestjs/common';
import { LoggerMiddleware } from './logger.middleware';

@Module({})
export class AppModule {
  configure(consumer: MiddlewareConsumer) {
    consumer.apply(LoggerMiddleware).forRoutes('*');
  }
}
```

---

## **4.2 Guards**
Guards are used to protect routes by determining whether a request should be handled by a route handler. They are commonly used for authentication and authorization.

### **Creating a Guard**
To create a guard, use the `@Injectable()` decorator and implement the `CanActivate` interface:
```typescript
import { Injectable, CanActivate, ExecutionContext } from '@nestjs/common';
import { Observable } from 'rxjs';

@Injectable()
export class AuthGuard implements CanActivate {
  canActivate(
    context: ExecutionContext,
  ): boolean | Promise<boolean> | Observable<boolean> {
    const request = context.switchToHttp().getRequest();
    return this.validateRequest(request);
  }

  private validateRequest(request: any): boolean {
    // Add your authentication logic here
    return true; // or false based on the request
  }
}
```

### **Applying a Guard**
Guards can be applied globally, at the controller level, or at the route level. For example:
```typescript
import { Controller, Get, UseGuards } from '@nestjs/common';
import { AuthGuard } from './auth.guard';

@Controller('users')
@UseGuards(AuthGuard)
export class UsersController {
  @Get()
  findAll() {
    return 'This route is protected by the AuthGuard';
  }
}
```

---

## **4.3 Interceptors**
Interceptors are used to modify the request or response before or after it reaches the route handler. They are useful for tasks like logging, transforming data, or handling errors.

### **Creating an Interceptor**
To create an interceptor, use the `@Injectable()` decorator and implement the `NestInterceptor` interface:
```typescript
import { Injectable, NestInterceptor, ExecutionContext, CallHandler } from '@nestjs/common';
import { Observable } from 'rxjs';
import { tap } from 'rxjs/operators';

@Injectable()
export class LoggingInterceptor implements NestInterceptor {
  intercept(context: ExecutionContext, next: CallHandler): Observable<any> {
    console.log('Before...');

    const now = Date.now();
    return next
      .handle()
      .pipe(tap(() => console.log(`After... ${Date.now() - now}ms`)));
  }
}
```

### **Applying an Interceptor**
Interceptors can be applied globally, at the controller level, or at the route level. For example:
```typescript
import { Controller, Get, UseInterceptors } from '@nestjs/common';
import { LoggingInterceptor } from './logging.interceptor';

@Controller('users')
@UseInterceptors(LoggingInterceptor)
export class UsersController {
  @Get()
  findAll() {
    return 'This route is logged by the LoggingInterceptor';
  }
}
```

---

## **4.4 Pipes**
Pipes are used to transform or validate incoming data before it reaches the route handler. They are commonly used for input validation and data transformation.

### **Built-in Pipes**
NestJS provides several built-in pipes, such as:
- `ValidationPipe`: Validates incoming data against a DTO (Data Transfer Object).
- `ParseIntPipe`: Transforms a string into an integer.
- `ParseUUIDPipe`: Validates and transforms a string into a UUID.

### **Creating a Custom Pipe**
To create a custom pipe, use the `@Injectable()` decorator and implement the `PipeTransform` interface:
```typescript
import { Injectable, PipeTransform, ArgumentMetadata, BadRequestException } from '@nestjs/common';

@Injectable()
export class ParseIntPipe implements PipeTransform<string, number> {
  transform(value: string, metadata: ArgumentMetadata): number {
    const val = parseInt(value, 10);
    if (isNaN(val)) {
      throw new BadRequestException('Validation failed');
    }
    return val;
  }
}
```

### **Applying a Pipe**
Pipes can be applied globally, at the controller level, or at the route level. For example:
```typescript
import { Controller, Get, Param, UsePipes } from '@nestjs/common';
import { ParseIntPipe } from './parse-int.pipe';

@Controller('users')
export class UsersController {
  @Get(':id')
  findOne(@Param('id', ParseIntPipe) id: number) {
    return `This action returns user #${id}`;
  }
}
```

---

## **🛠️ Mini Project: Authenticated Todo API**
### **Task**
1. Create a custom guard to protect the Todo API routes.
2. Add a logging interceptor to log all requests to the Todo API.
3. Use the `ValidationPipe` to validate incoming data for creating and updating todos.

---

## **✅ Learning Outcomes**
By the end of this chapter, you should be able to:
1. Implement middleware for request handling.
2. Secure endpoints using guards.
3. Modify requests and responses using interceptors.
4. Validate and transform incoming data using pipes.

---

# **Chapter 5: Databases & ORM - MongoDB & PostgreSQL with Prisma**

## **5.1 Introduction to Databases**
Databases are essential for storing and managing data in applications. They can be broadly categorized into two types:
1. **SQL Databases**: Relational databases like PostgreSQL, MySQL, and SQLite.
2. **NoSQL Databases**: Non-relational databases like MongoDB, Cassandra, and Redis.

### **SQL vs NoSQL**
| **Feature**          | **SQL**                              | **NoSQL**                          |
|----------------------|--------------------------------------|------------------------------------|
| **Data Structure**   | Tables with rows and columns         | Documents, key-value pairs, graphs |
| **Scalability**      | Vertical scaling                     | Horizontal scaling                 |
| **Schema**           | Fixed schema                         | Dynamic schema                     |
| **Use Case**         | Structured data, complex queries     | Unstructured data, high scalability|

---

## **5.2 Using MongoDB with Mongoose**
MongoDB is a popular NoSQL database that stores data in JSON-like documents. To interact with MongoDB in NestJS, we’ll use **Mongoose**, a MongoDB object modeling tool.

### **Step 1: Install Dependencies**
Install the required packages:
```bash
npm install @nestjs/mongoose mongoose
```

### **Step 2: Configure MongoDB Connection**
In your `AppModule`, configure the MongoDB connection using the `MongooseModule`:
```typescript
import { Module } from '@nestjs/common';
import { MongooseModule } from '@nestjs/mongoose';

@Module({
  imports: [
    MongooseModule.forRoot('mongodb://localhost/nestjs-db'),
  ],
})
export class AppModule {}
```

### **Step 3: Define a Schema**
Create a schema for your data. For example, a `User` schema:
```typescript
import { Schema, Document } from 'mongoose';

export const UserSchema = new Schema({
  name: { type: String, required: true },
  email: { type: String, required: true },
  age: { type: Number, required: false },
});

export interface User extends Document {
  name: string;
  email: string;
  age?: number;
}
```

### **Step 4: Create a Model**
Use the `@nestjs/mongoose` package to create a model:
```typescript
import { Module } from '@nestjs/common';
import { MongooseModule } from '@nestjs/mongoose';
import { UserSchema } from './user.schema';

@Module({
  imports: [
    MongooseModule.forFeature([{ name: 'User', schema: UserSchema }]),
  ],
})
export class UsersModule {}
```

### **Step 5: Use the Model in a Service**
Inject the model into a service and perform CRUD operations:
```typescript
import { Injectable } from '@nestjs/common';
import { InjectModel } from '@nestjs/mongoose';
import { Model } from 'mongoose';
import { User } from './user.schema';

@Injectable()
export class UsersService {
  constructor(@InjectModel('User') private userModel: Model<User>) {}

  async create(user: User): Promise<User> {
    const newUser = new this.userModel(user);
    return newUser.save();
  }

  async findAll(): Promise<User[]> {
    return this.userModel.find().exec();
  }

  async findOne(id: string): Promise<User> {
    return this.userModel.findById(id).exec();
  }
}
```

---

## **5.3 Using PostgreSQL with Prisma**
PostgreSQL is a powerful SQL database. To interact with PostgreSQL in NestJS, we’ll use **Prisma**, a next-generation ORM.

### **Step 1: Install Prisma**
Install the Prisma CLI and initialize Prisma in your project:
```bash
npm install @prisma/client
npx prisma init
```
This will create a `prisma` directory with a `schema.prisma` file.

### **Step 2: Configure PostgreSQL Connection**
In the `schema.prisma` file, configure the PostgreSQL connection:
```prisma
datasource db {
  provider = "postgresql"
  url      = env("DATABASE_URL")
}
```

Add the `DATABASE_URL` to your `.env` file:
```env
DATABASE_URL="postgresql://user:password@localhost:5432/nestjs-db"
```

### **Step 3: Define Models**
Define your database models in the `schema.prisma` file. For example, a `User` model:
```prisma
model User {
  id    Int    @id @default(autoincrement())
  name  String
  email String @unique
  age   Int?
}
```

### **Step 4: Generate and Migrate the Database**
Run the following commands to generate the Prisma client and apply migrations:
```bash
npx prisma migrate dev --name init
npx prisma generate
```

### **Step 5: Use Prisma in a Service**
Inject the Prisma client into a service and perform CRUD operations:
```typescript
import { Injectable } from '@nestjs/common';
import { PrismaService } from './prisma.service';

@Injectable()
export class UsersService {
  constructor(private prisma: PrismaService) {}

  async create(data: { name: string; email: string; age?: number }) {
    return this.prisma.user.create({ data });
  }

  async findAll() {
    return this.prisma.user.findMany();
  }

  async findOne(id: number) {
    return this.prisma.user.findUnique({ where: { id } });
  }
}
```

---

## **🛠️ Mini Project: Task Manager API**
### **Task**
1. Choose either MongoDB or PostgreSQL for your Task Manager API.
2. Create a `Task` model/schema.
3. Implement CRUD operations for tasks:
   - Create a task.
   - Retrieve all tasks.
   - Retrieve a single task by ID.
   - Update a task.
   - Delete a task.
4. Test your API using Postman or a similar tool.

---

## **✅ Learning Outcomes**
By the end of this chapter, you should be able to:
1. Integrate MongoDB with NestJS using Mongoose.
2. Integrate PostgreSQL with NestJS using Prisma.
3. Perform CRUD operations on both databases.
4. Choose the right database for your application’s needs.

---

# **Chapter 6: Authentication & Authorization**

## **6.1 Setting Up JWT Authentication**
JSON Web Tokens (JWT) are a popular method for implementing authentication in modern web applications. JWTs are compact, self-contained tokens that can securely transmit information between parties.

### **Step 1: Install Required Packages**
Install the necessary packages for JWT authentication:
```bash
npm install @nestjs/jwt @nestjs/passport passport passport-jwt bcrypt
```

### **Step 2: Create an Auth Module**
Generate an `auth` module, controller, and service:
```bash
nest generate module auth
nest generate controller auth
nest generate service auth
```

### **Step 3: Configure JWT**
In the `auth` module, configure the JWT module:
```typescript
import { Module } from '@nestjs/common';
import { JwtModule } from '@nestjs/jwt';
import { AuthService } from './auth.service';
import { AuthController } from './auth.controller';

@Module({
  imports: [
    JwtModule.register({
      secret: 'your-secret-key', // Replace with a secure key
      signOptions: { expiresIn: '1h' }, // Token expiration time
    }),
  ],
  providers: [AuthService],
  controllers: [AuthController],
})
export class AuthModule {}
```

### **Step 4: Implement User Registration and Login**
In the `auth` service, implement methods for user registration and login:
```typescript
import { Injectable } from '@nestjs/common';
import { JwtService } from '@nestjs/jwt';
import * as bcrypt from 'bcrypt';

@Injectable()
export class AuthService {
  constructor(private jwtService: JwtService) {}

  private users = [];

  async register(username: string, password: string) {
    const hashedPassword = await bcrypt.hash(password, 10);
    const user = { username, password: hashedPassword };
    this.users.push(user);
    return user;
  }

  async validateUser(username: string, password: string): Promise<any> {
    const user = this.users.find(u => u.username === username);
    if (user && await bcrypt.compare(password, user.password)) {
      return user;
    }
    return null;
  }

  async login(user: any) {
    const payload = { username: user.username };
    return {
      access_token: this.jwtService.sign(payload),
    };
  }
}
```

### **Step 5: Create Login and Registration Endpoints**
In the `auth` controller, create endpoints for registration and login:
```typescript
import { Controller, Post, Body, UnauthorizedException } from '@nestjs/common';
import { AuthService } from './auth.service';

@Controller('auth')
export class AuthController {
  constructor(private authService: AuthService) {}

  @Post('register')
  async register(@Body('username') username: string, @Body('password') password: string) {
    return this.authService.register(username, password);
  }

  @Post('login')
  async login(@Body('username') username: string, @Body('password') password: string) {
    const user = await this.authService.validateUser(username, password);
    if (!user) {
      throw new UnauthorizedException('Invalid credentials');
    }
    return this.authService.login(user);
  }
}
```

---

## **6.2 Role-Based Access Control**
Role-based access control (RBAC) allows you to restrict access to certain routes based on the user’s role (e.g., `admin`, `user`).

### **Step 1: Define Roles**
Create an enum for user roles:
```typescript
export enum Role {
  User = 'user',
  Admin = 'admin',
}
```

### **Step 2: Create a Roles Guard**
Create a guard to check if the user has the required role:
```typescript
import { Injectable, CanActivate, ExecutionContext } from '@nestjs/common';
import { Reflector } from '@nestjs/core';
import { Role } from './role.enum';
import { ROLES_KEY } from './roles.decorator';

@Injectable()
export class RolesGuard implements CanActivate {
  constructor(private reflector: Reflector) {}

  canActivate(context: ExecutionContext): boolean {
    const requiredRoles = this.reflector.get<Role[]>(ROLES_KEY, context.getHandler());
    if (!requiredRoles) {
      return true;
    }
    const { user } = context.switchToHttp().getRequest();
    return requiredRoles.some(role => user.roles?.includes(role));
  }
}
```

### **Step 3: Create a Roles Decorator**
Create a custom decorator to assign roles to routes:
```typescript
import { SetMetadata } from '@nestjs/common';
import { Role } from './role.enum';

export const ROLES_KEY = 'roles';
export const Roles = (...roles: Role[]) => SetMetadata(ROLES_KEY, roles);
```

### **Step 4: Apply the Roles Guard**
Apply the `RolesGuard` to your controllers or routes:
```typescript
import { Controller, Get, UseGuards } from '@nestjs/common';
import { Roles } from './roles.decorator';
import { RolesGuard } from './roles.guard';
import { Role } from './role.enum';

@Controller('admin')
@UseGuards(RolesGuard)
export class AdminController {
  @Get()
  @Roles(Role.Admin)
  adminDashboard() {
    return 'Welcome to the admin dashboard';
  }
}
```

---

## **🛠️ Mini Project: Secure User API**
### **Task**
1. Implement JWT-based authentication for your User API.
2. Add role-based access control to restrict certain routes to admin users.
3. Test the authentication and authorization flow using Postman.

---

## **✅ Learning Outcomes**
By the end of this chapter, you should be able to:
1. Implement JWT-based authentication in a NestJS application.
2. Secure API endpoints using role-based access control.
3. Understand the concepts of authentication and authorization.

---

# **Chapter 7: API Documentation with Swagger**

## **7.1 Setting Up Swagger**
Swagger is integrated into NestJS via the `@nestjs/swagger` package. It allows you to generate API documentation automatically based on your code.

### **Step 1: Install Swagger**
Install the required package:
```bash
npm install @nestjs/swagger
```

### **Step 2: Configure Swagger**
In your `main.ts` file, configure Swagger:
```typescript
import { NestFactory } from '@nestjs/core';
import { AppModule } from './app.module';
import { SwaggerModule, DocumentBuilder } from '@nestjs/swagger';

async function bootstrap() {
  const app = await NestFactory.create(AppModule);

  const config = new DocumentBuilder()
    .setTitle('Task Manager API')
    .setDescription('API for managing tasks')
    .setVersion('1.0')
    .addTag('tasks')
    .addBearerAuth() // Enable JWT authentication in Swagger
    .build();

  const document = SwaggerModule.createDocument(app, config);
  SwaggerModule.setup('api', app, document);

  await app.listen(3000);
}
bootstrap();
```

### **Step 3: Explore the Swagger UI**
Once your application is running, navigate to `http://localhost:3000/api` in your browser. You’ll see the Swagger UI, which provides an interactive interface for your API documentation.

---

## **7.2 Documenting Your API**
Swagger uses decorators to generate documentation. You can add these decorators to your controllers, routes, and DTOs (Data Transfer Objects) to provide detailed information about your API.

### **Documenting Controllers and Routes**
Use the `@ApiTags()` and `@ApiOperation()` decorators to document your controllers and routes:
```typescript
import { Controller, Get, Post, Body } from '@nestjs/common';
import { ApiTags, ApiOperation, ApiResponse } from '@nestjs/swagger';
import { CreateTaskDto } from './dto/create-task.dto';

@ApiTags('tasks')
@Controller('tasks')
export class TasksController {
  @Get()
  @ApiOperation({ summary: 'Get all tasks' })
  @ApiResponse({ status: 200, description: 'List of tasks' })
  findAll() {
    return 'This action returns all tasks';
  }

  @Post()
  @ApiOperation({ summary: 'Create a task' })
  @ApiResponse({ status: 201, description: 'Task created successfully' })
  create(@Body() createTaskDto: CreateTaskDto) {
    return 'This action adds a new task';
  }
}
```

### **Documenting DTOs**
Use the `@ApiProperty()` decorator to document your DTOs:
```typescript
import { ApiProperty } from '@nestjs/swagger';

export class CreateTaskDto {
  @ApiProperty({ description: 'The title of the task' })
  title: string;

  @ApiProperty({ description: 'The description of the task', required: false })
  description?: string;

  @ApiProperty({ description: 'Whether the task is completed', default: false })
  completed: boolean;
}
```

### **Documenting Authentication**
If your API uses authentication (e.g., JWT), you can document it using the `@ApiBearerAuth()` decorator:
```typescript
import { Controller, Get, UseGuards } from '@nestjs/common';
import { ApiBearerAuth, ApiTags } from '@nestjs/swagger';
import { AuthGuard } from './auth.guard';

@ApiTags('admin')
@ApiBearerAuth()
@UseGuards(AuthGuard)
@Controller('admin')
export class AdminController {
  @Get()
  adminDashboard() {
    return 'Welcome to the admin dashboard';
  }
}
```

---

## **🛠️ Mini Project: Documenting Task Manager API**
### **Task**
1. Set up Swagger in your Task Manager API.
2. Document all endpoints, including:
   - Task creation.
   - Retrieving all tasks.
   - Retrieving a single task by ID.
   - Updating a task.
   - Deleting a task.
3. Add descriptions for all DTOs and properties.
4. Test the Swagger UI to ensure all endpoints are documented correctly.

---

## **✅ Learning Outcomes**
By the end of this chapter, you should be able to:
1. Set up and configure Swagger in a NestJS application.
2. Document controllers, routes, and DTOs using Swagger decorators.
3. Generate and explore API documentation using the Swagger UI.

---

# **Chapter 8: Testing with Jest**

## **8.1 Introduction to Testing**
Testing is the process of verifying that your code works as expected. It helps catch bugs early, ensures code quality, and makes your application more maintainable.

### **Types of Tests**
1. **Unit Tests**: Test individual components (e.g., functions, classes) in isolation.
2. **Integration Tests**: Test how multiple components work together.
3. **End-to-End (E2E) Tests**: Test the entire application from start to finish.

### **Why Test?**
- **Catch Bugs Early**: Identify issues before they reach production.
- **Improve Code Quality**: Writing tests forces you to write cleaner, more modular code.
- **Documentation**: Tests serve as living documentation for your code.
- **Confidence**: Tests give you confidence when refactoring or adding new features.

---

## **8.2 Getting Started with Jest**
Jest is a popular JavaScript testing framework. It’s easy to set up and comes with built-in support for mocking, assertions, and code coverage.

### **Step 1: Install Jest**
If you’re starting a new project, install Jest:
```bash
npm install --save-dev jest
```

### **Step 2: Write Your First Test**
Create a simple function to test. For example, create a `math.js` file:
```javascript
// math.js
function add(a, b) {
  return a + b;
}

module.exports = { add };
```

Now, create a test file `math.test.js`:
```javascript
// math.test.js
const { add } = require('./math');

test('adds 1 + 2 to equal 3', () => {
  expect(add(1, 2)).toBe(3);
});
```

### **Step 3: Run the Test**
Run the test using Jest:
```bash
npx jest
```
If everything is set up correctly, you should see a passing test.

---

## **8.3 Writing Unit Tests**
Unit tests focus on testing individual functions or methods in isolation.

### **Example: Testing a Function**
Let’s test a function that checks if a string is a palindrome:
```javascript
// palindrome.js
function isPalindrome(str) {
  const cleaned = str.replace(/[^a-zA-Z0-9]/g, '').toLowerCase();
  return cleaned === cleaned.split('').reverse().join('');
}

module.exports = { isPalindrome };
```

Write a test for this function:
```javascript
// palindrome.test.js
const { isPalindrome } = require('./palindrome');

test('checks if "racecar" is a palindrome', () => {
  expect(isPalindrome('racecar')).toBe(true);
});

test('checks if "hello" is not a palindrome', () => {
  expect(isPalindrome('hello')).toBe(false);
});
```

### **Key Concepts**
- **`test()`**: Defines a test case.
- **`expect()`**: Asserts the expected outcome.
- **Matchers**: Functions like `toBe()`, `toEqual()`, and `toContain()` for making assertions.

---

## **8.4 Writing Integration Tests**
Integration tests focus on testing how multiple components work together.

### **Example: Testing a Module**
Let’s test a module that uses multiple functions. Create a `calculator.js` file:
```javascript
// calculator.js
const { add, subtract } = require('./math');

function calculate(a, b, operation) {
  switch (operation) {
    case 'add':
      return add(a, b);
    case 'subtract':
      return subtract(a, b);
    default:
      throw new Error('Invalid operation');
  }
}

module.exports = { calculate };
```

Write a test for this module:
```javascript
// calculator.test.js
const { calculate } = require('./calculator');

test('calculates 1 + 2 to equal 3', () => {
  expect(calculate(1, 2, 'add')).toBe(3);
});

test('calculates 5 - 3 to equal 2', () => {
  expect(calculate(5, 3, 'subtract')).toBe(2);
});
```

---

## **8.5 Testing in NestJS**
Now that you understand the basics of testing, let’s apply these concepts to NestJS.

### **Step 1: Write Unit Tests for a Service**
Let’s test a simple `TasksService`:
```typescript
// tasks.service.ts
import { Injectable } from '@nestjs/common';

@Injectable()
export class TasksService {
  private tasks = [];

  create(task: any) {
    this.tasks.push(task);
    return task;
  }

  findAll() {
    return this.tasks;
  }
}
```

Write a test for this service:
```typescript
// tasks.service.spec.ts
import { Test, TestingModule } from '@nestjs/testing';
import { TasksService } from './tasks.service';

describe('TasksService', () => {
  let service: TasksService;

  beforeEach(async () => {
    const module: TestingModule = await Test.createTestingModule({
      providers: [TasksService],
    }).compile();

    service = module.get<TasksService>(TasksService);
  });

  it('should be defined', () => {
    expect(service).toBeDefined();
  });

  it('should create a task', () => {
    const task = { title: 'Test Task' };
    expect(service.create(task)).toEqual(task);
  });

  it('should return all tasks', () => {
    const task = { title: 'Test Task' };
    service.create(task);
    expect(service.findAll()).toEqual([task]);
  });
});
```

### **Step 2: Write Integration Tests for a Controller**
Let’s test a `TasksController`:
```typescript
// tasks.controller.ts
import { Controller, Get, Post, Body } from '@nestjs/common';
import { TasksService } from './tasks.service';

@Controller('tasks')
export class TasksController {
  constructor(private tasksService: TasksService) {}

  @Get()
  findAll() {
    return this.tasksService.findAll();
  }

  @Post()
  create(@Body() task: any) {
    return this.tasksService.create(task);
  }
}
```

Write a test for this controller:
```typescript
// tasks.controller.spec.ts
import { Test, TestingModule } from '@nestjs/testing';
import { TasksController } from './tasks.controller';
import { TasksService } from './tasks.service';

describe('TasksController', () => {
  let controller: TasksController;
  let service: TasksService;

  beforeEach(async () => {
    const module: TestingModule = await Test.createTestingModule({
      controllers: [TasksController],
      providers: [TasksService],
    }).compile();

    controller = module.get<TasksController>(TasksController);
    service = module.get<TasksService>(TasksService);
  });

  it('should be defined', () => {
    expect(controller).toBeDefined();
  });

  it('should return all tasks', () => {
    const result = [{ title: 'Test Task' }];
    jest.spyOn(service, 'findAll').mockImplementation(() => result);
    expect(controller.findAll()).toBe(result);
  });

  it('should create a task', () => {
    const task = { title: 'Test Task' };
    jest.spyOn(service, 'create').mockImplementation(() => task);
    expect(controller.create(task)).toBe(task);
  });
});
```

---

Got it! Let’s keep the **exercises** separate from the **mini-project**. The exercises are meant to help readers practice and solidify their understanding of testing concepts, while the mini-project is a hands-on task to apply those concepts in a NestJS-specific context. Here's how we can structure it:

---

## **🛠️ Exercises**
These are standalone tasks to help you practice writing tests. They are not part of the mini-project.

1. **Exercise 1: Testing a Simple Function**
   - Write a function that multiplies two numbers.
   - Write unit tests for this function using Jest.

2. **Exercise 2: Testing a Validation Function**
   - Write a function that checks if a number is even.
   - Write unit tests for this function using Jest.

---

## **🛠️ Mini Project: Test-Driven Development**
This is a separate, hands-on task to apply testing concepts in a NestJS application.

### **Task**
1. Write unit tests for the `TasksService` to cover all methods:
   - `create()`
   - `findAll()`
   - `findOne()`
   - `update()`
   - `delete()`
2. Write integration tests for the `TasksController` to cover all endpoints:
   - `POST /tasks`
   - `GET /tasks`
   - `GET /tasks/:id`
   - `PATCH /tasks/:id`
   - `DELETE /tasks/:id`
3. Ensure all tests pass and provide adequate coverage.

---

## **✅ Learning Outcomes**
By the end of this chapter, you should be able to:
1. Explain the importance of testing and the different types of tests.
2. Write unit tests for simple functions and modules using Jest.
3. Write unit and integration tests for NestJS services and controllers.
4. Apply testing best practices to your projects.

---


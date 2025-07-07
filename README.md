# Personal Blog Platform

This project is a personal blogging platform built using ASP.NET MVC and Clean Architecture principles. The project is designed to improve my skills in back-end development with .NET technologies, while also showcasing a clean, modular, and scalable architecture suitable for real-world applications.

---

### _Tech Stack_
- ASP.NET Core MVC and Class Library
- Entity Framework Core
- Razor View Engine
- FluentValidation
- AutoMapper
- Bootstrap
- Clean Architecture & SOLID Principles

---

### _Project Structure_
├─ BlogProject.Web → UI layer (Controllers, Views)

├─ BlogProject.Application → Business logic and service layer

├─ BlogProject.Domain → Core entities and contracts

├─ BlogProject.Infrastructure → EF Core & data access layer

#### 🔹 `BlogProject.Web`
Handles all UI-related logic using ASP.NET MVC. Receives HTTP requests, invokes application services, and renders Razor Views.

#### 🔹 `BlogProject.Application`
Contains all the business logic and service implementations. Communicates with the domain and infrastructure layers via abstraction.

#### 🔹 `BlogProject.Domain`
Defines the core business entities and interfaces. Pure C# classes with no external dependencies. This layer knows nothing about the rest of the system.

#### 🔹 `BlogProject.Infrastructure`
Implements data access using Entity Framework Core. Contains `DbContext`, repositories, and configurations for persistence.

---

### _Features_
-  Create, edit, and delete blog posts
-  Category-based post filtering
-  Full-text search functionality
-  Comment system with moderation
-  Admin panel with authentication
-  Entity Framework Core




# ~~~
# _ASP.NET MVC ile Blog Projesine Başlarken_


### _MVC Nedir?_
...

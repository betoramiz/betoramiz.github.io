# Alberto Ramirez
**Senior Full Stack Engineer**  
Monterrey, Nuevo León, México  
**Phone:** +52 8127712285 | **Email:** maramirez10@gmail.com  
**GitHub:** [github.com/betoramiz](https://github.com/betoramiz) | **LinkedIn:** [linkedin.com/in/betoramiz](https://linkedin.com/in/betoramiz) (update link as needed)

---

## PROFESSIONAL SUMMARY

Senior Full Stack Engineer and Technical Lead with 15 years of experience architecting, building, and deploying scalable, mission-critical web applications. Expert in the Microsoft ecosystem (.NET Core, C#) and modern frontend architectures (Angular, NgRx, Signals). Proven track record of leading development lifecycles, translating complex business requirements into high-performance technical solutions, and mentoring engineering teams. Deep expertise in database optimization, connection pooling (PgBouncer, PostgreSQL, SQL Server), containerization (Docker), and cloud deployments (Azure, AWS, MinIO). Highly focused on delivering immediate business value, optimizing system performance, and driving engineering velocity.

---

## AREAS OF EXPERTISE

*   **Languages:** C# (up to C# 14), TypeScript, JavaScript, SQL, HTML5, CSS3, PHP, VB.NET.
*   **Backend Development:** .NET 10 / 8 / Core, ASP.NET Web API, Vertical Slice Architecture, Clean Architecture, CQRS, MediatR, RESTful APIs, Microservices, gRPC.
*   **Frontend Development:** Angular 21 / 17 / 12 / 7, NgRx (Store, Effects, Selectors), Angular Signals, RxJS, Tailwind CSS v4, PrimeNG, Angular Material, AngularJS, Zod, Bootstrap, jQuery.
*   **Databases & Performance:** PostgreSQL, PgBouncer (Connection Pooling), SQL Server, Entity Framework Core (up to EF 10), Dapper (Micro-ORM), Database Migrations, Query Optimization.
*   **DevOps & Cloud:** Docker, Docker Compose, Nginx (Reverse Proxy / API Gateway), AWS S3, Azure Blob Storage, MinIO, Azure WebApps, Azure Service Bus, PowerShell, Linux.
*   **Methodologies & Patterns:** Domain-Driven Design (DDD), Functional Error Handling (ErrorOr), Test-Driven Development (TDD), Agile/Scrum, Git, CI/CD pipelines.

---

## PROFESSIONAL EXPERIENCE

### **Developers.net** | *Senior Full Stack Engineer*
**May 2021 – Present**

Assigned to high-impact projects for US-based clients, responsible for architecture, development, deployment, and stakeholder communication.

#### **Project: FloreriaStore (High-Performance E-Commerce & ERP Platform)**
*Lead Full Stack Developer*
Architected and developed a next-generation e-commerce platform and administrative ERP system using the latest .NET and Angular frameworks.
*   **Backend Architecture:** Designed and built a scalable backend using **.NET 10** and **C# 14** following **Clean Architecture** and **Vertical Slice Architecture** patterns, improving code cohesion and reducing technical debt.
*   **CQRS & Hybrid Data Access:** Implemented a hybrid data layer using **Entity Framework Core 10** for transactional write operations (guaranteeing domain invariant safety) and **Dapper (Micro-ORM)** for high-performance read queries.
*   **Domain-Driven Design (DDD):** Developed a rich domain model utilizing factory methods, private setters, and functional error handling (`ErrorOr` pattern) to eliminate exceptions in business flows and improve API response predictability.
*   **Modern Frontend Development:** Built a responsive e-commerce storefront in **Angular 21** utilizing **Angular Signals** for fine-grained reactive state management and **NgRx** (Store & Effects) for global state orchestration.
*   **Frontend Architecture:** Applied the **Facade Pattern** in Angular to decouple presentation components from state management, managing RxJS streams with modern APIs like `takeUntilDestroyed` to prevent memory leaks.
*   **Database Scaling & Optimization:** Integrated and configured **PgBouncer** as a connection pooler for the **PostgreSQL** database, reducing connection overhead and drastically increasing API throughput under high concurrency.
*   **Integrations & Storage:** Implemented secure payment flows via **Stripe API (PaymentIntents)** and established a multi-cloud file storage abstraction supporting **Azure Blob Storage**, **AWS S3**, and local **MinIO** emulation.
*   **DevOps & Deployment:** Contained all services (API, Angular Storefront, ERP, PostgreSQL, PgBouncer, MinIO, Nginx Gateway) using **Docker** and **Docker Compose** to guarantee environment parity from local development to production.
*   *Technology Stack:* .NET 10, C# 14, EF Core 10, Dapper, PostgreSQL, PgBouncer, Angular 21, NgRx, Signals, Tailwind CSS v4, PrimeNG, Stripe, Docker, Nginx, MinIO.

#### **Project: Buba (Construction Management System)**
*Full Stack Developer*
Instrumental in building a comprehensive construction management platform from the ground up, ensuring scalability and maintainability.
*   **Backend API:** Engineered a robust backend using **.NET 8** and **C# 12**, designing and implementing a full suite of RESTful APIs to handle core business logic for project management, resource allocation, and financial tracking.
*   **Data Layer:** Leveraged **Entity Framework Core 8** with a code-first approach to design the database schema and build a high-performance data access layer, optimizing complex queries against **SQL Server**.
*   **Frontend UI:** Developed a dynamic frontend using **Angular 17**, creating a rich user experience with modular components, reactive forms, and state management services.
*   *Technology Stack:* C# 12, .NET Core 8, SQL Server, EF Core 8, Angular 17.

#### **Project: Ed-Fi Alliance (Ed-Tech Platform Enablement)**
*Senior Software Engineer & Consultant*
Provided expert-level technical consultation and engineering support to help clients deploy and maintain the Ed-Fi data standard platform.
*   **Deployment Automation:** Orchestrated complex deployments of the .NET-based solution across IIS on Windows, containerized environments with **Docker** on Linux, and cloud-native setups on **Azure App Services**. Authored and maintained **PowerShell** automation scripts.
*   **Core Contributions:** Spearheaded debugging and resolution of complex issues in the core .NET Core and MVC codebase, contributing high-quality fixes back to the open-source project via pull requests.
*   **Database Management:** Resolved and optimized intricate data-layer issues across both **SQL Server** and **PostgreSQL** environments.
*   *Technology Stack:* C#, .NET Core MVC, Docker, SQL Server, PostgreSQL, PowerShell, Razor Pages, JavaScript.

#### **Project: Sync1 (FinTech Loan Platform)**
*Full Stack Developer (Contract)*
Developed and integrated key features for a high-availability loan origination platform serving US customers.
*   **Backend Features:** Engineered critical business rules and user authentication features in the **ASP.NET Core 3.1** backend, adhering to strict financial security standards.
*   **Asynchronous Messaging:** Decoupled backend services using **Azure Service Bus**, ensuring system resilience and scalability during peak loan application periods.
*   **UI Implementation:** Constructed intuitive user interfaces using **Angular 12** and **Angular Material**, creating a seamless responsive experience.
*   **Cloud Deployment:** Managed deployments and configurations on **Azure WebApps** to ensure high availability.
*   *Technology Stack:* C# 8, ASP.NET Core 3.1, EF Core 5, SQL Server, Angular 12, Angular Material, Azure WebApps, Azure Service Bus.

#### **Project: Everyware (Online Payment Solution)**
*Full Stack Developer*
Modernized a high-volume payment platform and improved internal administrative tooling.
*   **API Architecture:** Architected and led the development of a secure payment API using **ASP.NET Core** for sending payment links via SMS and email, integrating it with a new Angular frontend.
*   **System Integration:** Engineered the integration of the new API with a legacy SQL Server database, ensuring data consistency during migration.
*   **ERP Modernization:** Enhanced a critical internal ERP built on **.NET Core MVC** by refactoring legacy code and implementing new features using Razor Pages, JavaScript, and jQuery.
*   *Technology Stack:* C#, ASP.NET Core, EF Core, SQL Server, Angular, JavaScript, Razor Pages, JQuery, MVC.

---

### **Fibo Systems** | *Tech Lead & Co-Founder*
**December 2019 – January 2021**

Co-founded a software development agency, managing both technical leadership and business operations.
*   **Leadership & Architecture:** Gathered requirements directly from clients, designed system architectures, and led engineering teams as Technical Lead to ensure project delivery.
*   **DevOps & Infrastructure:** Configured and managed Linux virtual machines, establishing CI/CD pipelines and deployment processes.
*   **Business Alignment:** Aligned all development efforts with client business goals, balancing code quality with time-to-market and business value.
*   *Technology Stack:* .NET Core, JavaScript, Linux, Docker, cloud VPS.

---

### **Definity First** | *Web Engineer*
**May 2018 – June 2020**

Assigned to various enterprise client projects focusing on frontend, backend, or full-stack development.
*   **Healthcare Platform Migration:** Key contributor in migrating a legacy Silverlight healthcare application to **Angular 7**, developing complex frontend modules and workflows.
*   **UI/UX Component Refactoring:** Modernized the styles and usability of Angular components by customization and refactoring of the **PrimeNG** component library.
*   **Microservices Backend:** Designed and implemented new features for a healthcare backend using **.NET Core** microservices.
*   *Technology Stack:* C#, .NET Core, Microservices, Angular 7, PrimeNG, CSS/SASS.

---

### **ePesos.com** | *Full Stack .NET Developer*
**November 2016 – May 2018**

Developed a financial "Lending as a Service" platform offering monetary loans to small businesses.
*   **Core Banking API:** Designed and developed RESTful APIs to expose core banking services to external financial partners.
*   **Full Stack Features:** Built the administrative web platform using **ASP.NET MVC 5** and **AngularJS (1.5)**, utilizing **Entity Framework** for SQL Server access.
*   *Technology Stack:* C#, ASP.NET MVC 5, Entity Framework, SQL Server, AngularJS 1.5, Bootstrap, Azure WebApps.

---

### **Janus Automation** | *Software Engineer*
**March 2016 – November 2016**

*   Developed and maintained production-reporting software using C#, ASP.NET MVC 4, SQL Server, and jQuery.

---

### **BSD Enterprise** | *Software Engineer*
**February 2015 – March 2016**

*   **Fábrica de Software:** Developed, tested, and deployed web modules for various clients using ASP.NET MVC, Entity Framework, and SQL Server.
*   **OXXO Assignment:** Led the migration of an internal workflow system from Java to ASP.NET MVC, using C#, AngularJS, and Bootstrap.

---

### **Univisit** | *Desarrollador .NET*
**June 2012 – February 2015**

*   Maintained and upgraded legacy systems using C#, VB.NET, ASP.NET WebForms, Windows Forms, jQuery, and SQL Server.

---

### **Gameloft** | *Desarrollador PHP*
**June 2011 – June 2012**

*   Maintained and developed new features for the mobile game distribution site (WAPShop) using PHP, MySQL, and jQuery.

---

## EDUCATION

**Instituto Tecnológico de La Paz**  
*B.S. in Computer Systems Engineering (Ingeniero en Sistemas Computacionales)*  
La Paz, Baja California Sur, México | **2004 – 2010**

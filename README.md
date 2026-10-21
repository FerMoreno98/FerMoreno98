# Hola, soy Fernando 👋

**Desarrollador .NET** en Madrid. Trabajo con C#, ASP.NET Core y SQL Server, y en mis proyectos personales construyo aplicaciones full stack con **.NET y Angular**, con especial interés en la arquitectura de software, el código testeable y las buenas prácticas.

- 💼 Desarrollador web .NET en **Grupo Leben** desde 2024 (ASP.NET Core, Razor Pages, Blazor, SQL Server, Dapper)
- 🎓 Técnico Superior en DAM y DAW · Cursando el Grado en Ingeniería del Software en U-tad
- 🔨 Ahora mismo construyendo **[LightWeight](https://github.com/FerMoreno98/LightWeight)**
- 📫 [LinkedIn](https://www.linkedin.com/in/fernandomoreno-marzal) · fmorenomarzal@gmail.com

---

## 🏋️ Proyecto destacado: [LightWeight](https://github.com/FerMoreno98/LightWeight)

Plataforma para planificar y registrar entrenamientos de fuerza y hacer seguimiento de las métricas corporales. Está en desarrollo activo: autenticación, métricas corporales y dashboard ya funcionan; entrenamiento, nutrición e integración con dispositivos están en camino.

**Stack:** .NET 10 · ASP.NET Core Minimal APIs · EF Core · PostgreSQL · Angular 22 · TypeScript · Tailwind CSS · Docker

**Lo más interesante técnicamente:**

- **Monolito modular con DDD y CQRS.** 8 módulos independientes, cada uno con su propio esquema en PostgreSQL, que solo se comunican mediante eventos de integración.
- **Mediator propio** con pipeline behaviors que validan cada comando con FluentValidation antes de llegar al handler.
- **Autenticación sin contraseña** por código OTP enviado al email, con JWT y refresh tokens rotativos.
- **Dashboard construido a partir de eventos:** un read model que escucha los eventos de otros módulos y alimenta las gráficas de evolución.
- **Más de 450 tests unitarios** con xUnit, NSubstitute y FluentAssertions.
- **Entorno completo con Docker Compose:** API, base de datos, servidor SMTP de pruebas y frontend con un solo comando.

---

## 🛠️ Tecnologías

**Backend**

![C#](https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Blazor](https://img.shields.io/badge/Blazor-512BD4?style=for-the-badge&logo=blazor&logoColor=white)
![EF Core](https://img.shields.io/badge/EF_Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)

**Frontend**

![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)

**Bases de datos**

![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Dapper](https://img.shields.io/badge/Dapper-555555?style=for-the-badge)

**Testing y herramientas**

![xUnit](https://img.shields.io/badge/xUnit-5E2750?style=for-the-badge)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

**Arquitectura:** Clean Architecture · DDD · CQRS · Monolito modular · SOLID

---

## 📂 Otros proyectos

| Proyecto | Descripción | Stack |
|---|---|---|
| [DiarioFit](https://github.com/FerMoreno98/DiarioFit) | Diario de entrenamiento con rutinas, sesiones, series y medidas corporales | .NET 9 · Clean Architecture · MediatR · EF Core · Dapper · Angular |

---

<p align="center"><i>¿Hablamos? Escríbeme por <a href="https://www.linkedin.com/in/fernandomoreno-marzal">LinkedIn</a> o por email.</i></p>

<p align="center">
  <img src="https://raw.githubusercontent.com/fahmiprasetio/fahmiprasetio/main/assets/banner3.gif" alt="Banner" style="border-radius:20;"/>
</p>


# Hello There! I'm Fahmi

---

I am a Software Engineer focused on reliable systems, data integrity, and maintainable architecture. I develop applications end to end, from database schemas and business logic to client applications, automated tests, and deployment pipelines.

---

## About Me

- Engineering Focus: Application architecture, relational databases, and real-time systems.
- System Reliability: Transaction safety, concurrency control, and predictable behavior under load.
- Security: Authentication, authorization, rate limiting, and request verification.
- Delivery: Automated testing, code quality checks, and reproducible deployments.
- Development Approach: Understand the constraints, make technical tradeoffs explicit, and verify behavior with tests.

---

## Tech Stack and Tools

### Languages
- TypeScript, JavaScript, C#, Python, Dart, PHP, C++

### Application Frameworks and Design
- Frameworks: React, Next.js, Vue.js, Nuxt.js
- Styling and State: HTML5, CSS3, Tailwind CSS, Zustand, Pinia
- Animation and Graphics: GSAP, Three.js, Framer Motion
- Design: Interface design, wireframing, and prototyping

### Mobile Development
- Frameworks: Flutter, React Native
- State Management: Riverpod
- Integration: REST APIs, real-time updates, and polling fallbacks

### Backend Development and Data Engineering
- Frameworks: Node.js, Express.js, ASP.NET Core, FastAPI
- Real-Time Communication: SignalR
- Databases: PostgreSQL, MySQL, MongoDB, Redis
- Data Access: Prisma, Entity Framework Core
- Data Integration: ETL pipelines and transformation workflows with Pentaho Data Integration

### Infrastructure, Testing, and Delivery
- Containers: Docker, Docker Compose
- CI/CD: Jenkins
- Testing and Quality: Jest, Vitest, .NET test suites, SonarQube
- Version Control: Git
- Deployment: Container configuration, application configuration, and automated build and deployment workflows

---

## Engineering Practices

### Data Integrity and Concurrency
I use database constraints, transactions, and concurrency controls to enforce business rules. My projects include serializable isolation, optimistic versioning, and row locking to prevent duplicate order claims and overselling.

### Security and Verification
I implement authorization, rate limits, webhook signature verification, and server-side validation. Sensitive operations such as price calculation and stock reservation are handled on the server.

### Real-Time Communication
I build event-driven updates for application clients and account for unreliable connections with polling fallbacks. This keeps order state available when a persistent connection cannot be maintained.

### Testing and Maintainability
I use automated tests to check application behavior and quality gates to catch regressions before deployment. I have worked on production framework migrations, test coverage improvements, and CI pipeline integration.

---

## Selected Projects

### [UPNVJ Suruh](https://github.com/fahmiprasetio/UPNVJ_Suruh_MobileApp)
A campus errand platform with a Flutter application, a React administration dashboard, and an ASP.NET Core backend.

- Prevents competing runners from claiming the same order through transaction isolation, unique constraints, and optimistic concurrency checks.
- Delivers live order updates through SignalR, with polling as a fallback.
- Implements OTP authentication with hashed codes, constant-time comparison, and phone-number-based rate limits.

### [Spurr](https://github.com/fahmiprasetio/Spurr-Website)
A car rental application built with Next.js, TypeScript, Prisma, and PostgreSQL.

- Supports rental management through a role-based administration panel.
- Records rental status changes in an audit log.
- Reconciles payment events through webhooks and sends automated notifications.

### [Lonjak](https://github.com/fahmiprasetio/Pesta_Pora_Ticket_Pass)
A ticketing application designed for flash-sale traffic and concurrent purchases.

- Uses atomic stock reservation and PostgreSQL row locking to prevent overselling.
- Includes a waiting-room queue, order management, and QR-based ticket verification.
- Applies API rate limits to control request volume.

---

## Connect with Me

- LinkedIn: [Naufal Fahmi Prasetio](https://www.linkedin.com/in/naufal-fahmi-prasetio-b865072b9/)
- Instagram: [@fahmi.prasetio_](https://instagram.com/fahmi.prasetio_)
- Email: [nfahmi086@gmail.com](mailto:nfahmi086@gmail.com)

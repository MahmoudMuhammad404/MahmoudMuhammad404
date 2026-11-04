# Mahmoud Muhammad

Back-End Developer with a B.Sc. in Computer Science (CGPA 3.50/4.0) and 2+ years building production-grade, scalable web services with Node.js, NestJS, TypeScript, and Express.js. Experienced in REST API design, multi-tenant SaaS, payment gateway integration, real-time systems, and clean layered architecture across PostgreSQL, MySQL, MongoDB, and Redis. Delivered ERP, CRM, and POS platforms from design through production deployment.


[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mahmoud-muhammad-6774b92b3/)
[![Email](https://img.shields.io/badge/Email-C0392B?style=flat-square&logo=gmail&logoColor=white)](mailto:mahmoudmuhammadd0@gmail.com)
[![Resume](https://img.shields.io/badge/Resume-FF5733?style=flat-square&logo=readme&logoColor=white)](https://drive.google.com/file/d/1DJAvZxaJY3b8Ygb-Y4ZQHNMaW6oDvbJ4/view?usp=sharing)

---

## About

I build the parts of a system where mistakes are expensive: money movement, access control and data integrity. My work covers fintech, retail and SaaS platforms across Iraq, Libya, the USA and Canada, from data modelling and API design through production deployment.

I also lead. At Elshayeb I managed a team of 7 across two products and set the shared engineering standards: authentication and RBAC, error handling, caching, logging and migration pipelines.

**What I focus on**

- **Correctness under concurrency:** double-entry ledgers, row-level locking, idempotent webhooks and jobs
- **Security by default:** deny-by-default authorization, tenant isolation, encrypted storage, rotating sessions
- **Maintainable architecture:** layered Clean Architecture with boundaries enforced by tooling, not convention
- **Verification:** unit, integration (real databases via Testcontainers) and end-to-end tests, plus automated checks on API contracts

---

## Selected Work

> Commercial projects are proprietary, so they are described at a high level and the source is not public.

**Fisa3: B2B Digital Cards Brokerage Platform** · NestJS · PostgreSQL · Redis/BullMQ
Multi-party marketplace backend where suppliers sell digital cards and companies buy through one API.
- Designed a double-entry ledger for wallets and settlements, using fixed-point amounts and row-locked transactions to keep balances correct under concurrent requests
- Built deny-by-default authorization (roles, per-module permissions, tenant isolation) with rate-limited API keys and refresh-token rotation
- Implemented idempotent background jobs with stuck-job recovery and a transactional audit trail

**AlphaCard: Multi-Market POS Platform** · Node.js · Express · MySQL
- Integrated a bank payment SDK with 3D-Secure and built an idempotent webhook handler that absorbs gateway retries
- Implemented transactional wallet crediting that prevents duplicate or lost credits under concurrency
- Delivered JWT session handling with device-aware validation across four user roles

**Money Transfer & Currency Exchange Platform (USA and Canada)** · NestJS · PostgreSQL · TypeORM
- Architected a modular backend with layer boundaries enforced by custom ESLint rules and a shared library for errors, pagination and response envelopes
- Set up migrations, soft-delete auditability and a four-level test strategy using real PostgreSQL

**ERP & CRM Platform, Elshayeb** · Node.js · TypeScript · MongoDB · Socket.IO · Redis
- Built HR automation, sales management and lead distribution on MongoDB aggregation pipelines, with real-time messaging and a WhatsApp Business integration

**Public products:** [RaiseUp LMS](https://www.raiseuplearn.com/en) · El-Fatih ([App Store](https://apps.apple.com/eg/app/el-fatih-%D8%A7%D9%84%D9%81%D8%A7%D8%AA%D8%AD/id6752825312) · [Google Play](https://play.google.com/store/apps/details?id=com.alwsamsa.el_fathih))

---

## Experience

| Role | Period | Scope |
|---|---|---|
| **Back-End Developer**, IT Land Canada | Mar 2026 – Present | Owns payment-critical workflows end to end; moving new development from a legacy MVC codebase to layered architecture |
| **Back-End Developer**, Elshayeb | Nov 2025 – Present | Led a team of 7; owns backend architecture for an ERP/CRM and a multi-tenant SaaS product |
| **Back-End Developer**, MAVOID | Mar 2025 – Dec 2025 | Backend for the Kalima online and blended learning platform |

---

## Tech Stack

| | |
|---|---|
| **Languages** | ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F0DB4F?style=flat-square&logo=javascript&logoColor=black) |
| **Back-End** | ![Node.js](https://img.shields.io/badge/Node.js-3C873A?style=flat-square&logo=nodedotjs&logoColor=white) ![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white) ![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white) ![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white) ![BullMQ](https://img.shields.io/badge/BullMQ-DC382D?style=flat-square) ![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=black) |
| **Data** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) ![TypeORM](https://img.shields.io/badge/TypeORM-FE0803?style=flat-square&logo=typeorm&logoColor=white) ![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white) |
| **Quality & Tooling** | ![Jest](https://img.shields.io/badge/Jest-C21325?style=flat-square&logo=jest&logoColor=white) ![Testcontainers](https://img.shields.io/badge/Testcontainers-9AE9D7?style=flat-square&logo=testcontainers&logoColor=black) ![ESLint](https://img.shields.io/badge/ESLint-4B32C3?style=flat-square&logo=eslint&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![GitLab](https://img.shields.io/badge/GitLab-FC6D26?style=flat-square&logo=gitlab&logoColor=white) ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white) |
| **Integrations** | ![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white) ![Twilio](https://img.shields.io/badge/Twilio-F22F46?style=flat-square&logo=twilio&logoColor=white) ![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black) ![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?style=flat-square&logo=cloudinary&logoColor=white) |

---

## Education

**B.Sc. in Computer Science**, Alexandria University (2021 – 2025), CGPA 3.50 / 4.0
Arabic (native) · English (professional working proficiency)

---

<p align="center">Open to senior-track back-end roles. <a href="https://www.linkedin.com/in/mahmoud-muhammad-6774b92b3/">LinkedIn</a> · <a href="mailto:mahmoudmuhammadd0@gmail.com">Email</a></p>

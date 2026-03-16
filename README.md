# Fajar Nur Trengginas - Backend Developer Portfolio

Backend Developer with 3+ years of experience building scalable APIs, reliable backend services, and high-performance data processing flows.

Jombang, Jawa Timur, Indonesia  
Phone: +62 812 8342 2156
Email: <fajartrengginas@gmail.com>  
GitHub: <https://github.com/devfajar>

---

## Summary

I focus on backend engineering for production systems: designing RESTful APIs, improving database performance, and building reliable async processing.

Key strengths:

- REST API architecture and implementation
- Authentication and Single Sign-On (SSO)
- Queue and background job processing
- Query optimization and indexing strategy
- Production issue investigation and system reliability improvements
- Global API response standardization for error handling
- Unit testing implementation in Go services

---

## Core Tech Stack

### Languages

- PHP
- Go
- JavaScript / TypeScript

### Frameworks and Runtime

- Laravel
- NestJS
- Node.js

### Database and Caching

- MySQL
- PostgreSQL
- Redis

### Tools and Environment

- Git
- Postman
- Linux
- Firebase

---

## Backend Project Highlights

### 1) SSO Pendaftaran Siswa (Education Platform)

**Role:** Backend Developer (Laravel)  
**Context:** Simplified student onboarding with centralized authentication and account registration.

**Technical Contributions:**

- Initially integrated SSO flow in backend (input validation, account registration, and user data persistence)
- After alignment with the mobile team, SSO authentication was handled on the mobile side and backend focused on receiving verified user data requests
- Prepared API endpoints and data contracts for web/mobile clients to keep onboarding flow consistent
- Improved login-related data validation and secure request handling

**Outcome:**

- Authentication process became easier for users
- Security and reliability of login process improved

**Tech Stack:** Laravel, REST API, MySQL/PostgreSQL

### 2) Job Queue Pengumpulan Ujian Siswa

**Role:** Backend Developer (Laravel)  
**Context:** Handled high-load exam submission traffic without overloading synchronous requests.

**Technical Contributions:**

- Designed asynchronous processing using job queue architecture
- Implemented Redis-based queue processing where exam submissions are pushed to queue workers instead of being processed synchronously
- Added retry mechanism, failed job handling, and process separation for traffic spikes
- Coordinated payload and API behavior with frontend/mobile team

**Outcome:**

- System handled exam-submission spikes more reliably and reduced blocking on main request flow

**Tech Stack:** Laravel Queue, Redis, MySQL/PostgreSQL

### 3) API Kiosk and Smartboard Services

**Role:** Backend Developer (Laravel)  
**Context:** Built backend services for kiosk and learning-support devices.

**Technical Contributions:**

- Designed stable API endpoints for device integration
- Implemented authentication and authorization based on device scenarios
- Implemented caching strategy to speed up kiosk load and frequent data reads
- Applied database indexing on high-traffic queries to improve endpoint performance
- Optimized response time for priority endpoints

**Outcome:**

- Reduced p95 latency on priority endpoints from around 1000 ms to around 400-500 ms
- Performance improvement was validated through k6 load testing by fellow backend engineers in the team

**Tech Stack:** Laravel, REST API

### 4) API Monitoring Tamu (Company Guest Monitoring App)

**Role:** Backend Developer (Go)  
**Context:** Built integrated backend for mobile guest monitoring connected with central company systems.

**Technical Contributions:**

- Built the API using pure Go (without framework) for better control and lightweight performance
- Designed backend system and database for CCTV-based guest monitoring use case
- Used goroutines for concurrent/background processing workloads
- Implemented service and repository pattern for maintainable architecture
- Integrated Redis and Firebase for caching and notification/data flow support

**Outcome:**

- Delivered production-ready guest monitoring APIs with improved architecture quality

**Tech Stack:** Go, REST API, MySQL, PostgreSQL, Redis, Firebase

### 5) Sistem Internal Perusahaan

**Role:** Backend Developer (TypeScript)  
**Context:** Fixed production bugs and developed backend APIs for internal service systems.

**Technical Contributions:**

- Investigated and fixed backend bugs affecting operational workflows
- Added API endpoints based on frontend requirements
- Improved attendance-time recording flow for mobile-based employee attendance

**Outcome:**

- Added transaction-record APIs and improved attendance reliability

**Tech Stack:** NestJS (TypeScript), Node.js, Prisma, MySQL

---

## Engineering Principles

- Clean Architecture
- SOLID Principles
- Modular service design
- Asynchronous processing strategy
- Scalable database design

---

## Additional Backend Contributions

- Standardized global API response format to handle specific error cases consistently across services
- Implemented Go unit testing for selected backend modules to improve code reliability

---

## Contact

- GitHub: <https://github.com/devfajar>
- Email: <fajartrengginas@gmail.com>
- Phone: +62 812 8342 2156

---

Backend is where performance meets architecture.

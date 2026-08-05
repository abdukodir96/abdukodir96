<h1 align="center">Abdukodir Sheraliev</h1>

<h3 align="center">Full-Stack & AI Engineer</h3>

<p align="center">
  TypeScript • React • Next.js • NestJS • Python • FastAPI • AI/RAG • Docker
</p>

<p align="center">
  <a href="https://abdukodir96.github.io/Portfolio-Website_React/">Portfolio</a>
  •
  <a href="https://github.com/abdukodir96">GitHub</a>
  •
  <a href="https://t.me/abdukodir9796">Telegram</a>
</p>

---

## About Me

Full-Stack & AI Engineer with 3+ years of experience building scalable web applications, AI-powered SaaS platforms, and production-ready backend systems.

- Design secure RESTful and GraphQL APIs
- Build full-stack applications with TypeScript, React, Next.js, NestJS, and Node.js
- Develop asynchronous backend and AI services with Python and FastAPI
- Build RAG pipelines with embeddings, semantic vector search, and citation-backed responses
- Implement real-time communication using WebSockets and Server-Sent Events
- Integrate OpenAI, OpenRouter, Google Gemini, PyTorch, OpenCV, OCR, and text-to-speech technologies
- Deploy and operate applications using Docker, Linux, Nginx, SSL, PM2, and automated backups
- Architect and deliver software products from concept and data modeling to production deployment

Currently based in South Korea and open to Full-Stack, Backend, and AI Engineering opportunities.

---

## Core Technologies

| Area             | Technologies                                                                            |
| ---------------- | --------------------------------------------------------------------------------------- |
| **Languages**    | TypeScript, JavaScript, Python                                                          |
| **Frontend**     | React, Next.js, HTML5, CSS3, Tailwind CSS, Material UI                                  |
| **Backend**      | Node.js, NestJS, Express.js, FastAPI, RESTful APIs, GraphQL, Socket.IO, SSE             |
| **Databases**    | MongoDB, MongoDB Atlas Vector Search, PostgreSQL, MySQL, Redis, Prisma, Mongoose        |
| **AI & ML**      | OpenAI API, OpenRouter, Google Gemini API, RAG, Embeddings, TTS, PyTorch, OpenCV, OCR   |
| **DevOps**       | Docker, Docker Compose, Linux, Nginx, SSL, PM2, Git, GitHub, Postman                    |
| **Architecture** | Service-Oriented Architecture, Microservices, MVC, Monorepo, RBAC, Dependency Injection |
| **Security**     | JWT, bcrypt, Google OAuth, Rate Limiting, Role-Based Access Control, HTTPS              |

---

## Featured Project

### BookMind — AI Reading Assistant

Production-ready AI SaaS platform that helps users understand books and documents through AI-generated summaries, citation-backed document chat, and podcast-style audio overviews.

Users can upload PDF, EPUB, DOCX, or TXT files and interact with their content through a retrieval-augmented generation pipeline. Every answer is grounded in the uploaded document and includes traceable page-level citations.

**Engineering highlights:**

- Built the complete product independently from architecture and data modeling to deployment
- Multi-format document parsing for PDF, EPUB, DOCX, and TXT files
- Page-aware chunking for accurate source citations
- MongoDB Atlas Vector Search-based semantic retrieval
- Citation-backed RAG chat with document-scoped top-k retrieval
- Token-by-token AI response streaming through Server-Sent Events
- Custom SSE client using `fetch` and `ReadableStream`
- Map-reduce summarization for long documents
- Two-host podcast generation using LLM-generated scripts and text-to-speech
- Email/password authentication, Google OAuth, password recovery, and account deletion
- Rate limiting and member-scoped resource authorization
- Automated daily MongoDB and file backups
- Multi-stage Docker deployment with Nginx, SSL, and persistent VPS storage
- SEO and AI discoverability through sitemap, JSON-LD, Open Graph images, and `llms.txt`

**Tech Stack:**
Next.js 16 • TypeScript • Tailwind CSS v4 • Python • FastAPI • MongoDB Atlas • Atlas Vector Search • OpenAI API • OpenRouter • RAG • SSE • Docker • Nginx • FFmpeg

**Live:** [bookmind.online](https://bookmind.online)

**Repository:** [github.com/abdukodir96/BookMind](https://github.com/abdukodir96/BookMind)

---

## Architecture-Focused Project

### MediBridge — AI-Powered Medical Tourism Platform

Medical tourism marketplace designed to connect international patients with verified hospitals and clinics in South Korea.

The platform is being developed with a service-oriented, microservice-based architecture that separates core business operations, payments, real-time communication, and AI functionality into independent services.

**Engineering highlights:**

- API Gateway as the central entry point for authentication, routing, and rate limiting
- Core service for members, clinics, procedures, bookings, reviews, and medical documents
- Payment service with PostgreSQL and Prisma for transactional consistency
- Escrow-oriented payment state management
- Payment idempotency to prevent duplicate transactions
- Atomic booking state transitions to handle concurrent requests
- JWT authentication and role-based access control for Patient, Clinic, and Admin roles
- GraphQL API for complex frontend data requirements
- TCP-based communication between NestJS services
- Database-per-service architecture
- Docker Compose-based development environment
- Cross-service consistency handling between MongoDB and PostgreSQL
- Real-world debugging of serialization, race conditions, and distributed data consistency

**Tech Stack:**
Next.js • TypeScript • NestJS • GraphQL • MongoDB • PostgreSQL • Prisma • Redis • Python • FastAPI • Docker

**Development Status:** In active development

---

## Selected Projects

### NearHelp — Community Assistance Platform

Location-based community platform that helps users discover and connect with nearby service providers through scalable APIs, online booking, real-time communication, and AI-assisted service discovery.

**Engineering highlights:**

- NestJS monorepo backend with GraphQL
- Role-based authentication for users, agents, and administrators
- Online booking with real-time status updates
- AI-powered service recommendations and semantic search
- Real-time messaging with Socket.IO
- Multilingual Next.js frontend
- Docker, Nginx, and Linux deployment

**Tech Stack:**
Next.js • NestJS • GraphQL • MongoDB • Socket.IO • Docker • OpenAI API • Google Gemini API

**Live:** [nearhelps.com](https://nearhelps.com)

---

### QuickStay — Hotel Booking Platform

Full-stack hotel booking platform featuring secure authentication, online payments, room management, reservation workflows, and an owner administration dashboard.

**Engineering highlights:**

- Server-side date-range validation to prevent double bookings
- Secure Stripe Checkout integration
- Signed webhook verification for payment confirmation
- Clerk authentication with MongoDB synchronization
- Role-protected hotel owner dashboard
- Automated booking confirmation and receipt emails
- Docker, Nginx, SSL, and Linux production deployment

**Tech Stack:**
React • Express.js • MongoDB • Clerk • Stripe • Cloudinary • Tailwind CSS • Docker • Nginx

**Live:** [quickstayhotel.com](https://quickstayhotel.com)

---

### AI Habit Tracker — AI-Powered Productivity Platform

AI-powered productivity platform that provides personalized habit coaching, intelligent progress tracking, and data-driven recommendations based on each user's real completion history.

**Engineering highlights:**

- AI coaching grounded in real habit and completion data
- Weekly AI progress reports
- Personalized recovery plans after broken streaks
- Structured AI output parsing with fallback handling
- Interactive charts and completion heatmaps
- Fully usable even when the AI provider is unavailable
- Docker, Nginx, and SSL production deployment

**Tech Stack:**
React • FastAPI • Python • OpenAI API • Google Gemini API

**Live:** [aihabittracker.online](https://aihabittracker.online)

---

## Professional Experience

### Full-Stack & DevOps Engineer

**Digital City IT Center**

Built scalable web and AI applications, developed RESTful and GraphQL services, integrated databases, and managed production deployment using Docker, Nginx, PM2, and Linux.

Worked with TypeScript, Node.js, NestJS, Express.js, FastAPI, Python, MongoDB, MySQL, Redis, Prisma, PyTorch, OpenCV, and LLM APIs.

### Backend & Frontend Developer

**Atlantis Gravity**

Developed and maintained full-stack web applications using React, Next.js, Node.js, Express.js, Python, MongoDB, and MySQL.

Collaborated through Git and GitHub-based monorepo workflows while implementing features, fixing bugs, improving performance, and maintaining existing services.

---

## Languages

- Uzbek — Native
- Korean — Advanced, TOPIK Level 6
- English — Advanced, Business Communication
- Russian — Elementary

---

## GitHub Analytics

<p align="center">
  <img width="49%" src="https://github-readme-stats.vercel.app/api?username=abdukodir96&show_icons=true&theme=default&hide_border=true" />
  <img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=abdukodir96&layout=compact&hide_border=true" />
</p>

---

## Contact

- **Portfolio:** [abdukodir96.github.io/Portfolio-Website_React](https://abdukodir96.github.io/Portfolio-Website_React/)
- **GitHub:** [github.com/abdukodir96](https://github.com/abdukodir96)
- **Telegram:** [@abdukodir9796](https://t.me/abdukodir9796)

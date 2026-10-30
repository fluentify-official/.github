# 🌐 Fluentify

<p align="center">
  <img src="https://img.shields.io/badge/Fluentify-English%20Learning-6366F1?style=for-the-badge" />
  <img src="https://img.shields.io/badge/AI-Powered-8B5CF6?style=for-the-badge&logo=openai&logoColor=white" />
  <img src="https://img.shields.io/badge/Platform-Cross--Platform-0EA5E9?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Organization-fluentify--official-181717?style=for-the-badge&logo=github" />
</p>

<p align="center">
  <strong>Làm chủ tiếng Anh theo cách của riêng bạn.</strong>
</p>

<p align="center">
  An AI-powered English learning ecosystem designed to make language learning more personalized, interactive, and accessible.
</p>

---

## 📖 About Fluentify

**Fluentify** is an AI-powered English learning ecosystem built to help learners improve their English proficiency through personalized learning experiences, interactive exercises, and intelligent AI assistance.

The platform combines modern mobile technology, scalable backend services, artificial intelligence, and centralized content administration to create a comprehensive language learning environment.

Fluentify provides a connected ecosystem where learners can practice English, administrators can manage educational content, and AI services can deliver intelligent and adaptive learning experiences.

Our goal is to make English learning more flexible, engaging, and accessible — allowing every learner to develop their skills at their own pace.

### 🎯 Our Vision

To create a personalized English learning ecosystem where technology and artificial intelligence empower learners to achieve their language goals.

### 🚀 Our Mission

- Deliver personalized English learning experiences.
- Make language learning accessible across mobile platforms.
- Integrate AI into everyday learning activities.
- Help learners develop practical communication skills.
- Build a flexible and scalable learning ecosystem.
- Provide structured educational content and intelligent learning resources.
- Create a centralized platform for managing learning data and AI operations.

---

## 🧩 Project Ecosystem

Fluentify is organized into four independent repositories, each responsible for a specific part of the ecosystem.

| Repository | Description | Main Technology |
|---|---|---|
| 📱 [fluentify-mobile](https://github.com/fluentify-official/fluentify-mobile) | Cross-platform English learning application for Android and iOS. | Flutter · Dart |
| ⚙️ [fluentify-backend](https://github.com/fluentify-official/fluentify-backend) | Backend APIs, business logic, authentication, learning data, and application services. | NestJS · TypeScript |
| 🤖 [fluentify-ai-service](https://github.com/fluentify-official/fluentify-ai-service) | AI-powered learning capabilities, intelligent tutoring, language processing, model training, and AI integrations. | AI / Python |
| 💎 [fluentify-management](https://github.com/fluentify-official/fluentify-management) | Centralized administration for educational content, datasets, AI operations, users, subscriptions, and system management. | Next.js · React · TypeScript |

### 📱 Fluentify Mobile

The mobile application provides the primary learning experience for Fluentify users.

Core learning areas:

- 📚 Vocabulary
- 📝 Grammar
- 🎧 Listening
- 🗣️ Speaking
- 📖 Reading
- ✍️ Writing
- 🤖 AI Tutor
- 📊 Learning Progress
- 🎯 Daily Tasks & Challenges
- 💎 Rewards & Achievements

Repository: [fluentify-mobile](https://github.com/fluentify-official/fluentify-mobile)

### ⚙️ Fluentify Backend

The backend provides the core application infrastructure, business logic, and APIs connecting the Fluentify ecosystem.

Main responsibilities:

- 🔐 Authentication and authorization.
- 👤 User and profile management.
- 📚 Learning content data management.
- 📝 Exercises and assessments.
- 📈 Learning progress tracking.
- 🔄 Data synchronization.
- 💎 Token and Coin transaction management.
- 📦 Subscription and package management.
- 🎯 Event and reward processing.
- 🔔 Notification services.
- 🔗 Integration with AI services.
- 🛡️ Security and audit logging.

Repository: [fluentify-backend](https://github.com/fluentify-official/fluentify-backend)

### 🤖 Fluentify AI Service

The AI Service provides intelligent capabilities that enhance the English learning experience.

Planned responsibilities:

- 💬 AI English Tutor.
- 🧠 Context-aware language explanations.
- 🗣️ AI conversation practice.
- 🎙️ Speech-to-Text integration.
- 🔊 Text-to-Speech integration.
- 📢 Pronunciation assessment.
- ✍️ AI writing evaluation.
- 🎯 Personalized learning recommendations.
- 📝 AI-powered exercise generation.
- 📊 Learning performance analysis.
- 🗂️ Dataset preprocessing and management.
- 🏋️ Model training and evaluation.
- 🧪 Model versioning and experimentation.
- 🚀 AI model deployment and inference.

Repository: [fluentify-ai-service](https://github.com/fluentify-official/fluentify-ai-service)

### 💎 Fluentify Management

The centralized administration platform responsible for managing educational content, AI operations, and the business operations of the entire Fluentify ecosystem.

Core management areas:

- 📊 Dashboard & Analytics.
- 📚 Vocabulary, Grammar & Learning Content.
- 📝 Question Banks, Quizzes & Lessons.
- 🗂️ Educational Dataset Management.
- 🎯 Daily Tasks, Challenges & Achievements.
- 🎉 Events, Campaigns & Rewards.
- 🧠 AI Dataset & Model Management.
- 🏋️ AI Training & Evaluation Operations.
- 👥 User & Account Management.
- 📦 Subscription & Package Management.
- 💎 Token & Coin Management.
- 💰 Revenue & Transaction Monitoring.
- 🔔 Notification & Announcement Management.
- 🛡️ Roles, Permissions & Audit Logs.
- ⚙️ System Configuration.

Repository: [fluentify-management](https://github.com/fluentify-official/fluentify-management)

---

## 🏗️ System Architecture

Fluentify follows a modular architecture in which each repository has a clearly defined responsibility.

```text
                    FLUENTIFY ECOSYSTEM
                              │
              ┌───────────────┴───────────────┐
              │                               │
              ▼                               ▼
    ┌────────────────────┐          ┌────────────────────┐
    │   Fluentify Mobile │          │ Fluentify Management│
    │   Flutter / Dart   │          │ Next.js / React     │
    └──────────┬─────────┘          └──────────┬─────────┘
               │                               │
               │        HTTPS / REST API       │
               └───────────────┬───────────────┘
                               │
                               ▼
                  ┌────────────────────────┐
                  │    Fluentify Backend  │
                  │    NestJS / TypeScript│
                  └────────────┬───────────┘
                               │
                 ┌─────────────┴─────────────┐
                 │                           │
                 ▼                           ▼
       ┌──────────────────┐       ┌────────────────────┐
       │   Data Layer     │       │ Fluentify AI       │
       │                  │       │ Service            │
       │   PostgreSQL     │       │                    │
       │   Redis          │       │ AI Processing      │
       │   Object Storage │       │ Model Training     │
       └──────────────────┘       │ AI Integrations    │
                                  └────────────────────┘
```

### 🔄 Service Responsibilities

| Component | Responsibility |
|---|---|
| Fluentify Mobile | User-facing learning experience and mobile interactions. |
| Fluentify Management | Administrative interfaces, content input, data management, AI operations, and system control. |
| Fluentify Backend | Core business logic, APIs, authentication, authorization, and data persistence. |
| Fluentify AI Service | AI processing, dataset operations, model training, evaluation, and inference. |
| Data Layer | Persistent storage, caching, and file management. |

### Architectural Principles

- Separation of concerns.
- Modular and maintainable design.
- Clear service responsibilities.
- Secure API communication.
- Provider-independent AI integration.
- Scalable and testable components.
- Offline-friendly mobile experience.
- Centralized content administration.
- Data integrity and version management.
- Secure and auditable administrative operations.

---

## 📚 Documentation

This repository serves as the central documentation hub for the Fluentify ecosystem.

All product specifications, technical documentation, architectural decisions, and development guidelines are organized inside the `docs/` directory.

### Documentation Structure

```text
.github/
│
├── README.md
│
├── docs/
│   │
│   ├── product/
│   │   ├── PRD.md
│   │   ├── SRS.md
│   │   ├── FEATURES.md
│   │   └── ROADMAP.md
│   │
│   ├── architecture/
│   │   ├── SYSTEM_ARCHITECTURE.md
│   │   ├── MOBILE_ARCHITECTURE.md
│   │   ├── BACKEND_ARCHITECTURE.md
│   │   ├── AI_ARCHITECTURE.md
│   │   ├── MANAGEMENT_ARCHITECTURE.md
│   │   └── ADR/
│   │
│   ├── database/
│   │   ├── DATABASE_DESIGN.md
│   │   ├── ERD.md
│   │   └── DATA_DICTIONARY.md
│   │
│   ├── api/
│   │   ├── API_OVERVIEW.md
│   │   ├── AUTHENTICATION.md
│   │   └── ENDPOINTS.md
│   │
│   ├── design/
│   │   ├── UI_UX_GUIDELINES.md
│   │   ├── DESIGN_SYSTEM.md
│   │   └── USER_FLOWS.md
│   │
│   ├── content/
│   │   ├── CONTENT_GUIDELINES.md
│   │   ├── LEARNING_CONTENT.md
│   │   ├── QUESTION_BANKS.md
│   │   └── DATA_IMPORT_GUIDELINES.md
│   │
│   ├── ai/
│   │   ├── DATASET_GUIDELINES.md
│   │   ├── MODEL_TRAINING.md
│   │   └── AI_OPERATIONS.md
│   │
│   ├── security/
│   │   ├── SECURITY_POLICY.md
│   │   └── DATA_PRIVACY.md
│   │
│   ├── development/
│   │   ├── SETUP_GUIDE.md
│   │   ├── CODING_CONVENTIONS.md
│   │   └── TESTING_GUIDELINES.md
│   │
│   └── deployment/
│       ├── DEPLOYMENT_GUIDE.md
│       └── ENVIRONMENT_CONFIGURATION.md
│
├── ISSUE_TEMPLATE/
├── PULL_REQUEST_TEMPLATE.md
└── profile/
    └── README.md
```

### 📚 Documentation Categories

| Category | Purpose |
|---|---|
| `product/` | Product vision, requirements, features, and roadmap. |
| `architecture/` | System architecture and architectural decisions. |
| `database/` | Database schema, ERD, relationships, and data dictionary. |
| `api/` | API specifications, authentication, and endpoint documentation. |
| `design/` | UI/UX guidelines, design system, and user flows. |
| `content/` | Educational content structures, question banks, and data import standards. |
| `ai/` | Dataset management, model training, and AI operational guidelines. |
| `security/` | Security policies and data privacy requirements. |
| `development/` | Development environment, coding standards, and testing guidelines. |
| `deployment/` | Deployment processes and environment configuration. |

---

## 🛠️ Technology Overview

The Fluentify ecosystem uses technologies selected for maintainability, performance, scalability, and extensibility.

| Component | Technology |
|---|---|
| Mobile Application | Flutter · Dart |
| Management Platform | Next.js · React · TypeScript |
| Backend Framework | NestJS · TypeScript |
| Database | PostgreSQL |
| ORM | Prisma |
| Caching | Redis |
| AI Service | Python · AI / LLM Providers |
| API Communication | REST API |
| Containerization | Docker |
| Version Control | Git · GitHub |

*Technology choices may evolve as the project develops.*

---

## 🔒 Security & Privacy

Security and user privacy are important principles throughout the Fluentify ecosystem.

- Never commit API keys, passwords, or access tokens.
- Keep sensitive credentials in environment variables or secret management services.
- Use secure authentication and authorization mechanisms.
- Enforce role-based permissions for administrative operations.
- Validate and sanitize incoming requests.
- Apply appropriate rate limiting to public APIs and AI endpoints.
- Protect user data and enforce access controls.
- Maintain audit logs for sensitive administrative actions.
- Validate uploaded datasets and educational content.
- Follow responsible data retention and deletion practices.
- Avoid exposing sensitive information in application logs.

For security-related issues, please follow the organization's private reporting process rather than publishing sensitive vulnerability details in public issues.

---

## 🗺️ Project Roadmap

### Phase 1 — Foundation

- [ ] Establish the Fluentify ecosystem.
- [ ] Set up mobile application architecture.
- [ ] Set up backend architecture.
- [ ] Establish AI service architecture.
- [ ] Establish management platform architecture.
- [ ] Design the initial database schema.
- [ ] Implement authentication and user management.
- [ ] Establish API communication between services.

### Phase 2 — Core Learning

- [ ] Vocabulary learning and spaced repetition.
- [ ] Grammar lessons and exercises.
- [ ] Listening and reading modules.
- [ ] Learning assessment.
- [ ] Learning progress tracking.
- [ ] Offline learning support.
- [ ] Centralized educational content management.
- [ ] Question bank and quiz management.

### Phase 3 — AI-Powered Learning

- [ ] AI English Tutor.
- [ ] AI conversation practice.
- [ ] Pronunciation assessment.
- [ ] AI writing evaluation.
- [ ] Personalized learning recommendations.
- [ ] AI-generated exercises.
- [ ] Dataset management and model evaluation.

### Phase 4 — Gamification & Ecosystem Management

- [ ] Daily tasks and weekly challenges.
- [ ] Achievement and reward systems.
- [ ] Learning streak management.
- [ ] Event and campaign management.
- [ ] Token and Coin economy.
- [ ] Subscription and package management.
- [ ] Administrative analytics.
- [ ] Revenue and transaction monitoring.

### Phase 5 — Optimization & Expansion

- [ ] Adaptive learning experiences.
- [ ] Advanced learning analytics.
- [ ] Enhanced data synchronization.
- [ ] AI model optimization.
- [ ] Performance and scalability improvements.
- [ ] Expanded learning content.
- [ ] Advanced management and monitoring capabilities.

---

## 📌 Organization

**GitHub Organization:** [fluentify-official](https://github.com/fluentify-official)

### Official Repositories

| Repository | Description |
|---|---|
| 📱 [Fluentify Mobile](https://github.com/fluentify-official/fluentify-mobile) | Cross-platform English learning application. |
| ⚙️ [Fluentify Backend](https://github.com/fluentify-official/fluentify-backend) | Core backend, APIs, and business services. |
| 🤖 [Fluentify AI Service](https://github.com/fluentify-official/fluentify-ai-service) | AI processing, model training, and intelligent learning services. |
| 💎 [Fluentify Management](https://github.com/fluentify-official/fluentify-management) | Centralized content, AI, and ecosystem administration. |
| 📚 [.github](https://github.com/fluentify-official/.github) | Organization documentation and configuration. |

---

<p align="center">
  <img src="https://img.shields.io/badge/Built%20with-Passion-EC4899?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Powered%20by-Innovation-6366F1?style=for-the-badge" />
</p>

<h3 align="center">🌐 Fluentify</h3>

<p align="center">
  <strong>Làm chủ tiếng Anh theo cách của riêng bạn.</strong>
</p>

<p align="center">
  Learn at your pace. Grow with confidence. Speak without limits.
</p>

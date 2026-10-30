<h1 align="center">🌐 Fluentify</h1>

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

The platform combines modern mobile technology, scalable backend services, and artificial intelligence to create a comprehensive language learning environment.

Our goal is to make English learning more flexible, engaging, and accessible — allowing every learner to develop their skills at their own pace.

### 🎯 Our Vision

To create a personalized English learning ecosystem where technology and artificial intelligence empower learners to achieve their language goals.

### 🚀 Our Mission

- Deliver personalized English learning experiences.
- Make language learning accessible across mobile platforms.
- Integrate AI into everyday learning activities.
- Help learners develop practical communication skills.
- Build a flexible and scalable learning ecosystem.

---

## 🧩 Project Ecosystem

Fluentify is organized into three independent repositories, each responsible for a specific part of the ecosystem.

| Repository | Description | Main Technology |
|---|---|---|
| 📱 [fluentify-mobile](https://github.com/fluentify-official/fluentify-mobile) | Cross-platform English learning application for Android and iOS. | Flutter · Dart |
| ⚙️ [fluentify-backend](https://github.com/fluentify-official/fluentify-backend) | Backend APIs, business logic, authentication, learning data, and application services. | NestJS · TypeScript |
| 🤖 [fluentify-ai-service](https://github.com/fluentify-official/fluentify-ai-service) | AI-powered learning capabilities, intelligent tutoring, language processing, and AI integrations. | AI Service |

### 📱 Fluentify Mobile

The mobile application provides the primary learning experience.

Core learning areas:

- 📚 Vocabulary
- 📝 Grammar
- 🎧 Listening
- 🗣️ Speaking
- 📖 Reading
- ✍️ Writing
- 🤖 AI Tutor
- 📊 Learning Progress

Repository: [fluentify-mobile](https://github.com/fluentify-official/fluentify-mobile)

### ⚙️ Fluentify Backend

The backend provides the core application infrastructure and business services.

Main responsibilities:

- 🔐 Authentication and authorization.
- 👤 User and profile management.
- 📚 Learning content management.
- 📝 Exercises and assessments.
- 📈 Learning progress tracking.
- 🔄 Data synchronization.
- 🔗 Integration with AI services.

Repository: [fluentify-backend](https://github.com/fluentify-official/fluentify-backend)

### 🤖 Fluentify AI Service

The AI Service provides intelligent capabilities that enhance the learning experience.

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

Repository: [fluentify-ai-service](https://github.com/fluentify-official/fluentify-ai-service)

---

## 🏗️ System Architecture

Fluentify follows a modular architecture in which each repository has a clearly defined responsibility.

```text
                 ┌──────────────────────┐
                 │    Fluentify Mobile  │
                 │    Flutter / Dart    │
                 └──────────┬───────────┘
                            │
                            │ HTTPS / REST API
                            ▼
                 ┌──────────────────────┐
                 │   Fluentify Backend │
                 │   NestJS / TypeScript│
                 └──────────┬───────────┘
                            │
                 ┌──────────┴───────────┐
                 │                      │
                 ▼                      ▼
       ┌─────────────────┐    ┌──────────────────┐
       │   PostgreSQL    │    │ Fluentify AI     │
       │   Redis         │    │ Service          │
       │   Data Storage  │    │ AI Integrations  │
       └─────────────────┘    └──────────────────┘
```

### Architectural Principles

- Separation of concerns.
- Modular and maintainable design.
- Clear service responsibilities.
- Secure API communication.
- Provider-independent AI integration.
- Scalable and testable components.
- Offline-friendly mobile experience.

---

## 📂 Documentation

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
│   ├── security/
│   │   ├── SECURITY_POLICY.md
│   │   └── DATA_PRIVACY.md
│   │
│   ├── development/
│   │   ├── SETUP_GUIDE.md
│   │   ├── CODING_CONVENTIONS.md
│   │   ├── GIT_WORKFLOW.md
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
| `security/` | Security policies and data privacy requirements. |
| `development/` | Development environment, coding standards, and Git workflow. |
| `deployment/` | Deployment processes and environment configuration. |

---

## 🛠️ Technology Overview

The Fluentify ecosystem uses technologies selected for maintainability, performance, and extensibility.

| Component | Technology |
|---|---|
| Mobile Application | Flutter · Dart |
| Backend Framework | NestJS · TypeScript |
| Database | PostgreSQL |
| ORM | Prisma |
| Caching | Redis |
| AI Integration | AI / LLM Providers |
| API Communication | REST API |
| Containerization | Docker |
| Version Control | Git · GitHub |

*Technology choices may evolve as the project develops.*

---

## 🌱 Development Workflow

Fluentify uses a branch-based development workflow to maintain code quality and coordinate development across repositories.

### Branch Strategy

| Branch | Purpose |
|---|---|
| `main` | Stable and production-ready code. |
| `develop` | Integration branch for ongoing development. |
| `feature/*` | New feature development. |
| `fix/*` | Bug fixes. |
| `refactor/*` | Code restructuring and optimization. |
| `docs/*` | Documentation updates. |
| `release/*` | Release preparation. |

### Development Flow

```text
feature/* ─────┐
fix/* ─────────┼───► develop
refactor/* ────┤       │
docs/* ────────┘       │
                       │ Pull Request
                       ▼
                     main
```

### Commit Convention

Fluentify follows Conventional Commits.

| Type | Description |
|---|---|
| `feat` | Introduce a new feature. |
| `fix` | Fix a bug. |
| `docs` | Update documentation. |
| `refactor` | Refactor existing code. |
| `test` | Add or update tests. |
| `chore` | Maintenance and tooling updates. |
| `perf` | Improve performance. |

Examples:

```bash
feat(mobile): implement vocabulary flashcards

feat(backend): add authentication endpoints

feat(ai): integrate AI tutor

docs(architecture): update system architecture

fix(mobile): resolve navigation issue
```

---

## 🔒 Security & Privacy

Security and user privacy are important principles throughout the Fluentify ecosystem.

- Never commit API keys, passwords, or access tokens.
- Keep sensitive credentials in environment variables or secret management services.
- Use secure authentication and authorization mechanisms.
- Validate and sanitize incoming requests.
- Apply appropriate rate limiting to public APIs and AI endpoints.
- Protect user data and enforce access controls.
- Follow responsible data retention and deletion practices.
- Avoid exposing sensitive information in application logs.

For security-related issues, please follow the organization's private reporting process rather than publishing sensitive vulnerability details in public issues.

---

## 🤝 Contribution Guidelines

Contributions and suggestions are welcome.

Before submitting changes:

1. Check the existing issues and project documentation.
2. Create a feature branch from the appropriate `develop` branch.
3. Follow the coding conventions of the relevant repository.
4. Write or update tests when necessary.
5. Ensure the project builds and passes its required checks.
6. Submit a Pull Request with a clear description of the changes.

All contributions should follow the development guidelines of the relevant repository.

---

## 🗺️ Project Roadmap

### Phase 1 — Foundation

- [ ] Establish the Fluentify ecosystem.
- [ ] Set up mobile application architecture.
- [ ] Set up backend architecture.
- [ ] Establish AI service architecture.
- [ ] Design the initial database schema.
- [ ] Implement authentication and user management.

### Phase 2 — Core Learning

- [ ] Vocabulary learning and spaced repetition.
- [ ] Grammar lessons and exercises.
- [ ] Listening and reading modules.
- [ ] Learning assessment.
- [ ] Learning progress tracking.
- [ ] Offline learning support.

### Phase 3 — AI-Powered Learning

- [ ] AI English Tutor.
- [ ] AI conversation practice.
- [ ] Pronunciation assessment.
- [ ] AI writing evaluation.
- [ ] Personalized learning recommendations.
- [ ] AI-generated exercises.

### Phase 4 — Optimization & Expansion

- [ ] Adaptive learning experiences.
- [ ] Advanced learning analytics.
- [ ] Enhanced synchronization.
- [ ] Performance optimization.
- [ ] Expanded learning content.

---

## 📌 Organization

**GitHub Organization:** [fluentify-official](https://github.com/fluentify-official)

### Official Repositories

- 📱 [Fluentify Mobile](https://github.com/fluentify-official/fluentify-mobile)
- ⚙️ [Fluentify Backend](https://github.com/fluentify-official/fluentify-backend)
- 🤖 [Fluentify AI Service](https://github.com/fluentify-official/fluentify-ai-service)
- 📚 [Fluentify Documentation & Organization Configuration](https://github.com/fluentify-official/.github)

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

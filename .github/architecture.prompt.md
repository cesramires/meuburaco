You are a Principal Software Architect designing a production-ready MVP platform.

# Goal
Design a scalable application where authenticated users upload images with metadata. Images are automatically moderated. Approved images are published to Instagram and a public website.

Frontend language:
- Portuguese (Brazil)

Developer ecosystem:
- Python-first

# Core Features
- Google Login
- Apple Login
- Camera capture
- Gallery upload
- Image description
- Image date
- AI moderation:
  - Pornography
  - Advertisement
  - People detection
- Automatic Instagram publishing
- Automatic public website publishing

# Architecture Constraints

## Backend
Preferred stack:
- Python 3.12+
- FastAPI
- PostgreSQL
- SQLAlchemy 2.0
- Pydantic v2
- Redis
- Celery or Dramatiq

## Frontend
Choose best option between:
1. Expo + React Native Web
2. Next.js PWA

Decision criteria:
- Shared codebase
- Mobile support
- Simplicity
- Fast MVP
- Camera support
- Maintainability

## Infrastructure
- Docker
- GitHub Actions
- S3-compatible object storage
- CDN
- Reverse proxy
- Queue workers

# Deliverables
Produce:

1. High-level architecture
2. System context diagram
3. Component diagram
4. Monorepo structure
5. Database schema
6. API architecture
7. Authentication architecture
8. Moderation pipeline architecture
9. Publishing pipeline architecture
10. Public website architecture
11. Security architecture
12. Scalability strategy
13. Observability strategy
14. Event-driven workflow design
15. Async processing design
16. Error handling strategy
17. Infrastructure topology
18. Cost optimization recommendations
19. Technical tradeoffs
20. Future evolution roadmap

# Requirements

## Security
Include:
- OAuth2/OIDC
- JWT strategy
- Signed uploads
- File validation
- Malware scanning strategy
- Secrets management
- API throttling
- CORS/CSRF handling
- Audit logs

## Scalability
Design for:
- Millions of uploads
- Horizontal scaling
- Async workloads
- CDN distribution
- Queue-based processing

## Moderation
Create provider abstraction for:
- AWS Rekognition
- Google Vision
- OpenAI vision models

## Publishing
Design:
- Instagram Graph API integration
- Retry strategy
- Dead-letter handling
- Idempotent jobs
- Publish status tracking

# Constraints
- Avoid microservices for MVP
- Prefer modular monolith
- Prioritize maintainability
- Minimize operational complexity
- Use async workflows

# Output
Provide a comprehensive prompt for GPT-5.3 Codex model covering the following sections:
1. Executive Summary
2. Architecture Diagrams
3. Tech Decisions
4. Data Model
5. API Design
6. Async Workflows
7. Security
8. Infrastructure
9. Scaling Strategy
10. Risks & Tradeoffs


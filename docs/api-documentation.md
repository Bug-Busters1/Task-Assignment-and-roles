```markdown
# 🔌 Comprehensive API Documentation (REST & AI Inference)
**Project:** QA Assistant System & Smart AI-Powered Bug Triage

---

## Authentication & Security Standard
All API endpoints require authentication using a **Bearer JWT (JSON Web Token)** passed in the request header:
```http
Authorization: Bearer <JWT_ACCESS_TOKEN>
Content-Type: application/json

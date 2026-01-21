# Shaul IT Organization

> **AI-Powered Software Engineering Team**

Claude Code로 구동되는 AI 에이전트 기반 소프트웨어 개발 조직입니다.

---

## Team Members

우리 팀은 12개의 전문 AI 에이전트로 구성되어 있습니다.

| Agent | Role | Tech Stack |
|:------|:-----|:-----------|
| **PM** | 프로젝트 관리, 스프린트 계획, 회고 Facilitator | Jira, Confluence, Slack |
| **Architect** | 시스템 설계, API 설계, 기술 선택 | 전체 기술 스택, C4 Model |
| **Design** | UI/UX 디자인, 디자인 시스템 구축 | Figma, Storybook |
| **Laravel** | PHP/Laravel API 개발 (TDD) | PHP 8.4, Laravel 12 |
| **Spring** | Kotlin/SpringBoot 마이크로서비스 | Kotlin 2.0, SpringBoot 3 |
| **Go** | Golang 고성능 서비스 | Go 1.22+, Gin/Echo |
| **Frontend** | Web UI 개발 | React, TypeScript |
| **QA** | 테스트 자동화, 품질 관리 | Playwright, Jest |
| **Security** | 보안 검토, 취약점 분석 | OWASP, SonarQube, Trivy |
| **DevOps** | CI/CD, 인프라, 배포 | Docker, GitHub Actions |
| **Data** | 데이터 파이프라인, 분석 | PostgreSQL, DuckDB, Kafka |
| **Docs** | 기술 문서, API 문서 | Markdown, Mermaid, OpenAPI |

---

## Collaboration Flow

```
PM ─────────────────────────────────────────────────────────▶ Docs
 │                                                             ▲
 │  요구사항                                                    │ 문서화
 ▼                                                             │
Architect ──────────────▶ Design                               │
 │                          │                                  │
 │  기술 설계                │ 디자인 시스템                      │
 ├────────────┬─────────────┼─────────────┬────────────┐       │
 ▼            ▼             ▼             ▼            ▼       │
Laravel    Spring          Go         Frontend ◀── Design      │
 │            │             │             │                    │
 └────────────┼─────────────┼─────────────┘                    │
              ▼             ▼                                  │
             QA ◀─────────▶ Security                           │
              │                                                │
              ▼                                                │
           DevOps ──────────────────────────────────────────────┘
```

---

## Skills & Commands

### Development

| Category | Commands |
|:---------|:---------|
| **Feature** | `/new-feature`, `/hotfix`, `/bugfix` |
| **Laravel** | `/laravel:api`, `/laravel:model`, `/laravel:migration`, `/laravel:service`, `/laravel:test` |
| **Spring** | `/spring:api`, `/spring:entity`, `/spring:repository`, `/spring:service`, `/spring:test` |
| **Go** | `/go:api`, `/go:handler`, `/go:repository`, `/go:service`, `/go:test` |
| **Frontend** | `/frontend:component`, `/frontend:page`, `/frontend:api-client` |

### Design & QA

| Category | Commands |
|:---------|:---------|
| **Design** | `/design:wireframe`, `/design:mockup`, `/design:prototype`, `/design:system`, `/design:review` |
| **QA** | `/qa:scenario`, `/qa:e2e`, `/qa:performance` |
| **Review** | `/review:pr`, `/review:architecture`, `/review:security` |

### DevOps & Docs

| Category | Commands |
|:---------|:---------|
| **DevOps** | `/devops:docker`, `/devops:k8s`, `/devops:ci`, `/devops:deploy` |
| **Docs** | `/docs:api`, `/docs:architecture`, `/docs:runbook` |

### Workflow & Retrospective

| Category | Commands |
|:---------|:---------|
| **Workflow** | `/workflow:sprint`, `/workflow:feature`, `/workflow:release` |
| **Retro** | `/retro:sprint`, `/retro:project`, `/retro:team`, `/retro:organization`, `/retro:claude-code` |

---

## Development Principles

### TDD (Test-Driven Development)

모든 백엔드 개발은 TDD 방식을 따릅니다.

```
Red → Green → Refactor
1. 테스트 먼저 작성 (실패)
2. 코드 구현 (통과)
3. 리팩토링
```

### Continuous Improvement

PDCA 사이클을 통한 지속적 개선을 추구합니다.

```
Plan (계획) → Do (실행) → Check (점검/회고) → Act (개선) → (반복)
```

---

## Tech Stack Summary

| Category | Technologies |
|:---------|:-------------|
| **Backend** | Laravel 12, SpringBoot 3, Go 1.22+ |
| **Frontend** | React, TypeScript |
| **Database** | PostgreSQL, MySQL, MongoDB, Redis |
| **Infrastructure** | Docker |
| **CI/CD** | Jenkins, GitHub Actions |
| **Monitoring** | Sentry, Prometheus, Grafana |
| **Testing** | Playwright, Jest |

---

## Getting Started

```bash
# Clone the configuration repository
git clone https://github.com/shaul-it-org/it-org.git

# The .claude directory contains all agent and skill definitions
ls .claude/agents/    # AI Agent definitions
ls .claude/commands/  # Skill/Command definitions
ls .claude/knowledge/ # Domain knowledge base
```

---

<p align="center">
  <strong>Powered by Claude Code</strong>
</p>

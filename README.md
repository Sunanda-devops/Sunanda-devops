# Ashok M.

### Backend Engineer | Python, .NET, Flask, RabbitMQ, Docker

I build production-oriented backend systems and review AI-generated code with an adversarial eye. My work focuses on secure APIs, reliable distributed workflows, testable architecture, and the failure modes that are easy to miss in a fast code review.

## What I work on

- Production Python and .NET services
- Flask APIs, RabbitMQ workflows, MySQL, and Docker
- Concurrency, validation, security, and failure analysis
- Adversarial testing for AI-generated code
- Clear technical documentation and reproducible developer workflows

## Featured work

### ML Leakage & Validation Benchmark

[![Tests](https://img.shields.io/badge/tests-10%20passing-2ea44f?style=flat-square)](https://github.com/Ashokm96/ml-leakage-benchmark)
[![Python](https://img.shields.io/badge/Python-3.11%2B-3776ab?style=flat-square&logo=python&logoColor=white)](https://github.com/Ashokm96/ml-leakage-benchmark)

[ml-leakage-benchmark](https://github.com/Ashokm96/ml-leakage-benchmark) is a deterministic, adversarial benchmark for model-generated ML code. It detects data leakage, invalid time-series validation, and unstable or irreproducible training through both source-aware graders and runtime checks. It includes intentionally flawed starters, corrected solutions, pinned dependencies, Docker support, CI, architecture documentation, and JSON/Markdown report generation.

### AI Code Audit Lab

[ai-code-audit-lab](https://github.com/Ashokm96/ai-code-audit-lab) documents three realistic AI-generated failures: a race condition, SQL injection paired with a fake test pass, and a hallucinated package. Each audit includes evidence, severity, reasoning quality, a corrected patch, and a regression test.

### Secure LMS Platform

[LMS](https://github.com/Ashokm96/LMS) is a .NET and Angular learning platform with environment-based configuration, fail-fast validation, Docker Compose, a `/health` endpoint, CI build checks, vulnerability scanning, Gitleaks, and a security review.

### EuniMart services

[task-eunimart](https://github.com/Ashokm96/task-eunimart) is a production-oriented Flask, RabbitMQ, and MySQL service with an application factory, pure testable functions, six tests, Docker Compose, and CI using pytest, Black, Flake8, and Bandit.

## Engineering principles

- Prefer explicit boundaries over hidden coupling.
- Treat validation as part of the feature, not a final step.
- Make failure modes observable and reproducible.
- Keep security and operational behavior close to the code that needs it.
- Document the reasoning behind a fix so the next reviewer can verify it.

## Contact

Open an issue or discussion in one of the repositories above for technical collaboration, code review, or benchmark ideas.

# Sunanda DevOps

### Software Engineer | Coding-Agent Evaluation | Python · TypeScript · AWS · Docker

I build production-oriented systems and evaluate generated code with an engineering and security mindset. My strongest work sits where software engineering judgment becomes measurable: realistic task design, adversarial review, executable regression tests, explicit rubrics, reproducible results, and clear technical feedback.

## What I bring to agentic coding environments

- Design realistic engineering tasks from concurrency, security, data, and operational failure modes.
- Red-team plausible implementations instead of accepting a green test signal at face value.
- Turn review judgment into security invariants, acceptance criteria, and regression suites.
- Compare unsafe and hardened implementations with deterministic, machine-readable reports.
- Document the reasoning flaw, evidence, remediation, and remaining operational caveats.
- Work independently with Python and TypeScript while keeping CI, Docker, and deployment behavior reproducible.

## Selected evidence

### Secure Code Review Forge

[![Tests](https://img.shields.io/badge/tests-16%20passing-2ea44f?style=flat-square)](https://github.com/Sunanda-devops/secure-code-review-forge)

[secure-code-review-forge](https://github.com/Sunanda-devops/secure-code-review-forge) is an independent security review environment for generated backend code. Four cases cover concurrent idempotency, path traversal, SSRF allowlists, and tenant authorization. Each case includes an unsafe fixture, threat model, security invariant, hardened implementation, audit narrative, and regression tests. A catalog CLI produces text, Markdown, or JSON evidence for review workflows.

### ML Validation Integrity Suite

[ml-validation-integrity-suite](https://github.com/Sunanda-devops/ml-validation-integrity-suite) is a deterministic benchmark for model-generated ML code. It tests leakage-safe preprocessing, time-aware validation, and stable training through adversarial source checks, runtime scoring, repeatability checks, a documented rubric, and CI-generated reports.

### LearnFlow LMS

[learnflow-LMS](https://github.com/Sunanda-devops/learnflow-LMS) is a full-stack learning platform built with React, Express, tRPC, Drizzle, and MySQL. It demonstrates real feature implementation, authenticated progress tracking, seed data, Docker Compose, architecture documentation, and production-oriented troubleshooting.

### DevOps and cloud delivery

- [devops-production-readiness-lab](https://github.com/Sunanda-devops/devops-production-readiness-lab) — production-readiness, security, CI/CD, and operational controls.
- [ct-aws-docker-k8s](https://github.com/Sunanda-devops/ct-aws-docker-k8s) — AWS, Terraform, Docker, EKS, Helm, Jenkins, monitoring, Route 53, ACM, and RDS.
- [jenkins-terraform-aws-eks-cicd-pipeline-project](https://github.com/Sunanda-devops/jenkins-terraform-aws-eks-cicd-pipeline-project) — automated build, test, containerization, and cloud delivery.
- [devops-portfolio](https://github.com/Sunanda-devops/devops-portfolio) — selected work across CI/CD, AWS, Terraform, Docker, Kubernetes, and observability.

## Review standard

- Define what must be true before choosing how to implement it.
- Test the dangerous path, not only the happy-path return value.
- Treat reproducibility and observability as part of correctness.
- Separate evidence from explanation and confidence from proof.
- Prefer a small, reviewable fix with a regression test over a broad rewrite.

## Collaboration

Open an issue or discussion in one of the repositories above for technical collaboration, benchmark ideas, security review, or reproducibility feedback.

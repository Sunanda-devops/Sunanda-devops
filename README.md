# Sunanda DevOps

### Software Engineer | Cloud Delivery, Platform Engineering & Coding-Agent Evaluation

**5+ years of hands-on experience** building, automating, securing, and documenting software delivery systems. I work across Python and TypeScript backends, AWS infrastructure, containers, Kubernetes, CI/CD, observability, and adversarial evaluation of generated code.

## Professional summary

Software engineer focused on making engineering quality measurable. I design realistic technical tasks, red-team plausible implementations, define explicit acceptance criteria, and turn failures into regression tests and clear remediation guidance. My engineering work combines production-oriented application development with independent benchmarks for security, correctness, and reproducibility.

## Core skills

**Languages:** Python, TypeScript, JavaScript, Bash, HCL/Terraform

**Backend & application:** Flask, FastAPI, Express, React, tRPC, REST APIs, MySQL, PostgreSQL, Redis

**Cloud & infrastructure:** AWS, EKS, EC2, RDS, S3, Lambda, API Gateway, DynamoDB, Terraform, Ansible

**Containers & orchestration:** Docker, Docker Compose, Kubernetes, Helm, Kustomize, ECR, GitOps

**CI/CD & security:** Jenkins, GitHub Actions, Trivy, Bandit, Gitleaks, dependency hygiene, secret-safe configuration

**Observability:** Prometheus, Grafana, Alertmanager, CloudWatch, Splunk, structured logging, health checks

**Evaluation focus:** coding-agent task design, adversarial review, threat modeling, security invariants, regression testing, rubrics, deterministic reports, technical writing

## Featured engineering evidence

### Secure Code Review Forge — Python, Security, Testing

[secure-code-review-forge](https://github.com/Sunanda-devops/secure-code-review-forge) is an independent review environment for generated backend code.

- Four audit cases cover concurrent idempotency, path traversal, SSRF allowlists, and tenant authorization.
- Each case includes an unsafe fixture, threat model, security invariant, hardened implementation, audit narrative, and regression tests.
- A catalog CLI produces text, Markdown, and JSON evidence for review workflows.
- CI verifies **16 regression tests**.

### ML Validation Integrity Suite — Python, Benchmarking, Reproducibility

[ml-validation-integrity-suite](https://github.com/Sunanda-devops/ml-validation-integrity-suite) is a deterministic benchmark for model-generated ML code.

- Tests leakage-safe preprocessing, time-aware validation, and stable training.
- Combines adversarial source checks, runtime scoring, repeatability checks, and an explicit evaluation rubric.
- Generates machine-readable and Markdown reports for CI and model comparison.
- CI verifies **10 tests** and repeatable scores.

### LearnFlow LMS — TypeScript, React, Express, MySQL

[learnflow-LMS](https://github.com/Sunanda-devops/learnflow-LMS) is a production-minded learning platform with a learner dashboard, searchable course library, lesson player, authenticated progress tracking, admin metrics, seed data, Docker Compose, architecture documentation, and troubleshooting guidance.

### Cloud-native delivery and platform engineering

- [devops-portfolio](https://github.com/Sunanda-devops/devops-portfolio) — CI/CD, Terraform, AWS, Docker, Kubernetes, serverless, monitoring, and logging reference projects.
- [devops-production-readiness-lab](https://github.com/Sunanda-devops/devops-production-readiness-lab) — Flask health service, secure containers, EKS infrastructure, CI quality gates, Gitleaks, and Trivy.
- [ct-aws-docker-k8s](https://github.com/Sunanda-devops/ct-aws-docker-k8s) — Terraform, Docker, EKS, Helm, Jenkins, SonarQube, Trivy, Prometheus, Grafana, Route 53, ACM, and RDS.
- [jenkins-terraform-aws-eks-cicd-pipeline-project](https://github.com/Sunanda-devops/jenkins-terraform-aws-eks-cicd-pipeline-project) — FastAPI, PostgreSQL, Docker Compose, Jenkins, Terraform, Kubernetes, EKS, and monitoring.
- [End-to-End-DevOps-Project](https://github.com/Sunanda-devops/End-to-End-DevOps-Project) — AWS infrastructure, Jenkins CI, ArgoCD GitOps, EKS, EFS, ALB, Prometheus, and Grafana.

## Engineering and review standard

- Define what must be true before choosing how to implement it.
- Test the dangerous path, not only the happy-path return value.
- Separate evidence from explanation and confidence from proof.
- Treat reproducibility, observability, and safe configuration as part of correctness.
- Prefer a small, reviewable fix with a regression test over a broad rewrite.
- Document the failure, the reasoning flaw, the remediation, and the remaining caveats.

## Collaboration

Open an issue or discussion in one of the repositories above for technical collaboration, coding-agent benchmark ideas, security review, or reproducibility feedback.

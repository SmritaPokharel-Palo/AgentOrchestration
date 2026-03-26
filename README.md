# Agent Orchestration (Using Claude Code)

This project aims to build a robust agent orchestrator using the Claude Code API from Anthropic.

## CI/CD Pipeline

This project uses a hybrid CI/CD approach:

-   **GitHub Actions**: Lightweight verification (Build, Security Scan, Terraform Scan).
-   **Buildkite**: Enterprise-grade orchestration (Deployment, Multi-stage builds).
    -   Config: `.buildkite/pipeline.yml`

## setup

```bash
npm install
```

## Running Tests

```bash
npm test
```

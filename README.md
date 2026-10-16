# terraform-aws-platform

> Infrastructure as code for deploying a containerised API on AWS — VPC, ECS Fargate, RDS PostgreSQL, ALB, CloudFront and Secrets Manager with Terraform.

![status](https://img.shields.io/badge/status-in%20progress-yellow) ![area](https://img.shields.io/badge/area-Cloud%20Computing-blue) ![license](https://img.shields.io/badge/license-MIT-green)

🚧 **Work in progress.** This repo is part of my public learning roadmap (**Phase 3 — Cloud**). I build in the open — follow the commits and the roadmap below.

## Why this project

Learn cloud infrastructure properly — everything in code, reviewable, repeatable and with costs under control.

## What I'm learning

- Terraform modules, remote state and environments
- AWS networking (VPC, subnets, security groups)
- Containers on ECS Fargate behind a load balancer
- Managed PostgreSQL (RDS) and Secrets Manager
- IAM least privilege and cost awareness

## Planned stack

Terraform · AWS (VPC, ECS Fargate, RDS, ALB, CloudFront, Secrets Manager) · GitHub Actions (OIDC)

## Roadmap

- [ ] Remote state (S3 + locking) and folder layout
- [ ] VPC module
- [ ] RDS PostgreSQL module
- [ ] ECS Fargate service for `lt-vocab-api` behind an ALB
- [ ] Secrets Manager + IAM roles
- [ ] `dev` and `prod` environments
- [ ] `terraform plan` in CI with OIDC (no long-lived keys)
- [ ] README: diagram, monthly cost estimate and teardown steps

## Part of a 10-repo learning roadmap

I'm a full-stack developer in Vilnius ([armansalek.com](https://armansalek.com)) growing into **Python, Go, DevOps, cloud and AI engineering**. These repos connect: the Python and Go services are containerised, deployed and monitored by the DevOps and cloud repos, and the AI projects run on that infrastructure.

| # | Repo | Area | Phase |
|---|---|---|---|
| 1 | [lt-jobs-scraper](https://github.com/arman-aru/lt-jobs-scraper) | Python | 1 |
| 2 | [lt-vocab-api](https://github.com/arman-aru/lt-vocab-api) | Python | 1 |
| 3 | [parcel-locker-api](https://github.com/arman-aru/parcel-locker-api) | Golang | 1 |
| 4 | [go-uptime](https://github.com/arman-aru/go-uptime) | Golang | 1 |
| 5 | [ci-cd-pipelines](https://github.com/arman-aru/ci-cd-pipelines) | DevOps | 2 |
| 6 | [k8s-gitops-lab](https://github.com/arman-aru/k8s-gitops-lab) | DevOps | 2 |
| 7 | **terraform-aws-platform** (this repo) | Cloud Computing | 3 |
| 8 | [serverless-media-pipeline](https://github.com/arman-aru/serverless-media-pipeline) | Cloud Computing | 3 |
| 9 | [site-audit-agent](https://github.com/arman-aru/site-audit-agent) | AI Engineering | 4 |
| 10 | [migration-rag-assistant](https://github.com/arman-aru/migration-rag-assistant) | AI Engineering | 4 |

## License

[MIT](LICENSE) © Arman Salek

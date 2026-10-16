# terraform-aws-platform

> Infrastructure as code for deploying a containerised API on AWS — VPC, ECS Fargate, RDS PostgreSQL, ALB, CloudFront and Secrets Manager with Terraform.

![status](https://img.shields.io/badge/status-in%20development-yellow) ![license](https://img.shields.io/badge/license-MIT-green)

## Overview

Terraform code that provisions a complete AWS environment for a containerised API: networking, ECS Fargate, a managed PostgreSQL database, load balancing, a CDN and secrets — for separate dev and prod environments.

## Features

- Reusable Terraform modules (VPC, RDS, ECS service)
- ECS Fargate service behind an Application Load Balancer
- RDS PostgreSQL with secrets in AWS Secrets Manager
- CloudFront CDN
- Separate `dev` and `prod` environments with remote state
- `terraform plan` in CI using GitHub OIDC — no long-lived keys

## Tech stack

Terraform · AWS (VPC, ECS Fargate, RDS, ALB, CloudFront, Secrets Manager) · GitHub Actions (OIDC)

## License

[MIT](LICENSE) © Arman Salek

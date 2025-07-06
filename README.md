**Note:** This project is a fork of `opentelemetry-demo`. Thanks to the team and contributors for opensourcing this wonderful demo project. Definitely one of the best on internet.

<!-- markdownlint-disable-next-line -->
# <img src="https://opentelemetry.io/img/logos/opentelemetry-logo-nav.png" alt="OTel logo" width="45"> OpenTelemetry Demo

[![Slack](https://img.shields.io/badge/slack-@cncf/otel/demo-brightgreen.svg?logo=slack)](https://cloud-native.slack.com/archives/C03B4CWV4DA)
[![Version](https://img.shields.io/github/v/release/open-telemetry/opentelemetry-demo?color=blueviolet)](https://github.com/open-telemetry/opentelemetry-demo/releases)
[![Commits](https://img.shields.io/github/commits-since/open-telemetry/opentelemetry-demo/latest?color=ff69b4&include_prereleases)](https://github.com/open-telemetry/opentelemetry-demo/graphs/commit-activity)
[![Downloads](https://img.shields.io/docker/pulls/otel/demo)](https://hub.docker.com/r/otel/demo)
[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg?color=red)](https://github.com/open-telemetry/opentelemetry-demo/blob/main/LICENSE)
[![Integration Tests](https://github.com/open-telemetry/opentelemetry-demo/actions/workflows/run-integration-tests.yml/badge.svg)](https://github.com/open-telemetry/opentelemetry-demo/actions/workflows/run-integration-tests.yml)
[![Artifact Hub](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/opentelemetry-demo)](https://artifacthub.io/packages/helm/opentelemetry-helm/opentelemetry-demo)
[![OpenSSF Best Practices](https://www.bestpractices.dev/projects/9247/badge)](https://www.bestpractices.dev/en/projects/9247)

## Welcome to the OpenTelemetry Astronomy Shop Demo

This repository contains the OpenTelemetry Astronomy Shop, a microservice-based
distributed system intended to illustrate the implementation of OpenTelemetry in
a near real-world environment

## Quick start

You can be up and running with the demo in a few minutes. Check out the docs for
your preferred deployment method:

- [Docker](https://opentelemetry.io/docs/demo/docker_deployment/)
- [Kubernetes](https://opentelemetry.io/docs/demo/kubernetes_deployment/)

## Documentation

For detailed documentation, see [Demo Documentation][docs]. If you're curious
about a specific feature, the [docs landing page][docs] can point you in the
right direction.

# 🚀 End-to-End DevOps Implementation for E-Commerce Platform 🛍️

This repository showcases a comprehensive DevOps project implementing a 3-tier e-commerce architecture using OpenTelemetry-powered microservices across AWS EKS 🌟.

## 📚 Project Overview
- **Multi-language Microservices**: Python, Go, and Node.js services with OpenTelemetry instrumentation 📊
- **AWS Infrastructure**: EKS cluster, VPC, IAM roles, Route53 DNS, and security groups 🌐
- **Containerization**: Docker images for each microservice with optimized layers 📦
- **IaC**: Terraform for provisioning cloud resources 🌿
- **GitOps**: Argo CD for Kubernetes manifest synchronization 🔄
- **CI/CD**: GitHub Actions building Docker images and triggering Argo CD deployments 🚀

## 📝 What I Learned
- **Infrastructure as Code (IaC)**: Managed 90% of infrastructure with Terraform 🌿
- **Containerization**: Created Docker images for multiple microservices 📦
- **Kubernetes Orchestration**: Deployed and managed services with Kubernetes 🚀
- **CI/CD Pipelines**: Automated build, test, and deployment using GitHub Actions 🔄
- **GitOps**: Implemented Argo CD for automated Kubernetes deployments 🔄
- **Monitoring & Tracing**: Used OpenTelemetry for unified service monitoring 📊

## 🙏 Acknowledgments
Special thanks to [Abhishek Veeramalla](https://www.udemy.com/user/abhishek-veeramalla/) for his exceptional *"Ultimate DevOps Project"* Udemy course that formed the foundation of this implementation 🙏.

---

📌 **Note:** Replace placeholder values with actual values before deployment.  
📂 Repository Structure organized by component:  
├── terraform/ # Infrastructure code

├── k8s/ # Kubernetes manifests

├── src/ # Microservices source

├── github/ # CI/CD workflows

└── docs/ # Architecture diagrams & runbooks

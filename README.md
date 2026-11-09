# End-to-End DevOps Project

A hands-on project taking a Node.js and MySQL application from containerization to automated deployment on AWS Kubernetes.

The project combines Docker, Kubernetes, monitoring, Jenkins CI pipelines, reusable shared libraries, and GitOps delivery with Argo CD.

## Project Scope

- Containerize the application and database using Docker Compose.
- Configure a Kubernetes cluster on AWS EC2.
- Manage application configuration, persistent storage, networking, and access permissions.
- Monitor infrastructure using Prometheus, Grafana, and Alertmanager.
- Build and scan Docker images using Jenkins and Trivy.
- Execute CI pipelines on a dedicated AWS EC2 Jenkins agent.
- Update deployment manifests in Git and deploy automatically through Argo CD.

## Source Repositories

| Repository | Purpose |
|---|---|
| [Application and CI Pipeline](https://github.com/Hager-83/ivolve-app-cicd/tree/lab23-portfolio-v1) | Application source, Docker configuration, Jenkinsfile, and Kubernetes deployment manifest. |
| [Jenkins Shared Library](https://github.com/Hager-83/iVolve-jenkins-shared-library/tree/lab23-portfolio-v1) | Reusable functions for application preparation, image building and scanning, and GitOps manifest updates. |
| [Training Labs](https://github.com/Hager-83/iVolve-training) | Detailed implementation steps and supporting lab documentation. |

> This project documents the implementation through Lab 23. Source links point to the `lab23-portfolio-v1` snapshots.

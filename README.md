# TechTrends: Cloud Native Fundamentals 
Techtrends is part of _Udacity - Cloud Native Application Architecture Nanodegree_
This project demonstrates the end-to-end deployment of a Python Flask application using modern DevOps practices, including containerization, continuous integration, and automated deployment with GitOps.

- Language: Python 3.8
- Framework: Flask
- Database: SQLite
- CI/CD: GitHub Actions
- Container Runtime: Docker
- Orchestration: Kubernetes (k3s)
- Package Manager: Helm
- GitOps Tool: ArgoCD

# Getting started

## Prerequisites
- Vagrant & VirtualBox
- Docker Hub account
- GitHub account

1. Clone the repository
2. Spin up the environment: `vagrant up` `vagrant ssh`
3. Deploy the aplication `kubetcl apply -f kubernetes`
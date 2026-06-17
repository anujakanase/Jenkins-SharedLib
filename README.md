# 🚀 Jenkins Shared Library

## 📖 Overview

This repository contains reusable Jenkins Shared Library functions designed to standardize, simplify, and automate CI/CD pipeline development.

Using Shared Libraries helps eliminate duplicate code, improve maintainability, and enforce DevOps best practices across multiple Jenkins pipelines.

---

## 🎯 Project Objectives

* Centralize common Jenkins pipeline logic
* Reduce code duplication
* Improve pipeline maintainability
* Enable reusable CI/CD components
* Standardize DevOps workflows across projects

---

## ⚙️ Shared Library Functions

### Git Checkout

Automates source code checkout from Git repositories.

**Usage:**

```groovy
code_checkout("repository-url","branch")
```

---

### Trivy Filesystem Scan

Performs security scanning to detect vulnerabilities in source code and dependencies.

**Usage:**

```groovy
trivy_scan()
```

---

### OWASP Dependency Check

Identifies vulnerable third-party dependencies used in applications.

**Usage:**

```groovy
owasp_dependency()
```

---

### SonarQube Analysis

Performs static code analysis and evaluates code quality.

**Usage:**

```groovy
sonarqube_analysis("Sonar","project-key","project-name")
```

---

### SonarQube Quality Gate

Validates whether the project meets predefined quality standards.

**Usage:**

```groovy
sonarqube_code_quality()
```

---

### Docker Build

Builds Docker images dynamically.

**Usage:**

```groovy
docker_build("image-name","tag","dockerhub-user")
```

---

### Docker Push

Pushes Docker images to Docker Hub.

**Usage:**

```groovy
docker_push("image-name","tag","dockerhub-user")
```

---

## 🔄 CI/CD Workflow

```text
GitHub
   │
   ▼
Code Checkout
   │
   ▼
Trivy Scan
   │
   ▼
OWASP Dependency Check
   │
   ▼
SonarQube Analysis
   │
   ▼
Quality Gate Validation
   │
   ▼
Docker Build
   │
   ▼
Docker Push
   │
   ▼
Deployment
```

---

## 🔐 DevSecOps Integration

This Shared Library integrates:

* Jenkins
* GitHub
* Docker
* SonarQube
* Trivy
* OWASP Dependency Check

to implement DevSecOps best practices within CI/CD pipelines.

---

## 📈 Benefits

✔ Reusable Pipeline Components

✔ Reduced Code Duplication

✔ Faster Pipeline Development

✔ Centralized Maintenance

✔ Improved Security Scanning

✔ Standardized CI/CD Workflows

✔ Scalable Jenkins Architecture

---

## 🛠️ Technologies Used

* Jenkins
* Groovy
* GitHub
* Docker
* SonarQube
* Trivy
* OWASP Dependency Check

---

## 📚 Learning Outcomes

Through this project, I gained hands-on experience in:

* Jenkins Shared Libraries
* Pipeline Automation
* DevSecOps Practices
* Groovy Scripting
* CI/CD Pipeline Design
* Security Integration
* Reusable Jenkins Components

---

## 👩‍💻 Author

### Anuja Kanase

DevOps Engineer | AWS | Terraform | Docker | Kubernetes | Jenkins | GitOps | DevSecOps

⭐ If you found this repository useful, consider starring it.

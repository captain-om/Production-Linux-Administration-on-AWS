# Jenkins CI/CD Pipeline

## Objective

The objective of this implementation was to automate repository validation using Jenkins and demonstrate a basic Continuous Integration (CI) workflow.

---

## Environment

- Ubuntu 24.04 EC2
- Jenkins
- GitHub Repository
- Git
- PHP
- Composer

---

## Jenkins Pipeline Stages

### 1. Checkout

- Clone the GitHub repository
- Checkout the `main` branch

### 2. Environment Validation

Verified:

- Hostname
- Current user
- Working directory
- Linux kernel information

### 3. Git Validation

Verified:

- Git installation
- Repository status
- Recent commits

### 4. Repository Validation

Verified project structure:

- README.md
- configs/
- docs/
- screenshots/

### 5. PHP Validation

Verified:

- PHP installation
- Composer installation

### 6. Build Complete

Pipeline finished successfully after all validation stages passed.

---

## Result

- Successfully connected Jenkins to GitHub
- Successfully executed the Jenkins Pipeline
- Repository validation completed successfully

---

## Skills Demonstrated

- Jenkins Installation
- Pipeline as Code
- Git Integration
- Linux Shell Commands
- Continuous Integration (CI)

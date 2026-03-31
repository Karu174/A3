# A3: CI and CD Pipeline with GitHub Actions

## 📌 Description
This project implements a basic CI/CD pipeline using GitHub Actions.

## ⚙️ Continuous Integration (CI)

The CI workflow is defined in `.github/workflows/ci.yml`.

### 🔹 Trigger
- Executes on:
  - push
  - pull request

### 🔹 Functionality
- Checks out the repository
- Runs a basic validation step (simulated CI process)

## 🚀 Continuous Deployment (CD)

The CD workflow is defined in `.github/workflows/cd.yml`.

### 🔹 Trigger
- Executes on:
  - push to main branch

### 🔹 Functionality
- Checks out the repository
- Simulates deployment of the project

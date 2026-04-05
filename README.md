# 🚀 Terraform GitHub Actions CI Project

This project demonstrates a **CI (Continuous Integration) pipeline** using GitHub Actions to automatically validate Terraform infrastructure code on every push.

---

## 📌 Project Overview

In this project, we implemented a CI workflow that:

- Automatically triggers on every push to the repository
- Initializes Terraform configuration
- Validates Terraform code
- Ensures infrastructure code is error-free before deployment

This is a basic but important step in **DevOps automation and Infrastructure as Code (IaC)**.

---

## 🛠️ Tech Stack

- Terraform
- GitHub Actions
- AWS (S3 - sample resource)
- Git & GitHub

---

## ⚙️ CI Workflow

The pipeline is defined using GitHub Actions and performs the following steps:

1. Checkout repository code
2. Setup Terraform environment
3. Run `terraform init`
4. Run `terraform validate`

---

## 📸 CI Pipeline Output

![CI Pipeline](./screenshots/ci-success.png)

---

## 📂 Project Structure

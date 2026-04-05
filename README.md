# 🚀 Terraform GitHub Actions CI Project

This project demonstrates a simple CI pipeline using GitHub Actions to validate Terraform code.

---

## 🛠 Tools Used
- Terraform
- GitHub Actions
- AWS (S3)

---

## ⚙️ What This Project Does
- Runs automatically on every push
- Initializes Terraform
- Validates Terraform code

---

## 🔄 CI Workflow
This pipeline is triggered whenever code is pushed to the `main` branch.

### Steps:
1. Checkout repository code
2. Setup Terraform
3. Run `terraform init`
4. Run `terraform validate`

---

## 📂 Project Structure

```text
.
├── main.tf
├── providers.tf
├── outputs.tf
├── .github/workflows/terraform-ci.yml
└── screenshots/

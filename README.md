# 🚀 Terraform Docker Task 3 - NGINX Container

This project demonstrates **Infrastructure as Code (IaC)** using **Terraform** to provision a **Docker container running NGINX** locally.

---

## 🛠️ Tools Used

- [Terraform](https://www.terraform.io/)
- [Docker](https://www.docker.com/)
- Provider: [kreuzwerker/docker](https://registry.terraform.io/providers/kreuzwerker/docker/latest)

---

## 📦 What It Does

- Pulls the `nginx:latest` image
- Provisions a Docker container named `nginx_terraform`
- Maps port `8081` (host) → `80` (container)

---

## OUTPUTS...

## terraform init

![tf-init](https://github.com/user-attachments/assets/bce9ab55-e6fa-452a-9e8d-d985f129ac72)

## terraform plan and terraform apply

![Screenshot 2025-04-10 192712](https://github.com/user-attachments/assets/ac8b2f7c-da1d-42a5-999c-dc681bddb932)

## docker images

![Screenshot 2025-04-10 190610](https://github.com/user-attachments/assets/a209f408-60eb-4354-9fb9-4ccfcf9a3181)

## docker ps

![Screenshot 2025-04-10 190702](https://github.com/user-attachments/assets/e9bd5b56-7197-453b-8abd-ce368ce4ad07)

## terraform destroy

![Screenshot 2025-04-10 190739](https://github.com/user-attachments/assets/c6e846b2-542e-47ae-8669-84d3a2755af5)


## localhost output

![Screenshot 2025-04-10 191955](https://github.com/user-attachments/assets/82f55acd-ba7d-4c5a-8110-b3880883283f)








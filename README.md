Terraform Project: Dynamic Security Group Ingress Using Public IP

📌 Overview

This project demonstrates how to use Terraform to dynamically configure an AWS Security Group by automatically allowing inbound access only from the user’s current public IP address.

The goal is to avoid hardcoding IP addresses and improve security by restricting access to trusted sources only.

🏗️ What This Project Does

- Detects the current public IP address of the user

- Creates an AWS Security Group

- Allows inbound access only from that public IP

- Prevents exposing resources to 0.0.0.0/0

- Uses Infrastructure as Code (IaC) best practices


🛠️ Technologies Used

- Terraform

- AWS EC2 Security Groups

- AWS Provider

- HTTP data source (to fetch public IP)

🚀 How to Run:

1️⃣ Initialize Terraform

```
terraform init
```

2️⃣ Review the Plan

```
terraform plan
```

3️⃣ Apply the Configuration

```
terraform apply
```

4️⃣ Destroy Resources (Cleanup)

```
terraform destroy
```
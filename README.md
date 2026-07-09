# DevOps Final Project

## Overview
This project demonstrates a complete DevOps deployment pipeline using Jenkins, Terraform, Ansible, and AWS.

## Technologies
- Jenkins
- Terraform
- Ansible
- AWS EC2
- Apache2
- GitHub

## Project Structure

```
DevOps-Final/
│
├── terraform/
│   ├── main.tf
│   ├── variables.tf
│   └── outputs.tf
│
├── ansible/
│   ├── inventory
│   └── playbook.yml
│
├── website/
│   └── index.html
│
├── screenshots/
├── docs/
└── README.md
```

## Deployment Process

The Jenkins Pipeline performs the following stages:

1. Terraform Init
2. Terraform Plan
3. Ansible Ping
4. Deploy Website using Ansible

## Result

The infrastructure is deployed successfully on AWS EC2.

Apache Web Server is installed automatically.

The website is deployed successfully.

The Jenkins Pipeline finishes with **SUCCESS**.

## GitHub Repository

https://github.com/NetanelYoune/DevOps-Final

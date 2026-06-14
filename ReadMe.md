<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a3a5c,100:0d1117&height=160&section=header&text=Anurag%20Bojja&fontSize=50&fontColor=58a6ff&fontAlignY=40" />

<p>
  <a href="mailto:anuragbojja23@gmail.com">
    <img src="https://img.shields.io/badge/Email-anuragbojja23%40gmail.com-0d1117?style=flat-square&logo=gmail&logoColor=EA4335&labelColor=161b22" />
  </a>
  <a href="https://www.linkedin.com/in/anurag-bojja-81a405192/">
    <img src="https://img.shields.io/badge/LinkedIn-Anurag%20Bojja-0d1117?style=flat-square&logo=linkedin&logoColor=0A66C2&labelColor=161b22" />
  </a>
  <a href="https://anuragbojja.github.io/">
    <img src="https://img.shields.io/badge/Portfolio-Visit%20Website-0d1117?style=flat-square&logo=vercel&logoColor=fff&labelColor=161b22" />
  </a>
  <a href="https://github.com/AnuragBojja">
    <img src="https://img.shields.io/badge/GitHub-AnuragBojja-0d1117?style=flat-square&logo=github&logoColor=fff&labelColor=161b22" />
  </a>
  <img src="https://komarev.com/ghpvc/?username=AnuragBojja&style=flat-square&color=58a6ff&label=Profile+Views&labelColor=161b22" />
</p>

</div>

---

## 🌐 About Me

```yaml
name       : Anurag Bojja
location   : Los Angeles, CA  |  Open to Relocation & Remote
education  : M.S. Computer Science — University of Wisconsin–Milwaukee (2023–2025)
focus      : DevSecOps · Cloud Infrastructure · Infrastructure as Code · Secure CI/CD
research   : Published @ Springer ICDSAI 2023 — NLP Sentiment Analysis
goal       : DevSecOps / Cloud Engineer roles where security and automation are one discipline
```

---

## 🛠️ Tech Stack

### ☁️ Cloud & Infrastructure
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=FF9900)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)
![CloudFormation](https://img.shields.io/badge/CloudFormation-FF9900?style=flat-square&logo=amazonaws&logoColor=white)

### 🔒 Security & Compliance
![IAM](https://img.shields.io/badge/IAM%20Least--Privilege-232F3E?style=flat-square&logo=amazonaws&logoColor=FF9900)
![SSM](https://img.shields.io/badge/SSM%20Secrets%20Mgmt-232F3E?style=flat-square&logo=amazonaws&logoColor=FF9900)
![TLS](https://img.shields.io/badge/TLS%2FSSL-005C99?style=flat-square&logo=letsencrypt&logoColor=white)
![ACM](https://img.shields.io/badge/ACM-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![SecurityGroups](https://img.shields.io/badge/Network%20Segmentation-1a3a5c?style=flat-square&logo=amazonaws&logoColor=white)

### ⚙️ DevOps & CI/CD
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![AWS CodePipeline](https://img.shields.io/badge/CodePipeline-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

### 💻 Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

### 🗄️ Databases & Monitoring
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)
![CloudWatch](https://img.shields.io/badge/CloudWatch-FF9900?style=flat-square&logo=amazonaws&logoColor=white)

---

## 🚀 Featured Projects

### 🏗️ RoboShop — Full Production Infrastructure (10-Layer Terraform Architecture)
> **Terraform · AWS VPC/EC2/ALB/ASG/CloudFront/ACM/SSM · Ansible · Route53**

A fully automated, zero-touch AWS production environment built across 10 independently managed infrastructure layers — security enforced at every level.

- 🔒 Security-first design: least-privilege network policies across all services, credentials managed through a centralized parameter store with zero values written to code, all public traffic encrypted with TLS at the edge
- 🤖 Self-bootstrapping entry point that automatically provisions databases, bakes service images, configures all application services via Ansible, and deploys behind an auto-scaling load-balanced architecture — fully hands-free from first boot to live production
- 📦 6 application services deployed through a single parameterized loop driving AMI baking, Launch Templates, Auto Scaling Groups with rolling refresh, and ALB listener rules
- 🌐 Public endpoint secured with a managed wildcard certificate, TLS-enforced load balancer, and a CDN layer with intelligent caching for static assets and direct pass-through for API traffic

[![GitHub](https://img.shields.io/badge/GitHub-View%20Repo-181717?style=flat-square&logo=github)](https://github.com/AnuragBojja/Terraform-RoboShop-Main.git)

---

### 🎭 RoboShop — Configuration Management (Ansible Roles Architecture)
> **Ansible · AWS EC2/Route53 · SSM Parameter Store · Jinja2 · amazon.aws**

A unified configuration management system for a 10-service polyglot platform — any service deploys through a single parameterized command, secrets never leave the secrets store.

- 🔑 Eliminated credential exposure across all configuration workflows — passwords and access keys resolved at runtime from AWS SSM Parameter Store, never stored in playbooks or version control
- 📄 All service and proxy configurations standardized as dynamic templates rendered at deploy time, ensuring environment-specific values are injected consistently and eliminating configuration drift
- ♻️ Shared setup logic defined once and inherited across all services — zero code duplication regardless of runtime or dependency stack

[![GitHub](https://img.shields.io/badge/GitHub-View%20Repo-181717?style=flat-square&logo=github)](https://github.com/AnuragBojja/ansible-roboshop-roles.git)

---

### 🐚 RoboShop — Infrastructure Automation (Shell Common Library)
> **Bash · AWS EC2/CLI · Route53 · Node.js · Java/Maven · Python**

Modular Bash automation for a 10-service polyglot e-commerce platform — 13 scripts refactored into a shared library, reducing per-service deployment code by over 85%.

- 🛡️ Idempotent design throughout — every script safely re-runnable with existing state detection for users, databases, and services
- ☁️ EC2 provisioning and Route53 DNS registration fully automated via AWS CLI, with centralized logging and structured error handling across all scripts

[![GitHub](https://img.shields.io/badge/GitHub-View%20Repo-181717?style=flat-square&logo=github)](https://github.com/AnuragBojja/shell-common.git)

---

### ☁️ Cloud-Based Food Delivery System (Multi-Cloud)
> **Django · AWS EC2 · Azure Web App · MySQL · Nginx · Gunicorn · GitHub Actions**

The same application deployed simultaneously on AWS (IaaS) and Azure (PaaS), comparing infrastructure control, scalability behavior, and operational overhead across both cloud models.

- 🔐 Hardened both deployments with automated CI/CD pipelines, TLS termination, IAM-scoped access controls, and strict network policies — no database or internal service exposed to the public internet
- 🗄️ Shared Azure MySQL backend maintains consistent schema and data across both cloud environments

[![Blog Post](https://img.shields.io/badge/📖%20Read%20Blog-uwm--cloudblog.net-58a6ff?style=flat-square)](https://uwm-cloudblog.net/general/deployment-of-a-food-delivery-system-using-iaas-and-paas/)

---

## 📚 Research & Publications

<table>
<tr>
<td width="60px" align="center">📄</td>
<td>
<strong>Review Analysis Using Web Scraping in Python</strong><br/>
<em>Springer ICDSAI 2023 — 2nd International Conference on Data Science & Artificial Intelligence</em><br/>
Designed and deployed an end-to-end sentiment classification pipeline — scraping and preprocessing large volumes of e-commerce reviews, training and evaluating multiple ML models through cross-validation and confusion matrix analysis, and deploying the complete system as a Flask web application on AWS for real-time sentiment prediction.<br/>
<a href="https://link.springer.com/chapter/10.1007/978-3-031-51167-7_77">
  <img src="https://img.shields.io/badge/Springer-View%20Publication-00629B?style=flat-square&logo=springer&logoColor=white" />
</a>
</td>
</tr>
</table>

---

## 💡 Currently Focused On

```text
✦  DevSecOps engineering — security embedded at the infrastructure level
✦  Advanced AWS production patterns — multi-layer IaC, AMI baking, ASG strategies
✦  Secrets management & least-privilege access design
✦  Container security & Kubernetes hardening
✦  Open to DevSecOps / Cloud Engineer roles
```

---

## 📊 GitHub Activity

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=AnuragBojja&hide_border=true&theme=github-dark" height="150" />
</div>

<div align="center">
  <a href="https://github.com/AnuragBojja?tab=repositories">View all repositories →</a>
</div>

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" />
</div>
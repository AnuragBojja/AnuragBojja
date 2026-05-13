<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a3a5c,100:0d1117&height=160&section=header&text=Anurag%20Bojja&fontSize=50&fontColor=58a6ff&fontAlignY=40" />

<p>
  <a href="mailto:anuragbojja19@gmail.com">
    <img src="https://img.shields.io/badge/Email-anuragbojja19%40gmail.com-0d1117?style=flat-square&logo=gmail&logoColor=EA4335&labelColor=161b22" />
  </a>
  <a href="https://www.linkedin.com/in/anurag-bojja-81a405192/">
    <img src="https://img.shields.io/badge/LinkedIn-Anurag%20Bojja-0d1117?style=flat-square&logo=linkedin&logoColor=0A66C2&labelColor=161b22" />
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
location   : Milwaukee, WI  |  Open to Relocation & Remote
education  : M.S. Computer Science — University of Wisconsin–Milwaukee (2023–2025)
focus      : Backend Systems · Cloud Infrastructure · DevOps Automation · Data Engineering
research   : Published @ Springer ICDSAI 2023 — NLP Sentiment Analysis
currently  : Data Analyst & Research Intern @ Eco Servants (California, USA)
```

---

## 🛠️ Tech Stack

### ☁️ Cloud & Infrastructure
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=FF9900)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)

### ⚙️ DevOps & Automation
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![AWS CodePipeline](https://img.shields.io/badge/CodePipeline-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

### 💻 Languages & Frameworks
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

### 🗄️ Databases & Analytics
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=flat-square&logo=mongodb&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)

---

## 🚀 Featured Projects

### ☁️ Cloud-Based Food Delivery System
> **Django · AWS EC2 · Azure Web App · MySQL · Nginx · Gunicorn · GitHub Actions**

A production-grade, full-stack food ordering and delivery platform showcasing **multi-cloud deployment architecture**.

- 🍽️ Built end-to-end user, restaurant, and delivery-agent workflows — menus, cart, orders, and real-time tracking
- 🏗️ Deployed simultaneously on **AWS EC2 (IaaS)** with Nginx + Gunicorn, and **Azure Web App (PaaS)** with GitHub CI/CD
- 🗄️ Shared **Azure MySQL Flexible Server** backend maintains consistent schema and migrations across both clouds
- 🔐 Secured with `.env` configs, IAM roles, Security Groups, TLS via Certbot, and firewall rules
- ⚙️ Automated server bootstrapping: virtual environments, NGINX config, domain setup, and TLS certificates

[![Blog Post](https://img.shields.io/badge/📖%20Read%20Blog-uwm--cloudblog.net-58a6ff?style=flat-square)](https://uwm-cloudblog.net/general/deployment-of-a-food-delivery-system-using-iaas-and-paas/)

---

### 🏗️ RoboShop Full Production Infrastructure — 10-Layer Terraform Architecture
> **Terraform · AWS VPC/EC2/ALB/ASG/CloudFront/ACM/SSM · Ansible · Route53**

Enterprise-grade IaC implementation with zero hardcoded values and fully hands-free provisioning.

- 🔧 Architected **10 independently state-managed Terraform layers** with S3 remote backends; cross-layer references via SSM Parameter Store
- 🤖 Self-bootstrapping Bastion auto-applies DB/service Terraform layers on first boot and triggers Ansible playbooks — zero manual steps
- 📦 Deployed 6 app services via a single `for_each` loop driving AMI baking, Launch Templates, ASGs with rolling refresh, and CPU-based autoscaling
- 🔒 Secured with wildcard ACM cert, TLS 1.3 ALB, and CloudFront with optimized caching for static assets

[![GitHub](https://img.shields.io/badge/GitHub-View%20Repo-181717?style=flat-square&logo=github)](https://github.com/AnuragBojja/Terraform-RoboShop-Main.git)

---

### 🎭 RoboShop Infrastructure Automation — Ansible Roles Architecture
> **Ansible · AWS EC2/Route53 · SSM · Jinja2 · amazon.aws**

A clean, reusable Ansible Roles architecture replacing flat per-service playbooks.

- 🔄 Any service deploys with **one command** using `$service_name` parameterization — zero code duplication across 10 roles
- 🔑 Integrated **AWS SSM Parameter Store** for secrets (SSH passwords, MySQL creds) via `amazon.aws` lookup plugin
- 📄 All systemd unit files and Nginx configs rendered as **Jinja2 templates** for full flexibility

[![GitHub](https://img.shields.io/badge/GitHub-View%20Repo-181717?style=flat-square&logo=github)](https://github.com/AnuragBojja/ansible-roboshop-roles.git)

---

### 🐚 RoboShop Microservices Deployment Automation — Shell Common Library
> **Bash · AWS EC2/CLI · Route53 · Node.js · Java/Maven · Python**

Modular Bash automation for a 10-service polyglot e-commerce platform.

- 📜 Authored **13 modular Bash scripts**; refactored into `common.sh` library reducing each service script from ~70 lines to **< 10**
- ☁️ Automated EC2 provisioning and Route53 DNS registration via **AWS CLI**
- 🛡️ Implemented `set -euo pipefail`, `trap ERR`, `VALIDATOR()`, and idempotent service/DB creation throughout

[![GitHub](https://img.shields.io/badge/GitHub-View%20Repo-181717?style=flat-square&logo=github)](https://github.com/AnuragBojja/shell-common.git)

---

## 📚 Research & Publications

<table>
<tr>
<td width="60px" align="center">📄</td>
<td>
<strong>Review Analysis Using Web Scraping in Python</strong><br/>
<em>Springer ICDSAI 2023 — 2nd International Conference on Data Science & Artificial Intelligence</em><br/>
Built an end-to-end NLP sentiment analysis pipeline using Python, BeautifulSoup, Selenium, NLTK, spaCy, and AWS EC2. Applied TF-IDF + supervised ML models (Naive Bayes, Logistic Regression, SVM) for e-commerce review classification.<br/>
<a href="https://link.springer.com/chapter/10.1007/978-3-031-51167-7_77">
  <img src="https://img.shields.io/badge/Springer-View%20Publication-00629B?style=flat-square&logo=springer&logoColor=white" />
</a>
</td>
</tr>
</table>

---

## 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=AnuragBojja&theme=github_dark&hide_border=true&include_all_commits=true&count_private=true&show_icons=true" height="165" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=AnuragBojja&theme=github-dark-blue&hide_border=true" height="165" />
</div>

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AnuragBojja&theme=github_dark&hide_border=true&layout=compact&langs_count=8" height="145" />
</div>

---

## 💡 Currently Focused On

```text
✦  Advanced SQL & Query Optimization
✦  Python for Data Engineering & Analytics  
✦  AWS + Terraform + Ansible Production Patterns
✦  Real-world Cloud Infrastructure Projects
✦  Geospatial Data Pipelines @ Eco Servants
```

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" />
</div>

<div align="center">
  <h1>Anurag Bojja</h1>
  <p>Software & Cloud Engineer &nbsp;·&nbsp; Published Researcher (Springer ICDSAI 2023)</p>
  <p>
    <a href="mailto:anuragbojja19@gmail.com">anuragbojja19@gmail.com</a> &nbsp;·&nbsp;
    <a href="https://www.linkedin.com/in/anurag-bojja-81a405192/">LinkedIn</a> &nbsp;·&nbsp;
    <a href="https://github.com/AnuragBojja">GitHub</a> &nbsp;·&nbsp;
    Milwaukee, WI — open to relocation
  </p>
</div>

---

I build backend systems, automate cloud infrastructure, and deploy distributed applications on AWS and Azure. My work spans Python data pipelines, Terraform-managed production infrastructure, Ansible role architectures, and CI/CD automation. Published NLP researcher — Springer ICDSAI 2023.

---

## Stack

| Cloud & IaC | DevOps | Languages | Data & Backend |
|---|---|---|---|
| AWS · Azure · Terraform · Ansible · CloudFormation | GitHub Actions · CodePipeline · Docker · Nginx · Linux | Python · Bash · SQL · Java · JavaScript | Django · Flask · MySQL · MongoDB · Redis · Pandas |

---

## Projects

**[RoboShop — 10-layer Terraform](https://github.com/AnuragBojja/terraform-roboshop-main)**
`Terraform` `AWS` `Ansible` `CloudFront` `SSM`

Full production AWS infra across 10 independently state-managed layers. SSM-decoupled cross-layer referencing, self-bootstrapping bastion, CloudFront + ACM endpoint, 6-service for_each deploy loop with rolling ASG refresh.

---

**[RoboShop — Ansible roles](https://github.com/AnuragBojja/ansible-roboshop-roles)**
`Ansible` `Jinja2` `AWS SSM` `EC2`

Flat per-service playbooks refactored into a full roles architecture. SSM secrets via amazon.aws lookup, all systemd units and Nginx configs as Jinja2 templates. One parameterized command deploys any of 10 services.

---

**[RoboShop — Bash automation](https://github.com/AnuragBojja/shell-roboshop)**
`Bash` `AWS CLI` `Route53` `EC2`

13 modular Bash scripts provisioning a 10-service polyglot platform, refactored into a shared common.sh library — each service script down from ~70 lines to under 10. Idempotent, set -euo pipefail, VALIDATOR() throughout.

---

**[Food delivery — multi-cloud deploy](https://github.com/AnuragBojja/food-delivery)**
`Django` `AWS EC2` `Azure` `MySQL`

Django app deployed simultaneously on AWS EC2 (Nginx + Gunicorn) and Azure Web App. Shared Azure MySQL backend, GitHub CI/CD, TLS via Certbot, IAM and SG-based access controls.

---

## Research

**Review Analysis Using Web Scraping in Python**
*Springer Proceedings · ICDSAI 2023 · California State University, USA*

End-to-end NLP sentiment analysis pipeline: web scraping with BeautifulSoup & Selenium, preprocessing with NLTK & spaCy, TF-IDF feature extraction, SVM / Logistic Regression / Naive Bayes classification — deployed and benchmarked on AWS EC2.

`NLP` `Python` `AWS EC2` `scikit-learn` `NLTK`

---

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=AnuragBojja&show_icons=true&hide_border=true&count_private=true&theme=default" height="120" />
  &nbsp;
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=AnuragBojja&hide_border=true&theme=default" height="120" />
</div>

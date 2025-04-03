# 🛠️ DevOps Roadmap: From Self-Taught to Job-Ready (2025 Edition)

> ⚠️ **Note:**  
> This roadmap assumes prior technical skill. I’m not starting from scratch — I’m sharpening and formalizing my knowledge to become a **certified, cloud-native DevOps engineer**.  
>
> **Background Snapshot:**
> - 🐧 2+ yrs Arch Linux (daily driver) – CLI fluency, web server config, systemd, package management  
> - 🐳 1+ yr Docker – Compose, container management, troubleshooting  
> - 🧠 Git/GitHub – Branching, rebasing, merge strategies, PR reviews  
> - 🧑‍💻 Python, Flask, React, AI integration  
> - 🤖 1+ yr AI-accelerated dev (Claude, Cursor, Windsurf)  
> - 🧰 Familiar with CI/CD, IaC, K8s, observability tooling  

This roadmap takes me from **self-taught Dev** to **cloud-native DevOps pro** ready to contribute to SRE/infra/code pipelines at a high level.

---

## 📅 Roadmap Overview

| Phase | Timeline   | Focus                              |
|-------|------------|-------------------------------------|
| 1️⃣   | Weeks 1–4   | Linux, Bash, Git, CLI tooling       |
| 2️⃣   | Weeks 5–8   | Docker, GitHub Actions, CI pipelines |
| 3️⃣   | Weeks 9–12  | AWS, Terraform, IAM, modules        |
| 4️⃣   | Weeks 13–16 | K8s, Helm, ArgoCD                   |
| 5️⃣   | Weeks 17–20 | Prometheus, Grafana, full project polish |

---

## ✅ Phase 1: Core Skills & Shell Mastery

**Primary Resource:**  
✅ [The Missing Semester of Your CS Education](https://missing.csail.mit.edu/)

**Skills:**
- Shell scripting, dotfiles, piping, tmux, grep/awk/sed mastery
- Git CLI deep dive: squash merges, cherry-pick, bisect
- SSH, rsync, systemctl, journald, crontab, networking

**Projects:**
- [ ] Dotfiles with install script  
- [ ] Custom `systemd` service for a web app  
- [ ] Bash script: backup + sync to cloud (rclone or AWS S3 CLI)  

---

## ⚙️ Phase 2: Containers & CI/CD

**Certs Targeted:**
- [ ] Docker Certified Associate *(optional)*  
- [ ] GitHub Actions beginner + advanced badge  

**Skills:**
- Dockerfile layering, multi-stage builds, Docker networking  
- GitHub Actions: matrix builds, reusable workflows, secrets  
- CI best practices: testing, artifact upload, deployments  

**Projects:**
- [ ] Dockerized Flask/React fullstack app  
- [ ] GH Actions pipeline: test + build + push to DockerHub  
- [ ] Private Docker registry on a VPS  

---

## ☁️ Phase 3: Cloud & Infrastructure as Code (IaC)

**Certs Targeted:**
- [ ] **Terraform Associate (HashiCorp)**  
- [ ] **AWS Cloud Practitioner → AWS SAA (in time)**  

**Skills:**
- Terraform: resources, providers, outputs, modules, remote state  
- AWS: EC2, VPC, IAM, S3, CloudWatch  
- IAM policies: least privilege, roles, trust policies  

**Projects:**
- [ ] Terraform-managed AWS infra: EC2 + VPC + S3 + IAM  
- [ ] Remote backend on S3 w/ DynamoDB locking  
- [ ] CI/CD deploy to AWS via Terraform GitHub Actions workflow  

---

## ☸️ Phase 4: Kubernetes & GitOps

**Certs Targeted:**
- [ ] **Certified Kubernetes Administrator (CKA)**  

**Skills:**
- K8s architecture: pods, services, deployments, statefulsets  
- Helm templating & value overrides  
- GitOps principles: ArgoCD/FluxCD  
- Secrets management (sealed secrets or SOPS)  

**Projects:**
- [ ] K3d or Minikube local cluster w/ Helm-deployed app  
- [ ] ArgoCD repo: GitOps CD for staging & prod  
- [ ] Self-healing app demo with HPA and node taints/tolerations  

---

## 📊 Phase 5: Monitoring, Logging & Capstone

**Skills:**
- Prometheus metrics, exporters, alerting rules  
- Grafana dashboards: templated views, alerts  
- Loki or ELK for logs (optional)  
- CI visibility: monitor builds + deploys  

**Capstone Ideas:**
- [ ] End-to-end infra: IaC + K8s + CI/CD + monitoring  
- [ ] Demo: self-healing app + dashboard + GitOps deploy  
- [ ] Resume-ready blog post: "My DevOps Pipeline in the Cloud"  

**Polish Checklist:**
- [ ] Portfolio README with diagrams  
- [ ] DevOps resume tailored to SRE/platform roles  
- [ ] GitHub cleaned up: pin top projects, descriptive READMEs  
- [ ] LinkedIn optimized: keywords, banner, pinned projects  

---

## 🎓 Certifications to Prioritize

| Cert                           | Purpose                         | Priority     |
|--------------------------------|----------------------------------|--------------|
| **Terraform Associate**        | Prove cloud/IaC automation skills | 🥇 High      |
| **CKA**                        | In-demand K8s admin skillset      | 🥈 High      |
| **AWS Cloud Practitioner**     | Cloud fluency baseline            | 🥉 Optional  |
| **AWS Solutions Architect**    | Architect-level cert              | Bonus        |
| ~~RHCSA~~                      | Legacy Linux admin                | ❌ Skip      |

---

## 🛠️ Tech Stack Focus

![Linux](https://img.shields.io/badge/Linux-000000?style=for-the-badge&logo=linux&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326ce5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)

---

## ✍️ Notes & Blog (Coming Soon)

- 📁 `/notes` directory: shell tricks, Terraform patterns, CI workflows  
- 📝 Blog: Lessons learned, tutorials, build breakdowns  

---

## 📫 Connect With Me

- GitHub: [@diegonunez77](https://github.com/diegonunez77)  
- LinkedIn: [Diego Saavedra](https://www.linkedin.com/in/your-link/)  
- Blog: *Coming soon*  

# Hi, I'm Zain Ul Abdin 👋

**DevOps Engineer | Founder & CEO — Zain Tech Automation Solutions | Karachi, Pakistan**

I build and automate infrastructure: CI/CD pipelines, containers, infrastructure as code, and monitoring. Alongside DevOps, I build machine learning projects and practice cyber security in my own home lab. Every major project below is public, with run evidence and verification scripts — no inflated claims, just work you can open and check.

I am also a **Hafiz and Alim**, and the founder of **Zain Tech Automation Solutions** — *Automate. Accelerate. Achieve.*

- 🌐 **Website:** https://zaintechautomationsolutions.lovable.app/
- 📧 **Email:** zainpatel1213@gmail.com
- 💬 **WhatsApp:** +92 322 1837390
- 🎓 **Currently:** AIOps — Level 6 (in progress)
- 🔭 **Open to:** Junior/trainee DevOps roles and freelance automation projects

---

## 🚀 Featured Projects — hands-on work, with run evidence

| Project | What it proves |
|---|---|
| [Multi-Tier AWS Infrastructure with Terraform](https://github.com/zain-ul-abadeen-1213/terraform-multi-tier-aws) | VPC across 2 AZs, ALB + Auto Scaling Group, RDS MySQL in private tier. Applied to AWS (**28 resources**), verified serving live traffic, then destroyed to control cost. |
| [Multi-Environment CI/CD Pipeline](https://github.com/zain-ul-abadeen-1213/multi-env-deployment) | GitHub Actions with a self-hosted runner; one artifact promoted Dev → QA → Production with manual approval gates and SSH deployments. |
| [Jenkins CI/CD Pipeline](https://github.com/zain-ul-abadeen-1213/jenkins-cicd-pipeline) | Declarative Pipeline-from-SCM (Jenkinsfile): verify, package a versioned artifact, deploy with a written receipt — build **SUCCESS**. |
| [Ansible Server Automation](https://github.com/zain-ul-abadeen-1213/ansible-server-automation) | One playbook configuring 3 Ubuntu servers over SSH key auth. Idempotency proven — rerun changed=0; verification **3/3 PASS**. |
| [Kubernetes Cluster Deployment](https://github.com/zain-ul-abadeen-1213/kubernetes-cluster-deployment) | Local 3-node kind cluster, 3 replicas behind a NodePort service, rolling update V1 → V2 with **zero downtime**; verification 4/4. |
| [Kubernetes Autoscaling under Load (HPA)](https://github.com/zain-ul-abadeen-1213/kubernetes-autoscaling-hpa) | Load drove CPU to 204% and the HPA scaled the deployment **1 → 4 replicas on its own**; verify script Passed 5 / Failed 0. |
| [Service Mesh with Istio](https://github.com/zain-ul-abadeen-1213/istio-service-mesh) | Bookinfo microservices behind the Istio ingress gateway on a 3-node kind cluster: reviews traffic split **80/20 (v1/v3)** and **mTLS in STRICT mode**. Core mesh verified running — product page serving HTTP 200. Kiali/Prometheus addons and the final verification suite are still to finish. |
| [GitOps with ArgoCD](https://github.com/zain-ul-abadeen-1213/gitops-apps) | Argo CD keeps a demo app synced purely from Git: one web commit scaled it **2 → 4 replicas** and moved the image nginx:1.25 → 1.27, and a manual drift (scale to 1) was **self-healed** back automatically. The Git rollback test is still to finish. |
| [Prometheus & Grafana Monitoring](https://github.com/zain-ul-abadeen-1213/prometheus-grafana-monitoring) | Docker Compose monitoring stack (Prometheus, node-exporter, cAdvisor, Grafana), 6-panel dashboard, all targets UP. |
| [Dockerized App on AWS ECR](https://github.com/zain-ul-abadeen-1213/exportsight-docker-aws-ecr) | ExportSight BI application containerized with Docker and pushed to Amazon ECR (ap-south-1). |
| [ExportSight — live product](https://github.com/zain-ul-abadeen-1213/exportsight) | Business intelligence dashboard for textile exporters. **Live demo:** https://exportsight.streamlit.app/ |

---

## 🤖 Machine Learning — project work

| Project | What it is |
|---|---|
| [Zain Doctor — Multiple Disease Prediction](https://github.com/zain-ul-abadeen-1213/zain-doctor) | Streamlit app with 3 trained SVM models — Diabetes (8 features), Heart Disease (13), Parkinson's (22 voice features). FastAPI backend built and tested locally; Flask version prepared for deployment. |
| **Customer Churn Analytics (in progress)** | SQL Server ETL + Power BI dashboards + a Random Forest churn-prediction model on telecom data. |
| [ExportSight — live product](https://github.com/zain-ul-abadeen-1213/exportsight) | Business intelligence dashboard for textile exporters. **Live demo:** https://exportsight.streamlit.app/ |

## 🔐 Cyber Security — home lab practice

| Project | What it is |
|---|---|
| [Password Security Audit Lab](https://github.com/zain-ul-abadeen-1213/password-security-audit-lab) | Hands-on audit in my own Kali Linux lab: John and Hashcat tested against MD5 hashes; Medusa and Hydra tested against my own VM's SSH — with a full written report and remediation notes. Own systems only. |
| **Kali Linux Home Lab** | Self-built practice lab (VirtualBox, own network): Wireshark traffic analysis practice, OWASP Top 10 study, blue-team tooling study. |

---

## 🛠️ Skills

- **DevOps & Cloud:** Docker, Kubernetes, Terraform, Jenkins, GitHub Actions, Ansible, Prometheus, Grafana, AWS (EC2, S3, VPC, IAM, ECR, ALB)
- **Systems:** Linux administration (Debian/Ubuntu), SSH, Bash scripting
- **Machine Learning:** scikit-learn (SVM, Random Forest), Pandas, NumPy, Streamlit, model evaluation
- **Cyber Security (lab practice):** Kali Linux, John, Hashcat, Hydra, Medusa, Wireshark
- **Languages & Data:** Python, Git & GitHub, SQL Server / T-SQL (project work)
- **Project experience:** FastAPI / Flask, Streamlit, Power BI (churn analytics project in progress)

## 📚 Currently learning

- AIOps — Level 6 (in progress)
- Istio service mesh and ArgoCD GitOps — built and running in my home lab; final verification and closeout in progress

---

⚡ *"Keep learning, keep building — and verify everything."*

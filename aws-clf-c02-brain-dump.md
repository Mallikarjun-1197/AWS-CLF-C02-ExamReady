# 🚀 AWS Cheat Sheet  
Concise, exam‑ready notes with a touch of flair ✨  

---

## 🔐 Security & Identity
- 🔑 **IAM** → Manage accounts, policies, roles  
- 🛡️ **GuardDuty** → Threat detection, malicious activity monitoring  
- 🔍 **Macie** → Data security & privacy (PII detection)  
- ⚔️ **Shield (Standard/Advanced)** → DDoS protection  
- 🧱 **WAF** → Protects against SQL injection, XSS, CORS  
- 🕵️ **Detective** → Security investigations (CloudTrail, VPC Flow Logs, GuardDuty, EKS Audit)  
- 📜 **Config** → Tracks resource state changes, compliance rules  
- 🏰 **Control Tower** → Landing zone setup with guardrails  
- 📏 **Service Control Policies (SCPs)** → Org‑wide permission boundaries  

---

## 📊 Monitoring & Management
- 📡 **CloudWatch** → Metrics, logs, alarms, dashboards  
- 📝 **CloudTrail** → Governance & audit of API calls (who did what, when, from where)  
- 🧭 **Trusted Advisor** → Recommendations on cost, performance, security, fault tolerance, limits  
- ❤️ **Health Dashboard** → Service health & account‑specific issues  
- 🛠️ **Systems Manager** → Centralized operational data, resource groups  
- 🔦 **X‑Ray** → App performance tracing  

---

## 💾 Storage & Databases
- 📦 **S3** → Object storage, lifecycle policies, multiple classes  
  - Standard (no retrieval fee)  
  - IA / One Zone IA (lower cost, retrieval fee)  
  - Glacier (Instant, Flexible, Deep Archive)  
- 📀 **EBS** → Block storage, tied to EC2 lifecycle  
- 📂 **EFS** → Elastic file storage, supports on‑prem  
- 🗄️ **RDS** → Managed relational DB (MySQL, PostgreSQL, Multi‑AZ, Read Replica, Multi‑Region)  
- ⚡ **Aurora** → SSD‑based relational DB, MySQL/Postgres compatible  
- 🏢 **Redshift** → Petabyte‑scale data warehouse  
- 🔗 **Neptune** → Graph DB  
- 📊 **Athena** → Serverless SQL queries on S3  
- 🔄 **Glue** → ETL service  
- 🐘 **EMR** → Hadoop framework  

---

## 🌐 Networking
- 🌍 **VPC** → Private cloud network across AZs  
- 🧩 **Subnet** → Single AZ scope  
- 🔄 **NAT Gateway** → Managed outbound internet access for private subnets  
- 🔌 **PrivateLink** → Private access to AWS services  
- 🔗 **Transit Gateway** → Connect multiple networks privately  
- ⚡ **Direct Connect** → Private line connection, higher performance  
- 🌐 **Site‑to‑Site VPN** → Public internet connection, lower cost  
- 🎯 **Global Accelerator** → Static IP entry point, non‑HTTP use cases  

---

## 💰 Cost Optimization
- 💵 **Cost Explorer** → Monitor spend, usage reports  
- 📉 **Savings Plans** → Compute & EC2 instance options  
- 🧭 **Trusted Advisor** → Cost optimization checks  

---

## 🌀 Disaster Recovery
- 🕒 **Backup & Restore** → Hours downtime  
- 🔥 **Pilot Light** → Minimal compute, live data  
- 🌡️ **Warm Standby** → Scaled‑down infra, minutes downtime  
- 🌍 **Multi‑Site / Active‑Active** → Zero downtime, real‑time  
- 📏 **RPO/RTO** → Recovery Point & Recovery Time Objectives  

---

## 🧭 Frameworks & Governance
### 🏗️ Well‑Architected Framework
1. ⚙️ Operational Excellence  
2. ⚡ Performance Efficiency  
3. 🔒 Reliability  
4. 💸 Cost Optimization  
5. 🛡️ Security  

### 🌐 AWS CAF Perspectives
| 🏢 Business | 👥 People | 📜 Governance | 🖥️ Platform | 🔐 Security | 🔧 Operations |
|-------------|-----------|---------------|--------------|-------------|---------------|
| Outcomes    | Training  | Policies      | Setup        | Privacy     | Monitoring    |
| Values      | Skills    | Budgets       | Apps         | Data        | Support       |

### 🛠️ Support Plans
| Plan       | Features |
|------------|----------|
| 🟢 Basic      | Health checks |
| 🟡 Developer  | Use‑case guidance, billing |
| 🔵 Business   | Infra diagnosis |
| 🔴 Enterprise | TAM, dedicated support |

### 🔑 KMS Keys
- **AWS Owned** → Automatic encryption at rest  
- **AWS Managed (CMK)** → AWS manages lifecycle, logs in your account  
- **Customer Managed** → Full control by customer  

---

## ✨ Extra Context You Might’ve Missed
- **AWS Step Functions** → Serverless orchestration of multiple AWS services  
- **AWS Security Hub** → Centralized security findings across services  
- **Amazon Lex** → Chatbot service (used in Alexa & AWS Chatbot)  
- **AWS Concierge Team** → Billing/account support for Enterprise plans  
- **AWS OpsHub** → UI for managing Snowball devices  
- **Encryption in Transit** → Traffic between AZs is always encrypted  

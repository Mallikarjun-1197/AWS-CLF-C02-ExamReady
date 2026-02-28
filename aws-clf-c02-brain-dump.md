
# 🛡️ AWS CLF‑C02 Survival Guide  
From scribbles to secrets — distilled notes, polished and battle‑ready.  

---

## Part 1: 🔐 Numbered Service Index (1–17)

1. **AWS Inspector** → Automatically scans applications for vulnerabilities and network gaps. Suggests security best practices for EC2 and containers.  
2. **AWS GuardDuty** → Continuous threat detection, monitors malicious activity and unauthorized access.  
3. **Amazon Macie** → ML‑powered data security & privacy service for sensitive data (PII) in S3.  
4. **AWS Shield** → Managed DDoS protection.  
   - Standard: Free, enabled by default.  
   - Advanced: Paid, higher‑level protection for Route 53, CloudFront, ELB.  
5. **AWS WAF** → Layer 7 firewall, protects against SQL injection, XSS.  
6. **AWS Systems Manager (SSM)** → Centralized console to view/manage resources at scale.  
7. **AWS Trusted Advisor** → Real‑time guidance on Cost, Performance, Security, Fault Tolerance.  
8. **AWS Detective** → Investigates root causes using CloudTrail, VPC Flow Logs, GuardDuty.  
9. **AWS X‑Ray** → Debugging for distributed apps (microservices, Lambda).  
10. **AWS IAM** → Global identity & access management.  
    - Identity Center (SSO) → Centralized access across accounts.  
    - Credential Report → Audit MFA, password age.  
    - Access Analyzer → Detect external sharing.  
11. **AWS Health Dashboard** →  
    - Service Health → General AWS status.  
    - Personal Health → Resource‑specific alerts.  
12. **AWS Compute Optimizer** → ML‑based resource recommendations for cost/performance.  
13. **AWS Cost Explorer** → Visualize/manage costs, usage, forecasting.  
14. **AWS RAM** → Securely share resources across accounts/orgs.  
15. **AWS Config** → Inventory + configuration history, compliance auditing.  
16. **AWS CloudTrail** → Governance & auditing of API calls (“Who did what?”).  
17. **AWS CloudWatch** → Performance monitoring, metrics, logs, alarms.  

---

## Part 2: 💾 Databases, Storage & Analytics

### 🗄️ Databases
- **Amazon RDS** → Managed SQL DB (Aurora, MySQL, PostgreSQL).  
- **Amazon Aurora** → AWS‑native relational DB, 5× faster than MySQL.  
- **Amazon DynamoDB** → Fully managed NoSQL DB, DAX caching.  
- **Amazon Redshift** → OLAP data warehouse for big data analytics.  
- **Amazon ElastiCache** → In‑memory caching (Redis/Memcached).  
- **Amazon Neptune** → Managed Graph DB.  

### 📦 S3 Storage Classes
- Standard → Frequent access.  
- Intelligent‑Tiering → Auto cost savings for unknown patterns.  
- Standard‑IA → Infrequent access, lower cost.  
- One Zone‑IA → Non‑critical, single AZ storage.  
- Glacier Instant/Flexible/Deep Archive → Cold storage, retrieval minutes–hours.  

---

## Part 3: 🌐 Networking & Hybrid

- **VPC** → Private, isolated cloud environment.  
- **Subnets** → Public vs. Private partitions.  
- **Direct Connect** → Dedicated physical line, no internet.  
- **Site‑to‑Site VPN** → Encrypted tunnel over public internet.  
- **Route 53** → Scalable DNS service.  
- **Global Accelerator** → Improves traffic availability/performance via AWS global network.  

---

## Part 4: 🚛 Migration & AI Services

- **Snowball Edge** → TB‑scale transfer device with compute.  
- **Snowmobile** → Exabyte‑scale transfer (shipping container).  
- **Glue** → Serverless ETL.  
- **Athena** → SQL queries on S3.  
- **Kendra** → ML‑powered intelligent search.  
- **Lex** → Conversational AI (chatbots).  
- **Connect** → Cloud contact center.  

---

## Part 5: 🏛️ Cloud Adoption Framework (CAF)

Perspectives for cloud migration:  
- **Business** → Align IT with outcomes (CEO, CFO).  
- **People** → Bridge tech & people (HR).  
- **Governance** → Orchestrate initiatives (CIO).  
- **Platform** → Design/implement environment (CTO).  
- **Security** → Compliance & risk (CISO).  
- **Operations** → Reliability & health (Ops Mgr).  

---

## Part 6: 📞 AWS Support Plans

| Feature | Developer | Business | Enterprise |
|---------|-----------|----------|------------|
| Best For | Testing/Dev | Production | Mission Critical |
| Response Time | < 24 hrs | < 1 hr (System Down) | < 15 min (Critical) |
| Support | Email (Biz hours) | 24/7 Phone/Email | 24/7 Phone/Email |
| TAM | No | No | Yes (Technical Account Manager) |

---

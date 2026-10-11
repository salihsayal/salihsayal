# M. Salih Sayal
**Cloud & DevOps Engineer** · Duisburg, Germany  
[LinkedIn](https://www.linkedin.com/in/muhammet-salih-sayal-327565206) · [Email](mailto:muhammet.salih.sayal@hotmail.com)

Infrastructure and automation engineer focused on enterprise Linux environments, resilient container orchestration, and practical pipeline automation. Experienced in bare-metal hypervisors (Proxmox VE), stateless Kubernetes deployments (K3s, GitOps), and Python/Bash-driven systems integration.

---

### 🛠️ Core Focus & Technologies
- **Languages & Frameworks:** Java (Spring Boot), Python (FastAPI, Pandas, Automation), SQL, JavaScript / TypeScript, Next.js, Bash, PowerShell
- **Infrastructure, Cloud & DevOps:** Linux Administration (Debian/Ubuntu, RHEL), Kubernetes (K3s/K8s), ArgoCD (GitOps), Proxmox VE, Docker / Compose, ZFS, CI/CD Pipelines, High Availability / Replication
- **Security & Networking:** Identity Management (Samba AD DC), Nginx Reverse Proxy, OPNsense Firewall, WireGuard / Tailscale VPN, NFS Storage, SSH, TLS, DNS
- **Tools & Quality:** Git (Gitea/GitHub/Bitbucket), Jira, Confluence, SAP-API-Integration, Dev Containers, JUnit 5, Mockito, SonarQube, Checkstyle

---

### 🚀 Featured Systems & Projects

#### [Jobentra – Hybrid Infrastructure Architecture](https://github.com/salihsayal/jobentra-infrastructure)
Highly available infrastructure and stateless 3-Node-Kubernetes-Cluster for Jobentra, a recruitment and staffing agency.
- **Key Concepts:** Decoupled stateless compute (microservices) from stateful storage via NFS, PostgreSQL, and ZFS.
- **GitOps Deployment:** Automated CI/CD pipelines and rolling updates via ArgoCD connected to a self-hosted Gitea instance.
- **High Availability:** Active replication and failover architecture across dedicated Proxmox VE hardware nodes.

#### [Jobentra CRM – Multi-Service Platform](https://github.com/salihsayal/jobentra-crm)
Containerized recruitment CRM platform featuring a decoupled, 4-tier microservice architecture.
- **Architectural Separation:** Strict hub-and-spoke design where Java Spring Boot acts as the sole authenticated gateway to PostgreSQL. Frontend (Next.js) and AI Service (FastAPI) are fully isolated from direct database access.
- **AI & Document Pipeline:** FastAPI-driven document generation and applicant profile synthesis using Google Vertex AI / Gemini to process candidate CVs.
- **DevOps & Portability:** Fully containerized multi-container setup via Docker Compose and declarative Kubernetes deployment manifests.

#### [HPC Resource & Cost Aggregator](https://github.com/salihsayal/hpc-cost-calculation)
Containerized 3-stage ETL (Extract, Transform, Load) and reporting pipeline for heterogeneous compute environments.
- **Architecture & Orchestration:** Sequentially orchestrated Docker containers (Ingestion, Automation, Notification) interacting with a persistent, bind-mounted PostgreSQL database.
- **Data Ingestion & Identity:** Automated extraction of unstructured data and email attachments via Microsoft Graph API (OAuth2), paired with Active Directory (LDAP) synchronization for user mapping.
- **Data Processing:** Python-based data transformation (Regex, Pandas) and SQL aggregations to calculate bare-metal, VDI, and cloud storage costs.
- **Automated Reporting:** Multi-threaded generation of interactive data visualizations (Plotly) and automated distribution of personalized HTML reports.

---

*Looking for operative roles in Platform Operations, Systems Engineering, and DevOps Automation.*

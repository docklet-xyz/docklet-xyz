<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=7C3AED&height=200&section=header&text=Docklet&fontSize=90&fontAlignY=38&desc=PostgreSQL%20%E2%80%A2%20VPS%20%E2%80%A2%20Docker%20%E2%80%A2%20AI%20DevOps%20Platform&descAlignY=65&descAlign=62" />

  <a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=500&size=22&pause=1000&color=A78BFA&center=true&vCenter=true&width=500&lines=All-in-One+DevOps+Platform;PostgreSQL+First+Experience;Docker+%2B+VPS+Management;AI-Powered+Automation" alt="Typing SVG" /></a>

  <br />

  [![Stars](https://img.shields.io/github/stars/rehanweb3/Docklet?style=for-the-badge&color=eab308&logo=github)](https://github.com/rehanweb3/Docklet)
  [![License](https://img.shields.io/github/license/rehanweb3/Docklet?style=for-the-badge&color=3b82f6)](https://github.com/rehanweb3/Docklet/blob/main/LICENSE)
  [![Issues](https://img.shields.io/github/issues/rehanweb3/Docklet?style=for-the-badge&color=ef4444)](https://github.com/rehanweb3/Docklet/issues)
  [![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)](https://www.docker.com/)
  [![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org/)

</div>

<br/>

## 🚀 About Docklet

Docklet is an **all-in-one DevOps platform** designed to bring the cloud-native developer experience to your own servers. It combines:
- **PostgreSQL management** (Table editing, SQL execution, metrics)
- **Docker container control** (Deployment, monitoring, logs)
- **VPS infrastructure** (Real-time monitoring, SSH access)
- **AI automation** (Natural language DevOps via NVIDIA LLM)

---

## ✨ Features

### 🐘 PostgreSQL Tools
* **Table Editor**: Manage your schema with inline editing and relations.
* **SQL Editor**: Execute queries with autocomplete and history.
* **Query insights**: Monitor slow queries and index usage.
* **Backup & Restore**: Point-in-time recovery and snapshot management.

### 🐳 Docker Manager
* **Manage containers**: Start, stop, restart, and remove containers visually.
* **Docker Compose support**: Deploy multi-container apps seamlessly.
* **Quick deployments**: One-click installs for popular databases and services.

### 🖥️ VPS Management
* **Real-time Metrics**: Live CPU, Memory, and Storage monitoring charts.
* **Host Information**: System load, uptime, and architecture details at a glance.

### 🤖 AI Features
#### AI Agent
* **User Command**: "Install PostgreSQL" or "Deploy Nginx"
* **Automated Workflow**:
  * **Executes** the necessary shell commands
  * **Verifies** the installation was successful
  * **Fixes** issues with up to 3 automatic retries

#### AI Terminal
* **Generate commands** using natural language prompts.
* **Optional auto-run** to execute generated commands directly on the host.

### ⚙️ DevOps Tools
* **SSH Access**: Direct terminal access to your VPS.
* **Reverse Proxy**: Built-in Nginx proxy manager.
* **Domains & SSL**: Map domains to containers with automated Let's Encrypt SSL.
* **Scheduler**: Manage cron jobs for containers and the host.
* **Auto Deploy**: Deploy Dockerfiles directly from GitHub repositories.

### 📦 Storage
* **S3 / MinIO Support**: Built-in object storage management.
* **File Management**: Visual bucket browser and file upload utility.

### 📊 Monitoring
* **Real-time metrics**: Granular resource tracking.
* **System stats**: Unified dashboard for entire infrastructure health.

---

## 🛠️ Tech Stack

<div align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=react,ts,nodejs,docker,postgres,linux,nginx&perline=10" />
  </a>
</div>

---

## 💻 Installation

Get started with Docklet on your own server in minutes:

```bash
# Clone & enter the repo
git clone https://github.com/rehanweb3/Docklet.git docklet
cd docklet

# Configure your environment
cp .env.example .env && nano .env

# Launch the full stack
docker compose -f postgres.yml up -d --build
```

---

## ⚙️ Environment Setup

Configure your `.env` file before launching:

```env
# PostgreSQL database
DB_NAME=mydb
DB_USERNAME=myuser
DB_PASSWORD=StrongPassword123!

# Docklet admin login
ADMIN_USERNAME=admin
ADMIN_PASSWORD=SecureAdminPass!

# JWT secret — openssl rand -hex 32
JWT_SECRET=replace_with_a_64_char_random_string
```

---

## 📈 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=rehanweb3&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117" alt="GitHub Stats" width="48%" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=rehanweb3&theme=tokyonight&hide_border=true&background=0D1117" alt="GitHub Streak" width="48%" />
  
  <br/><br/>
  
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=rehanweb3&theme=tokyo-night&hide_border=true&bg_color=0D1117" alt="Contribution Graph" width="98%" />
</div>

<br/>

<div align="center">
  <h3>Build. Deploy. Automate.</h3>
  <p>Made with ❤️ by the Docklet Team.</p>
</div>

## Updates
Added dashboard with stat cards
Added skills page with progress bars
# Devops-dashboard
Real-time DevOps CI/CD monitoring dashboard built with HTML, CSS &amp; JavaScript. Visualizes Jenkins pipelines, SonarQube code quality, Docker containers, and AWS EC2 status. Hosted on GitHub Pages.

# 🚀 DevOps CI/CD Pipeline Dashboard

A real-time DevOps monitoring dashboard built with **HTML, CSS, and JavaScript** — visualizing Jenkins CI/CD pipelines, SonarQube code quality metrics, Docker containers, and AWS EC2 instance status.

> 🔗 **Live Demo:** [View Dashboard](https://harivasantharava41-rgb.github.io/devops-dashboard)

---

## 📸 Preview

![DevOps Dashboard Preview](assets/preview.png)

---

## 🛠️ Tools & Technologies Used

| Category | Tools |
|---|---|
| **Frontend** | HTML5, CSS3, JavaScript (ES6+) |
| **CI/CD** | Jenkins, Maven |
| **Code Quality** | SonarQube |
| **Containerization** | Docker |
| **Cloud** | AWS EC2 (ap-south-1) |
| **Web Server** | Apache Tomcat |
| **Database** | MySQL |
| **Version Control** | Git, GitHub |

---

## ✨ Features

- 📊 **Live Build Stats** — Animated counters for successful builds, total deployments, avg build time, and failed builds
- 🔁 **CI/CD Pipeline Visualizer** — Step-by-step stage tracker (Git → Maven → SonarQube → Docker → AWS → Tomcat)
- 🖥️ **Terminal Log** — Real-time build log output with timestamps
- 🔘 **Trigger Build Button** — Simulates manually triggering a Jenkins pipeline
- 🧰 **Tool Status Grid** — Live status and progress bars for all 8 DevOps tools
- 🔍 **SonarQube Panel** — Code quality grades, coverage %, bug count, and vulnerability count
- ☁️ **AWS EC2 Info** — Instance type, region, open ports, and live uptime counter
- 🐳 **Docker Containers** — List of running/stopped containers with port mappings
- 📋 **Recent Builds List** — Build history with branch names, status, and durations
- ⏱ **Live Clock** — Real-time clock in the header

---

## 📁 Project Structure

```
devops-dashboard/
├── index.html          # Main dashboard (single-file app)
├── assets/
│   └── preview.png     # Screenshot for README
├── README.md           # Project documentation
├── LICENSE             # MIT License
└── .gitignore          # Git ignore rules
```

---

## 🚀 Getting Started

### Option 1: Open Directly
Just download and open `index.html` in any browser — no setup needed.

### Option 2: Clone & Run Locally
```bash
git clone https://github.com/harivasantharava41-rgb/devops-dashboard.git
cd devops-dashboard
# Open index.html in your browser
```

### Option 3: Host on GitHub Pages
1. Go to your repo → **Settings** → **Pages**
2. Set source to `main` branch, `/ (root)`
3. Click **Save** — your dashboard is live!

---

## 🧪 CI/CD Pipeline Stages Shown

```
📦 Git Clone  →  🔨 Maven Build  →  🔍 SonarQube  →  🐳 Docker Build  →  ☁️ AWS Deploy  →  🌐 Tomcat
```

Each stage shows real-time status: ✅ Done / 🔄 Running / ❌ Failed / ⏳ Pending

---

## 📊 SonarQube Metrics Displayed

- **Quality Gate:** A (Passed)
- **Code Coverage:** 82.4%
- **Duplications:** 1.2%
- **Bugs:** 0
- **Vulnerabilities:** 0
- **Reliability / Security / Maintainability Grades**

---

## ☁️ AWS EC2 Configuration Shown

- **Instance:** t2.micro (Free Tier)
- **OS:** Ubuntu 22.04 LTS
- **Region:** ap-south-1 (Mumbai)
- **Open Ports:** 22 (SSH), 80 (HTTP), 8080 (App)

---

## 🐳 Docker Containers Shown

| Container | Port | Status |
|---|---|---|
| heyd-media-app | 8080 | ✅ Running |
| mysql-db | 3306 | ✅ Running |
| jenkins-ci | 8081 | ✅ Running |
| sonarqube | 9000 | ✅ Running |
| nexus-repo | — | ⛔ Stopped |

---

## 👤 Author

**Harivasanth Arava**
- 📧 hariarava41@gmail.com
- 🔗 [LinkedIn](https://linkedin.com/in/harivasanth-arava)
- 🐙 [GitHub](https://github.com/harivasantharava41-rgb)

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

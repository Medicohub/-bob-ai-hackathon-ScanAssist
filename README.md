# 🩺 ScanAssist

> Safety-First CT/MRI Troubleshooting Assistant

---

## 👥 Team

| Field | Value |
|---|---|
| **Team Name** | ScanAssist |
| **Track** | AI |
| **Team Lead** | Mohmedkaif Ranawadiya |
| **Members** | Ishita SanjivKumar Desai, Angel Hiteshbhai Hirpara, Ishita Nileshkumar Parekh |

---

## 🎯 Problem Statement

CT and MRI scanners are critical healthcare systems. When faults occur, technologists often need to search manuals, remember troubleshooting procedures, or wait for engineer support, increasing downtime and delaying patient care.

ScanAssist helps technologists quickly identify approved troubleshooting procedures, follow safety-first workflows, and generate structured engineer handover reports when issues cannot be resolved.

---

## 💡 Solution

ScanAssist is a Streamlit-based troubleshooting assistant designed for CT and MRI environments .

The platform provides guided troubleshooting procedures, risk assessment, severity scoring, engineer recommendations, analytics dashboards, and automated escalation report generation. This helps reduce downtime, standardize troubleshooting, and improve communication with service engineers.

---

## ✨ Key Features

- **Smart Procedure Search** – Finds troubleshooting procedures using keyword and similarity matching.
- **Safety-First Guidance** – Displays risk levels and severity scores before troubleshooting.
- **Interactive Checklists** – Guides technologists through approved troubleshooting steps.
- **Engineer Report Generation** – Creates TXT and PDF escalation reports automatically.
- **Analytics Dashboard** – Provides insights into procedure categories, risk distribution, and severity trends.
- **Knowledge Base Management** – Supports a structured CT/MRI troubleshooting database.

---

## 🛠️ Tech Stack

| Category | Technologies |
|---|---|
| **Languages** | Python |
| **Frameworks** | Streamlit |
| **IBM Technologies** | Repository structure based on IBM Hackathon Template |
| **Databases** | JSON Knowledge Base |
| **Other** | Git, GitHub, FPDF, Pandas |

---

## 📁 Repository Structure

```text
├── src/
│   ├── app.py
│   ├── procedures.json
│   ├── pages/
│   └── reports/
│
├── docs/
│   ├── problem-statement.md
│   ├── solution-overview.md
│   ├── architecture.md
│   └── setup-guide.md
│
├── demo/
│   ├── screenshots/
│   ├── demo-video-link.txt
│   └── live-demo-url.txt
│
├── presentation/
│
└── submission.yaml
```

---

## ⚡ How to Run

```bash
# Clone repository

git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git

# Open repository

cd YOUR_REPOSITORY

# Install dependencies

pip install -r src/requirements.txt

# Run application

streamlit run src/app.py
```

---

## 🖥️ Demo

| Artifact | Link |
|---|---|
| 📹 Demo Video | See demo/demo-video-link.txt |
| 🌐 Live Demo | See demo/live-demo-url.txt |
| 🖼️ Screenshots | See demo/screenshots/ |
| 📊 Presentation | See presentation/ |

---

## ⚠️ Known Limitations

- Uses a static JSON knowledge base.
- Troubleshooting procedures are currently predefined.
- Does not directly integrate with hospital systems.
- Engineer recommendations are rule-based rather than predictive.

---

## 🏅 What We're Most Proud Of

ScanAssist transforms static troubleshooting documentation into an interactive safety-first assistant. By combining guided procedures, risk assessment, analytics, and automated engineer handover reports, the platform helps CT/MRI technologists respond to equipment issues faster and more consistently while maintaining patient safety.

---

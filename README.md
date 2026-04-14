<div align="center">

<img src="slides/slide-01.jpg" alt="Sanjeevani - Team Jagannath" width="100%">

<br>

# 🌿 Sanjeevani
### Rural Tele-Health Triage System

> *"Right care, at the right time, for the right patient."*

![HACK4IMPACT](https://img.shields.io/badge/HACK4IMPACT-Track%201-00c9a7?style=for-the-badge&logoColor=white)
![KIIT DU](https://img.shields.io/badge/KIIT%20DU-Training%20%26%20Placement-1e3a8a?style=for-the-badge)
![SDI 2026](https://img.shields.io/badge/SDI-2026-6366f1?style=for-the-badge)
![UiPath](https://img.shields.io/badge/UiPath-Automation-FA4616?style=for-the-badge&logo=uipath&logoColor=white)
![LLM](https://img.shields.io/badge/LLM%2FRAG-AI%20Powered-22c55e?style=for-the-badge)

</div>

---

## 👥 Team Jagannath

| Member | Roll Number |
|--------|------------|
| Mehul Kumar | 23051351 |
| Ayush Patwari | 2306109 |
| Rahul | 23052015 |

---

## 🚨 Problem Statement

<img src="slides/slide-02.jpg" alt="Problem Statement" width="100%">

<br>

In **rural and remote areas**, healthcare systems lack an effective triage mechanism — causing all patients, regardless of severity, to be treated with the same priority.

This leads to **dangerous delays** in identifying and treating critical cases such as:
- 🧠 Strokes
- 🩸 Trauma
- 🦠 Severe infections

There is a critical need for an intelligent system that can:
1. Analyze patient symptoms at the point of intake
2. Classify cases based on urgency — **Critical**, **Urgent**, or **Routine**
3. Automatically trigger appropriate actions without requiring expert intervention

---

## 💡 Our Solution

**Sanjeevani** is an AI-powered, fully automated tele-health triage platform that:

- 📋 **Collects** structured patient data via a digital form
- 🤖 **Classifies** urgency using an LLM/RAG-powered agent
- ⚡ **Escalates** critical cases instantly via automated workflows
- 📊 **Empowers** doctors with a real-time case management dashboard

---

## 🔄 Methodology

<img src="slides/slide-03.jpg" alt="Methodology" width="100%">

<br>

### Pipeline Overview

```
Patient Form (UiPath Apps)
        ↓
LLM/RAG Triage Agent → Classifies: Critical / Urgent / Routine
        ↓
UiPath Maestro Workflow → Orchestrates response actions
        ↓
Doctor Dashboard + Email Notification
```

| Step | Component | Description |
|------|-----------|-------------|
| 1️⃣ | **Patient Data Collection** | UiPath Apps form captures name, age, gender, symptoms, duration, severity, medications & location |
| 2️⃣ | **Data Processing & Triage Decision** | LLM/RAG agent processes the data and classifies urgency |
| 3️⃣ | **Decision Execution** | UiPath Maestro orchestrates the workflow based on triage outcome |
| 4️⃣ | **Output & Monitoring** | Doctors receive email alerts; cases tracked on dashboard |

---

## 🛠️ Tech Stack

<img src="slides/slide-04.jpg" alt="Tools Used" width="100%">

<br>

| Tool | Purpose |
|------|---------|
| **UiPath Apps** | Patient-facing intake form UI |
| **UiPath Maestro** | Workflow orchestration engine |
| **UiPath Agents** | AI agent for triage decision-making |
| **UiPath Studio Web** | Workflow design and automation |
| **Google Sheets** | Backend data storage & logging |
| **LLM / RAG** | Natural language symptom analysis & classification |

---

## 📸 Results & Screenshots

### 🧑‍⚕️ Patient Registration Interface

<img src="slides/slide-05.jpg" alt="Patient Registration Interface" width="100%">

> Patients fill in their full name, age, gender, symptoms, symptom duration, self-reported severity, current medications, and location — then hit **Submit**.

---

### 👨‍⚕️ Doctor Case Management Interface

<img src="slides/slide-06.jpg" alt="Doctor Interface" width="100%">

> Doctors see the full case details including AI-assigned severity and reasoning. Actions available: **Accept Case**, **Contact Patient**, **Mark As Resolved**, **Reject Case**.

---

### ⚙️ UiPath Maestro Workflow

<img src="slides/slide-07.jpg" alt="UiPath Maestro Workflow" width="100%">

> The Maestro orchestration view shows the full automation pipeline — from `PatientInfoApp` → `SeverityClassifyAgent` → `NotificationFlow` → `PatientRecordUpdate` — with live execution logs and status tracking.

---

### 📧 Automated Email Notification

<img src="slides/slide-08.jpg" alt="Email Notification Output" width="100%">

> When a case is submitted, the doctor receives a structured email with token number, patient demographics, symptoms, duration, severity classification, and system reasoning.

---

## 🏁 Conclusion

<img src="slides/slide-09.jpg" alt="Conclusion" width="100%">

<br>

The **Sanjeevani Rural Tele-Health Triage System** leverages UiPath's full automation ecosystem to:

- ✅ **Improve Accessibility** — Patients in remote areas submit cases digitally without travelling first
- ⚡ **Reduce Response Times** — AI triage classification happens in seconds
- 📈 **Scale Effortlessly** — Maestro workflows handle concurrent cases across any healthcare network
- 🎯 **Optimize Resources** — Doctors focus on what matters most — critical patients

---

<div align="center">

### Built with ❤️ by Team Jagannath
**Mehul Kumar · Ayush Patwari · Rahul**

*HACK4IMPACT Track 1 · Department of Training & Placement · KIIT DU · SDI 2026*

</div>

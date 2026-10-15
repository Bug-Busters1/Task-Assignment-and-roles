# Team Synergy and Architecture

This document presents the structural hierarchy and the accountability matrix (RACI) for the project team.

---

## 1. Academic Supervision & Team Hierarchy

- **Academic Supervisor:** Eng. Ahmed Abd Elhafez

### Structural Graph
```mermaid
graph TD
    SUP[🎓 Academic Supervisor<br/><b>Eng. Ahmed Abd Elhafez</b>] --> AI
    SUP --> DEV
    SUP --> QA
    subgraph 🧠 Core AI Engine
        AI[<b>Lead AI/ML Engineer</b><br/>Ahmed Sherif]
    end
    subgraph 💻 System Engineering
        DEV1[<b>Senior Backend Engineer</b><br/>Abd Elrahman Esmat]
        DEV2[<b>Lead Frontend Engineer</b><br/>Jana Elshemy]
    end
    subgraph 🛡️ Quality & Delivery
        QA1[<b>Lead SQA Engineer</b><br/>Hana Alaa]
        QA2[<b>Project Manager</b><br/>Ahmed Omar]
    end
```

---

## 2. RACI Matrix

مصفوفة المسؤوليات والأدوار (RACI Matrix):
- **R (Responsible):** القائم بالعمل التنفيذي للمهمة.
- **A (Accountable):** المسؤول المباشر عن جودة النتيجة واعتمادها.
- **C (Consulted):** المستشار الذي يُؤخذ رأيه أثناء العمل.
- **I (Informed):** المطلع على النتائج والتحديثات.

| مرحلة / مهمة العمل (Project Phase / Task) | Hana Alaa (SQA) | Ahmed Omar (PM) | Ahmed Sherif (AI) | Abd Elrahman (Backend) | Jana Elshemy (Frontend) |
| :--- | :---: | :---: | :---: | :---: | :---: |
| Requirements & Project Charter | C | A / R | C | C | C |
| AI Model Training & Optimization | C | I | A / R | C | I |
| Database Architecture & APIs | C | I | C | A / R | C |
| Frontend UI/UX & Dashboard | C | I | I | C | A / R |
| Software Test Plan & Test Execution | A / R | I | C | C | C |
| AI Triage & Integration Testing | A / R | I | R | R | R |
| Final Project Delivery & Pitch | R | A / R | R | R | R |

---

## Navigation
- [Back to Main README](../README.md)
- [View Roles and Responsibilities](./roles-and-responsibilities.md)
- [View Jury Pitch Tips](./jury-pitch-tips.md)
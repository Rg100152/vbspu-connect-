# 🎓 VBSPU Connect
> **Independent Student Portal Prototype**  
> An academic frontend project exploring modern responsive interface design, client-side data workflows, and educational technology.
[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Vanilla JS](https://img.shields.io/badge/Built%20With-Vanilla%20JS%20%7C%20HTML5%20%7C%20CSS3-orange.svg)](#technology-stack)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](#contributing)
---
### ⚠️ Important Notice & Disclaimer
**VBSPU Connect is an independent student project developed for portfolio and educational demonstration purposes.**  
It is **not** an official service, website, or portal of Veer Bahadur Singh Purvanchal University (VBSPU), Jaunpur. All academic records, marks, examination timetables, fee estimates, and notices contained within this project are fictional or illustrative sample data. Official university notifications, schedules, and genuine examination marksheets are published exclusively on the university's official website: [vbspu.ac.in](http://www.vbspu.ac.in).
---
## 📌 Project Overview
**VBSPU Connect** is a mobile-first, zero-dependency, single-file frontend client (`index.html`) engineered to provide an intuitive, modern dashboard experience for university scholars. Designed and built from scratch directly on mobile/browser environments, it serves as a lightweight demonstration of how university resources, attendance monitoring, and syllabus navigation can be brought under a unified UI framework.
### 🌟 Key Highlights
- **Single-File Architecture:** Fully contained in one executable `index.html` file (Semantic HTML5, CSS3 Variables, ES6+ JavaScript).
- **Zero Third-Party Dependencies:** No React, Vue, jQuery, Tailwind, or NPM build tooling required. Runs natively in any browser.
- **Client-Side Computation:** Computes academic GPA/percentage, attendance shortages, and fee deficits directly from data structures.
- **Persistent Local State:** Demonstrates localized preferences (Color Theme, Motion settings, attendance logs, custom notices) using safe, namespaced `localStorage`.
- **Accessible & Responsive:** Fluid mobile drawer, high-contrast borders, focus states, and a global keyboard shortcut search (`Ctrl + K`).
---
## 🚀 Live Demo & Modules

| Module | Features & Capabilities |
| :--- | :--- |
| **Dashboard** | Semester stats, quick-glance attendance meter, assignments tracker, and academic activity log. |
| **Notices & Circulars** | Filter by category (Exam, Admission, Academic, Scholarship), keyword search, text copying, and user-added demo circulars. |
| **Courses & Syllabi** | Departmental directory across Computer Applications, Engineering, Sciences, and Management. |
| **Examination Centre** | Illustrative timetable, countdown counters, CSV schedule export, and print-ready layout. |
| **Result Verification** | Interactive roll-number query engine calculating total marks, percentage, and letter grades client-side. |
| **Attendance Tracker** | Daily lecture attendance calculator with 75% statutory requirement warning highlights. |
| **Fee & Scholarship** | Editable fee calculation tool and UP Post-Matric Scholarship prerequisite checklist. |
| **Digital Library** | Reference catalog with department filters and stock status. |
| **Demo Admin Console** | Preview interface demonstrating content management and local notice administration. |

---
## 🛠️ Technology Stack
- **Markup:** Semantic HTML5 (`<main>`, `<section>`, `<aside>`, `<nav>`, `<header>`, `<footer>`)
- **Styling:** Vanilla CSS3 (Custom properties / CSS variables, Flexbox, CSS Grid, Glassmorphism, Print stylesheets)
- **Scripting:** Modern ECMAScript (ES6+) with modular controller patterns
- **Data Storage:** Browser `window.localStorage` (isolated under `vbspu_connect_*` namespaces)
- **Export Engines:** Client-side Blob and DataURI generators (CSV and JSON export)
---
## ⚡ Getting Started
Since the entire application is bundled in a single lightweight file, setup requires zero installation steps:
### Option 1: Direct File Execution
1. Clone or download this repository:
   ```bash
   git clone [https://github.com/Rg100152/vbspu-connect.git](https://github.com/Rg100152/vbspu-connect.git)
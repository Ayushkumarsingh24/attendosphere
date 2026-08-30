<div align="center">

# 🏫 AttendoSphere
### Smart Attendance Monitoring System (Smart India Hackathon Prototype)

[![HTML5](https://img.shields.io/badge/HTML5-Vanilla-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-CDN-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![Hackathon](https://img.shields.io/badge/Event-Smart_India_Hackathon-blue?style=flat-square)](https://www.sih.gov.in/)

</div>

---

## 💡 Core Concept

**AttendoSphere** is a lightweight, single-file frontend prototype simulating a next-generation automated attendance ecosystem. It combines **simulated facial recognition** and **Bluetooth proximity detection** with Aadhaar-based face registration to secure classroom entry and exit logs without expensive backend infrastructure.

---

## 🚀 Key Features

* **Facial Recognition & Bluetooth Verification:** Simulates proximity checks and biometric scans for secure entry/exit marking.
* **Aadhaar Integration:** Simulated 12-digit Aadhaar-linked face registration for administrative verification.
* **Role-Based Access Control (RBAC):** Tailored dashboards and workflows for Students, Teachers, and Administrators.
* **In-Memory Mock Data:** Generates dynamic schedules, student directories, and attendance metrics out-of-the-box (`generateFakeData()`).

---

## 👥 Role-Based Dashboards

| Role | Key Capabilities | Demo Credentials |
| :--- | :--- | :--- |
| **Student** | • View daily, weekly, and monthly attendance percentage progress bars<br>• Monitor subject-wise daily analytics & recent attendance history<br>• Trigger simulated face + Bluetooth verification (**Mark Entry** / **Mark Exit**) | `student1` / `demo1` |
| **Teacher** | • Schedule classes by subject, date, and time<br>• Review subject-wise attendance summaries with filtering options<br>• Audit daily attendance detail tables | `teacher1` / `pass123` |
| **Admin** | • Register student faces against a 12-digit Aadhaar number<br>• Onboard new students (name, credentials, branch, semester)<br>• Manage and remove active student records | `admin` / `admin123` |

---

## 🛠️ Tech Stack

* **Frontend:** Vanilla JavaScript (ES6+), HTML5
* **Styling:** Tailwind CSS (via CDN)
* **Icons:** Font Awesome
* **Data Layer:** In-memory mockup generation (resets on page refresh)

---

## 🏃‍♂️ Quick Start

1. Clone or download the repository.
2. Open the main file in any modern web browser (no local server or backend required).
3. Log in using any of the pre-configured demo credentials listed above.

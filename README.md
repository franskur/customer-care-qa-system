# Customer Care QA & Complaint Resolution System 🎧

An enterprise ticketing and quality assurance web platform built to resolve customer complaints under strict Service Level Agreements (SLA) while auditing support agent communication standards.

---

## 🌟 Live Demo & Portfolio
- **Author:** Frans Kurniawan
- **Portfolio:** [https://franskur.github.io](https://franskur.github.io)
- **Role:** Full-Stack PHP Web Developer

---

## 🚀 Key Features

- **SLA Countdown Tracking & Automated Escalation:**
  - Real-time countdown timers based on complaint severity (Urgent, High, Normal, Low).
  - Automated ticket re-routing and notification alerts when an SLA deadline approaches breach status.

- **Quality Assurance (QA) Sampling & Scorecards:**
  - Dedicated supervisor module for random ticket sampling and QA audit scoring.
  - Customizable grading rubrics (Greeting, Problem Resolution, Politeness, Policy Compliance) with automated agent scorecard calculation.

- **Omnichannel Complaint Ticket Queue:**
  - Centralized intake dashboard with priority tagging, status filters, and departmental handovers.
  - Full internal notes and public customer response threads.

- **Root-Cause Analytics & Sentiment Dashboard:**
  - Categorized complaint trend charts identifying recurring product defects or operational bottlenecks.

---

## 🛠️ Tech Stack & Architecture

- **Backend:** PHP 8.x, Laravel Framework, RESTful API Endpoints
- **Database:** MySQL (Normalized relational schema with immutable audit logs)
- **Frontend:** HTML5, CSS3, JavaScript (ES6+), DataTables.js, Bootstrap 5
- **Security:** Secure Session Management, Input Sanitization, Role-Based Access Control

---

## ⚡ Local Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/franskur/customer-care-qa-system.git
   cd customer-care-qa-system
   ```

2. **Install Dependencies:**
   ```bash
   composer install
   ```

3. **Configure Environment:**
   ```bash
   cp .env.example .env
   php artisan key:generate
   ```

4. **Run Database Migrations:**
   ```bash
   php artisan migrate --seed
   ```

5. **Start Application:**
   ```bash
   php artisan serve
   ```

---

## 📄 License & Notes
Designed and developed by **Frans Kurniawan**. Open for portfolio showcase and customer service operations.

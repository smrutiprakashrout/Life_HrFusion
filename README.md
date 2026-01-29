<div align="center">
   <picture>
      <img src="./release/Debian/devnest_1.0_arm64/usr/share/icons/hicolor/512x512/apps/devnest.png" width="150" height="150">
   </picture>
   <h2>Life_HrFusion</h2>
</div>
<div align="center">

![Static Badge](https://img.shields.io/badge/Devnest-v1.1.0-blue)
![Static Badge](https://img.shields.io/badge/Downloads-10+-green)
![Static Badge](https://img.shields.io/badge/License-MIT-yellow)
![Static Badge](https://img.shields.io/badge/Total_Lines-86k-red)

| Employee Management & HR Automation Platform fullstack web app |
|-----------------------------------------|
</div>

**Life_HrFusion** is a full-stack web application designed to provide a **centralized HR and employee management ecosystem**. It goes beyond basic employee records by integrating **personal data management, salary processing, income tax management, notifications, events, and organizational workflows** into a single scalable platform.

> Life_HrFusion is a complete digital HR ecosystem for modern organizations.

---

## 🚀 Overview

Life_HrFusion provides an end-to-end solution for:

* Employee lifecycle management
* Payroll and salary handling
* Tax information management
* Internal communication
* Event and notification systems
* Organizational data centralization

It is built for **scalability, security, automation, and enterprise readiness**.

---

## ✨ Core Features

* 👤 **Employee Personal Data Management**
  Centralized management of employee profiles and records

* 💰 **Salary & Payroll Management**
  Salary structures, payments, and history tracking

* 🧾 **Income Tax Management**
  Tax calculation, records, and compliance data

* 🔔 **Notifications System**
  Internal alerts, announcements, and updates

* 📅 **Events Management**
  Company events, schedules, and calendars

* 🗂 **HR Workflow Automation**
  Automated HR processes and data flows

* 🔐 **Secure Access Control**
  Role-based authentication and authorization

* 📊 **Admin Dashboard**
  Centralized control and monitoring system

---

## 🧠 System Architecture

```text
[ Next.js Frontend ]
        │
        │  (API Requests)
        │
[ Node.js + Express Backend ]
        │
        │  (Business Logic + Auth)
        │
[ MongoDB Database ]
        │
        │
[ Nginx Reverse Proxy ]
        │
        │
[ Docker Containerization ]
        │
        │
[ Cloud Deployment (Vercel) ]
```

---

## 🛠️ Tech Stack

### Frontend

* Next.js
* React
* Tailwind CSS

### Backend

* Node.js
* Express.js

### Database

* MongoDB

### Infrastructure

* Docker
* Nginx
* Vercel

---

## 🔧 Platform Capabilities

* Employee lifecycle management
* Secure data storage
* Payroll automation
* Tax data handling
* Event scheduling
* Notification pipelines
* Admin control panel
* API-driven architecture
* Scalable microservice-ready design
* Cloud-native deployment

---

## 📦 Installation

### Prerequisites

* Node.js
* Docker & Docker Compose (optional)
* MongoDB (local or cloud)

---

### Docker Setup

```bash
# Clone repository
git clone <repo-link>
cd life_hrfusion

# Build and run services
docker-compose up -d
```

---

### Local Development

```bash
# Backend
cd server
npm install
npm run dev

# Frontend
cd client
npm install
npm run dev
```

---

## ▶️ Usage Flow

1. Admin creates organization structure
2. Employees are onboarded
3. Personal data is managed
4. Salary and payroll are processed
5. Tax data is calculated and stored
6. Notifications and events are published
7. Admin monitors through dashboard

---

## 🎯 Project Positioning

Life_HrFusion functions as:

* 🏢 **Enterprise HR Platform**
* 📊 **Workforce Management System**
* 💼 **Payroll Management System**
* 🧠 **Organizational Data Platform**
* 🔄 **HR Automation Engine**

---

## 🤝 Contributing

1. Fork the repository
2. Create a branch

   ```bash
   git checkout -b feature-name
   ```
3. Commit changes

   ```bash
   git commit -m "Add feature"
   ```
4. Push branch

   ```bash
   git push origin feature-name
   ```
5. Open Pull Request

---

## 📄 License

MIT License

---


> Life_HrFusion is a scalable, secure, and modern HR ecosystem platform built for real-world organizational needs.

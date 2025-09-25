# 🚨 Alerting & Notification Platform

A lightweight, extensible system for delivering persistent, targeted in-app alerts with team/org/user-level visibility and recurring reminders every 2 hours until snoozed or expired.

---

## ✨ Features

### 👩‍💼 Admin
- Create alerts with:
  - Title, message, severity (Info, Warning, Critical)
  - Delivery type: In-App (future: Email, SMS)
  - Visibility: Organization, Teams, or Users
  - Start & expiry time
  - Recurring reminders (every 2 hours by default)
- Update, archive, and manage alerts
- View alerts with filters (severity, status, audience)
- Track alert delivery, reads, and snoozes

### 👤 End Users
- Receive alerts based on visibility
- Alerts repeat every 2 hours until snoozed or expired
- Snooze alerts for the day
- View dashboard with:
  - Active alerts
  - Read/unread status
  - Snoozed history

### 📊 Analytics Dashboard
- Total alerts created
- Delivery vs. read count
- Snoozes per alert
- Severity breakdown

---

## 🧱 Architecture

- Clean OOP design following SOLID principles
- Key Design Patterns:
  - **Strategy Pattern** – for pluggable notification channels
  - **Observer Pattern** – for user subscriptions to alerts
  - **State Pattern** – for read/unread/snoozed logic
- Modular separation of:
  - Alert Management
  - Notification Delivery
  - User Preferences

---







# 🚀 Automation Week 1 – Workflow Engineering

This repository documents practical automation workflows built using Zapier to integrate productivity platforms and implement validation logic.

---

## 🧩 Automation 1: Form Submission Notification System

### 🎯 Objective
Eliminate manual monitoring of Google Form submissions.

### 🛠 Architecture
Google Forms → Google Sheets → Zapier Filter → Slack Notification

### ⚙️ Implementation Details
- Trigger: New Google Sheets row
- Validation: Filter step ensuring Name and Email are not empty
- Action: Structured Slack message
- Failure Handling: Execution stops if validation fails

### 📦 Tools
- Zapier
- Google Forms
- Google Sheets
- Slack

---

## 📧 Automation 2: Gmail to Slack Alert System

### 🎯 Objective
Improve response time to incoming emails.

### 🛠 Architecture
Gmail Trigger → Slack Channel Notification

### ⚙️ Implementation Details
- Trigger: New Gmail message
- Extracted fields: Sender, Email, Subject, Snippet
- Action: Formatted Slack notification

### 📦 Tools
- Zapier
- Gmail
- Slack

---

## 🧠 Skills Demonstrated
- Workflow architecture design
- Conditional logic implementation
- Cross-platform API integration
- Error prevention and validation
- Documentation best practices

---

## 📌 Status
✔ Fully functional  
✔ Tested with valid and invalid scenarios  
✔ Successfully deployed

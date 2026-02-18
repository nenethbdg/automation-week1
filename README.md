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

---

## 🔀 Automation 3: Priority Email Router

### 🎯 Objective
Automatically route incoming emails to different Slack channels based on urgency.

### 🛠 Architecture
Gmail Trigger → Filter (Subject Contains "URGENT") → Slack Channel Routing

### ⚙️ Implementation Details

#### Priority Flow
- Trigger: New Gmail message
- Condition: Subject contains "URGENT"
- Action: Send message to #priority Slack channel

#### General Flow
- Trigger: New Gmail message
- Condition: Subject does NOT contain "URGENT"
- Action: Send message to #general Slack channel

### 🧠 Logic Design
This workflow simulates conditional branching using Zapier’s Filter step by splitting urgency-based email handling into two separate automation flows.

### 📦 Tools Used
- Zapier
- Gmail
- Slack

### 📌 Status
✔ Successfully tested with URGENT and non-urgent emails  
✔ Confirmed correct Slack channel routing  


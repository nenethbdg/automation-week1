# Week 1 – Automation Foundations

## Overview
This repository documents automation workflows built using Zapier to integrate productivity platforms and implement validation logic.

---

## Automation 1: Form Submission Notification System

### Problem
Manual checking of Google Form responses caused delays in responding to submissions.

### Solution
Built an automated workflow that:
- Detects new Google Sheets rows from form submissions
- Validates required fields (Name and Email)
- Sends structured Slack notifications
- Stops execution if validation fails

### Tools Used
- Zapier
- Google Forms
- Google Sheets
- Slack

### Reliability Improvements
- Implemented conditional filter step
- Tested invalid input scenarios
- Confirmed controlled execution flow

---

## Automation 2: Gmail Notification System

### Problem
Important emails required immediate team visibility.

### Solution
Built a workflow that:
- Detects new Gmail messages
- Extracts sender and subject details
- Sends formatted Slack channel notification

### Tools Used
- Zapier
- Gmail
- Slack

---

## Skills Demonstrated
- Workflow design
- Trigger-based automation
- Conditional logic implementation
- Cross-platform integration
- Structured documentation

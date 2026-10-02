# Eventforce Management System

## 📌 Project Overview

Eventforce Management System is a Salesforce-based application designed to manage events, clients, vendors, venues, event budgets, approvals, and notifications in one centralized system.

The system helps event coordinators organize event-related information and automate important processes such as cancellation approvals and client reminders.

## 🎯 Objectives

- Manage event details efficiently.
- Maintain client, vendor, and venue information.
- Track event dates, types, status, and budgets.
- Automate event approval processes.
- Send automated reminders to clients.
- Improve event coordination and reduce manual work.

## 🛠️ Technologies Used

- Salesforce
- Salesforce Object Manager
- Custom Objects & Fields
- Lightning Experience
- Flow Builder
- Approval Processes
- Email Alerts
- Apex

## 📂 Main Components

### Custom Objects

- **Event** – Stores event information such as event name, date, type, status, budget, client, and venue.
- **Client** – Stores client-related information.
- **Vendor** – Stores vendor information.
- **Venue** – Stores venue details.
- **Feedback** – Stores event feedback.

### Automation

- **Event Cancellation Approval Process**
  - Handles approval for events with pending cancellation status.
  - Assigns the approval request to the appropriate approver.
  - Updates the event status during the approval process.
  - Sends notification after approval.

- **Client Reminder Flow**
  - Record-triggered flow for Event records.
  - Includes a scheduled path for sending a reminder 3 days before the event.
  - Uses an email alert to notify the client.

## ⚙️ Features

- Event management
- Client management
- Vendor management
- Venue management
- Event budget tracking
- Event status tracking
- Event cancellation approval
- Automated client reminders
- Email notifications
- Salesforce custom tabs
- Apex-based functionality

## 📸 Screenshots

Screenshots demonstrating the Salesforce configuration and automation are included in this repository.

## 🚀 Project Outcome

The Eventforce Management System provides a centralized Salesforce solution for managing event operations. It combines custom objects, automation, approval processes, email alerts, and Apex functionality to streamline event management.

## 👩‍💻 Project

**Eventforce Management System**

Built using Salesforce Developer Edition.

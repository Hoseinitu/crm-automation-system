CRM Automation System

An automated Customer Relationship Management (CRM) system built with n8n to manage leads, track sales activities, automate follow-ups, generate reports, and monitor workflow errors.

Project Overview

This project demonstrates how business processes can be automated using low-code tools and workflow automation.

The system consists of four independent workflows that work together to simplify lead management and improve operational efficiency.

Workflows

1. Lead Registration

Collects lead information through a form.

Validates submitted data.

Checks for duplicate leads.

Calculates lead scores and assigns priorities.

Automatically assigns leads to sales representatives.

Stores new leads in the CRM database.

Sends email notifications.

2. Lead Status Management

Allows users to update lead statuses.

Searches for leads using their email addresses.

Checks whether the requested status has changed.

Updates lead records and handles missing leads.

3. Lead Follow-up & Reporting

Automatically checks leads that require follow-up.

Prevents duplicate follow-up reminders.

Sends reminder emails.

Generates weekly CRM reports.

Provides statistics about lead priorities and statuses.

4. CRM Error Notifications

Captures errors from connected workflows.

Collects execution and error information.

Sends automated email notifications to help with troubleshooting.

Technologies Used

n8n – Workflow automation

JavaScript – Data processing and business logic

Data Tables – Data storage and management

SMTP / Email – Automated notifications

GitHub – Version control and project documentation

Project Structure

crm-automation-system/ │ ├── workflows/ │ ├── 01-lead-registration.json │ ├── 02-lead-status-management.json │ ├── 03-lead-follow-up-reporting.json │ └── 04-error-notifications.json │ ├── screenshots/ │ └── README.md 

Setup & Usage

Install and run n8n.

Import the workflow JSON files into n8n.

Configure the required Data Tables.

Set up your own SMTP credentials.

Review and configure workflow connections and references.

Activate the workflows and test the forms and automation processes.

Note: Credentials, Data Table references, and other environment-specific settings must be configured after importing the workflows.

Key Features

Automated lead registration and validation

Duplicate lead detection

Lead scoring and priority assignment

Sales representative assignment

Lead status tracking

Automated follow-up reminders

Weekly performance reporting

Centralized error notifications

Purpose

This project was developed as part of a practical low-code automation portfolio to demonstrate workflow design, business process automation, data handling, and error management using n8n.

Author: Hoseinitu

Project: CRM Automation System

Platform: n8n

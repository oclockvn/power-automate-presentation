---
title: "Introduction to Workflow Automation & Power Automate"
author: Quang Phan
theme: default
---

# Introduction to Workflow Automation

---

## What is Workflow Automation?

- **Definition**: 
  - Workflow automation is the process of automating repetitive tasks and processes to improve efficiency, reduce errors, and save time.
  
- **What can it do?**
  - Automate manual tasks (e.g., sending emails, data entry)
  - Integrate different systems and applications
  - Streamline business processes
  
- **Use Cases**:
  - Sending automated emails
  - Data synchronization between apps
  - Employee onboarding/offboarding
  - Generating reports
  - Approval workflows

---

# Introducing Power Automate

---

## What is Power Automate?

- **Overview**:
  - Power Automate (formerly Microsoft Flow) is a cloud-based service provided by Microsoft that allows users to create automated workflows between apps and services.
  
- **Key Features**:
  - Integration with Microsoft 365, Dynamics 365, and other third-party apps
  - Pre-built templates for common workflows
  - Drag-and-drop interface for easy automation
  - Supports both cloud and desktop flows

- **Benefits**:
  - No-code/low-code solution
  - Easy to integrate with Microsoft ecosystem
  - Scalable for enterprise use

---

# Demo: Sending Emails Using Power Automate

---

## Scenario: Send Monthly Email to Employees

1. **Objective**:
   - Send an email to employees listed in a Google Sheet on the first day of every month.

2. **Steps**:
   - **Step 1**: Connect Power Automate to Google Sheets.
   - **Step 2**: Create a flow that triggers on the first day of each month.
   - **Step 3**: Loop through the list of employees in the Google Sheet.
   - **Step 4**: Send an email to each employee using Outlook or Gmail.

---

## Demo Walkthrough

1. **Trigger**: 
   - Use the "Recurrence" trigger to set the flow to run on the first day of every month.

2. **Action 1**: 
   - Use the "List rows present in a table" action to fetch employee data from Google Sheets.

3. **Action 2**: 
   - Use the "Apply to each" loop to iterate through each employee.

4. **Action 3**: 
   - Use the "Send an email (V2)" action to send an email to each employee.

---

# Alternatives to Power Automate

---

## Other Workflow Automation Tools

1. **Make (formerly Integromat)**:
   - **Overview**: A powerful automation tool with a visual builder.
   - **Pros**: Highly customizable, supports complex workflows.
   - **Cons**: Can be expensive for large-scale use.

2. **n8n**:
   - **Overview**: An open-source workflow automation tool.
   - **Pros**: Self-hosted, highly flexible, and free for small projects.
   - **Cons**: Requires more technical knowledge to set up.

3. **Zapier**:
   - **Overview**: A popular no-code automation tool.
   - **Pros**: Easy to use, integrates with thousands of apps.
   - **Cons**: Limited customization compared to Make or n8n.

---

# Conclusion

---

## Why Automate Workflows?

- **Efficiency**: Save time by automating repetitive tasks.
- **Accuracy**: Reduce human error in manual processes.
- **Scalability**: Easily scale workflows as your business grows.

---

## Questions?

Thank you for your attention! Feel free to ask any questions about workflow automation or Power Automate.

---


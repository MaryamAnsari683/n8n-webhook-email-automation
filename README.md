# n8n Webhook to Email Automation

## Project Overview

This project is an automated email workflow built with **n8n**. It receives form data through a POST webhook, processes the incoming JSON data, and sends an automated email response.

The workflow demonstrates how webhooks, JSON data processing, and email automation can be connected to create a simple and practical business automation system.

## Objective

The main objective of this project is to automate the process of receiving contact information and sending an email response without manual intervention.

## Workflow

The automation follows this flow:

**Webhook → Edit Fields → Send an Email**

### 1. Webhook

The workflow starts when a POST request is received through the n8n Webhook node.

The incoming JSON contains information such as:

- Name
- Email
- Message

### 2. Edit Fields

The incoming data is processed and the required fields are prepared for the email step.

### 3. Send an Email

The processed information is used to send an automated email response to the submitted email address.

## Technologies Used

- n8n
- Webhooks
- JSON
- JavaScript / Data Transformation
- Gmail / SMTP

## Example Input

```json
{
  "name": "Maryam",
  "email": "user@example.com",
  "message": "Hello"
}Example Result

After receiving the webhook request, the workflow processes the submitted information and automatically sends an email response.

Key Features
Webhook-based automation
JSON data processing
Automated email response
No manual processing required
Simple and reusable workflow
Built with n8n
Testing

The workflow was tested by sending a POST request containing form data to the n8n webhook.

The test confirmed that:

The webhook successfully received the request.
The JSON data was processed correctly.
The email was sent successfully.
The automated email was received in the inbox.
Screenshots
Workflow

Form Submission

Automated Email

Repository Contents
workflow.json — Exported n8n workflow
README.md — Project documentation
Screenshots — Workflow and testing results
Task

This project was developed as part of the Barakah TechLabs AI & Workflow Automation internship.

The implementation covers the requirements of the Basic Webhook to Email Automation task.

Author

Maryam Ansari


### Paste karne ke baad

Neeche **Commit changes** par click karo.

Phir README ke **Preview** mein check karna hai ke:
- headings properly show ho rahi hain
- JSON ek box mein show ho raha hai
- screenshots render ho rahe hain

**Abhi sirf paste + commit karo.** Uske baad screenshot bhej dena, main check kar dungi.

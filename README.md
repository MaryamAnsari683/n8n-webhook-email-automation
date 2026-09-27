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
  "email": "maryam992@gmail.com",
  "message": "Hello"
}

# Project Planning

## Project Title

Auto-Ticket Classification using Flow Designer

## 4.1 Project Workflow

The planned workflow of the system is:

Student creates an IT ticket
↓
Ticket is stored in the Incident WorkFlow table
↓
Flow Designer is triggered
↓
The ticket description is checked
↓
Relevant keywords are identified
↓
Category is assigned
↓
Subcategory is assigned
↓
Email notification is sent

## 4.2 Ticket Classification Plan

| Issue / Keyword | Category | Subcategory |
|---|---|---|
| WiFi | Network | Wi-Fi |
| Projector | Hardware | Projector |
| Password/Login | Access | Forgot Password |
| Slow/Hanging | Performance | Slow Computer |

## 4.3 Flow Planning

Flow Name:

Auto Classify School IT Tickets

Application:

Global

Trigger:

Record Created

Table:

Incident WorkFlow

Condition:

Category is Empty

## 4.4 Expected Working

When a new ticket is created, the Flow Designer checks the ticket
description and identifies the type of issue.

Based on the identified keyword, the appropriate Category and
Subcategory are assigned automatically.

## 4.5 Notification Planning

After processing the ticket, an email notification is sent to the caller.

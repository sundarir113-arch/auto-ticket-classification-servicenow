# Project Development

## Project Title

Auto-Ticket Classification using Flow Designer

## 5.1 Development Platform

The project was developed using ServiceNow and Flow Designer.

## 5.2 Flow Name

Auto Classify School IT Tickets

## 5.3 Trigger

The flow is triggered when a new record is created in the Incident
WorkFlow table.

The condition used is:

Category is Empty

## 5.4 Wi-Fi Classification

When the ticket description contains a WiFi-related keyword:

Category = Network

Subcategory = Wi-Fi

## 5.5 Projector Classification

When the ticket description contains a Projector-related keyword:

Category = Hardware

Subcategory = Projector

## 5.6 Password Classification

When the ticket description contains Password or Login-related
keywords:

Category = Access

Subcategory = Forgot Password

## 5.7 Slow Computer Classification

When the ticket description contains Slow or Hanging-related keywords:

Category = Performance

Subcategory = Slow Computer

## 5.8 Email Notification

The flow sends an email notification to the caller after the ticket
processing.

Email Subject:

Your Request for the issue has been submitted.

## 5.9 Update Set

The ServiceNow project is maintained using the Update Set:

Project Update Set

The exported Update Set XML file will be included in this project
repository.

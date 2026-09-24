# Final Project Report

# Auto-Ticket Classification using Flow Designer

## 1. Abstract

Auto-Ticket Classification using Flow Designer is a ServiceNow-based
project that automates the classification of school IT helpdesk tickets.

The system identifies keywords in the ticket description and automatically
assigns the appropriate category and subcategory.

The project reduces manual classification work and improves ticket
routing efficiency.

## 2. Introduction

School IT helpdesks receive different types of technical issues such as
Wi-Fi problems, projector failures, password problems and slow computers.

Manual classification requires helpdesk staff to review and categorize
each ticket.

This project uses ServiceNow Flow Designer to automate the classification
process.

## 3. Problem Statement

Manual classification of IT tickets requires additional time and effort.
The helpdesk staff must identify the issue and select the appropriate
category and subcategory.

## 4. Objectives

- Automatically classify IT tickets.
- Reduce manual classification work.
- Improve ticket routing efficiency.
- Maintain consistent classification.
- Send email notifications.
- Provide a maintainable automation solution.

## 5. Existing System

In the existing process, helpdesk staff manually review tickets and
select the category and subcategory.

## 6. Proposed System

The proposed system uses ServiceNow Flow Designer to automatically
classify tickets based on keywords in the ticket description.

## 7. System Design

The system uses an Incident WorkFlow table containing ticket details,
category, subcategory, caller and other required information.

## 8. Category and Subcategory

| Category | Subcategory |
|---|---|
| Network | Wi-Fi |
| Hardware | Projector |
| Access | Forgot Password |
| Performance | Slow Computer |

## 9. Flow Designer

The flow is named:

Auto Classify School IT Tickets

The flow is triggered when a new record is created and the Category is
empty.

## 10. Automatic Classification

The system checks the ticket description and assigns the appropriate
Category and Subcategory.

## 11. Email Notification

After processing the ticket, an email notification is sent to the caller.

## 12. Testing

The system was tested using different IT issue descriptions, including
WiFi and Projector issues.

## 13. Update Set

The project configuration is maintained using the ServiceNow Update Set
named Project Update Set.

The Update Set is exported as an XML file for sharing and project
submission.

## 14. Result

The developed system automatically classifies IT tickets according to
the defined keyword mappings and performs the required notification
process.

## 15. Conclusion

The project demonstrates how ServiceNow Flow Designer can be used to
automate IT ticket classification.

The solution reduces manual categorization work and provides a
structured and maintainable automation process.

## 16. Future Enhancements

Possible future enhancements include automatic assignment, SLA tracking
and predictive intelligence.

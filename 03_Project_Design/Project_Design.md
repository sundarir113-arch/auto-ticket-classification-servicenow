# Project Design

## Project Title

Auto-Ticket Classification using Flow Designer

## 3.1 Custom Table

The project uses a custom table named:

Incident WorkFlow

The table stores the information required for IT tickets.

## 3.2 Table Fields

The main fields used in the table are:

- Number – Auto Number
- Caller – Reference to sys_user
- Category – Choice
- Subcategory – Choice
- Short Description – String
- Description – String
- State – Choice
- Assigned Group – Reference to sys_user_group
- Assigned to – Reference to sys_user

## 3.3 Category Values

The Category field contains:

- Network
- Hardware
- Access
- Performance

## 3.4 Subcategory Values

The Subcategory field contains:

- Wi-Fi
- Projector
- Forgot Password
- Slow Computer

## 3.5 Dependent Category and Subcategory

The Subcategory depends on the selected Category.

The mapping is:

- Network → Wi-Fi
- Hardware → Projector
- Access → Forgot Password
- Performance → Slow Computer

## 3.6 Purpose of the Design

The system design provides a structured way to store IT tickets and
automatically classify them using ServiceNow Flow Designer.

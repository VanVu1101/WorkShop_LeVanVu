---
title: "Week 9 Worklog"
date: 2026-06-29
weight: 9
chapter: false
pre: "<b>1.9.</b>"
---

{{% notice info %}}
This worklog summarizes the analysis, UI/UX design, and frontend development activities carried out during the ninth week of the internship project. The primary objective was to finalize the overall system architecture, assign development responsibilities among team members, and begin implementing the user interface according to the agreed software design.
{{% /notice %}}

# Week 9 Objectives

The objectives for Week 9 were:

- Analyze project requirements and define the overall system scope.
- Design the software architecture and application workflow.
- Define functional modules and allocate development tasks among team members.
- Design UI/UX wireframes for the main pages of the system.
- Establish frontend development standards and project structure.
- Develop the initial frontend interface using ReactJS.
- Prepare reusable UI components for future integration with backend APIs.

---

# Weekly Activities

| Day | Task | Start Date | Completion Date | Deliverables |
|-----|------|------------|----------------|--------------|
| Monday | Conduct team meeting to analyze business requirements, clarify project objectives, identify user roles, and define functional requirements. | 15/06/2026 | 15/06/2026 | Requirement Analysis |
| Tuesday | Design the overall software architecture, application workflow, and interaction between frontend, backend, and database components. | 16/06/2026 | 16/06/2026 | System Architecture Diagram |
| Wednesday | Break down the system into functional modules and assign responsibilities to each development team member. | 17/06/2026 | 17/06/2026 | Module Assignment Document |
| Thursday | Design UI wireframes for Login, Dashboard, Internship Management, Weekly Reports, Task Management, Profile, and Document Management pages. | 18/06/2026 | 18/06/2026 | UI Wireframes |
| Friday | Define UI/UX standards including typography, color palette, spacing, responsive layout, reusable components, and project folder structure. | 19/06/2026 | 19/06/2026 | UI Design Guidelines |
| Saturday | Initialize React project structure, configure routing, organize folders, create shared layouts, navigation, and common UI components. | 20/06/2026 | 20/06/2026 | Frontend Project Structure |
| Sunday | Develop the first version of frontend pages and perform interface integration testing between components to ensure consistency. | 21/06/2026 | 21/06/2026 | Initial Frontend Prototype |

---

# Detailed Activities

## 1. Requirement Analysis

During this week, the development team organized multiple meetings to collect and analyze the software requirements. Functional requirements, user stories, and business processes were discussed to ensure every team member had a common understanding of the project objectives.

The analysis focused on:

- Internship management process
- Weekly report management
- Task assignment and progress tracking
- User profile management
- CV and document management
- Authentication and authorization
- Administrator management features

The outputs included:

- Functional requirements
- Non-functional requirements
- User roles
- Business workflow
- Initial database entities

---

## 2. System Architecture Design

Designed the overall architecture of the Internship Management System using a three-tier architecture integrated with AWS cloud services to improve scalability, security, reliability, and deployment efficiency.

### Frontend Technologies

- ReactJS
- Vite
- JavaScript

### Backend Technologies

- Node.js
- Express.js
- RESTful API
- JWT Authentication

### Database

- Mysql
- Amazon RDS for mysql

### AWS Cloud Services

- Amazon EC2 – Host backend services
- Amazon S3 – Store CVs, profile images, and uploaded documents
- Amazon CloudFront – Deliver static content with low latency
- Elastic Load Balancer (ELB) – Distribute incoming traffic
- Amazon EC2 Auto Scaling – Automatically scale application servers
- AWS IAM – Identity and Access Management
- AWS VPC – Network isolation and security
....
### Development Tools

- Visual Studio Code
- Git
- GitHub
- Postman
- Figma
- Draw.io

---

## 3. Functional Module Planning

The application was divided into independent modules to facilitate parallel development.

Main modules include:

- Authentication Module
- Dashboard Module
- Internship Management
- Weekly Worklog Management
- Task Management
- Notification Module
- User Profile Module
- CV & Document Module
- Administration Module

Each module was assigned to a responsible team member with clearly defined deliverables and deadlines.

---

## 4. UI/UX Design

Designed wireframes and mockups before implementation.

The following pages were completed:

- Login
- Dashboard
- Internship List
- Internship Detail
- Weekly Worklog
- Task List
- Task Detail
- Profile
- CV Upload
- Document Management
- Settings

UI design principles:

- Clean and modern interface
- Consistent navigation
- Responsive layout
- Easy-to-use interaction
- Reusable design system

---

## 5. Frontend Project Organization

Established frontend coding standards.

Configured:

- React Router
- Component structure
- Pages directory
- Layouts
- Hooks
- Services
- API layer
- Assets
- Constants
- Utilities

Folder organization
Naming conventions were standardized to ensure maintainability and consistency across the project.

---

## 6. Frontend Development

Started implementing the frontend according to the approved UI design.

Completed:

- Header
- Sidebar
- Navigation Menu
- Dashboard Layout
- Login Page
- Profile Page
- Weekly Report Page
- Internship List Page
- Shared Components

Reusable components created:

- Button
- Input
- Modal
- Table
- Card
- Loading Spinner
- Pagination
- Search Box
- Status Badge

---

## 7. Integration Preparation

Prepared the frontend for backend integration by:

- Creating API service templates
- Defining request/response models
- Configuring Axios instance
- Handling authentication tokens
- Creating reusable API hooks
- Planning error handling strategy

This preparation allows seamless integration with backend APIs in the following development phase.

---

# Weekly Deliverables

Completed deliverables include:

- Requirement Analysis Document
- System Architecture Diagram
- Functional Module Diagram
- User Flow Diagram
- UI Wireframes
- Frontend Design Guidelines
- React Project Structure
- Shared UI Components
- Initial Frontend Screens
- API Integration Plan

---

# Skills Acquired

During this week, the following skills were strengthened:

- Software Requirement Analysis
- Software Architecture Design
- UI/UX Design
- ReactJS Project Organization
- Component-Based Development
- Team Collaboration
- Git Workflow
- Responsive Web Design
- Frontend Project Planning
- API Integration Preparation

---

# Week 9 Achievements

Successfully analyzed and finalized the functional requirements of the internship management system.

Completed the overall software architecture and application workflow.

Designed the primary user interface and reusable frontend components.

Established frontend coding standards and project structure.

Assigned development responsibilities among team members and synchronized the implementation plan.

Completed the initial frontend prototype, providing a solid foundation for backend API integration in the following development stages.
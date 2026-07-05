MedFlow
Intelligent Digital Patient Triage & Queue Management System
Overview

MedFlow is a digital healthcare platform that improves patient flow in hospitals by replacing traditional first-come-first-served queue systems with intelligent patient prioritization based on clinical urgency.

Patients complete a structured symptom assessment before or during their hospital visit.

Healthcare workers receive a prioritized queue based on Emergency, Urgent and Routine classifications.

Case Study

University of Benin Teaching Hospital

Benin City

Edo State

Nigeria

Features

Digital Patient Registration

Appointment Booking

Symptom Assessment

Clinical Decision Support

Emergency Detection

Queue Management

Hospital Dashboard

Analytics

Patient Notifications

QR Code Check-in

Technology Stack

Frontend

React.js

Tailwind CSS

TypeScript

Backend

Node.js

Express.js

Database

PostgreSQL

Authentication

JWT

Deployment

Docker

NGINX

AWS

System Architecture

                        +---------------------------+
                        |        Web Browser        |
                        |---------------------------|
                        | Patient Portal            |
                        | Hospital Portal           |
                        +------------+--------------+
                                     |
                                     |
                           HTTPS / REST API
                                     |
                                     ▼
                  +------------------------------------+
                  |         Backend Application        |
                  |------------------------------------|
                  | Authentication (JWT)               |
                  | Patient Management                 |
                  | Appointment Management             |
                  | Queue Management                   |
                  | Triage Decision Engine             |
                  | Notification Service              |
                  | Analytics Engine                  |
                  +----------------+-------------------+
                                   |
                                   |
                          SQL Queries
                                   |
                                   ▼
                +-------------------------------------+
                |          PostgreSQL Database        |
                |-------------------------------------|
                | Users                              |
                | Patients                           |
                | Appointments                       |
                | Symptoms                           |
                | Triage Questions                   |
                | Triage Responses                   |
                | Risk Assessments                   |
                | Queue Records                      |
                | Medical Profiles                   |
                | Notifications                      |
                | Audit Logs                         |
                +-------------------------------------+

Screenshots

Landing Page

Dashboard

Appointments

Queue

Analytics

Installation

Clone Repository

Install Dependencies

Run Backend

Run Frontend

Open Browser

Folder Structure

MedFlow/
│
├── .github/                         # GitHub workflows and templates
│   ├── workflows/
│   │   ├── ci.yml
│   │   ├── lint.yml
│   │   └── deploy.yml
│   ├── ISSUE_TEMPLATE/
│   └── PULL_REQUEST_TEMPLATE.md
│
├── docs/                            # Project documentation
│   ├── ProjectProposal.md
│   ├── PRD.md
│   ├── SRS.md
│   ├── Architecture.md
│   ├── DatabaseDesign.md
│   ├── API.md
│   ├── UserFlows.md
│   ├── DesignSystem.md
│   ├── DeploymentGuide.md
│   ├── Testing.md
│   └── UserManual.md
│
├── frontend/                        # React Frontend
│   ├── public/
│   │
│   ├── src/
│   │   ├── assets/
│   │   │   ├── images/
│   │   │   ├── icons/
│   │   │   └── logos/
│   │   │
│   │   ├── components/
│   │   │   ├── common/
│   │   │   ├── dashboard/
│   │   │   ├── appointments/
│   │   │   ├── queue/
│   │   │   ├── triage/
│   │   │   └── notifications/
│   │   │
│   │   ├── pages/
│   │   │   ├── Landing/
│   │   │   ├── Login/
│   │   │   ├── Register/
│   │   │   ├── Dashboard/
│   │   │   ├── Assessment/
│   │   │   ├── Appointments/
│   │   │   ├── Queue/
│   │   │   ├── Profile/
│   │   │   ├── MedicalHistory/
│   │   │   ├── Analytics/
│   │   │   └── Settings/
│   │   │
│   │   ├── layouts/
│   │   ├── hooks/
│   │   ├── services/
│   │   ├── context/
│   │   ├── routes/
│   │   ├── utils/
│   │   ├── styles/
│   │   ├── constants/
│   │   ├── types/
│   │   ├── App.tsx
│   │   └── main.tsx
│   │
│   ├── package.json
│   └── vite.config.ts
│
├── backend/                         # Node.js Backend
│   ├── src/
│   │   ├── config/
│   │   ├── controllers/
│   │   ├── middleware/
│   │   ├── routes/
│   │   ├── services/
│   │   ├── repositories/
│   │   ├── models/
│   │   ├── validators/
│   │   ├── database/
│   │   ├── utils/
│   │   ├── triage/
│   │   ├── analytics/
│   │   ├── notifications/
│   │   └── app.js
│   │
│   ├── tests/
│   ├── package.json
│   └── server.js
│
├── database/
│   ├── schema.sql
│   ├── seed.sql
│   ├── migrations/
│   ├── ERD.png
│   └── README.md
│
├── design/
│   ├── figma/
│   ├── wireframes/
│   ├── mockups/
│   ├── prototypes/
│   └── assets/
│
├── presentation/
│   ├── MedFlow_Presentation.pptx
│   ├── DemoScript.md
│   └── PitchDeck.pdf
│
├── screenshots/
│   ├── landing-page.png
│   ├── patient-dashboard.png
│   ├── triage.png
│   ├── appointments.png
│   ├── hospital-dashboard.png
│   └── analytics.png
│
├── .env.example
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
├── README.md
└── docker-compose.yml

API Documentation

Link

Database Schema

Link

Authors

Your Team

License

MIT

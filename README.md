# Manaksetu
# ManakSetu

### Digital Verification and Certification Platform for Weighing and Measuring Instruments

**Smart India Hackathon 2026**  
**Problem Statement: SIH26036**

---

## Project Overview

ManakSetu is a digital platform designed to connect the verification lifecycle of weighing and measuring instruments.

It connects manufacturers, businesses and traders, Legal Metrology Officers, GATCs, administrators and citizens through a unified digital workflow.

The platform aims to support:

- Instrument registration and lifecycle tracking
- Manufacturer pre-registration
- Shopkeeper instrument claiming or assignment
- Verification and reverification applications
- Inspection scheduling and assignment
- Digital inspection records
- Digital verification certificates
- QR-based public verification
- Validity and expiry tracking
- Complaint submission and authority review
- GPS-assisted complaint submission when QR access is unavailable
- Role-based dashboards

---

## Problem Statement

**SIH26036 — Development of an Online Verification System for Weighing and Measuring Instruments**

The proposed system aims to support stakeholder registration, online verification and reverification applications, inspection scheduling, digital inspection results, QR-enabled certificates, validity tracking, alerts, dashboards, document management and public verification.

---

## Proposed Solution

ManakSetu connects the complete verification journey:

**Manufacturer Registration**  
→ **Instrument Claim**  
→ **Verification Application**  
→ **Inspection**  
→ **Digital Certificate**  
→ **QR Verification**  
→ **Complaint and Authority Review**

---

## Main Stakeholders

- Manufacturer
- Business / Trader
- Legal Metrology Officer
- Government Approved Testing Centre
- Central Administrator
- Customer / Citizen

---

## Key Features

### Instrument Lifecycle

An instrument can be pre-registered by the manufacturer and later claimed or assigned to a business.

### Verification Workflow

Businesses can submit verification or reverification applications, while authorized officers can manage inspection and record results.

### Digital Certificate

The platform generates a digital verification certificate with a QR code linked to the verification record.

### Public Verification

Citizens can scan the QR code to view the current public verification status of an instrument.

### GPS-Assisted Complaint

If QR access is unavailable, a citizen can use their current location to help identify the nearby shop and auto-fill available shop address details before submitting a complaint.

GPS is treated as supporting location information, not as proof of a violation.

---

## Project Links

- **Live Prototype:**  [Open ManakSetu Prototype](https://manaksetu-b388xi6l8-aryan2006choudhary-9873.vercel.app)
- **Project Demonstration Video:** [Watch ManakSetu Demo](https://youtu.be/3JTCsRi566I?si=NYlVc6gWP0ATm15S)
- **Project Report:** [View Project Report](docs/ManakSetu_SIH_Project_Report.pdf)
- **Presentation PDF:** [View SIH Presentation](docs/MANAKSETU_pdf.pdf)
- **technical document PDF:**[View technical documentation](ManakSetu_Updated_Technical_Documentation.pdf)


## Technology Stack

- **Frontend:** React.js
- **Styling:** Tailwind CSS
- **Backend:** Node.js / Express.js
- **Database:** PostgreSQL / Supabase
- **Authentication:** Role-based authentication
- **QR:** QR-enabled certificate verification
- **Deployment:** Cloud deployment


## Current Implementation Status

The current prototype demonstrates the main stakeholder interfaces and selected verification and public verification workflows.

Backend validation, role-based access control, database constraints, certificate integrity, complaint handling and other production-hardening features are being developed and tested.


## Future Scope

- Integration with existing state Legal Metrology systems
- State-wise jurisdiction management
- Bulk migration of active instrument records
- Mobile field support for officers
- Advanced reporting and analytics
- Notification and reminder automation
- Wider deployment across districts and states

---

## Repository Structure

```text
ManakSetu/
├── README.md
└── docs/
    ├── ManakSetu_SIH_Project_Report.pdf
    └── README.md

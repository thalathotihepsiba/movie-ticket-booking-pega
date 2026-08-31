# 🎬 Movie Ticket Booking Management Application

> A workflow-based Movie Ticket Booking Management Application developed using **Pega Platform** to streamline booking requests, show availability, booking confirmation, processing, and customer communication.

---

## 📌 Project Overview

The **Movie Ticket Booking Management Application** is a Pega-based case management solution designed for **CineWave Entertainment**.

The application provides a centralized workflow for managing movie ticket booking requests and improving visibility across the booking lifecycle. It demonstrates how **Pega App Studio, Pega Blueprint, Case Management, Data Modeling, and Workflow Automation** can be used to design a real-world business application.

---

## 🎯 Project Objectives

* Allow customers to submit movie ticket booking requests
* Manage movie and show information
* Check show availability
* Calculate booking costs
* Capture customer confirmation
* Review and process booking requests
* Track booking status
* Notify customers about booking confirmation
* Define service-level requirements
* Route booking requests based on show type

---

## 🔄 Booking Workflow

```text
┌──────────────────────────┐
│ Submit Movie Ticket      │
│ Request                  │
└────────────┬─────────────┘
             ↓
┌──────────────────────────┐
│ Check Show Availability  │
└────────────┬─────────────┘
             ↓
┌──────────────────────────┐
│ Calculate Booking Cost   │
└────────────┬─────────────┘
             ↓
┌──────────────────────────┐
│ Confirm Booking Request  │
└────────────┬─────────────┘
             ↓
┌──────────────────────────┐
│ Review Booking Details   │
└────────────┬─────────────┘
             ↓
┌──────────────────────────┐
│ Process Ticket Booking   │
└────────────┬─────────────┘
             ↓
┌──────────────────────────┐
│ Booking Confirmation     │
└────────────┬─────────────┘
             ↓
┌──────────────────────────┐
│ Customer Notification    │
└──────────────────────────┘
```

---

## 🚀 Implemented User Stories

### US-001 — Submit Movie Ticket Request

Provides a structured process for submitting a new movie ticket booking request.

### US-002 — Check Show Availability

Supports checking the availability of movie shows before proceeding with a booking.

### US-003 — Calculate Booking Cost

Provides the booking cost calculation as part of the booking workflow.

### US-004 — Confirm Booking Request

Captures customer confirmation before the booking proceeds.

### US-005 — Maintain Movie and Show Data

Supports maintaining movie and show-related information used by the application.

### US-006 — Review Booking Details

Allows booking information to be reviewed before processing.

### US-007 — Process Ticket Booking

Processes the booking request through the configured case lifecycle.

### US-008 — Notify Booking Confirmation

Provides customer notification after successful booking confirmation.

### US-009 — Define Booking SLA

Defines service-level requirements for timely processing of booking requests.

### US-010 — Route Booking Request by Show Type

Supports routing booking requests according to the configured show type.

---

## 🏗️ Application Architecture

The application was designed using the Pega application architecture consisting of:

* **Personas & Channels**
* **Case Workflows**
* **Data Objects**
* **Business Rules**
* **Workflow Automation**

### Blueprint Configuration

| Component    | Configuration         |
| ------------ | --------------------- |
| Application  | Movie Ticket Booking  |
| Industry     | Entertainment         |
| Location     | India                 |
| Platform     | Pega Infinity '25.1.3 |
| Personas     | 3                     |
| Workflows    | 1                     |
| Data Objects | 6                     |

---

## 🛠️ Technology Stack

| Technology              | Purpose                                   |
| ----------------------- | ----------------------------------------- |
| **Pega Platform**       | Application development                   |
| **Pega App Studio**     | Case and workflow configuration           |
| **Pega Blueprint**      | Application design and blueprinting       |
| **Case Management**     | Booking lifecycle management              |
| **Data Modeling**       | Structured application data               |
| **Workflow Automation** | Business process automation               |
| **GitHub**              | Project documentation and version control |

---

## 🧩 Core Functional Areas

### 🎥 Movie & Show Management

Management of movie and show information required for booking requests.

### 🎟️ Booking Management

Structured workflow for submitting, reviewing, confirming, and processing ticket bookings.

### 💺 Availability Management

Supports show availability checking as part of the booking process.

### 💰 Cost Calculation

Calculates the booking cost before confirmation.

### ✅ Booking Confirmation

Captures confirmation before completing the booking process.

### 📧 Customer Notification

Provides notification after booking confirmation.

### ⏱️ SLA Management

Supports service-level requirements to ensure booking requests are processed within defined timeframes.

### 🔀 Request Routing

Routes booking requests according to configured show-type requirements.

---

## 📊 Case Management

The application uses **Pega Case Management** to represent and manage movie ticket booking requests.

Each booking request can be tracked through its configured lifecycle, providing improved visibility into the current status and next action required.

---

## 📸 Screenshots

Project screenshots can be added here to demonstrate:

* Application Home Page
* Create Booking Request
* Movie/Show Selection
* Booking Details
* Booking Processing
* Confirmation
* Case Status

---

## 🎥 Demo

**Demo Video:**
[View Movie Ticket Booking Demo](Demo%20video.mp4)

---

## 🔗 Project Links

**GitHub Repository:**
https://github.com/thalathotihepsiba/movie-ticket-booking-pega

**Demo Video:**
Available in this repository as `Demo video.mp4`.

---

## 📚 Learning Outcomes

This project provided practical experience in:

* Pega App Studio
* Pega Blueprint
* Case Lifecycle Design
* Case Management
* Data Modeling
* Workflow Automation
* Business Process Design
* SLA Configuration
* Request Routing
* User Interaction Design
* Low-Code Application Development
* Software Engineering Documentation
* GitHub Version Control

---

## 👩‍💻 Author

### Thalathoti Hepsiba

**B.Tech — Computer Science and Engineering**

**Areas of Interest:**
Software Engineering • Application Development • AI • Full-Stack Development

---

## 📌 Project Status

**Status: Completed**

Developed as an internship/Skill Wallet project using **Pega Platform** to demonstrate practical application development, workflow automation, case management, and software engineering principles.

---

⭐ **Thank you for reviewing this project!**

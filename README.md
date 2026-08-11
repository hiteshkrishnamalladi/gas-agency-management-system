# Gas Agency Management System

## 📌 Project Overview

The **Gas Agency Management System (GasMS)** is an online application designed to automate and simplify the gas cylinder booking process for customers and gas agency managers.

The system is designed to reduce manual work involved in customer registration, cylinder booking, connection transfer, complaint handling, payment, delivery tracking, and customer feedback.

---

## 🎯 Objectives

* Automate the gas cylinder booking process.
* Reduce manual work involved in handling customer requests.
* Provide online consumer registration.
* Enable customers to book gas cylinders online.
* Allow customers to track booking and delivery status.
* Support connection transfer requests.
* Provide complaint handling functionality.
* Enable payment during booking or delivery.
* Collect customer feedback after delivery.
* Provide managers with the ability to approve or reject requests.

---

## 🏗️ Application Details

**Application Name:** Gas Agency Management System (GasMS)

**Team Name:** Pega Challengers

### Team Members

1. Akhil Abhiram P
2. **Hitesh Krishna M**
3. Venkata Rupa Vardhan B
4. Nakul Sri Sai G

**Scrum Master:** Akhil Abhiram P
**Product Owner:** Mr. SatyaVeer Soma

---

## 🛠️ Technology

* **Pega Platform**
* Pega Case Management
* Pega Data Types
* Pega Work Queues
* Pega Access Groups
* Pega Portals

---

## 🔄 Core Workflows

### 1. Consumer Registration

Customers can register through the online portal by providing required details such as:

* Consumer Number
* 17-digit LPG ID
* Aadhaar Number
* Mobile Number
* Contact Address

### 2. Gas Booking

Registered consumers can:

1. Log in to the portal.
2. Enter the required booking details.
3. Submit a cylinder booking request.
4. Make payment online or during delivery.
5. Track the booking/delivery status.
6. Provide feedback after delivery.

### 3. Connection Transfer

The system supports connection transfer requests through a dedicated case type and workflow.

---

## 📋 Case Types

* **Gas Booking**
* **Connection Transfer**
* **Booking Complaints**

---

## 👥 Actors

### Consumer

Consumers can register, book cylinders, make payments, track deliveries, provide feedback, submit complaints, and request connection transfers.

### Agency Manager

Agency Managers can approve or reject consumer registration and cylinder booking requests and review consumer feedback.

---

## 🖥️ Portals

### User Portal

Used by consumers to access registration, booking, connection transfer, complaints, payment, and tracking functionality.

### Manager Portal

Used by agency managers to review and process customer requests.

---

## 🔐 Access Groups

* **GasMS: Users**
* **GasMS: Authors**
* **GasMS: Managers**

---

## 🗂️ Data Types

1. Connection Transfer
2. Consumer
3. Distributor
4. Feedback
5. Payment Details
6. Complaints

---

## 📦 Work Queue

Work queues are used for workload management and task routing within the application, helping categorize and route assignments to appropriate users.

---

## 💰 Dynamic Pricing

The application includes dynamic pricing logic for domestic cylinders:

* **$75** within the annual subsidy limit of 12 cylinders.
* **$150** after exceeding the annual subsidy limit.

---

## 🔁 High-Level Application Flow

```text
Consumer
   │
   ▼
Registration
   │
   ▼
Manager Approval
   │
   ▼
Consumer Login
   │
   ▼
Gas Booking
   │
   ▼
Distributor / Agency
   │
   ▼
Payment & Delivery
   │
   ▼
Delivery Tracking
   │
   ▼
Consumer Feedback
   │
   ▼
Manager Review
```

---

## 📊 Application Components

The project documentation includes:

* Application structure
* Case life cycles
* Flow diagrams
* Data Flow Diagram (DFD)
* Data types
* Actors
* Portals
* Access groups
* Work queues
* Login page
* Registration page

---

## 📸 Screenshots

Recommended screenshots to add:

* Login Page
* Consumer Registration Page
* Gas Booking Page
* Manager Portal
* Case Processing
* Booking Status
* Connection Transfer
* Complaint Management

---

## 👨‍💻 My Contribution

**Team Member:** Hitesh Krishna M

This project was developed as a team project under **Pega Challengers**.

### My Role

> Add the specific activities you personally worked on here.

Examples:

* Worked on Pega case type development.
* Worked on application workflows.
* Configured data types.
* Worked on UI screens.
* Configured business rules.
* Worked on testing and debugging.
* Contributed to application documentation.

**Note:** Keep only the responsibilities that accurately represent your actual contribution.

---

## 📚 Project Documentation

The complete High-Level Design (HLD) document is included in this repository.

```text
HLD/
└── HLD_GAM_Pega_Challengers.pdf
```

---

## 🚀 Future Enhancements

Potential enhancements can include improvements to automation, reporting, tracking, and overall user experience.


##  Project Team

**Team:** Pega Challengers

**Members:**

1. Akhil Abhiram P
2. **Hitesh Krishna M**
3. Venkata Rupa Vardhan B
4. Nakul Sri Sai G

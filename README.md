# Key Activities in Requirement Analysis 


# Requirement Analysis in Software Development

## Introduction
This repository provides an overview of **Requirement Analysis** in the Software Development Lifecycle (SDLC).  
It explains key activities, types of requirements, use case diagrams, and acceptance criteria — all crucial steps to ensure that software projects are clearly defined and meet stakeholder expectations.

## What is Requirement Analysis?

**Requirement Analysis** is a critical phase in the **Software Development Lifecycle (SDLC)** where the project team gathers, analyzes, and defines what a software system should do and how it should perform.

It helps ensure that all stakeholders — developers, clients, and end-users — have a shared understanding of the system requirements before design and development begin.
## Why is Requirement Analysis Important?

Requirement Analysis is essential because it:

1. **Provides Clarity and Understanding**  
   It ensures that all stakeholders have a clear and mutual understanding of project goals and expected functionalities.

2. **Defines the Project Scope**  
   Helps prevent scope creep by setting clear boundaries on what the system will and will not do.

3. **Lays the Foundation for Design and Development**  
   Serves as a roadmap for developers and designers, ensuring that the system is built according to user needs.

4. **Improves Cost and Time Estimation**  
   Helps in accurately estimating project effort, cost, and duration.

5. **Enhances Product Quality**  
   Leads to the development of a reliable product that meets user expectations.

## Types of Requirements

### Functional Requirements ⚙️
Functional requirements describe **what the system should do**.

**Examples (for a Booking Management System):**
- Users can **search for available properties** by location, price, or date.
- Users can **register and log in** securely.
- Admins can **manage property listings** (add, update, or delete).
- The system allows users to **book properties** and **receive confirmation emails**.

### Non-Functional Requirements 🛡️
Non-functional requirements describe **how the system should perform**.

**Examples:**
- **Performance:** Pages should load within 2 seconds.
- **Security:** User data must be encrypted and protected from unauthorized access.
- **Usability:** The system must be easy to navigate and user-friendly.
- **Scalability:** The platform should handle increased traffic without performance degradation.
- **Reliability:** The system should have 99.9% uptime.


## Use Case Diagrams

**Definition:**  
Use Case Diagrams visually represent how users (actors) interact with the system to achieve specific goals.

**Actors:**
- Guest
- Registered User
- Admin

**Use Cases:**
- Search Property
- Register/Login
- Book Property
- Manage Listings

**Benefits of Use Case Diagrams:**
- Provides a clear overview of system functionalities.
- Helps identify and organize system requirements.
- Facilitates better communication between stakeholders and developers.

### Booking Management System - Use Case Diagram

![Use Case Diagram](alx-booking-uc.png)




## Acceptance Criteria 

**Definition:**  
Acceptance Criteria are specific conditions that a software feature must meet to be accepted by stakeholders.

**Importance:**
- Ensures that all parties agree on what “done” means.
- Provides a measurable basis for testing.
- Improves software quality and user satisfaction.

**Example (Checkout Feature - Booking System):**
- Users can proceed to checkout only after selecting a property and available dates.
- The system should calculate the total amount including taxes and display it before confirmation.
- Users must receive a confirmation email within 2 minutes after successful payment.



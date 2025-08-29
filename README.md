# requirement-analysis
This repository documents the Requirement Analysis phase for a **Booking Management System**.  
It covers concepts, activities, types of requirements, use case diagrams, and acceptance criteria, providing a structured foundation for software development.

---

## What is Requirement Analysis?

Requirement Analysis is the process of identifying, documenting, and analyzing the needs and expectations of stakeholders for a software system.  
It ensures that developers understand *what* to build before deciding *how* to build it.  
This step is crucial in the Software Development Lifecycle (SDLC) because it provides a blueprint for the entire project.

---

## Why is Requirement Analysis Important?

1. **Clarity and Understanding**  
   Ensures that developers, clients, and users are aligned on what the system should do.

2. **Reduced Development Risks**  
   Prevents costly mistakes by catching misunderstandings early.

3. **Foundation for Design & Testing**  
   Provides clear requirements that guide system design, development, and test planning.

---

## Key Activities in Requirement Analysis

- **Requirement Gathering** – Collecting needs from stakeholders through interviews, surveys, and observation.  
- **Requirement Elicitation** – Refining gathered needs into precise, actionable requirements.  
- **Requirement Documentation** – Writing requirements in a structured, clear format for reference.  
- **Requirement Analysis & Modeling** – Evaluating, prioritizing, and creating models/diagrams to represent requirements.  
- **Requirement Validation** – Confirming requirements meet business goals and are technically feasible.  

---

## Types of Requirements

### Functional Requirements
Functional requirements define **what the system should do** (features & functionality).  

**Examples for Booking Management System:**
- Users can search for available rooms by date.  
- Users can book a room and receive a booking confirmation.  
- Users can cancel an existing booking.  
- Admins can add, edit, or remove rooms.  

### Non-functional Requirements
Non-functional requirements define **system quality attributes** (performance, usability, security, etc.).  

**Examples:**
- The system should support up to 500 concurrent users.  
- The booking confirmation email should be delivered within 1 minute of booking.  
- The platform should be accessible via mobile and desktop devices.  
- User data must be stored securely following encryption standards.  

---

## Use Case Diagrams

Use Case Diagrams visually represent system interactions between users (actors) and functionalities (use cases).  
They help in understanding user needs, system scope, and boundaries.  

**Actors in the Booking System:**
- **User (Customer)** – Searches rooms, books, pays, cancels bookings.  
- **Admin** – Manages rooms and booking records.  

![Booking System Use Case](alx-booking-uc png
)

---

## Acceptance Criteria

Acceptance Criteria define the **conditions that must be met for a requirement to be accepted as complete**.  
They ensure clarity and prevent misunderstandings between stakeholders and developers.  

**Example – Checkout Feature:**
- The user can view a summary of their booking before making payment.  
- The system must support multiple payment methods (credit card, PayPal, mobile money).  
- A confirmation message and email must be sent immediately after successful payment.  
- If payment fails, the user should be able to retry or cancel the transaction.  

---

## 📌 Conclusion
This repository demonstrates the importance of Requirement Analysis in ensuring successful software projects.  
By clearly defining requirements, modeling system interactions, and setting acceptance criteria, we lay a strong foundation for the **Booking Management System** and future scalable solutions.

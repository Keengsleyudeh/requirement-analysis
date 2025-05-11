---

## 🎯 Use Case Diagrams

### What Are Use Case Diagrams?

**Use Case Diagrams** are a type of behavioral diagram defined by UML (Unified Modeling Language) that visually represent the functional requirements of a system. They illustrate how users (actors) interact with the system to achieve specific goals (use cases). These diagrams provide a high-level overview of system functionalities and user interactions.

### Benefits of Use Case Diagrams

- **Clarity:** They help stakeholders understand system functionality from a user perspective.
- **Communication:** They serve as an effective communication tool between technical and non-technical team members.
- **Scope Management:** They help define system boundaries and identify all possible interactions.
- **Requirement Validation:** They assist in validating that all user expectations are captured in the system.

### 📌 Use Case Diagram for the Booking Management System

Below is the use case diagram for the ALX Booking Management System. It highlights the major actors and the key actions they can perform in the system.

![Use Case Diagram](./alx-booking-uc.png)

### Actors:
- **User (Guest):** Interacts with the system to search, book, and manage reservations.
- **Admin:** Manages room availability, user data, and oversees system functions.
- **Payment Gateway:** Handles transaction processing and confirmations.

### Key Use Cases:
- Search Available Rooms  
- Make Booking  
- Modify/Cancel Booking  
- View Booking History  
- Process Payment  
- Manage Room Inventory (Admin)  
- View Reports and Analytics (Admin)

## ✅ Acceptance Criteria

### Importance of Acceptance Criteria in Requirement Analysis

Acceptance Criteria are conditions that a software product must satisfy to be accepted by a user, customer, or other stakeholders. They define the boundaries of a user story or feature and ensure that everyone involved in the project has a shared understanding of the expected outcome.

**Why Acceptance Criteria Matter:**
- 🧭 **Clarity:** They provide clear and measurable expectations for what a feature should do.
- 🧪 **Testability:** They serve as the basis for test cases and QA validation.
- 🔄 **Alignment:** They help developers, testers, and stakeholders stay aligned on the scope and functionality.
- 📦 **Deliverability:** They ensure that features meet user needs before being marked as complete.

### Example: Acceptance Criteria for Checkout Feature

**Feature:** Checkout for Booking Management System

**Acceptance Criteria:**
- ✅ The user must be able to view a summary of their booking, including dates, room type, and total cost.
- ✅ The system must support secure payment through the integrated Payment Gateway.
- ✅ The booking is only confirmed after successful payment authorization.
- ✅ A booking confirmation email must be sent to the user immediately after successful checkout.
- ✅ If the payment fails, the user must be notified with an appropriate error message and allowed to retry.
- ✅ The system must update room availability after a successful checkout to prevent overbooking.

These criteria help ensure the Checkout feature delivers value, works as expected, and aligns with the business goals.


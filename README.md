# Event Management System

## 📌 Project Overview

A comprehensive **Java-based Event Management System** that provides a multi-role platform for **Customers, Organizers, and Administrators** to manage events, bookings, and system operations efficiently. This project showcases enterprise-level Java application development with robust features, real-time analytics, and scalable architecture for commercial event management needs.

---

## 🔑 Key Features

### 🔐 Authentication & Security

* Multi-role login system (Customer, Organizer, Admin)
* OTP verification for Organizer & Admin (via mobile/email)
* Strong password validation using regex patterns
* Secure session management

### 👥 User Roles & Capabilities

**Customer**

* Browse/search events with filters (category, price, date)
* Book events with real-time ticket availability
* Manage bookings & cancellations with automatic ticket reallocation
* Edit personal profile and view booking history

**Organizer**

* Create, edit, and delete events
* Manage events with detailed forms (venue, pricing, capacity)
* Access real-time analytics dashboard (revenue, attendance)
* Manage profile with company details
* Control event status (Pending, Approved, Rejected)

**Administrator**

* Central dashboard with system statistics
* Manage users (activate/deactivate, edit profiles)
* Approve or reject events
* Configure system settings
* Access revenue & growth analytics
* Export data and reports (CSV)

---

## ⚙️ Technical Implementation

### Frontend (Java Swing)

* JTabbedPane navigation
* JTable with custom renderers/editors
* Responsive layouts (GridBagLayout, BorderLayout, FlowLayout)
* Custom button components and dialogs

### Backend (MySQL + JDBC)

* CRUD operations with SQL queries
* Transaction management for bookings
* Data validation & error handling
* Connection pooling for efficiency

### Database Schema

* **Members** (Customer profiles)
* **Organizers** (Event organizers)
* **Events** (Event details & status)
* **Bookings** (Customer reservations)
* **Payments** (Transactions)
* **SystemSettings** (Configurations)

---

## 🖥️ User Interface Highlights

* Tabbed navigation for role-specific modules
* Real-time data refresh (every 30 seconds)
* Color-coded event and booking status
* Search & filter capabilities
* Custom confirmation dialogs

---

## 📊 Key Functionalities

* Event creation with date/time pickers
* Ticket capacity & revenue management
* Real-time booking with automated payment records
* Cancellation with refund processing
* Analytics (monthly revenue, user growth, attendance)
* CSV export functionality

---

## 🏗️ System Architecture

```
Login → Role-based Dashboard
├── Customer: Browse Events → Book → Manage Bookings
├── Organizer: Create Events → Analytics → Profile
└── Admin: User Mgmt → Event Mgmt → System Settings → Analytics
```

---

## 💼 Business Value

* Streamlines event planning & booking
* Provides real-time insights for decision-making
* Enables collaboration across multiple roles
* Scalable for growing event management needs
* Comprehensive reporting for performance tracking

---

## 📐 ER Diagram

*(Add your ER diagram image here if available)*

---

## 🚀 Tech Highlights

* Object-oriented modular design
* Custom Swing components (tables, buttons, dialogs)
* Exception handling with user-friendly messages
* Maintainable and scalable code structure
* Database connection pooling for optimized performance


<img width="773" height="517" alt="image" src="https://github.com/user-attachments/assets/65653ab9-e45c-4df7-9d4d-5ec64ab5b041" />


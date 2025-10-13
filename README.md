🎟️ Event Management System & Booking Platform
📋 Overview

A comprehensive Java Swing-based Event Management System with role-based access control, real-time analytics, and multi-user functionality.
This enterprise-grade application enables organizers, customers, and administrators to efficiently manage events, bookings, communication, and analytics — all from one unified platform.

🎯 Key Features
🔐 Multi-Role Authentication

Customers: Browse events, make bookings, manage profiles

Organizers: Create/manage events, track performance, view analytics

Admins: Oversee system operations, manage users, view financial analytics

Secure OTP verification for organizer and admin logins

📊 Advanced Analytics & Reporting

Real-time financial dashboards with revenue tracking

Profit/Loss calculations with built-in formulas

Break-even analysis for event profitability

Performance metrics and occupancy rate analysis

Comprehensive PDF reports for events, users, and organizers

💳 Event & Booking Management

Event creation with detailed configurations (capacity, pricing, categories)

Smart booking system with real-time seat availability

Automated email confirmations with PDF invoices

Booking cancellation with automatic seat reallocation

Payment tracking and transaction monitoring

🗣️ Integrated Communication System

Real-time chat between customers, organizers, and admins

Multi-room chat architecture for conversation separation

Persistent messaging with read status tracking

🛠️ Technical Architecture
🖥️ Frontend

Java Swing GUI with modern, responsive design

Custom UI components and tabbed interface navigation

Real-time data visualization in tables and charts

🗄️ Backend & Database

MySQL database with optimized relational schema

JDBC with connection pooling and transaction management

Stored procedures and SQL views for complex queries

🔒 Security & Configuration

Role-based access control (RBAC)

Encrypted password handling

OTP verification (Twilio SMS & Email)

External configuration via ConfigEditor and ConfigManager

📁 Core Modules
Module	Description
Authentication & Registration (App.java, Register.java)	Multi-role login, user registration, OTP verification
Customer Dashboard (Customer.java)	Event browsing, booking management, profile editing, chat integration
Organizer Dashboard (Organizer.java)	Event creation, analytics, revenue tracking, break-even calculations
Admin Dashboard (Admin.java)	User management, event approvals, system reporting, financial analytics
Configuration System (ConfigEditor.java, ConfigManager.java)	Database setup, integration management, system settings
Reporting Engine (PDF_Generator.java, RevenuePDFGenerator.java)	Multi-format PDF generation, financial reports, custom exports
🗃️ Database Schema

Main Tables:

Users – Customer, Organizer, and Admin details

Events – Event info, pricing, and capacity

Bookings – Reservations and ticket counts

Payments – Transaction records and statuses

Chat – Message history and conversation rooms

System – Configuration and sequence tracking

🚀 Installation & Setup
Prerequisites

Java JDK 8+

MySQL Server 5.7+

Maven for dependency management

Configuration Steps

Run ConfigEditor to set up database credentials

Configure Twilio for SMS OTP

Set up Email credentials for notifications

Initialize the database using the built-in schema setup

Dependencies

MySQL Connector/J

iTextPDF (for PDF reporting)

Twilio Java SDK

JavaMail API

💡 Technical Highlights
🎨 Advanced UI/UX

Modern, professional design with responsive layout

Color-coded indicators for status and alerts

Real-time data refresh and analytics visualization

📈 Business Intelligence

Automated profit/loss and occupancy rate calculations

Trend and revenue analysis

Performance benchmarking and event ranking

🔄 Real-Time Features

Instant chat and booking updates

Dynamic analytics refresh

Real-time system notifications

📋 Comprehensive Reporting

Executive and financial summaries

Deep-dive analytics with PDF export

Organizer and event ranking reports

🎭 Use Cases
For Organizers

Create and manage multiple events

Track sales, performance, and revenue

Communicate directly with customers

For Customers

Discover and book events

Manage bookings and receive updates

Access customer support through chat

For Administrators

Manage all users and events

Analyze financial and operational metrics

Generate reports and oversee configurations

🔮 Future Enhancements

📱 Mobile application (Android/iOS)

💰 Advanced payment gateway integration

🌐 Social media and marketing integration

🤖 AI-powered event recommendations

🌏 Multi-language & cloud deployment support

<img width="964" height="956" alt="Event Management System ER Diagram" src="https://github.com/user-attachments/assets/1ecfcd97-2c8a-4969-a8a6-6fcd2615b623" />

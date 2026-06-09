# 🎵 Concert Ticket Management and Sales System

## 📖 Description

This project is a web application developed with Laravel that allows the management and sale of concert tickets. The system enables seat selection, buyer registration, PDF ticket generation, and automatic ticket delivery via email.

---

## 🎯 Objective

To automate the ticket sales and management process for musical events, providing efficient control of available and sold seats.

---

## ⚙️ Features

### 🎫 Ticket Reservation

Users can:

- View available seats.
- Select one or multiple seats.
- Enter their personal information.
- Confirm the purchase.

Once the purchase is completed, the selected seats are marked as sold.

---

### 👤 Buyer Registration

The system stores buyer information, including:

- Full Name
- Email Address
- Phone Number
- Address

This information is linked to the purchased tickets.

---

### 📄 Ticket Generation

After a successful purchase:

- A PDF ticket is automatically generated.
- The ticket can be downloaded by the buyer.
- The ticket contains all reservation details.

---

### 📧 Ticket Delivery by Email

The system automatically sends an email to the buyer containing:

- Purchase confirmation.
- PDF ticket attached.

---

### 🛒 Bulk Ticket Sales

The application allows multiple seats to be sold in a single transaction, making group purchases faster and more efficient.

---

### 🔐 User Authentication

The system includes an administrator login module with secure authentication.

---

### 📊 Administrative Dashboard

Administrators can:

- View completed sales.
- Manage system users.
- Review registered buyers.
- Monitor seat availability and sales.
- Manage collections and payments.

---

## 🏗️ Project Architecture

The application follows the **MVC (Model-View-Controller)** architectural pattern.

### Models

Responsible for managing and interacting with database records.

Main entities:

- Buyer
- Seat
- SeatSold
- Collection
- UserGmo

### Views

Provide the graphical interface for customers and administrators.

### Controllers

Handle business logic and communication between models and views.

---

## 🔄 System Workflow

```text
Customer accesses the system
        ↓
Views available seats
        ↓
Selects desired seats
        ↓
Enters personal information
        ↓
Purchase is registered
        ↓
Seats are marked as sold
        ↓
PDF ticket is generated
        ↓
Ticket is sent via email
```

## 🛠️ Technologies Used

- PHP
- Laravel
- MySQL
- HTML5
- CSS3
- JavaScript
- DomPDF
- SMTP Email Service

---

## 📂 System Modules

### Customer Module

- Ticket reservation.
- Seat availability consultation.
- Ticket download.

### Sales Module

- Individual ticket sales.
- Bulk ticket sales.
- Buyer registration.

### Administration Module

- User management.
- Sales management.
- Collection management.
- General system supervision.

---

## ✅ Benefits

- Automated ticket sales process.
- Reduced manual errors.
- Automatic ticket generation.
- Instant email confirmations.
- Centralized information management.

---

## 👨‍💻 Author

Academic project developed for concert ticket sales and management using Laravel.
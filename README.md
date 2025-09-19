# 🚍 Smart Transit Management System (ServiceNow)

<p align="center">
  <img src="https://1000logos.net/wp-content/uploads/2021/05/ServiceNow-logo.png" alt="ServiceNow Logo" width="300"/>
</p>

## 📌 Project Overview
This project is a **ServiceNow-based Smart Transit Management System** designed to handle the core operations of a bus travel service.  
It was developed using **custom tables, workflows, email notifications, and dashboards** in a ServiceNow instance and packaged into an Update Set (`update_set.xml`) for portability.

---

## ✨ Features
- 👤 **Passenger Management** – store passenger details and link them to bookings.
- 🚌 **Bus & Driver Management** – maintain bus and driver records with auto-generated IDs.
- 📑 **Booking System** – manage trip bookings with references to buses and passengers.
- 💳 **Payments** – payment records with auto-generated Payment IDs.
- ⭐ **Feedback** – passengers can provide feedback; email notifications are triggered on new submissions.
- 📊 **Dashboard** – visualize KPIs like payment distribution, feedback summary, and bookings overview.

---

## 🗂️ Tables
The system includes the following major tables:

| Table Name   | Purpose |
|--------------|---------|
| **Passenger** | Store passenger details |
| **Driver** | Manage drivers with auto IDs |
| **Bus** | Store bus information |
| **Bookings** | Track passenger bookings |
| **Payment** | Manage payments (auto-generated Payment ID) |
| **Feedback** | Collect feedback from passengers |
| **GPS Tracking** | Track buses |

---

## ⚙️ Workflows & Business Rules
- **Auto ID Generation** for Bus, Driver, Payment, Feedback, and Bookings.  
- **Business Rule** for Payment ID generation.  
- **Flow Designer Flow** to send **email notifications** when a new Feedback is created.  

---

## 📊 Dashboard
The dashboard provides a single place to monitor:
- 📌 **Feedback Overview** – Pie chart by rating  
- 📌 **Payment Distribution** – Bar chart by payment method  
- 📌 **Recent Bookings** – List of latest booking records  
- 📌 **KPIs** – e.g., Total Payments, Pending Payments  

---

## 🚀 Installation (Importing Update Set)
To use this project in your own ServiceNow instance:

1. Navigate to: **System Update Sets → Retrieved Update Sets**  
2. Click **Import Update Set from XML**  
3. Upload the file: `update_set.xml`  
4. Click **Preview Update Set** → then **Commit Update Set**  

This will install all the tables, forms, business rules, flows, and dashboards.

---

## 📸 Screenshots
(Place your screenshots inside a `screenshots/` folder and reference them here)

Example:

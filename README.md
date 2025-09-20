# 🚍 Smart Transit Management System (ServiceNow)

<p align="center">
  <img src="https://companieslogo.com/img/orig/NOW_BIG-ada03f01.png?t=1647966832" alt="ServiceNow Logo" width="300"/>
</p>

## 📌 Project Overview
The **Smart Transit Management System** is a custom-built solution on the **ServiceNow Platform** to streamline and automate bus service operations.  
It enables:
- Passengers to book and manage tickets, give feedback, and make payments  
- Drivers to access schedules and assignments  
- Administrators to oversee buses, routes, and generate reports  

The project leverages ServiceNow’s **tables, flows, business rules, notifications, dashboards, and catalog items** to deliver a smooth end-to-end transit experience.  
All configurations are packaged into an **Update Set** (`update_set.xml`) for easy import.

---

## 🛠️ Skills & Tools
- **ServiceNow**: Tables, Forms, Lists, Studio, Flow Designer, Business Rules, Catalog Items, Notifications, Reporting, Dashboards, Knowledge Base  
- **Technical**: JavaScript, Glide API, Database Design  
- **Soft Skills**: Problem Solving, Requirement Analysis, Documentation, Team Collaboration  

---

## 📂 Tables Implemented
- **Passenger** – passenger details & registration  
- **Driver** – driver contact & assignment details  
- **Bus** – bus information & status  
- **Bookings** – booking records with seat info  
- **Tickets** – ticket records with status (Booked, Completed, Cancelled)  
- **Payments** – payment records with auto-generated IDs  
- **Feedback** – passenger reviews & ratings  
- **Schedule** – bus schedules with timing & availability  
- **Route** – start point, end point, and stops  
- **GPS Tracking** – real-time bus location  
- **Prices** – fare details between points  

---

## ⚙️ Workflows & Flows
- **Auto-generate IDs** (Bus ID, Booking ID, Payment ID, etc.) using Business Rules  
- **Passenger Registration Flow** – creates passenger, updates record, and sends confirmation email  
- **Feedback Flow** – sends email notification when feedback is created  
- **Booking Flow** – automates booking status updates (Pending, Booked, Cancelled)  
- **Payment Processing Flow** – validates payments, updates ticket status, and sends confirmation email  
- **Ticket & Schedule Flows** – auto-complete expired tickets, deactivate completed ones, validate schedules  
- **Reporting Flow** – generates daily reports and emails to admins  

---

## 📊 Dashboards
The system provides interactive dashboards for:
- **Bus Management** – active vs maintenance buses, buses by route, driver performance  
- **Feedback** – rating distribution, passenger comments  
- **Payments** – transactions overview, payment methods, daily revenue  
- **Routes** – usage statistics and route performance  

---

## 📑 Service Catalog
- **Book a Ticket** – reserve seats on available buses  
- **Cancel a Ticket** – submit ticket cancellation request  
- **Bus Maintenance Request** – request repairs/maintenance  
- **Report Lost Item** – report lost belongings during travel  
- **Request Refund** – financial service request for passengers  

---

## 📖 Knowledge Base
The project also provides categorized KB articles for:
- **Admin & Operations** – driver management, reporting, route setup  
- **Driver Support** – checking assigned routes via mobile app  
- **Passenger Support** – booking, cancelling, and refund instructions  

---

## 🚀 Installation (Importing Update Set)
1. Go to **System Update Sets → Retrieved Update Sets**  
2. Click **Import Update Set from XML**  
3. Upload `update_set.xml`  
4. **Preview** and then **Commit Update Set**  

---



# Welcome to the dev.restaurant Ecosystem 🍔🚀

**dev.restaurant** is a comprehensive, production-ready microservice architecture designed to handle the end-to-end operations of a modern food delivery and restaurant management business. 

Built with scalability, security, and real-time synchronization in mind, this ecosystem seamlessly bridges the gap between customers, kitchen staff, management, and delivery fleets.

---

## 🏛️ System Architecture

The ecosystem is decoupled into four dedicated repositories, working together to create a unified platform:

### 1. The Brain: [Core Spring Boot API](https://github.com/dev-restaurant-system/dev.restaurant-springbackend) ⚙️
The central nervous system of the platform. A stateless, N-Tier REST API built with Java Spring Boot.
* **Security:** Role-Based Access Control (RBAC) and JWT Authentication.
* **Payments:** Direct integration with Razorpay for secure checkout.
* **Verification:** OTP-based login via MessageCentral.
* **Database:** Spring Data JPA over MySQL handling complex order state machines.

### 2. The Control Center: [Admin Web Dashboard](https://github.com/dev-restaurant-system/dev.restaurant-webapp) 📊
A powerful React.js portal for restaurant management and staff.
* **Operations:** Real-time polling for incoming orders with audio alerts.
* **Point of Sale:** Built-in POS system with thermal printer support (57mm/80mm).
* **Analytics:** Recharts-powered dashboards and jsPDF report generation.
* **Content:** Dynamic menu management and promotional slider control.

### 3. The Storefront: [Customer Android App](https://github.com/dev-restaurant-system/dev.restaurant-customerapp) 📱
A native-feel Android application designed for a frictionless ordering experience.
* **UX/UI:** Dynamic home feeds, categorical menu browsing, and cart management.
* **Real-Time:** Live order tracking (Pending → Preparing → Out for Delivery → Delivered).
* **Profile:** Secure address management and order history.

### 4. The Fleet: [Delivery Partner App](https://github.com/dev-restaurant-system/dev.restaurant-deliveryapp) 🛵
A streamlined Android application for delivery personnel on the ground.
* **Logistics:** Real-time push assignments for active orders.
* **Status Control:** One-tap delivery status updates synced instantly with the backend.
* **Availability:** Easy online/offline toggling for shift management.

---

## 🛠️ The Tech Stack

| Domain | Technologies |
| :--- | :--- |
| **Backend Architecture** | Java 17, Spring Boot 3, Spring Security, Hibernate |
| **Frontend Web** | React.js, Material UI (MUI), Axios, Recharts |
| **Mobile Clients** | Android (Java/XML), MVVM Architecture, Retrofit2 |
| **Database & Storage** | MySQL 8.0, Multipart File Handling |
| **External Integrations** | Razorpay SDK, MessageCentral API |

---

## 👨‍💻 About the Developer

This entire ecosystem was architected and engineered by **[Somnath Pandit](https://github.com/somnath503)**, a Backend Software Engineer specializing in scalable enterprise systems, applied cryptography, and IoT integrations.

*Built for performance. Designed for scale.*

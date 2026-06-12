# Shopping Cart Web Application

A full-stack E-Commerce Web Application developed using Java, JSP, Servlets, JDBC, MySQL, Apache Tomcat, Maven, and GitHub. The application enables users to browse products, manage shopping carts, place orders, and receive email notifications. An admin dashboard is included for inventory and order management.

## About

This project is designed to simulate a real-world online electronics shopping platform. Users can register, log in, search products, filter products by category, add products to the cart, update quantities, place orders, and track order status.

The admin panel provides complete control over product inventory, customer orders, stock management, and shipment tracking.

The application also includes an email notification system that informs users about successful registration, order placement, stock availability, and shipment updates.

> Note: Payment functionality is for demonstration purposes only and is not integrated with any real payment gateway.

---

## Key Features

### User Features

* User Registration & Login
* Product Search & Category Filtering
* Shopping Cart Management
* Order Placement
* Order History Tracking
* Email Notifications
* User Profile Management

### Admin Features

* Admin Authentication
* Product Management (Add, Update, Delete)
* Inventory Management
* Order Management
* Shipment Tracking
* Customer Order Monitoring

---

## Email Notifications

Users receive email notifications for:

* Successful Registration
* Successful Order Placement
* Product Back in Stock Alerts
* Shipment and Delivery Updates

---

## Technologies Used

### Frontend

* HTML5
* CSS3
* JavaScript
* Bootstrap

### Backend

* Java
* JSP
* Servlets
* JDBC

### Database

* MySQL

### Tools & Server

* Apache Tomcat
* Maven
* Git
* GitHub
* MySQL Workbench

---

## Project Setup

### Prerequisites

* Java JDK 8+
* Apache Maven
* Apache Tomcat 8+
* MySQL Server
* MySQL Workbench
* Git

### Database Setup

1. Create a database named:

```sql
shopping-cart
```

2. Execute:

```text
databases/mysql_query.sql
```

3. Configure database credentials in:

```text
application.properties
```

### Run the Application

1. Clone Repository

```bash
git clone https://github.com/harshit0808/shopping-cart.git
```

2. Import project into Eclipse or IntelliJ IDEA.

3. Update:

```properties
db.username=your_mysql_username
db.password=your_mysql_password

mailer.email=your_email@gmail.com
mailer.password=your_app_password
```

4. Build Project

```bash
mvn clean install
```

5. Deploy WAR file on Apache Tomcat.

6. Start Tomcat Server.

7. Open:

```text
http://localhost:8080/shopping-cart-0.0.1-SNAPSHOT/
```

---

## Default Credentials

### Admin

Email:

```text
admin@gmail.com
```

Password:

```text
admin
```

### User

Email:

```text
guest@gmail.com
```

Password:

```text
guest
```

---

## Project Screenshots

### Home Page

![Home Page](Screenshot%202026-06-12%20134320.png)

### Login Page

![Login Page](Screenshot%202026-06-12%20135730.png)

### Product Page

![Product Page](Screenshot%202026-06-12%20135740.png)

### Shopping Cart

![Shopping Cart](Screenshot%202026-06-12%20135754.png)

### Admin Dashboard

![Admin Dashboard](Screenshot%202026-06-12%20135853.png)

### Order Management

![Order Management](Screenshot%202026-06-12%20135948.png)

---

## Future Enhancements

* Payment Gateway Integration
* Product Reviews & Ratings
* Wishlist Functionality
* REST API Development
* Spring Boot Migration
* Docker Deployment

---

## Author

### Harshit Kushwah

Java Full Stack Developer

GitHub:
https://github.com/harshit0808

Repository:
https://github.com/harshit0808/shopping-cart

---

Suggestions and project improvement ideas are always welcome.

Thank you for visiting this repository.

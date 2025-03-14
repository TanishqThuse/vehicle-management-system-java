# Vehicle Management System (Java Swing)

## 📌 About the Project  
This **Vehicle Management System** is developed using **Java Swing (WindowBuilder)** as part of my **4th Semester Object-Oriented Programming System (OOPS) course project**. It provides an interface for **Customers and Dealers** to interact, where:  

- **Dealers** can **add, delete, and manage vehicles**.  
- **Customers** can **view, search, and request vehicles** for purchase.  
- **Admin** has control over users and vehicles.  
- **Normal users** can browse available vehicles.  

🚀 **Note:** This project does **not** use a database or file storage. Data is lost when the application is closed.  

---

## 🔹 Features  
✅ **Login & Signup System** for Dealers and Customers.  
✅ **Dealers** can **add, delete, and update vehicles**.  
✅ **Customers** can **search for vehicles** and place an **order request**.  
✅ **Order Management** – Dealers can accept or reject orders.  
✅ **Admin Control Panel** to manage users and vehicles.  
✅ **Sorting & Filtering** – Customers can easily find vehicles.  
✅ **GUI Interface** using **Java Swing (JPanels, JTables, and Applets)**.  

---

## 🛠️ Implementation Details  
This project is built using **Object-Oriented Programming (OOP) principles** in Java, with the following key components:  

### **🔹 Project Structure**  
- **`Project.java`** – Main application class that initializes the UI and manages navigation.  
- **`Dealer.java`** – Handles dealer-related functionalities like login, signup, and managing vehicles.  
- **`Customer.java`** – Manages customer accounts and their ability to browse and request vehicles.  
- **`Vehicle.java`** – Stores vehicle details, ownership status, and purchase requests.  
- **`Details.java`** – Parent class for `Dealer` and `Customer` to inherit user attributes like name, phone, and email.  

### **🔹 Functionality Overview**  
- **Login System** – Users can log in as a Dealer, Customer, or Admin.  
- **Dealer Functions**:
  - Add, delete, and manage vehicles.  
  - View and process customer purchase requests.  
  - Accept or reject orders.  
- **Customer Functions**:
  - Search, filter, and browse available vehicles.  
  - Send purchase requests to dealers.  
  - Cancel purchase requests if needed.  
- **Admin Functions**:
  - View and manage all dealers and customers.  
  - Delete dealer/customer accounts if necessary.  
  - Manage all vehicle listings.  

---

## 🔑 Default Login Credentials  
```plaintext
Username: admin  
Password: admin  
```

## 📌 Future Enhancements:

🔹 Integrate a database (MySQL/SQLite) for data persistence.

🔹 Improve UI design for better user experience.

🔹 Implement advanced search filters for vehicles.

🔹 Add email notifications for order confirmations.

🔹 Implement a dashboard with sales analytics.


## 💻 How to Run

Clone this repository:

```bash
git clone https://github.com/TanishqThuse/vehicle-management-system-java.git
```

Open Eclipse and import the project.

Run Project.java to start the application.

Login using the default credentials or create a new account.

## 📜 License

Copyright (c) 2025

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software.

# 🛍️ **Store Management System**

Welcome to the **Store Management System** project! This application is designed to streamline the management of users, products, and invoices within a small store. The system is built with a focus on providing a user-friendly interface and robust functionality, making it an ideal tool for store administrators.

![Captura de pantalla 2024-08-18 212743](https://github.com/user-attachments/assets/291cceb3-7bad-4009-a880-7a4f24fadb03) <!-- Replace with a real banner if available -->

## 🚀 **Features**

### 🔐 **Secure Login System**
- **User Authentication**: Implemented using Spring Security with session-based authentication. Users log in with their credentials, which are securely encrypted and validated against the database.
- **Role-Based Access Control**: Depending on the user's role (Admin, Manager, etc.), different views and permissions are granted.

### 📋 **Customer Management**
- **Customer List View**: Display all customers in a dynamic table, allowing administrators to:
  - ✏️ Modify existing user information
  - 🗑️ Delete selected customers
  - 🆔 View detailed information related to each customer, including their unique ID and associated profile icon

### 🛒 **Real-Time Product Search & Purchase**
- **Purchase View**: Facilitates real-time product search using jQuery and JavaScript. 
  - 🛍️ **Purchase Products**: Easily select and purchase products.
  - 📄 **Generate Invoices**: Automatically create invoices in PDF or Excel format, ready for download.

### 🧾 **User Information & Invoices**
- **User Profile View**: Allows administrators to:
  - 🔧 Modify user-related information
  - 📜 View all invoices associated with a particular user in a well-organized table

### 🧾 **Invoice Details**
- **Invoice Details View**: Provides comprehensive details about specific invoices, including:
  - 👤 **Owner Information**
  - 🛍️ **Purchased Products**
  - 📝 **Description**
  - 💰 **Total Amount**

### 🌐 **Multilingual Support**
- **Language Options**: Users can switch between German 🇩🇪, Spanish 🇪🇸, and English 🇬🇧 with ease.

## 💻 **Technologies Used**

- **Backend**: [Spring Boot](https://spring.io/projects/spring-boot) 🟢
- **Frontend**: [Thymeleaf](https://www.thymeleaf.org/) 🟣, [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML) 🟠, [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) 🔵
- **Database**: [SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-downloads) 🟡
- **Real-Time Interactions**: [jQuery](https://jquery.com/) 💻, [Ajax](https://developer.mozilla.org/en-US/docs/Web/Guide/AJAX) 🌐, [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) 🧑‍💻
- **Security**: [Spring Security](https://spring.io/projects/spring-security) 🔒
- **PDF & Excel Generation**: Libraries used for generating downloadable invoices 📄

## 🛠️ **Project Structure**

- **Controllers**: Manage requests and direct them to the appropriate services.
- **Services**: Handle business logic and interactions with the database.
- **Repositories**: Manage database access, utilizing Spring Data JPA for ORM with SQL Server.
- **Views**: Rendered with Thymeleaf, offering a responsive and dynamic UI.
- **Security**: Managed with Spring Security, implementing session-based authentication.

## 🧑‍💼 **Target Audience**

- **Store Administrators**: Manage customers, products, and invoices with ease.
- **Store Managers**: Access detailed reports and customer information to make informed decisions.

## 🌟 **Why This Project?**

This project demonstrates my ability to create a full-stack application with secure user management, dynamic content, and real-time interactions. It showcases my skills in:

- Building RESTful services with Spring Boot
- Developing dynamic and responsive user interfaces with Thymeleaf, HTML, CSS, and JavaScript
- Implementing secure authentication mechanisms with Spring Security
- Handling complex database interactions using Spring Data JPA with SQL Server
- Generating reports and documents in PDF and Excel formats

## 📷 **Screenshots**


![Captura de pantalla 2024-08-18 212743](https://github.com/user-attachments/assets/291cceb3-7bad-4009-a880-7a4f24fadb03) 

![Captura de pantalla 2024-08-18 212704](https://github.com/user-attachments/assets/9bf53a68-24a6-45e1-88b2-1239bc21f52e)

![Captura de pantalla 2024-08-19 081811](https://github.com/user-attachments/assets/854d82d1-60d7-4851-8903-d11263a3dfa0)

![Captura de pantalla 2024-08-19 081716](https://github.com/user-attachments/assets/33e3e44b-e618-4ca3-8047-61f69832006c)



![Captura de pantalla 2024-08-19 081837](https://github.com/user-attachments/assets/0a17cf0c-b2a7-47d2-b289-a65b21da9335)

![Captura de pantalla 2024-08-18 212845](https://github.com/user-attachments/assets/7675578b-c0a3-4ae2-a811-755d9c8ca73a)



## 📜 **Getting Started**

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/store-management-system.git


- **Integration with Web Frameworks**: Consider migrating to Spring Boot for scalability.
- **Enhanced Security**: Implement OAuth2 or JWT for improved authentication and authorization.
- **Reporting Features**: Add more detailed reports and analytics.

---

## 🤝 **Contributing**

Contributions are welcome! Please fork this repository and submit a pull request for any improvements.

---

## 📄 **License**

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 📧 **Contact**

For any inquiries or support, please contact [carlosjosuelopezsolano98@gmail.com](carlosjosuelopezsolano98@gmail.com).


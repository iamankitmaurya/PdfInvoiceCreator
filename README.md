# PdfInvoiceCreator

## 📌 Project Overview
PdfInvoiceCreator is a Java and Spring Boot-based application that generates professional PDF invoices dynamically. It processes itemized billing, applies discounts, and exports invoices in PDF format using **iTextPDF**.

## 🚀 Features
- **Invoice Generation:** Automatically creates detailed PDF invoices.
- **JDBC Integration:** Connects with MySQL for storing invoice data.
- **Dynamic Billing:** Processes itemized bills and applies discounts.
- **Spring Boot Backend:** Ensures a scalable and robust API.
- **Apache Tomcat Deployment:** Hosts web forms for invoice management.

## 🛠️ Technologies Used
- **Java 11+**
- **Spring Boot**
- **JDBC (MySQL)**
- **iTextPDF** (For PDF generation)
- **Apache Tomcat**

## 📂 Project Structure
```
PdfInvoiceCreator/
│── src/main/java/com/invoicecreator/
│   │── controller/          # REST API Controllers
│   │── service/             # Business Logic Services
│   │── repository/          # Database Repositories
│   │── model/               # Invoice Data Models
│── resources/
│   │── application.properties # Database & app config
│── pom.xml                  # Maven Dependencies
│── README.md                # Project Documentation
```

## 🔧 Setup & Installation
1. **Clone the Repository:**
   ```sh
   git clone https://github.com/iamankitmaurya/PdfInvoiceCreator.git
   cd PdfInvoiceCreator
   ```
2. **Configure Database (MySQL):**
   Update `application.properties` with your MySQL details:
   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/db_invoice
   spring.datasource.username=root
   spring.datasource.password=yourpassword
   ```
3. **Build and Run the Application:**
   ```sh
   mvn clean install
   mvn spring-boot:run
   ```
4. **Access the Application:**
   - Open `http://localhost:8080` in your browser.

## 📜 Usage
- Use the web form to enter invoice details.
- Click "Generate Invoice" to download a PDF.
- View saved invoices in the MySQL database.




💡 **Created by [Ankit Maurya](https://github.com/iamankitmaurya)**

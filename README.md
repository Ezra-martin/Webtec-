
# 🛒 E-Commerce CRUD REST API

A simple E-Commerce RESTful API built using Spring Boot.  
This project allows users to perform CRUD (Create, Read, Update, Delete) operations on products.

---

## 👤 Student Information

- **Name:** MANZI Ezra  
- **Registration Number:** 26688  

---

## 🚀 Features

- Create a new product
- Retrieve all products
- Retrieve a product by ID
- Update an existing product
- Delete a product
- RESTful API structure
- Layered architecture (Controller, Service, Repository)

---

## 🛠️ Technologies Used

- Java
- Spring Boot
- Spring Web
- Spring Data JPA
- H2 / MySQL Database
- Maven

---

## 📁 Project Structure

src/main/java/auca/ac/rw/restfullApiAssignment/
│
├── controller/
│ └── ProductController.java
│
├── service/
│ └── ProductService.java
│
├── repository/
│ └── ProductRepository.java
│
├── modal/
│ └── Product.java
│
└── RestfullApiAssignmentApplication.java

yaml
Copy code

---

## ▶️ How to Run the Project

1. Clone the repository:

git clone https://github.com/Ezra-martin/Webtec-.git

csharp
Copy code

2. Navigate into the project folder:

cd Webtec-

css
Copy code

3. Switch to the branch:

git checkout Ecommerce-CRUD

markdown
Copy code

4. Run the application:

mvn spring-boot:run

nginx
Copy code

The application will start on:

http://localhost:8080

yaml
Copy code

---

## 📌 API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST   | /api/products | Create product |
| GET    | /api/products | Get all products |
| GET    | /api/products/{id} | Get product by ID |
| PUT    | /api/products/{id} | Update product |
| DELETE | /api/products/{id} | Delete product |

---

## 🧪 Example JSON (Create Product)

```json
{
  "name": "Laptop",
  "description": "Gaming Laptop",
  "price": 1500
}
📄 License
This project is for academic purposes.

⭐ Developed by MANZI Ezra (26688)














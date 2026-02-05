# Java Servlet Projects - Group E (26688)

This repository contains two Java servlet projects:

## 1. LoginServlet
- **Location**: `LoginServlet/`
- **Purpose**: Handles user authentication with login form
- **Port**: http://localhost:8080/LoginServlet/

### Quick Start - LoginServlet
```bash
cd LoginServlet
mvn clean package
mvn tomcat7:run
```

## 2. SearchServlet  
- **Location**: `SearchServlet_Project/`
- **Purpose**: Handles search queries and redirects to Google
- **Port**: http://localhost:8081/SearchServlet/

### Quick Start - SearchServlet
```bash
cd SearchServlet_Project
mvn clean package
mvn tomcat7:run
```
<img width="960" height="1008" alt="Screenshot 2026-02-05 003901" src="https://github.com/user-attachments/assets/76a3a71f-8a11-43b1-bb75-cd778e311568" />

<img width="960" height="1008" alt="Screenshot 2026-02-05 003918" src="https://github.com/user-attachments/assets/2c4ab851-a080-475e-b75f-8f46e8520a5e" />

## Notes
- Both projects are independent and can be run simultaneously on different ports
- Each project has its own Maven configuration and dependencies
- Projects follow standard Maven directory structure

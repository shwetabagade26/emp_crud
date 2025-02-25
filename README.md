# Employee CRUD API 🚀

A Spring Boot REST API for managing employees, using PostgreSQL for storage and Swagger UI for API documentation.

## 📌 Tech Stack
- **Spring Boot** (Backend)
- **PostgreSQL** (Database)
- **Spring Data JPA** (ORM)
- **Swagger UI** (API Docs)
- **Lombok** (Boilerplate Reduction)

## ⚙️ Setup Instructions

### 1️⃣ Clone Repository & Navigate
```sh
git clone https://github.com/your-username/emp-crud-app.git
cd emp-crud-app
```
### 2️⃣ Configure PostgreSQL
```sh
  datasource:
    url: jdbc:postgresql://localhost:5432/hrmdb?createDatabaseIfNotExist=true&autoReconnect=true&showSSL=false
    username: postgres # check for changes
    password: 1234 # check for changes
```
- Next
```sh
psql -U your_db_user -d postgres -c "CREATE DATABASE employee_db;"
```
### 3️⃣ Build & Run
```sh
mvn clean install
mvn spring-boot:run
```

✅ Server Running At: http://localhost:8080
✅ Swagger UI: http://localhost:8080/swagger-ui.html


# Course Service (Spring Boot + GCP MySQL) ☁️⛅🌧️🌪️

This project is a Spring Boot application that connects to a MySQL database hosted on **Google Cloud SQL**.  
It demonstrates managing multiple environments (local & cloud) using **Spring Profiles**.

---

## Video Demonstration about GCP 🥬
https://drive.google.com/file/d/1-eKZNfG3FEK5yk1XeEaIaYxwpqiuxTZP/view?usp=sharing

## ⚙️ Prerequisites
- Java 21 LTS
- MySQL (local or GCP Cloud SQL)
- A GCP MySQL Instance

---


## 📖 Database Setup

### Cloud (for GCP) application-gcp.properties ⛅☁️

#### add your credentials in the specified areas here
```properties
spring.datasource.url=jdbc:mysql://<PUBLIC_GCP_IP>:3306/<DB_NAME>?createDatabaseIfNotExist=true&useSSL=false&allowPublicKeyRetrieval=true
spring.datasource.username=<GCP_MYSQL_USER_NAME>
spring.datasource.password=<GCP_MYSQL_PASSWORD>

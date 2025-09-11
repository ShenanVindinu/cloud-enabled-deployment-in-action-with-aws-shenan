# Course Service (Spring Boot + GCP MySQL)

This project is a Spring Boot application that connects to a MySQL database hosted on **Google Cloud SQL**.  
It demonstrates how to manage multiple environments (local & cloud) using **Spring Profiles**.

---

## Video Demonstration about GCP
https://drive.google.com/file/d/1-eKZNfG3FEK5yk1XeEaIaYxwpqiuxTZP/view?usp=sharing

## ⚙️ Prerequisites
- Java 17+
- Maven 3+
- MySQL (local or GCP Cloud SQL)
- A GCP project with Cloud SQL enabled

---


## 🔑 Database Setup

### Cloud (for GCP) application-gcp.properties
## add your credentials here
```properties
spring.datasource.url=jdbc:mysql://<PUBLIC_IP>:3306/<DB_NAME>?createDatabaseIfNotExist=true&useSSL=false&allowPublicKeyRetrieval=true
spring.datasource.username=<DB_USER>
spring.datasource.password=<DB_PASSWORD>

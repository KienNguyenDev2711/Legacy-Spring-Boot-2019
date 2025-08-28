# 📑 Spring Boot Slides & Notes  

This repository contains my collection of **slides and notes on Spring Boot**, prepared during an 11-day learning journey.  
The content ranges from beginner-level CRUD operations to advanced topics such as **DevOps, database persistence, and integration with external libraries**.  
Although originally created a few years ago, the material still provides valuable insights for those learning or revisiting Spring Boot. 🚀  

---

## 📌 Table of Contents

- [Day 1: Student Management (CRUD)](#day-1-student-management-crud)  
- [Day 2: Spring Boot Hello World](#day-2-spring-boot-hello-world)  
- [Day 3: Externalized Configuration](#day-3-externalized-configuration)  
- [Day 4: Spring Boot Testing](#day-4-spring-boot-testing)  
- [Day 5: Spring Data JPA](#day-5-spring-data-jpa)  
- [Day 6: Advanced Annotations & CommandLineRunner](#day-6-advanced-annotations--commandlinerunner)  
- [Day 7: Spring Boot Customization](#day-7-spring-boot-customization)  
- [Day 8: Spring Boot Under the Hood](#day-8-spring-boot-under-the-hood)  
- [Day 9: Persistence (Database & JPA)](#day-9-persistence-database--jpa)  
- [Day 10: DevOps Tools](#day-10-devops-tools)  
- [Day 11: Integration With Other Libraries](#day-11-integration-with-other-libraries)  

---

## 🔹 Day 1: Student Management (CRUD)
A hands-on introduction to Spring Boot by building a simple **Student Management System**.  
- **Add Student** → Create a new student record.  
- **Update Student (Phone number)** → Update information based on ID or email.  
- **Delete Student** → Remove a student record via ID or email.  
- **Retrieve Students** → Export student data to a file or print the top 10 students.  

👉 This day focuses on **basic CRUD operations** and familiarizing yourself with controllers, services, and repositories.  

---

## 🔹 Day 2: Spring Boot Hello World
- Building a simple **Hello World REST API** with Spring Boot.  
- Exploring the project structure, dependencies, and auto-configuration.  
- Understanding the role of the **main class with @SpringBootApplication**.  

👉 Goal: Get a running application within minutes and understand the minimal setup required.  

---

## 🔹 Day 3: Externalized Configuration
- **Default configuration files** → `application.properties` / `application.yml`.  
- **Accessing property values** via `@Value` or `@ConfigurationProperties`.  
- **Multiple property files** → load custom configs.  
- **System properties & environment variables** → override values.  
- **Default values** for placeholders.  
- **Handling missing property files** gracefully.  

👉 Goal: Learn how Spring Boot manages configuration and how to provide flexible setups for different environments.  

---

## 🔹 Day 4: Spring Boot Testing
- Writing **Unit Tests** with JUnit and Mockito.  
- Writing **Integration Tests** using `@SpringBootTest`.  
- Using `TestRestTemplate` and `MockMvc` for API testing.  
- Introduction to in-memory databases for testing.  

👉 Goal: Build confidence by ensuring application logic works as expected.  

---

## 🔹 Day 5: Spring Data JPA
- Introduction to **Spring Data JPA** and repositories.  
- Creating **entities, repositories, and relationships**.  
- Using **JPQL** and **native queries**.  
- Pagination and sorting support.  

👉 Goal: Simplify database access and learn ORM with Spring Boot.  

---

## 🔹 Day 6: Advanced Annotations & CommandLineRunner
- `@ConditionalOnProperty` → Enable/disable beans based on property values.  
- `@DynamicPropertySource` → Dynamically register properties in tests.  
- `@ServiceConnection` → Manage service connections for containers.  
- `CommandLineRunner` → Execute code after application startup.  
- Demo: Running a `CommandLineRunner` conditionally.  

👉 Goal: Understand advanced annotations and how to run startup logic.  

---

## 🔹 Day 7: Spring Boot Customization
- **Custom Filters** → Implement authentication/logging filters.  
- **Changing default port** and **context path**.  
- **Customize Whitelabel Error Page**.  
- **Custom Banners** at startup.  
- **Customize Jackson ObjectMapper** for JSON serialization.  

👉 Goal: Make Spring Boot applications more flexible and tailored to business needs.  

---

## 🔹 Day 8: Spring Boot Under the Hood
- Creating a **Custom Starter**.  
- Writing **Custom Auto-Configuration**.  
- Displaying **Auto-Configuration Report**.  
- Retrieving all Spring-managed beans.  
- Understanding **Spring Boot Security Auto-Configuration**.  
- Deep dive into **Component Scanning**.  

👉 Goal: Understand how Spring Boot auto-configuration works behind the scenes.  

---

## 🔹 Day 9: Persistence (Database & JPA)
- Database migrations with **Liquibase**.  
- Loading initial data.  
- Using **multiple SQL import files**.  
- Displaying Hibernate/JPA SQL statements.  
- Integration with **H2 Database** for testing.  
- Configuring **multiple data sources**.  

👉 Goal: Master database persistence and migrations in Spring Boot.  

---

## 🔹 Day 10: DevOps Tools
- Running applications with **Minikube**.  
- **Dockerizing Spring Boot apps**.  
- Creating Docker images.  
- Deploying a WAR file to **Tomcat**.  
- Monitoring with **Spring Boot Admin**.  
- Overview of **DevTools** for hot reload.  
- Introduction to **Spring Boot CLI**.  
- Running Spring Boot as a service.  
- Using the **Gradle Plugin**.  
- Deploying to **Azure**.  

👉 Goal: Learn how to package, deploy, and monitor Spring Boot applications in production.  

---

## 🔹 Day 11: Integration With Other Libraries
- **Keycloak** for authentication and authorization.  
- **Mustache** templating engine integration.  
- **GraphQL** API with Spring Boot.  
- **Apache Camel** for integration flows.  
- **DynamoDB** with Spring Data.  
- **Jasypt** for encrypted configuration properties.  
- **JHipster** for rapid application development.  

👉 Goal: Explore real-world integrations to extend Spring Boot’s capabilities.  

---

## 📂 Repository Contents
- 📝 **Slides (PDF)** stored in this repository.
- 📖 **README.md** (this document).  

---

## 🙌 Audience
This repository is suitable for:  
- Beginners starting with **Spring Boot**.  
- Developers revisiting Spring Boot concepts.  
- Engineers exploring persistence, DevOps, and integrations.  

---

✍️ *Created with passion for sharing knowledge.*


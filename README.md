# Student Registration System

A full-stack web application built with **Spring Boot**, **Thymeleaf**, and an **H2 Database** as part of **COSC 32133 / BECS 32263 (Full-Stack Software Development)** at the University of Kelaniya.

## Features
* **CRUD Operations:** Register, view, update, and delete student records.
* **Input Validation:** Server-side validation using Bean Validation (`@NotBlank`, `@Email`, `@Pattern`, `@Min`, `@Max`).
* **Duplicate Prevention:** Checks for existing email addresses before saving or updating records.
* **Database Integration:** Stores data using Spring Data JPA and an H2 in-memory/file-based database.
* **Web Interface:** Dynamic HTML pages styled with Thymeleaf and custom CSS.

## Tech Stack
* **Backend:** Java 21, Spring Boot, Spring MVC, Spring Data JPA, Hibernate
* **Frontend:** HTML5, Thymeleaf, CSS3
* **Database:** H2 Database (Console enabled)
* **Build Tool:** Maven

## Prerequisites
* **Java Development Kit (JDK) 21** or later (check with `java -version`)
* Git installed on your local machine

## How to Run the Application

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/](https://github.com/)<Pemindu-Prabodhitha>/student-manager-springboot.git
   cd student-manager-springboot

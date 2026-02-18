# 🛡️ OAuth 2.0 API Automation Suite (Rest Assured)

## 📄 Project Overview
This repository contains a professional-grade API automation framework built using **Rest Assured** and **Java**. It is specifically designed to demonstrate the implementation of **OAuth 2.0 authentication** flows in a real-world e-commerce API context.

The framework follows industry best practices such as the **Request/Response POJO Pattern**, **Spec Builders**, and **Serialization/Deserialization** using Jackson.

---

## 🧰 Technology Stack
- **Java 21** – Latest LTS version for robust backend logic.
- **Rest Assured 5.5.6** – Leading library for REST API testing.
- **TestNG 7.11.0** – Advanced testing framework for execution and assertions.
- **Jackson Databind** – For seamless POJO serialization/deserialization.
- **Maven** – Build automation and dependency management.

---

## ✨ Key Features
- **🔐 OAuth 2.0 Integration:** Automated token generation and management for secure API access.
- **🏗️ POJO Modeling:** Structured request and response bodies using Plain Old Java Objects.
- **🔄 Serialization/Deserialization:** Efficient handling of JSON data using Jackson.
- **🛠️ Spec Builders:** Reusable Request and Response specification builders to reduce code duplication.
- **📊 Detailed Reporting:** Integrated with TestNG for clear execution results.
- **🚀 End-to-End Scenarios:** Comprehensive test cases covering authentication and business flows.

---

## 📁 Project Structure
```text
demo_Oauth-RestAssured/
├── src/
│   ├── main/java/
│   │   ├── pojos/          # Request & Response POJO classes
│   │   ├── utils/          # SpecBuilders and Config utilities
│   ├── test/java/
│   │   ├── tests/          # Functional & E2E API test classes
├── pom.xml                 # Project dependencies
└── README.md               # Project documentation
```

---

## ▶️ How to Run
1. **Prerequisites:** Install JDK 21 and Maven.
2. **Clone:** `git clone https://github.com/Chandrakant-Jadhav/demo_OAuth-RestAssured.git`
3. **Execute:** `mvn clean test`

---

## 👤 Author
**Chandrakant Jadhav**
*QA Automation Engineer | SDET*

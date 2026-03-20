# 🛒 Cloudberry Store BDD Automation Framework

A Behavior-Driven Development (BDD) test automation framework designed for the Cloudberry Store application. This project leverages modern testing tools and best practices to ensure scalable, maintainable, and readable test automation.

---

## 🚀 Tech Stack

* **Java**
* **Selenium WebDriver**
* **Cucumber (BDD)**
* **TestNG**
* **Maven**
* **Page Object Model (POM)**
* **Gherkin (Feature Files)**

---

## 📌 Key Features

* ✅ BDD framework using **Cucumber** with Gherkin syntax
* ✅ Scalable design using **Page Object Model (POM)**
* ✅ Clean separation of **test logic and test data**
* ✅ Supports **data-driven testing**
* ✅ Cross-browser test execution capability
* ✅ Reusable utility functions for common actions
* ✅ Detailed test reports

---

## 📂 Project Structure

```
Cloudberry-Store-BDD-Framework
│── src/test/java
│   ├── stepDefinitions      # Step definition classes
│   ├── pageObjects          # Page Object classes
│   ├── runners              # Test runners (TestNG/Cucumber)
│   ├── utilities            # Utility/helper classes
│
│── src/test/resources
│   ├── features             # Gherkin feature files
│   ├── config               # Configuration files
│
│── pom.xml                  # Maven dependencies
│── testng.xml               # TestNG configuration
```

---

## 🧪 How to Run Tests

### 🔧 Prerequisites

* Java (JDK 8 or higher)
* Maven installed
* IDE (IntelliJ / Eclipse recommended)

---

### ▶️ Run via Maven

```bash
mvn clean test
```

---

### ▶️ Run via TestNG

* Right-click on `testng.xml`
* Select **Run As → TestNG Suite**

---

## 📊 Reporting

* Cucumber HTML Reports are generated after test execution
* Reports provide:

  * Step-by-step execution details
  * Pass/Fail status
  * Screenshots (if configured)

---

## 🧩 Design Pattern

This framework follows:

* **Page Object Model (POM)** → Improves maintainability
* **BDD (Cucumber)** → Enhances readability for non-technical stakeholders
* **Modular Architecture** → Easy to extend and scale

---

## ✍️ Sample Feature File

```gherkin
Feature: Login Functionality

  Scenario: Valid user login
    Given User is on login page
    When User enters valid credentials
    Then User should be logged in successfully
```


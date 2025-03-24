# B43_SDET_001_Automation_Avengers

## Introduction
B43_SDET_001_Automation_Avengers is an automation testing project designed to validate the UI elements of a web application using Selenium, Cucumber, and Java. The project focuses on ensuring the visibility, functionality, and responsiveness of key UI components.

## Project Type
Software Testing (Automation)

## Testing on 
- **Frontend:** [Nykaa](https://sweet-donut-1ca8e9.netlify.app/index.html)

## Directory Structure
```
B43_SDET_001_Automation_Avengers/
├─ src/
│  ├─ main/
│  │  ├─ java/
│  │  │  ├─ pageObject/
│  │  │  │  ├─ HomePage.java
│  │  │  │  ├─ LoginPage.java
│  │  │  │  ├─ NavigationPage.java
│  │  │  │  ├─ UIValidationPage.java
│  │  ├─ test/
│  │  │  ├─ java/
│  │  │  │  ├─ stepdefinitions/
│  │  │  │  │  ├─ UIValidationSteps.java
│  │  │  │  ├─ testrunner/
│  │  │  │  │  ├─ TestRunner.java
│  ├─ resources/
│  │  ├─ features/
```

## Video Walkthrough of the Project
[Link] (#)

## Video Walkthrough of the Codebase
[Link] (#)

## Features
- Validates the visibility of UI elements such as logo, search bar, navigation menu, and cart icon.
- Ensures primary buttons are visible and clickable.
- Tests hover effects on buttons.
- Uses Selenium WebDriver for browser automation.
- Implements Page Object Model (POM) for maintainability.

## Design Decisions & Assumptions
- Page Object Model (POM) is used for better test maintenance and reusability.
- WebDriverWait is utilized to handle dynamic elements.
- Assertions ensure the presence and functionality of UI components.
- Tests are designed for a Chrome browser environment.

## Installation & Getting Started
### Prerequisites
- Java 8+
- Maven
- Selenium WebDriver
- Cucumber
- IntelliJ IDEA (Recommended) or Eclipse


## APIs Used
N/A (Project focuses on UI testing, no external APIs used)

## Technology Stack
- **Java** - Core programming language
- **Selenium WebDriver** - Browser automation
- **Cucumber** - BDD framework
- **JUnit/TestNG** - Test framework
- **Maven** - Dependency management

## API Endpoints
N/A (Only UI testing is performed)

---


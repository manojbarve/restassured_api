# RestAssured API Testing Framework

This project demonstrates API testing using RestAssured framework.

## Overview

This API testing framework is built using RestAssured, a Java library for RESTful API automation testing. It provides a simple and intuitive way to interact with RESTful web services and perform various types of API tests, including functional, integration, and regression tests.

## Features

- Utilizes RestAssured for API requests and response validation.
- Implements BDD (Behavior-Driven Development) approach using Cucumber for writing test scenarios.
- Includes test scenarios for various API endpoints covering different use cases.
- Configures test environment settings for different environments (e.g., development, testing, production).
- Generates HTML reports for test execution results, providing detailed insights into test outcomes.

## Project Structure

│ │ └── stepdefinitions # Cucumber step definitions
│ └── resources
│ ├── features # Cucumber feature files
│ └── testdata # Test data files
│
├── pom.xml # Maven project configuration file
└── README.md # Project documentation (you are here)

## Dependencies

The project uses the following dependencies:
- RestAssured: For API testing.
- Cucumber: For BDD feature files and step definitions.
- JUnit: For running and organizing test cases.

## Running Tests

### Prerequisites
- JDK (Java Development Kit)
- Maven

### Steps
1. Clone the project repository : git clone https://github.com/manojbarve/restassured_api.git
2. Navigate to the project directory.
3. Execute the following Maven command to run the tests:mvn clean test
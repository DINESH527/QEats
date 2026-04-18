# 🍽️ QEats – Food Ordering Backend Application

## 📌 Overview

  QEats is a popular food ordering application that allows users to browse and order their favorite dishes from nearby restaurants.
     
  In this project, I developed the backend system using Spring Boot, focusing on scalability, performance, and real-world production scenarios.

## 🚀 Features

 * 🔍 Browse restaurants based on user location
   
 * 📦 Order food from nearby restaurants
   
 * 📡 REST API endpoints for restaurant data and order handling
   
 * ⚡ Optimized performance for high-load scenarios
   
 * 🛠️ Debugged real-world production issues using scientific methods

## 🧩 Scope of Work

📍 Retrieve Restaurant Data Based on Location

 * Implemented GET /qeats/v1/restaurants
   
 * Designed request handlers and response models
   
 * Fetched restaurant data from MongoDB using location filters
   
 * Ensured clean architecture using MVC layers
   
   
## 🧪 Testing & Development

* Used Mockito for unit testing and layer isolation
  
* Wrote test cases using JUnit
  
* Ensured reliability and maintainability

## 🛠️ Tech Stack

* Backend: Spring Boot
* Database: MongoDB
* API: REST APIs
* Testing: JUnit, Mockito
* Serialization: Jackson

## 🏗️ Project Architecture

  Controller → Service → Repository → Database

   * Controller Layer: Handles HTTP requests
   * Service Layer: Business logic and processing
   * Repository Layer: Database interaction
   * DTOs: Data transfer between layers

## ▶️ Getting Started

 Prerequisites
 
 * Java 8+
 * Maven
 * MongoDB

## ⚙️ Installation

```bash
  # Clone the repository
  git clone https://github.com/your-username/QEats.git

  # Navigate to project folder
  cd QEats

  # Build the project using Gradle Wrapper
  ./gradlew build

  # Run the application
 ./gradlew bootRun

```



## 📌 API Endpoints

## 🔍 Get Restaurants by Location
 GET /qeats/v1/restaurants?latitude={lat}&longitude={lon}

## 🍔 Place Order
POST /qeats/v1/orders

## 🔎 Search Restaurants
GET /qeats/v1/restaurants/search?query={name}


## 🧪 Running Tests

```bash
./gradlew test

```

## API Request/Response Example

### Example Request

GET /qeats/v1/restaurants?latitude=12.9716&longitude=77.5946

### Example Response
```json
[
  {
    "id": "1",
    "name": "Burger King",
    "rating": 4.3,
    "distance": 2.5
  }
]

```

## 📚 What I Learned

* Designing scalable REST APIs
* Writing clean layered architecture
* Debugging production issues systematically
* Writing unit tests using Mockito & JUnit



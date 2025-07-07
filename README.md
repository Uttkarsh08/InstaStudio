# InstaStudio – Photography Studio Management App

## Introduction

InstaStudio is a comprehensive backend-driven platform tailored for managing photography studios, event schedules, team collaboration, and client engagement. Designed with Indian photographers in mind, it brings structure, automation, and convenience to a studio’s day-to-day operations.

## ⭐ Key Features
- **🔐 Role-Based Access Control**
Implements a secure authentication and authorization system using Spring Security and JWT for Admins, Members, and Customers.

- **📅 Event Scheduling & Management**
Allows creation, assignment, and tracking of photography events—managing dates, locations, associated teams, and client details.

- **👥 Team & Customer Management**
Manage studio team members and customers with dedicated modules for assigning roles, responsibilities, and tracking participation.

- **📤 Layered REST API Architecture**
Clean RESTful API design using DTOs, service layers, and repository abstraction for maintainability and scalability.

- **💳 Payment & Booking Status**
Backend-ready structure for integrating payment systems (like UPI or Razorpay) and tracking payment status across events.

- **🧪 Testing & Validation**
All APIs are tested using Postman and JUnit to ensure reliability and smooth frontend integration.

- **🛠️ Exception Handling & Consistent Responses**
Custom exceptions and response wrappers for cleaner debugging, better client-side error handling, and consistent API formats.

- **📸 Use Cases**
  - A studio admin can create events, assign team members, and track their completion status.
  - Clients can be onboarded and linked with specific events or shoots.
  - Members can view assigned events and contribute to real-time progress tracking.
  - API responses are consistently structured to support smooth mobile frontend integration.

## 🚀 How to Get Started

- **Move to the Android Repository**

- **Clone the Repository:**
 ```bash
git clone https://github.com/Uttkarsh08/InstaStudio-Android.git
cd InstaStudio-Android
```
- **Open in Android Studio:**

Open the cloned folder in Android Studio.
Let Gradle sync and dependencies resolve.

- **Run the Backend Server:**
 ```bash
./mvnw spring-boot:run
```
- **Configure Firebase for Google Sign-In:**

Create a Firebase project at Firebase Console.
Enable Google Sign-In in Authentication > Sign-in method.
Download google-services.json and place it in the app/ directory.
Sync the project.

OR

Contact me for google-services.json

- **Build and Run:**

Connect your device (recommended) or use an emulator with Android Studio.
Run the Application

## 🧱 Tech Stack
- **Language:** Kotlin(Android), Java(Backend)

- **UI:** Jetpack Compose

- **Auth:** Firebase Google Sign-In

- **Backend Framework:** Spring Boot

- **Database:** PostgreSQL

- **Security:** Spring Security, JWT

- **API Testing:** Postman, JUnit


## 📅 Development Timeline
- **🧩 Backend Modules Developed:** Authentication, Role Authorization, Event & Team Management, Customer Module, Exception Handling.

- **📦 Current State:** Fully deployed and integrated.

- **🎯 Target:** Currently working on the Android frontend, integrating it with the deployed backend to enable studio management, Google sign-in, and image handling workflows in the app.
>>>>>>> 667653ad57018392e835cbf1e2efbd4b4c80c58d

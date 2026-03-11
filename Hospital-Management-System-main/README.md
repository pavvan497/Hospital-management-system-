# Hospital Management System 🏥

A Java-based Hospital Management System (HMS) designed to streamline healthcare operations, including patient registrations, doctor records, and appointment scheduling, while ensuring data accuracy and efficiency.

## Problem Statement
Hospitals require an efficient system to manage patient and doctor information, schedule appointments, and maintain patient history. The current manual processes often lead to errors, delays, and inefficiency in handling data. The goal is to build a robust Hospital Management System (HMS) to automate these tasks, ensuring accuracy, quick access to records, and a seamless experience for both patients and hospital staff.

## Overview
The Hospital Management System is a software application that manages and streamlines healthcare operations. The system handles:

- **Patient Registrations**
- **Doctor Records**
- **Appointment Scheduling**

It also checks doctor availability to ensure optimal resource utilization. The project uses Java for backend processing and MySQL for database management.

## Features
### 1. Patient Management
- Add new patients.
- View patient details (name, age, gender, ID).

### 2. Doctor Management
- View doctor details, including specialization.
- Check if a doctor is available on a specific date.

### 3. Appointment Booking
- Schedule appointments between doctors and patients.
- Ensure doctor availability before booking.

### 4. Validation
- Prevent duplicate bookings for the same doctor on a specific date.
- Verify patient and doctor IDs before scheduling.

### 5. User-Friendly Interface
- Console-based, menu-driven interaction.

## Technology Used
- **Frontend**: Java (Command-Line Interface)
- **Backend**: JDBC (Java Database Connectivity)
- **Database**: MySQL (Relational Database Management System)
- **Development Tools**: IntelliJ IDEA, MySQL Workbench
- **Java Features**: Exception Handling, Prepared Statements, Object-Oriented Programming (OOP)

## Applications
- Ideal for small to medium-sized hospitals to manage daily operations efficiently.
- Provides a scalable foundation for larger hospital management systems with advanced features.
- Serves as an educational project for learning Java-JDBC connectivity and database application development.

## How to Run
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/HospitalManagementSystem.git
- Open the project in IntelliJ IDEA or your preferred IDE.
- Set up the MySQL database using the provided schema and configure the connection details in the code.
- Run the HospitalManagementSystem class to start the program.

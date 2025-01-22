# Dentist Appointment Manager 🦷

## Overview

&nbsp;&nbsp;&nbsp;The **Dentist Appointment Manager** is a Java-based console application designed to provide a comprehensive interface for managing dentists and their appointments. Built using a layered architecture, the application integrates multiple data persistence strategies, including text files, binary files, JSON, and databases. It empowers users to efficiently manage appointment schedules and dentist details, ensuring data integrity with robust error handling and validation.

## Features

### 1. **Appointment and Dentist Management**
   &nbsp;&nbsp;&nbsp;• Full **CRUD operations** for managing both appointments and dentists.
   
   &nbsp;&nbsp;&nbsp;• **Filter** dentists by specialty or grade.
   
   &nbsp;&nbsp;&nbsp;• **Sort** dentists by name, ID, specialty, or grade.

### 2. **Dentist Management**
   &nbsp;&nbsp;&nbsp;• **Add**, **update**, and **delete** dentist records.

   &nbsp;&nbsp;&nbsp;• **Filter** dentists by specialty or grade.
   
   &nbsp;&nbsp;&nbsp;• **Sort** dentists by name, ID, specialty, or grade.

### 3. **Data Persistence**
   &nbsp;&nbsp;&nbsp;• Supports **text files**, **binary files**, **JSON**, and **database** storage.
   
   &nbsp;&nbsp;&nbsp;• Easily switch between storage types using configuration in the `settings.properties` file.
   
   &nbsp;&nbsp;&nbsp;• Implements a **repository pattern** to abstract data operations.

### 4. **Validation and Error Handling**
   &nbsp;&nbsp;&nbsp;• Ensures **valid inputs** for IDs, times, specialties, and grades.
   
   &nbsp;&nbsp;&nbsp;• Displays **user-friendly error messages** with robust **exception handling**.

### 5. **Test Coverage**
   &nbsp;&nbsp;&nbsp;• Includes a comprehensive suite of **unit tests** to ensure correctness and reliability.

## Technologies Used:
   &nbsp;&nbsp;&nbsp;• **Java** for application logic.
   
   &nbsp;&nbsp;&nbsp;• **Java Properties API** for configuration management.
   
   &nbsp;&nbsp;&nbsp;• **OOP principles** and **exception handling** for maintainability and scalability.

## 🚀 Getting Started:

1. **Clone the Repository**:  
   `git clone https://github.com/MarioMaxim18/Dentist-Appointment-Manager`

2. **Configure Storage**:  
   Edit the `settings.properties` file to choose your desired repository type (e.g., text, binary, JSON, or DB) and specify file paths or database credentials.

3. **Run the Application**:  
   Compile and run the `Main` class in your IDE or terminal.

## 🤝 Contributing:

Fork the repository, make changes, and submit a pull request!

---

📧 **Contact**: maximmarioandrei@gmail.com  
🔗 **GitHub**: [MarioMaxim18](https://github.com/MarioMaxim18)

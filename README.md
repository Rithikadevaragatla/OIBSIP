# Online Reservation System (Java Swing)

A **Java Swing–based desktop application** that simulates an **online railway reservation system**.  
The system allows passengers to reserve and cancel tickets, while managers can manage train details.

This project demonstrates **GUI development, event handling, file handling, and OOP concepts** in Java.

---

## Features

### Login System
- Role-based login:
  - Passenger
  - Manager
- Simple authentication using predefined credentials.

### Passenger Module
- **Ticket Reservation**
  - Enter passenger details (Name, Age, Gender)
  - Enter train number and select class type
  - Provide journey details (Date, From, To)
  - Auto-generates a **PNR number**
  - Displays reservation details in a new window
- **Ticket Cancellation**
  - Cancel reservation using PNR number

### 🛠️ Manager Module
- View and manage:
  - Train Number
  - Train Name
- Train data is loaded from an external file (`trains.txt`)

---

## Technologies Used

- Java
- Java Swing
- AWT
- File Handling (BufferedReader, FileReader)
- Collections (HashMap)
- CardLayout

---




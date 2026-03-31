# 🚌 Blue Bus - Reservation System

A smart, console-based Java application for managing bus reservations with a visual seat selection interface.

## 🌟 Project Overview

Blue Bus is a project built to demonstrate **Object-Oriented Programming (OOP)** and **File Handling** concepts in Java. It specifically solves the real-world problem of "blind booking" by offering a transparent, visual map of the bus layout. This allows passengers to pick their specific seats (Window/Aisle) before confirming a ticket, just like modern web apps.

## ✨ Key Features

* 🗺️ **Visual Seat Map:** A dynamic grid display allowing users to see the bus layout (Rows/Columns) and identify free seats instantly.
* 🔒 **Real-time Booking Validation:** Robust logic that prevents duplicate bookings for the same seat index.
* 💾 **Data Persistence:** All bookings and bus data are saved to local `.dat` files automatically using Java Serialization (no database required).
* 👨‍💻 **Admin Dashboard:** Functionality to view all buses in the fleet and the complete booking history.

## 🛠️ Technology Stack

* **Language:** Java (JDK 17+)
* **Concepts Used:**

  * Object-Oriented Programming (Encapsulation, Classes, Objects)
  * Collections Framework (`ArrayList`, `List`)
  * File I/O (`ObjectOutputStream` for data storage)
  * Exception Handling
* Tools: Git, VS Code

## 🚀 How to Run

Follow these steps to get the project running on your local machine.

1. **Clone the repository**

```bash
    git clone https://github.com/abhijoypaul/libraryManagementSystem_Abhijoy.git

```

2. **Compile the code**  
Navigate to the project root folder (where `src` is located) and run:

```bash
    javac src/\\\\\\\*.java -d out

```

3. **Run the application**  
Execute the main class:

```bash
    java -cp out Main

```

## 📸 Usage Guide

1. **Start the App:** Run the `Main` class to see the menu.
2. **Book a Ticket:** Select **Option 2** from the main menu.
3. **Choose a Bus:** Enter a Bus ID (default available: `B-101`).
4. **Pick a Seat:** The system will display a map:\\

   * `\\\\\\\[ ]` = Empty Seat
   * `\\\\\\\[X]` = Booked Seat
   * Enter your desired Row (1-10) and Column (A-D).
5. **Confirmation:** Enter passenger details to receive your unique **Ticket ID**.

## 📂 Project Structure

```bash
  Blue-Bus-System/
  ├── src/
  │   ├── Main.java          # Entry point and UI logic
  │   ├── Bus.java           # Data model for Bus (contains 2D seat array)
  │   ├── Passenger.java     # Data model for Passenger details
  │   ├── Booking.java       # Data model for Ticket transactions
  │   ├── BusService.java    # Business logic and operations
  │   └── DataManager.java   # File I/O handling
  ├── data/                  # Stores .dat files (generated automatically after first run)
  ├── statement.md           # Formal Problem Statement and Scope
  └── README.md              # Project Documentation
```

## 👨‍💻 Author

* **Name:** Abhijoy Paul
* **Subject:** Programming in Java  
This project was built as part of the "Build Your Own Project" evaluation.


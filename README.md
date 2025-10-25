# 🚆 E-Train Ticket Reservation Management System

A **console-based Java project** that simulates an **Electronic Train Ticket Reservation System**.  
It allows both **Admin** and **Users** to manage trains, view stops, book seats, check prices, and even watch a **train movement animation** — all through an interactive terminal interface.

---

## 🧩 Features

### 👨‍💼 Admin
- Secure admin login (`admin / admin123`)
- Add new trains with:
  - Train name, start and end points
  - Stops between stations
  - Bhogies (coaches) with seat layouts and prices
- View seat availability for each train
- Display all train stops

### 👤 User
- Signup and Login functionality
- Book seats by selecting train and bhogie type
- Check ticket prices for any bhogie type
- View train stops and seat availability
- Watch a live **train movement simulation**
- Simulated payment process with transaction ID

---

## ⚙️ Technologies Used

- **Language:** Java  
- **Version:** JDK 8 or higher  
- **Libraries Used:**  
  - `java.util.*` for collections and scanner  
  - `java.time.*` for date and time handling  

---

## 📁 Project Structure

E-Train-Ticket-Reservation-Management-System/

│

└── TrainReservationSystemd.java # Single Java file containing the entire project logic

---

## 🚀 How to Run

1. **Clone the repository**
   ```bash

    git clone https://github.com/code4Keerthi/E-Train-Ticket-Reservation-Management-System.git

2. **Navigate into the project folder**

    cd E-Train-Ticket-Reservation-Management-System

3. **Compile and Run**

    javac TrainReservationSystemd.java
   
    java TrainReservationSystemd

4. **🧱 Classes Overview**


| Class Name                | Purpose                                                      |
| ------------------------- | ------------------------------------------------------------ |
| `TrainReservationSystemd` | Main driver class containing all menus and logic             |
| `Admin`                   | Handles admin login and train management                     |
| `User`                    | Stores user details and manages login/signup                 |
| `Train`                   | Represents each train with stops, bhogies, and pricing       |
| `Bhogie`                  | Represents train coaches with seat layout and booking status |
| `Payment`                 | Simulates payment processing and transaction generation      |
| `Cancel`                  | Placeholder for future cancellation logic                    |

## 💡 Key Concepts Used

Object-Oriented Programming (OOP)

Classes and Objects

Arrays and Lists (ArrayList)

Nested loops and conditions

Console input/output with colors

Multithreading (for train movement animation)

Real-time display with LocalDateTime

## 🎥 Train Movement Simulation

The trainmovement() method visually simulates a moving train on the console.

Uses threading and ASCII animation to show the train’s journey between positions, with delays at certain stops.

## 🖥️ Sample Menu Output
---------------------------------------
🚆  WELCOME TO KSKD TRAIN RESERVATION SYSTEM
---------------------------------------
1. Admin 
2. User 
3. Exit
Enter your choice:

## Example Booking Flow

User Menu
1. Book Seat
  
2. Check Price

3. Check Train Stops

4. Check Seat Availability

 5. Check train movement

6. Logout

Enter your choice :
1

Enter the train number to book a seat                   : 1

Enter the Bhogie Type                                   : 1

Seat booked successfully. Proceed to payment.

Processing payment...

Enter amount                                            : 400

Enter payment method    : phonepay

Payment successful.

 Transaction ID: 1001

## 🔮 Future Enhancements

Add real cancellation logic and refund calculation

Save data to files for persistence

Add admin reports (like total revenue, bookings, etc.)

Create GUI or web version using JavaFX or JSP

## 👩‍💻 Author

GitHub Link   
**[Code4Keerthi](https://github.com/code4Keerthi)**


## 📜 License

This project is open-source and free for learning or academic use.


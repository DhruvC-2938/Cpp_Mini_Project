🏨 Hotel Booking System (C++)
📌 Project Description

The Hotel Booking System is a menu-driven, console-based C++ application that simulates basic hotel room management operations.
It allows users to book rooms, calculate bills with tax, checkout guests, and view occupied rooms.

The project demonstrates practical usage of Object-Oriented Programming (OOP) concepts in C++ and is suitable for academic mini-projects.

🎯 Key Features

Multiple room categories:

Single

Double

Deluxe

Room availability tracking

Room booking with:

Number of rooms

Number of nights

Automatic bill calculation with 10% tax

Guest checkout functionality

View currently occupied rooms

Simple and interactive menu system

🛠️ Technologies Used

Programming Language: C++

Core Concepts Applied:

Classes and Objects

Encapsulation (private data members)

Abstraction (public methods)

Arrays

Loops and conditional statements

Platform: Console / Terminal

🧩 Program Structure
Hotel_Booking_System/
│
├── Hotel_Room_Booking.cpp
└── README.md
🧠 OOP Concepts Explained

Class (Hotel)
Represents the hotel and manages room details, pricing, and availability.

Object (h)
An instance of the Hotel class used to access booking and checkout operations.

Encapsulation
Room data (price, availability, occupied rooms) is kept private and accessed only through class methods.

Abstraction
Users interact with the system via menu options without knowing internal data handling.

▶️ How to Compile and Run

Clone the repository:

git clone https://github.com/your-username/hotel-booking-system.git

Navigate to the project directory:

cd hotel-booking-system

Compile the program:

g++ Hotel_Room_Booking.cpp -o hotel

Run the executable:

./hotel
📸 Sample Menu Output
====================================
===== Hotel Booking System =====
1. Book Room
2. Guest Checkout
3. Show Occupied Rooms
4. Exit
====================================
Enter choice:
🧾 Billing Logic

Subtotal = Room Price × Number of Rooms × Number of Nights

Tax = 10% of Subtotal

Grand Total = Subtotal + Tax

🎓 Academic Relevance

This project is ideal for:

C++ Mini Project

OOP Concept Demonstration

Practical Exams & Viva

Beginner-level system design

🚀 Possible Future Enhancements

Store customer details

File handling for permanent data storage

Date-based booking system

Admin and user login

Graphical User Interface (GUI)

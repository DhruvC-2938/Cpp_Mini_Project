Hotel Booking System (C++)
A console-based Hotel Management System built in C++ that automates room reservations, guest checkouts, and occupancy tracking with automated billing calculations.
+2

🏨 Project Overview
Managing room bookings manually can be time-consuming and prone to human errors, such as double bookings or incorrect billing. This project simplifies hotel operations by providing an interactive interface to manage room availability, calculate taxes, and track occupied rooms in real-time.
+3

🚀 Features

Room Booking System: Supports three categories—Single (Rs.1500), Double (Rs.2000), and Deluxe (Rs.4000).


Automated Billing: Automatically generates a professional bill including a 10% tax calculation.


Real-time Availability: Dynamically updates room inventory as guests book or check out.
+1


Occupancy Tracking: View a summary of all currently occupied rooms and the duration of stays.
+1


Input Validation: Built-in checks to prevent invalid selections, overbooking, or invalid stay durations.
+1

🛠️ Technical Highlights

Object-Oriented Programming (OOP): All operations are encapsulated within a single Hotel class.
+1


Data Structure: Utilizes parallel arrays to manage room types, pricing, and availability states.
+1


Menu-Driven Interface: Uses a do-while loop and switch statements for a seamless user experience.
+1

📋 How to Use
Book Room: Select a room type, enter the quantity of rooms, and specify the number of nights. The system will display a Grand Total.
+1

Guest Checkout: Select the room type to check out. The system will update the availability for future guests.


Show Occupied: Quickly view which rooms are currently taken and for how many nights.
+1

Exit: Close the application. Note: As the current version does not use file handling, data is maintained only during program execution.
+1

💻 Installation
Ensure you have a C++ compiler installed (e.g., GCC, Clang, or MSVC).

Download main.cpp.

Compile the code:

Bash
g++ main.cpp -o HotelSystem
Run the executable:

Bash
./HotelSystem
👥 Contributors

Group No: 7 


Presented By: Pranav Nair, Mahek Yadav, Pratik Swain, Dhruv Chavda 
+1

🔮 Future Improvements

Persistence: Implementation of file handling to save data permanently.
+1


Guest Records: Tracking customer names, contact IDs, and booking history.
+1


GUI: Developing a graphical user interface using modern frameworks.

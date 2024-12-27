Hotel Booking System
A simple Python-based hotel booking system that allows users to manage room reservations, view customers, and check room availability. This script uses text file storage to persist booking information and provides basic functionality for a small-scale hotel operation.

Features
Room Booking:

Select a room type (Single, Double, Suite).
View available rooms.
Book a room for specific dates.
Validate date inputs and ensure room availability.
View All Customers:

Display a list of all booked customers with their details.
Room Availability:

Dynamically check room availability for the chosen dates.
File Storage:

All customer data is saved in a file (customers.txt) for persistent storage.
Interactive Menu:

A simple text-based menu guides users through the available options.
Installation
Clone the repository or copy the script.
Ensure Python 3.x is installed on your machine.
Usage
Run the script:
bash
Copy code
python hotel_booking_system.py
Follow the on-screen menu:
Book a Room: Choose room type, check-in and check-out dates, and confirm booking.
View All Customers: See a list of all booked customers and their details.
Exit: Exit the program.
File Structure
customers.txt: Stores booking data persistently in plain text format.
How It Works
Booking:

Input customer details, room type, room number, and stay duration.
Validate the dates and check for room availability before confirming the booking.
Customer Viewing:

Reads data from customers.txt and displays it in a user-friendly format.
Room Availability:

Tracks and ensures rooms are not double-booked by comparing booking dates.
Room Details
Single Rooms: 101, 102, 103, 104, 105
Double Rooms: 201, 202, 203, 204, 205
Suite Rooms: 301, 302, 303
Example Usage
Booking a Room
Enter your name and phone number.
Choose a room type (Single, Double, Suite).
Pick a room number from the list of available rooms.
Enter check-in and check-out dates.
If the room is available, the booking is confirmed.
Viewing Customers
Select the "View All Customers" option from the menu.
View the list of customers and their booking details.
Limitations
Data is stored in plain text format; a database is recommended for scalability.
No support for modifying or canceling bookings.
Basic error handling for user input.
Future Enhancements
Integrate with a database for robust storage.
Add options for canceling or modifying bookings.
Improve user interface with a GUI or web-based system.
Implement advanced search and filtering for customer and room details.
License
This project is open-source and free to use. Feel free to modify and expand it as needed.

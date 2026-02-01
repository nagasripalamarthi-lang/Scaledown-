Restaurant reservation-bot 
🍽️ Restaurant Table Booking System (Python)

A simple command-line based restaurant table booking system built using Python.
The program allows users to select a table type, choose a booking date and time, enter their name, and receive a booking summary after validation.

✨ Features

📋 Displays a welcome message and available table options

🪑 Supports multiple table types:

Single

Couple

Family

📅 Checks date availability

⏰ Validates booking time (5 PM – 11 PM only)

🧾 Generates a booking summary

❌ Handles invalid inputs gracefully

🛠️ Requirements

Python 3.8+

No external libraries required

📂 Project Structure (Example)
restaurant-booking/
│
├── booking.py          # Main program file
├── utils.py            # Helper functions (validation, summaries, etc.)
├── README.md           # Project documentation

▶️ How to Run

Clone or download this repository

Open a terminal in the project folder

Run the program:

python booking.py

🧑‍💻 How It Works

Welcome Screen

Displays a greeting and available table types

Table Selection

User selects: single, couple, or family

Invalid selections are rejected

Date Input

User enters a date in YYYY-MM-DD format

Date availability is checked

Time Input

Accepts times between 5 PM and 11 PM

Examples of valid input:

8

8 pm

11 PM

Time is internally converted to 24-hour format

Booking Name

User enters the booking name

Confirmation

A booking summary is displayed

⏰ Time Rules
Input	Interpreted As	Valid
5 pm	17:00	✅
11 pm	23:00	✅
12 pm	—	❌
4 pm	—	❌
🧪 Example Output
Welcome to ABC Restaurant!
Available tables: Single, Couple, Family

Select table type (single / couple / family): couple
Enter booking date (YYYY-MM-DD): 2026-02-14
✅ Date is available.

Enter booking time (5 to 11 PM only): 8 pm
Enter booking name: Alex

🎉 Booking Confirmed!
Name: Alex
Table Type: Couple
Date: 2026-02-14
Time: 8:00 PM

# Railway Management System

A Python-based railway management system with MySQL backend that allows users to book tickets, cancel reservations, check fares, and more.

## Features

- **Book Tickets**: Reserve seats on available trains
- **Cancel Bookings**: Cancel existing reservations
- **Check Fares**: View ticket prices before booking
- **View Bookings**: See all your current reservations
- **Train Availability**: Check available trains between stations
- **User-Friendly Interface**: Simple terminal-based menu system

## System Requirements

- Python 3.x
- MySQL Server
- pip (Python package manager)

## Installation

1. **Clone the repository**:
   ```bash
   git clone [repository-url]
   cd railway-management-system
Set up a virtual environment (recommended):

bash
Copy
python3 -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
Install dependencies:

bash
Copy
pip install -r requirements.txt
Database Setup:

Ensure MySQL server is running

Update MySQL credentials in the relevant files:

Replace YOUR_USERNAME with your MySQL username

Replace YOUR_PASSWORD with your MySQL password

Usage
Run the application:

bash
Copy
python3 Main.py
Menu Options
Book a Ticket: Reserve a seat on a train

Cancel a Booking: Cancel an existing reservation

Check Fares: View ticket prices

Show My Bookings: Display all your reservations

Show Available Trains: View trains between stations

Clear Screen: Clean the terminal

Menu: Show this menu again

About: Display system information

Exit: Quit the application

File Structure
Copy
railway-management-system/
├── Assets/
│   └── Train_details.csv          # Train data in CSV format
├── core/
│   ├── __init__.py                # Module initialization
│   ├── Checks.py                  # Validation functions
│   ├── InsertData.py              # Database insertion functions
│   ├── User_Functions.py          # User operations
│   └── Other.py                   # Common utilities
├── Main.py                        # Main application file
└── requirements.txt               # Python dependencies


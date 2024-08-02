# Airline Reservation System

## Description
The Airline Reservation System is a comprehensive C++ application designed to manage customer details, handle flight registrations, and generate tickets. This project showcases the use of Object-Oriented Programming (OOP) principles and file handling in C++.

## Features
- **Customer Management**: Allows the addition and storage of customer information.
- **Flight Booking**: Facilitates the selection and booking of flights to various international destinations.
- **Ticket Generation**: Generates and prints tickets with detailed flight and cost information.
- **File Handling**: Saves and retrieves booking records from a file.

## Technologies Used
- C++
- File Handling
- Object-Oriented Programming (OOP)

## Usage

### Main Menu
Upon running the program, you will be presented with the main menu:

         Indigo Airlines 

         Main Menu

| |
| Press 1 to add the Customer Details |
| Press 2 for Flight Registration |
| Press 3 for Ticket and Charges |
| Press 4 to Exit |
| |


### Options
- **Add Customer Details**: Enter customer details such as ID, name, age, address, and gender.
- **Flight Registration**: Choose from a list of destinations and available flights.
- **Ticket and Charges**: Generate and display the ticket for the booked flight.
- **Exit**: Exit the application.

## Classes and Methods

### Management
- **Constructor**: Calls the `mainMenu()` function.

### Details
- **Attributes**: `name`, `gender`, `phoneNo`, `age`, `address`, `cId`, `arr`.
- **Methods**:
  - `information()`: Prompts the user to enter customer details.

### Registration
- **Attributes**: `choice`, `choice1`, `back`, `charges`.
- **Methods**:
  - `flights()`: Displays available flights and handles the booking process.

### Ticket
- **Inheritance**: Inherits from `Registration` and `Details`.
- **Methods**:
  - `Bill()`: Generates and saves the ticket to a file.
  - `dispBill()`: Displays the ticket from the file.


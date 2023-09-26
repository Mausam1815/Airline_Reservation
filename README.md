# Airline Reservation System

Welcome to the Airline Reservation System, a comprehensive Java-based application for managing flight bookings, customer information, and ticketing services. This system provides an efficient and user-friendly platform for airline administrators and customers alike.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Maven Configuration](#maven-configuration)
- [Usage](#usage)
- [Contributors](#contributors)
- [License](#license)

## Introduction

The Airline Reservation System is designed to streamline the flight booking process and enhance the overall travel experience. Whether you are an airline administrator responsible for managing flights and customer data or a traveler looking to book a flight, this system has you covered.

## Features

### User Authentication

- **Login and Authentication**: The system features secure user authentication, ensuring that only authorized personnel can access administrative functions.

### Administrative Functions

- **Add Customer**: Administrators can easily add new customers to the system by providing customer details, including names, contact information, and gender. All customer data is securely stored in the database.

- **Add Flight**: Administrators can add and manage flight details, including flight names, arrival and departure locations, flight durations, departure dates, and fare information. Flight data is stored in the database for booking purposes.

- **Add Administrator**: System administrators can add new administrators, granting them access to system management functions.

### Customer Services

- **Search Customer**: Customers can search for their details in the system by providing a customer ID. The system retrieves and displays customer information, making it easy for customers to verify their details.

- **Book Flight**: Travelers can search for available flights, select their preferred flight, specify the number of tickets needed, calculate the total fare, and proceed to book tickets. The system generates a unique ticket ID for each booking and records the ticket details in the database.

- **View Ticket**: Customers can view their booked tickets by entering a ticket ID. The system retrieves and displays detailed ticket information, including customer details, flight information, and contact details.

## Technologies Used

The Airline Reservation System leverages a powerful set of technologies and tools:

- **Java**: The core programming language, offering platform independence and robust capabilities for building the application.

- **Swing (Java GUI Toolkit)**: Swing is utilized to create the intuitive graphical user interface (GUI) of the application, ensuring an efficient and user-friendly experience.

- **MySQL Database**: The system relies on the MySQL relational database management system to securely store and manage customer data, flight details, and ticket information.

- **JDBC (Java Database Connectivity)**: JDBC facilitates the connection between the Java application and the MySQL database, enabling seamless data retrieval and storage operations.

- **Logging**: Java's built-in logging system is employed to record events and errors, simplifying debugging and troubleshooting.

- **Maven**: The project is structured and managed using Apache Maven, simplifying project build and dependency management.

## Maven Configuration

The project's configuration details are specified in the `pom.xml` file:

- **Group ID**: `com.mycompany`
- **Artifact ID**: `Airline_Reservation`
- **Version**: `1.0-SNAPSHOT`
- **Packaging**: `jar`
- **Dependencies**: The project relies on external libraries, such as `AbsoluteLayout`, `jcalendar`, and `mysql-connector-j`, which are automatically managed by Maven.

- **Main Class**: The main entry point of the application is defined as `com.mycompany.airline_reservation.Main`.

## Usage

1. Compile and run the Java files using your preferred IDE or the command line.
2. Log in as an administrator or customer to access the respective features.
3. Utilize the provided functionality to add customers, flights, and administrators, search for customer details, book flights, and view booked tickets.

## Contributors

- Mausam Raj

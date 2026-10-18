Project Title: Hotel Booking System

1. Project Introduction: 
The Hotel Booking System is a proposed information system designed to organize guest information, hotel room details, reservations, and payments. This project uses a UML (Unified Modeling Language) class diagram to represent the structure of the proposed system.

The project identifies the main classes, their attributes, methods, and relationships to provide a clear model of how hotel booking system can be organized.

2. Business Idea
Hotels need an organized way to manage guest records, room information, reservations, and payments. Using paper records or separate files can make it difficult to track room availability, retrieve guest information, and manage bookings accurately.

The proposed Hotel Booking System aims to address these challenges by providing a structured model for managing hotel booking information.

3. Project Scope
The project focuses on analysing and modelling the basic operations of a hotel booking system using a UML class diagram.

Functions Included:
* Managing guest information
* Recording room details, room types, prices, and availability.
* Creating, viewing, and cancelling bookings.
* Recording check-in and check-out dates.
* Calculating the total booking cost.
* Recording payment information associated with bookings.

Functional Excluded
* Online payment gateway integration.
* Housekeeping and room cleaning management
* Employee payroll and staff management.
* Restaurant and food ordering servises.
* Development and deployment of a complete working application.

4. Main Classes
The system contains four main classes:

 Guest:
Stores guest information, including guest ID, full name, and phone number. It supports making bookings and updating guest details.

Room: 
Stores room number, room type, price per night, and room status. It supports checking availability and updating room status.

Booking:
Stores booking ID, check-in date, check-out date, and booking status. It supports creating and cancelling bookings and calculating the total cost.

Payment: 
Stores payment ID, payment amount, payment date, and payment method. It supports recording payment information and issuing receipts.

5. Class Relationships
The system contains three main associations:

* Guest and Booking: One guest can have zero or many bookings, while each booking belongs to exactly one guest.
* Room and Booking: One room can be associated with zero or many bookings over time, while each booking refers to exactly one room.
* Booking and Payment: One booking can have zero or one payment in this model, while each payment belongs to exactly one booking.

These relationships describe how guest records, room reservations, and payment records are connected.
   

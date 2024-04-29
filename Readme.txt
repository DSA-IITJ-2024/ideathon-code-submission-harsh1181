# Bus Reservation System

This is a C++ program for a Bus Reservation System. It allows users to register, update, and delete their profiles, while also providing functionality for managing buses, drivers, routes, reservations, and seat allocation.

## Features

- User Registration and Management
  - Create user profile
  - Update user profile
  - Delete user profile
  - View all user profiles

- Bus Management
  - Add bus information (number, seats, driver, route, arrival/departure times, passengers, payment)
  - Update bus information
  - Delete bus information
  - Display all bus information

- Driver Management
  - Add driver information (name, bus number, address, ID, CNIC)
  - Update driver information
  - Delete driver information
  - Display all driver information

- Route Management
  - Create new route
  - Update route
  - Delete route
  - View all routes

- Reservation Management
  - Create new reservation
  - Update reservation
  - Delete reservation
  - View all reservations

- Seat Management
  - Reserve seat
  - Update seat reservation
  - Cancel seat reservation
  - Display reserved seats

## Classes

1. *User*: Represents a user of the system. Provides functionality for user registration, updating, and deletion.

2. *Driver*: Represents a bus driver. Provides functionality for adding, updating, deleting, and displaying driver information.

3. *Bus*: Represents a bus. Provides functionality for adding, updating, deleting, and displaying bus information.

4. *Seat*: Represents a seat on a bus. Provides functionality for reserving, updating, canceling, and displaying reserved seats.

5. *Route*: Represents a bus route. Provides functionality for adding, updating, deleting, and displaying routes.

6. *Reservation*: Represents a reservation for a bus. Provides functionality for creating, updating, deleting, and displaying reservations.

7. *MBus*: The main class that provides the user interface and handles the interaction between different components of the system.

## Usage

1. Compile the BusReservation.cpp file using a C++ compiler.
2. Run the compiled executable.
3. Follow the on-screen prompts to navigate through the menu and perform various operations.

Note: The program uses a console-based interface and does not have a graphical user interface (GUI).

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.
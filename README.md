# SQL-DESIGNS
## Overview Of Project
Welcome to my SQL-DESIGNS! This repository contains a sample SQL database designed to demonstrate various database management concepts, schema designs, and SQL queries. 
#The database is built using MySQL and is structured to reflect real-world applications. 

### Key Features:
- Relational database with multiple tables and relationships.
- Includes sample data to help understand the structure and usage.
- Demonstrates advanced SQL features such as stored procedures, triggers,functions and events.

## Tech Stack
- **MySQL** for database management
- **SQL** for querying and data manipulation
- 
## Database Structure
This database includes the following tables:
- `Airlines` – Stores Details of Airline which `passengers` make use of
- `Airplanes` – Stores Details of Airplane which `passengers` use for `Flights`
- `Airports` – Stores Details of Airport which `passengers` took a `Flight`
- `Bookings` – Stores all detail of the booking 
- `Flights` – Stores flight to be detail (this is tricky)
- `Passengers`- Keeps the detail of the passenger

### Example of Relationships:
- The `Flights` table is linked to the `Airplanes` and `Airports` table via a foreign key (`AirplanesID`), (`AirportsID`) accordingly.
- The `Bookings` table is connected to the `Flights` table through a foreign key (`FlightID`).

## Installation Instructions
To get started with this project:

1. Clone the repository:
   ```bash
   git clone https://github.com/Liveeasy/SQL DESIGNS.git

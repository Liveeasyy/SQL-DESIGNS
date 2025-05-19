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

-  ## Entity-Relationship Diagram
You can view or edit the ERD using [MySQL Workbench](https://www.mysql.com/products/workbench/).  
File: `erd/SQL-DESIGNS/airbort Model.mwb` 

### Example of Relationships:
- The `Flights` table is linked to the `Airplanes` and `Airports` table via a foreign key (`AirplanesID`), (`AirportsID`) accordingly.
- The `Bookings` table is connected to the `Flights` table through a foreign key (`FlightID`).

## Installation
1. Clone the repository
2. Import the SQL files into your MySQL server
3. Run the scripts in the following order:
   - `Create Schema.sql`
   - `Create Table.sql`
   - `Insert Data.sql`



## Usage
Execute the provided SQL scripts to set up the database and explore the functionalities.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License.

1. Clone the repository:
   ```bash
   git@github.com:Liveeasyy/SQL-DESIGNS.gitgit

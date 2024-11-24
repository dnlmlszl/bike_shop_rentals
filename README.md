# Bike Rental Shop - FreeCodeCamp Project

This is a solution for the FreeCodeCamp *Learn Bash and SQL by Building a Bike Rental Shop* project, where I created a bike rental management system using PostgreSQL and Bash scripting. This project covers relational database basics and Bash scripting fundamentals for user interaction.

## Project Overview

The *Bike Rental Shop* system allows users to:
- View available bikes for rent.
- Rent a bike, updating its availability in the database.
- Return a bike, marking it available again.

### Database Structure

- **bikes** table: Contains bike details with columns for `bike_id`, `type`, `size`, and `availability`.
- **rentals** table: Logs each rental transaction with references to `bike_id` and customer data.

### How to Run the Project

1. Clone the project repository to your local environment.
2. Import the SQL data into PostgreSQL (if necessary).
3. Execute the `bike_shop.sh` script:
   ```bash
   ./bike_shop.sh
   ```
4. Follow the interactive prompts to rent or return bikes.

### Key Commands and Features

- ** SQL Commands: The project uses SQL for table creation, inserting data, updating records, and querying bike availability.
- ** Bash Commands: Bash handles user inputs, displays menus, and triggers SQL commands to manage rentals.

### Lessons Learned

This project reinforced foundational SQL concepts and introduced me to using Bash for scripting in a practical application.

## Acknowledgements

- **FreeCodeCamp for providing the project guidelines and relational database resources.

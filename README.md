# Celestial Bodies Database

This repository contains a PostgreSQL database schema for managing celestial bodies. The database, named `universe`, includes tables for galaxies, stars, planets, and moons.

## Files

- **universe.sql**: SQL dump file containing the schema and sample data for the `universe` database.

## Instructions

### Importing the Database

1. **Create the Database**:
   - Open your terminal and create a PostgreSQL database named `universe`:
     ```bash
     createdb universe
     ```

2. **Import the SQL File**:
   - Run the SQL commands from `universe.sql` to set up the schema and insert data:
     ```bash
     psql -U freecodecamp -d universe -f universe.sql
     ```

### Exporting the Database

- To export the database, use the following command:
  ```bash
  pg_dump -cC --inserts -U freecodecamp universe > universe.sql
  ```

## Usage

- This database is designed for practice with PostgreSQL and for understanding relational database design. It includes sample data that can be used for testing and development.

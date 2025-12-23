# fcc-postgres-universedb

# Universe Database

This project is part of the **freeCodeCamp Relational Database Certification**.  
It uses **PostgreSQL** to create a database that models a universe with galaxies, stars, planets, moons, and asteroids.

## Database Structure

The database is named **`universe`** and contains the following tables:

- galaxy  
- star  
- planet  
- moon  
- asteroid  

Each table:
- Has a primary key that auto-increments
- Includes a `name` column (VARCHAR and UNIQUE)
- Uses foreign keys to represent relationships
- Uses multiple data types (INT, NUMERIC, TEXT, BOOLEAN)

## Relationships

- A galaxy has many stars  
- A star has many planets  
- A planet has many moons  

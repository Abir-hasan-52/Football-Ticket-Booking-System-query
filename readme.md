# Football Ticket Booking System

## Project Overview

This project is a PostgreSQL-based Football Ticket Booking System designed to manage users, football matches, and ticket bookings. The database uses relational tables, primary keys, foreign keys, and constraints to ensure data integrity and efficient ticket management.

## Database Structure

### Users

Stores information about registered users and administrators.

Fields:

* user_id
* full_name
* email
* role
* phone_number

### Matches

Stores football match information and ticket pricing details.

Fields:

* match_id
* fixture
* tournament_category
* base_ticket_price
* match_status

### Bookings

Stores ticket purchase records and connects users with matches.

Fields:

* booking_id
* user_id
* match_id
* seat_number
* payment_status
* total_cost

## Relationships

* One User can have many Bookings.
* One Match can have many Bookings.
* Each Booking belongs to one User and one Match.

## Features Implemented

* Primary Key Constraints
* Foreign Key Constraints
* Unique Constraints
* Check Constraints
* Data Seeding
* Filtering with WHERE
* Pattern Matching using LIKE and ILIKE
* NULL Handling with COALESCE
* INNER JOIN
* LEFT JOIN
* Aggregate Functions (AVG)
* Subqueries
* Sorting, LIMIT, and OFFSET

## Technologies Used

* PostgreSQL
* SQL

## Author

Abir Hasan .
Software Engineering .
Daffodil International University

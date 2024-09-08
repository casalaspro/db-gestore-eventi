# ER Diagram Excercise
I created a ER Diagram with the website [Supabase](https://supabase.com/).
I discovered that i can't use the ENUM type of value defining the columns af a table. This is unpleasent.

## The tables used

- addresses
- bookings
- events
- locations
- roles
- tags
- users

## The exercise explanation

Our client wants to create a platform for managing the events it organizes.

The management system will allow ```users``` to manage ```events``` and see ```reservations``` related to them. 
There will be 4 types of ```users``` , with different roles: 
- those who can administer all users
- those who can access the management system to create or edit events
- those who can only access the management system without the ability to edit data
- those who do not have access to the management system and can only book events

Each ```event``` may have multiple ```tags``` to define its type.
The client organizes events only in a number of exclusive ```locations``` that through the management software he wants to keep an eye on at all times, to understand what events will be held in each of them.

🎯 Objective.
Design the database for the platform in question, creating the ER diagram and then performing the queries provided.


# WitleShop Online Retail System

## About
This assignment is a complete database design for WitleShop, a South African online retail company. The project covers everything from identifying entities and relationships to writing the SQL code that creates the database tables. All business rules from the case study have been applied.

## What is included
- Entity list with attributes, primary keys and foreign keys
- Entity-Relationship Diagram showing relationships and cardinality
- SQL script to create all tables
- Explanation of design choices and business rules

## Main entities
Customer, Customer Address, Supplier, Product, Order, Order Line, Payment, Delivery

## Key rules implemented
- Customers must register before ordering
- One customer can have multiple delivery addresses
- One order has exactly one payment
- One order has exactly one delivery
- Delivery is linked to one of the customer's saved addresses
- Email addresses are unique

## Tools used
- Lucid chart for ERD diagram
- Crow's Foot notation for cardinality
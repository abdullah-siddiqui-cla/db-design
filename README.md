# Exercise Plan: Database Schema Design
## Scenario: Define Requirements
A library system needs a database to manage its operations. The system must track:

- Books and their details (title, author, genre, publication year).
- Members who borrow books (name, contact, membership date).
- Borrowing transactions (which member borrowed which book and when).
- Books can be authored by multiple authors.

## Step 1: Identify Entities
Based on the requirements above, list down the entities we'll have in the system as tables/collections.

## Step 2: Define Relationships
Model the relationships between entities.

- Each book can have multiple authors (Books ↔ Authors: Many-to-Many).
- A member can borrow multiple books (Members ↔ Transactions: One-to-Many).
- Each borrowing transaction is associated with one book (Books ↔ Transactions: One-to-Many).

## Goal
- Entity List: List of tables/collections and their attributes.
- Relationships: Model all the relationships in the tables/collections
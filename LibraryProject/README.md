# Django Models Project

## Project Overview

This project demonstrates advanced model relationships in Django, showcasing the use of **ForeignKey**, **ManyToMany**, and **OneToOne** relationships in a real-world scenario.  
The project is built on a Django framework and serves as a learning exercise to understand how to model complex data relationships efficiently.

The main goal of this project is to simulate a **library management system**, including authors, books, libraries, and librarians. This project allows users to explore Django’s powerful ORM capabilities, query relationships, and understand how different entities interact in a relational database.

---

## Features

1. **Author and Book Relationship**  
   - One `Author` can write multiple `Book` instances (ForeignKey relationship).  
   - Each `Book` belongs to exactly one `Author`.

2. **Library and Book Relationship**  
   - A `Library` can hold multiple books, and a `Book` can belong to multiple libraries (ManyToMany relationship).  
   - Demonstrates how to model many-to-many relationships effectively in Django.

3. **Librarian and Library Relationship**  
   - Each `Library` has exactly one `Librarian` (OneToOne relationship).  
   - Shows how to enforce a strict one-to-one mapping between entities.

---

## Project Structure


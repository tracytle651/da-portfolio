# Bookstore Operational Database Design & Analysis

This project was developed for my Databases course at Trinity University. It showcases the end-to-end design of an operational relational database for a **hypothetical used bookstore** called *The Story Keeper*. The goal was to simulate real-world business processes such as inventory control, employee transactions, customer engagement, and marketing operations — and to analyze those processes through structured SQL queries.

---

## Project Objective

- Translate a business case into a normalized relational database schema
- Populate the system with realistic sample data
- Develop SQL queries to support data-driven decision-making
- Address business questions involving revenue, sales, and customer behavior

---

## Business Scenario

*The Story Keeper* is a used bookstore that buys and sells used, rare, and out-of-print books across a variety of categories. The store uses a multi-warehouse inventory system, promotes its books via social media, and keeps detailed records of customer interactions, purchases, and staff checkout activity.

The database was designed to support four key functional areas:
- **Operations**: Track and manage inventory and book sales
- **Marketing**: Handle social media advertisements and track delivery to customers
- **Finance**: Calculate profit based on purchase vs. selling prices
- **HR Management**: Record employee information and work activity

---

## Database Structure

The system includes the following major entities:

- `UsedBook`: Includes ISBN, title, author, publisher, language, condition, price, and warehouse info
- `Category`: Each book can belong to multiple categories
- `Customer`: Stores buyer/seller contact information
- `Employee`: Processes checkout carts
- `CheckoutCart`: Connects purchases with customers and employees
- `Warehouse`: Stores stock and location details
- `Advertisement`: Linked to individual books and delivered to customers

The schema was normalized to 3NF and built using appropriate primary and foreign key constraints. Sample data includes customer profiles, book inventory, promotional post URLs, employee records, and sales history.

---

## Research Questions

Three business questions were explored using SQL queries. Full implementations can be found in the SQL script (`Tracy - SQL Script.sql`):

1. **Revenue Analysis by Category**  
   Identify the revenue generated from each book category based on sales and pricing data.

2. **Top 10 Best-Selling Books**  
   Rank book titles by total units sold to highlight customer preferences and sales performance.

3. **Customer Behavior Report**  
   For each customer, provide a breakdown including:
   - Total books purchased
   - Total books sold
   - Number of advertisements received

---

## Files in This Repository

| File | Description |
|------|-------------|
| `Tracy - SQL Script.sql` | Full SQL script containing schema definitions, data inserts, and queries |
| `Final_Project_Description.docx` | Project report including bookstore description, business logic, and schema explanation |

---

## Key Learnings

- Translated real-world business processes into a logical data model
- Designed a multi-entity relational schema with normalized structure
- Applied SQL to derive insights for marketing, operations, and finance
- Strengthened my ability to communicate technical data solutions clearly

---

📁 [← Back to Portfolio Homepage](../README.md)

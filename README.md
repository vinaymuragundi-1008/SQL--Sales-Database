**🌐 Retail Sales Management System(SQL Project)**

**📌 Project Overview**

A Retail Sales Management System is a database-driven project designed to manage, track, and analyze sales activities within a retail store. The primary goal of this project is to provide an efficient system that stores Sales-related data, manages inventory, tracks customer purchases, and generates useful business insights. By using SQL as the core technology, the system ensures structured data storage, fast querying, and reliable reporting.

**🎯 Main Objectives**

	•	Store customer details (name, city, email) in a structured way.
	•	Maintain a catalog of products (name, category, price).
	•	Record sales transactions using orders and order items.
	•	Ensure data integrity with primary keys, foreign keys, and constraints.
	•	Generate business insights using SQL queries (joins, aggregates, filters).

**🧱 Core Database Structure**

In SQL, the retail sales system is usually built with related tables like:
	1.	customers
	•	customer_id (PK), name, city, email
	•	Stores who is buying.
	2.	products
	•	product_id (PK), name, category, price
	•	Stores what is being sold.
	3.	orders
	•	order_id (PK), customer_id (FK), order_date, total_amount
	•	One record per order placed by a customer.
	4.	order_items
	•	order_item_id (PK), order_id (FK), product_id (FK), quantity, subtotal
	•	Line-level details of each product inside an order.

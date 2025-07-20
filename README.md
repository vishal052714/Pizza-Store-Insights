# 🍕 Pizza Sales SQL Analysis Project

This project is based on a pizza sales database and explores various SQL queries to derive meaningful insights from customer orders, pizza details, and sales trends. The dataset is structured in a relational format across multiple tables including `orders`, `order_details`, `pizzas`, and `pizza_types`.

---

## 📁 Dataset Schema Overview

- **order_details**
  - `order_details_id`
  - `order_id`
  - `pizza_id`
  - `quantity`

- **pizza_types**
  - `pizza_type_id`
  - `name`
  - `category`
  - `ingredients`

- **pizzas**
  - `pizza_id`
  - `pizza_type_id`
  - `size`
  - `price`

- **orders**
  - `order_id`
  - `date`
  - `time`

---

## 📊 SQL Questions Included

The project includes 30 SQL-based questions, categorized into three levels:

### 🟢 Basic Level
1. List all unique pizza sizes available.
2. Retrieve all orders placed on a specific date.
3. Find the total number of pizzas sold.
4. Show the name and category of all pizza types.
5. Display all pizzas with a price greater than ₹500.
6. List all pizzas along with their size and price.
7. Count the number of different pizza types.
8. Show the total quantity of each pizza sold.
9. Find the details of the most expensive pizza.
10. List all distinct ingredients used in any pizza.

### 🟡 Intermediate Level
11. Find total revenue generated from all orders.
12. Display the top 5 most ordered pizza types.
13. Calculate the average price of pizzas by size.
14. Get all pizza types that contain “cheese” in their ingredients.
15. List the number of orders per day.
16. Find the pizza with the highest total sales (quantity × price).
17. Show the number of times each pizza type was ordered.
18. Retrieve all orders that include a "Veggie" category pizza.
19. List pizzas that were never ordered.
20. Get the time of the first and last order on a specific date.

### 🔴 Advanced Level
21. Calculate total sales (in ₹) per pizza category.
22. Find the most popular pizza size for each category.
23. Rank pizzas by revenue generated.
24. Retrieve customers who ordered more than 10 pizzas in a single order.
25. Display the monthly revenue trend.
26. Find the pizza type with the widest variety of sizes.
27. Calculate average quantity ordered per pizza per day
28. Determine the category with the highest revenue.
29. Show the hourly distribution of pizza orders.
30. Find the least ordered pizza type and its total sales.

---

## ⚙️ Technologies Used

- **SQL** (Structured Query Language)
- **MySQL / PostgreSQL** (Compatible with both)
- **DB Diagram** for schema design (based on the uploaded image)

---

## 🧠 Key Learnings

- Writing and optimizing SQL queries
- Performing data aggregation and transformations
- Gaining insights from relational data
- Real-world schema analysis and reporting

---

## ✅ How to Use

1. Clone the repository.
2. Import the dataset and schema into your SQL environment.
3. Run each query from the question set to analyze insights.
4. Optionally, visualize results using BI tools (Power BI, Tableau, etc.)

---

## 📌 License

This project is for educational and portfolio purposes.

---

## 👤 Author

**Vishal Singh**  
Aspiring Data Analyst  
Connect with me on [LinkedIn](linkedin.com/in/vishal-singh-81187426b)

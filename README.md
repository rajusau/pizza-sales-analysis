# Pizza Sales Analysis SQL Project

## Project Overview
This project involves analyzing pizza sales data using SQL. The database `pizzahut` was created using data imported from four CSV files. The analysis covers various aspects of pizza sales, including total revenue, most popular pizzas, and revenue distribution.

## Database Schema
The database `pizzahut` includes the following tables:
- **pizzas:** Contains details about each pizza, including ID, type, size, and price.
- **pizza_types:** Provides information about different pizza types, including ID, name, category, and ingredients.
- **orders:** Records information about each order, including ID, date, and time.
- **order_details:** Links orders to pizzas and includes the quantity of each pizza ordered.

## Data Analysis
### Basic Questions
- **Total number of orders placed**
- **Total revenue generated from pizza sales**
- **Highest-priced pizza**
- **Most common pizza size ordered**
- **Top 5 most ordered pizza types**

### Intermediate Questions
- **Total quantity of each pizza category ordered**
- **Distribution of orders by hour of the day**
- **Category-wise distribution of pizzas**
- **Average number of pizzas ordered per day**
- **Top 3 most ordered pizza types based on revenue**

### Advanced Questions
- **Percentage contribution of each pizza category to total revenue**
- **Cumulative revenue generated over time**
- **Top 3 most ordered pizza types based on revenue for each pizza category**

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/pizza-sales-analysis.git
2. Import the CSV files into MySQL Workbench.
3. Run the SQL scripts provided in the folder to create tables and insert data.
4. Execute the queries to analyze the data.

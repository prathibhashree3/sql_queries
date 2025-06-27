E-Commerce SQL Project

This project demonstrates how to use SQL to manage and analyze data for a sample e-commerce business. It includes customer and order data, various queries, views, and performance optimization using indexes.

 Dataset Description
sample_customers.csv (50 rows)
customer_id: Unique ID
  first_name,last_name: Name of customer
  email: Email address
  signup_date: Date joined
  total_orders: Total orders made
  total_spent: Total money spent
  is_active: 1 = active, 0 = inactive

 sample_orders.csv` (50 rows)
order_id: Unique order ID
customer_id: Links to customer
order_date: Date of the order
order_amount: Amount spent
payment_method: Card, UPI, etc.
order_status: Completed, Cancelled
shipping_city, 'shipping_state': Delivery info


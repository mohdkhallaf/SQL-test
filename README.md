# SQL-test Questions
1. Write a SQL query to find employees whose salary is greater than the average salary of employees in their respective location.

Table Name: Employee 
Column Names: EmpID (Employee ID), Emp_name (Employee Name), Manager_id (Manager ID), Salary (Employee Salary), Location (Employee Location)

---

2. Write a SQL query to identify riders who have taken at least one trip every day for the last 10 days.

Table Name: Trip 
Column Names: trip_id (Trip ID), driver_id (Driver ID), rider_id (Rider ID), trip_start_timestamp (Trip Start Timestamp)

---

3. Write a SQL query to calculate the percentage of successful payments for each driver. A payment is considered successful if its status is 'Completed'.

Table Name: Rides 
Column Names: ride_id (Ride ID), driver_id (Driver ID), fare_amount (Fare Amount), driver_rating (Driver Rating), start_time (Start Time) 

Table Name: Payments 
Column Names: payment_id (Payment ID), ride_id (Ride ID), payment_status (Payment Status)

---

4. Write a SQL query to calculate the percentage of menu items sold for each restaurant.

Table Name: Items 
Column Names: item_id (Item ID), rest_id (Restaurant ID)

Table Name: Orders 
Column Names: order_id (Order ID), item_id (Item ID), quantity (Quantity), is_offer (Is Offer), client_id (Client ID), Date_Timestamp (Date Timestamp)

---

5. Write a SQL query to compare the time taken for clients who placed their first order with an offer versus those without an offer to make their next order.

Table Name: Orders 
Column Names: order_id (Order ID), user_id (User ID), is_offer (Is Offer), Date_Timestamp (Date Timestamp)

---

6. Write a SQL query to find all numbers that appear at least three times consecutively in the log.

Table Name: Logs 
Column Names: Id (ID), Num (Number)

---

7. Write a SQL query to find the length of the longest sequence of consecutive numbers in the table.

Table Name: Consecutive 
Column Names: number (Number)
Sample Table -
Number
1
2
3
4
10
11
20
21
22
23
24
30

---

8. Write a SQL query to calculate the percentage of promo trips, comparing members versus non-members.

Table Name: Pass_Subscriptions 
Column Names: user_id (User ID), pass_id (Pass ID), start_date (Start Date), end_date (End Date), status (Status)

Table Name: Orders 
Column Names: order_id (Order ID), user_id (User ID), is_offer (Is Offer), Date_Timestamp (Date Timestamp)

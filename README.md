# SQL Challenge #3: Foodie-Fi 🥑

This repo contains my own SQL solutions for Case Study #3 (Foodie-Fi), part of the [8 Week SQL Challenge](https://8weeksqlchallenge.com/case-study-3/) created by Danny Ma. The full problem statement, dataset and questions can be found on the official website.

## About

Danny and his friends launched Foodie-Fi in 2020, a subscription-based streaming service focused only on food and cooking content. Customers can sign up for a 7-day free trial before choosing a Basic Monthly, Pro Monthly, or Pro Annual plan. Danny wants to use the subscription data to understand the customer journey, measure churn and upgrade patterns, and support future investment decisions with data.

## 📁 Data Model

Two tables are used:

* **plans** — plan_id, plan_name and price for each subscription tier
* **subscriptions** — customer_id, plan_id and start_date for every plan change a customer makes

## 🛠️ SQL Techniques Used

* JOIN (INNER JOIN)
* GROUP BY, aggregate functions (COUNT, AVG)
* Window Functions (LEAD, ROW_NUMBER)
* CTEs (WITH clauses)
* CASE WHEN
* Date functions (DATE_TRUNC, EXTRACT)

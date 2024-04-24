# Project-on-Operation-Analytics-and-Investigating-Metric-Spike
Operational Analytics is a necessary process that involves analyzing a company's end-to-end operations. This analysis helps identify areas for improvement within the company. The role of a Data Analyst is linked closely with various teams, such as operations, support, and marketing, helping them derive valuable insights from the data they collect.

One of the critical aspects of Operational Analytics is investigating metric spikes. This involves understanding and explaining sudden changes in key metrics, such as a dip in daily user engagement or a drop in sales. As a Data Analyst, it is our job to answer these questions daily, making it crucial to understand how to investigate these metric spikes.



Case Study 1: Job Data Analysis

Here, we will be working with a table named job_data with the following columns:

job_id: Unique identifier of jobs
actor_id: Unique identifier of actor
event: The type of event (decision/skip/transfer).
language: The Language of the content
time_spent: Time spent reviewing the job in seconds.
org: The Organization of the actor
ds: The date in the format yyyy/mm/dd (stored as text)




The problems

A)Jobs Reviewed Over Time:
Objective: Calculate the number of jobs reviewed per hour for each day in November 2020.
Task: Write an SQL query to calculate the number of jobs reviewed per hour for each day in November 2020.

B)Throughput Analysis:
Objective: Calculate the 7-day rolling average of throughput (number of events per second).
Task: Write an SQL query to calculate the 7-day rolling average of throughput. Also, explain why you prefer using the daily metric or the 7-day rolling average for throughput.



C)Language Share Analysis:
Objective: Calculate the percentage share of each language in the last 30 days.
Task: Write an SQL query to calculate the percentage share of each language over the last 30 days.

D)Duplicate Rows Detection:
Objective: Identify duplicate rows in the data.
Task: Write an SQL query to display duplicate rows from the job_data table.


Case Study 2: Investigating Metric Spike

Here, we will be working with three tables:

users: Contains one row per user, with descriptive information about that user’s account.
events: Contains one row per event, where an event is an action that a user has taken (e.g., login, messaging, search).
email_events: Contains events specific to the sending of emails.

Weekly User engagement:
Objective: Measure the activeness of users on a weekly basis.
Task: Write an SQL query to calculate the weekly user engagement.

User Growth Analysis:
Objective: Analyze the growth of users over time for a product.
Task: Write an SQL query to calculate the user growth for the product.

Weekly Retention Analysis:
Objective: Analyze the retention of users on a weekly basis after signing up for a product.
Task: Write an SQL query to calculate the weekly retention of users based on their sign-up cohort.
Weekly Engagement Per Device:
Objective: Measure the activeness of users on a weekly basis per device.
Task: Write an SQL query to calculate the weekly engagement per device.

Email Engagement Analysis:
Objective: Analyze how users are engaging with the email service.
Task: Write an SQL query to calculate the email engagement metrics.


Database and tools:
MySQL
MySQL Workbench 8.0 CE


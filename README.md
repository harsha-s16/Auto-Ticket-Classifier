# Auto-Ticket-Classifier

## Problem Statement: Enhancing Support Efficiency by Automatically Categorizing Customer Queries.

## Link to the dataset 📂: https://www.kaggle.com/datasets/thoughtvector/customer-support-on-twitter

## Business Problem 💼:
Business organizations of today get thousands of customer requests from different sources like email, chat, contact forms, and so on. If these requests were handled manually, it would be very inefficient, very much prone to errors, and very expensive. The same problem will occur as a result of delays in routing, which leads to longer resolution times, poor customer experience, and missed SLAs.

It is highly likely that our company, which operates in the e-commerce sector, will set up an automated system to sort the support tickets that come in the given categories. The purpose is to decrease the human workload, to make the first-response times better, and to send the queries to the right departments immediately.

## Importance 🚀:

* Faster ticket triaging leads to customer satisfaction (CSAT) being higher.
* The problems can be solved by the internal agents and they do not have to waste their time in sorting the issues.
* It also reduces misrouting e.g., if the technical queries are accidentally sent to billing then it will be reduced.

## Formulated as an NLP Task 🔎:

This problem can be framed as a multi-class text classification task.

* Input: It is in the form of a text of a customer query/ticket.
* Output: One of several predefined categories (e.g., Billing, Technical, Shipping, Returns, Product Info, cancellations, etc.).

## Dataset Collection Strategy 📚:

For this, we will be using a dataset inspired and derived from real-world support tickets. Hence, we select the dataset named "Customer Support on Twitter" available at Kaggle. It contains tweets by customers and replies by support teams of companies such as Apple, Xbox, etc.

We:

* Are going to get/extract customer-side queries only.
* Manually organize the tickets and group them into 6 to 8 broad support categories.

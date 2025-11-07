## Project Overview

This project aims to automate the classification of customer support tickets into predefined categories (e.g., *Technical Issue*, *Billing Inquiry*) using **Machine Learning** and **Natural Language Processing (NLP)**. By analyzing both structured data (like customer demographics and ticket channel) and unstructured text data (from ticket subjects and descriptions), the goal is to improve ticket routing efficiency, reduce response times, and enhance the overall customer support experience.

Despite the challenges of limited predictive features, this project explores a wide range of techniques, from traditional ML models to advanced deep learning and topic modeling, with the **LSTM model** emerging as the most generalized solution.

## Business Problem

Manually classifying thousands of daily support tickets is slow, inconsistent, and prone to error. Automating this process can lead to:
*   **Faster Resolution:** Tickets are routed to the correct department instantly.
*   **Improved Agent Efficiency:** Agents spend less time triaging and more time solving issues.
*   **Enhanced Customer Satisfaction:** Customers get help from the right expert faster.

## Dataset

The project uses a publicly available **Customer Support Ticket Dataset** from Kaggle.
*   **Source:** [Kaggle: Customer Support Ticket Dataset](https://www.kaggle.com/datasets/suraj520/customer-support-ticket-dataset/data)
*   **Records:** 8,469 support tickets.
*   **Target Variable:** `Ticket Type` (5 classes: Billing Inquiry, Cancellation Request, Product Inquiry, Refund Request, Technical Issue).

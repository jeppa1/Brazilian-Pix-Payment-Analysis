# Brazilian Pix Payments Analysis (2020-2025)

## Project Overview
This project performs an end-to-end Exploratory Data Analysis (EDA) on the usage of **Pix**, the Brazilian instant payment system introduced by the Central Bank in late 2020. 

Using historical data spanning from launch (Nov/2020) to 2025, this notebook investigates how Pix evolved from a simple P2P transfer tool into the dominant payment method for retail and corporate sectors in Brazil.

## Objectives
* **Temporal Analysis:** Visualize the exponential adoption curve and identify growth phases.
* **Segmentation:** Compare P2P (Person-to-Person) vs. B2B/P2B (Business) usage patterns.
* **Value Analysis:** Determine the "Average Ticket" size to understand the nature of transactions across different user types.
* **Regional Impact:** Map transaction volumes across Brazil's five geopolitical regions.

## Tech Stack
* **Language:** Python 3.x
* **Libraries:** Pandas, Matplotlib, Seaborn, NumPy
* **Techniques:** Data Cleaning, Time Series Aggregation, Dual-Axis Plotting, Pivot Tables.

## Key Business Insights
1.  **The Retail Shift (P2B):** While originally designed for P2P transfers, Pix has massively penetrated the retail sector. Transaction volumes for **Person-to-Business (P2B)** have reached **113 Billion**, nearly tying with P2P numbers, indicating Pix has effectively replaced cash/cards for daily expenses.
2.  **Corporate Dominance in Value:** The analysis reveals that **B2B transactions (PJ->PJ)** have the highest Average Ticket (**~R$ 5,850**), suggesting companies are using Pix for significant supply chain and service payments, not just micropayments.
3.  **Hyper-Growth to Stability:** The system saw an explosive **158,000% growth** in financial volume during its first full year (2021) and has since settled into a mature, steady growth phase in 2024-2025.

## File Structure
* `the-evolution-of-instant-payments-in-brazil.ipynb`: The main Jupyter Notebook containing code, visualizations, and commentary.

---
*Author: [Jadson Chagas](https://www.linkedin.com/in/jadson-chagas/)*
*Data Source: Central Bank of Brazil (Open Data BCB)*

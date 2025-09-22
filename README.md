# UPI Transaction Data Analysis Project

## Project Overview

This project analyzes **UPI Transaction Data (2024)** to uncover insights into digital payments across banks, cities, devices, demographics, and transaction purposes. The analysis focuses on **transaction patterns, payment methods, balances, and user behavior** throughout the year.

## Key Features

* Track **monthly transaction volumes and balances** across 2024
* Analyze **city-wise transaction distribution** (Bangalore, Delhi, Hyderabad, Mumbai)
* Study **demographics** (Gender, Age Groups) affecting UPI usage
* Explore **merchant and purpose-based transactions**
* Compare **payment methods and device types**
* Visualize **bank-to-bank transactions** (BankNameSent vs BankNameReceived)

## Dataset Columns

* `BankNameSent`, `BankNameReceived`
* `City`
* `DeviceType`
* `Gender`
* `Age Groups`
* `MerchantName`
* `PaymentMethod`
* `Purpose`
* `TransactionType`
* `TransactionByMonth` (January – December 2024)
* `Amount`, `RemainingBalance`

## Tools & Technologies

* **Language:** Python
* **Libraries:** Pandas, NumPy
* **Visualization:** Line charts, column charts for amount & balance trends
* **Techniques:** Data Cleaning, Aggregation, Exploratory Data Analysis (EDA), Time-Series Analysis

## Analysis Highlights

* **Monthly Transactions (2024):**

  * Average monthly transaction volume \~1.65M INR
  * Peak in **May (1.71M INR)**, lowest in **July (1.61M INR)**
* **City-Wise Breakdown:**

  * Consistent growth across Bangalore, Delhi, Hyderabad, and Mumbai
  * February and May observed higher balances across most cities
* **Demographic Insights:**

  * Both Male and Female users actively contribute
  * Young Adults show highest transaction engagement
* **Device & Payment Method:**

  * Mobile-first usage dominates
  * Wallet & Bank Transfer methods widely adopted

## Project Structure

```
UPI-Transaction-Analysis/
│
├── data/                 # Dataset CSV files
├── notebooks/            # Jupyter notebooks with analysis code
├── visuals/              # Plots and visualizations
├── README.md             # Project documentation
└── requirements.txt      # Python libraries used
```

## Author

**Hitesh Moota**
Data Analyst
📧 [hiteshdataman@gmail.com](mailto:hiteshdataman@gmail.com)
[LinkedIn](https://www.linkedin.com/in/hitesh-moota)

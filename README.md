
# Income & Expense Tracker incl. NoSQL Database built with Streamlit

Have you ever wanted to keep track of your monthly income and expenses but didn't want to use Excel? How about levering the power of Python and the streamlit library to build an interactive web application? To store your monthly reports, we will use the **FREE** NoSQL Database from deta (https://deta.sh).
To visualize the monthly spending, we will use a Sankey Chart from Plotly.


# Expense Tracker App

## Overview

The Expense Tracker App is a user-friendly, web-based application built using Streamlit, a Python library for creating interactive web applications, and a NoSQL database to help users manage their expenses efficiently. Whether you want to keep track of your personal finances or monitor your business expenses, this app provides a convenient and customizable solution.

## Features

### 1. User-Friendly Interface

The Expense Tracker App boasts an intuitive and visually appealing user interface. It allows users to easily input, categorize, and review their expenses, making financial management accessible to individuals with varying levels of tech-savviness.

### 2. Expense Entry

Users can effortlessly record their expenses by entering details such as the expense date, description, category, and amount. The app supports multiple categories, enabling users to organize their expenses effectively.

### 3. Data Visualization

Gain insights into your spending habits with the built-in data visualization tools. The app generates charts and graphs to display expense patterns over time, making it easier to identify areas where you can cut back or allocate more funds.

### 4. Flexible Search and Filtering

Quickly locate specific expenses or filter expenses based on date, category, or description. The search and filter functionalities make it simple to find and review past transactions.

### 5. Data Backup and Restore

Worried about losing your expense data? The app includes a backup and restore feature that allows you to save your expense records and restore them when needed, ensuring your financial history is always secure.

### 6. Secure Authentication

Implement user authentication to protect sensitive financial information. Users can create accounts, log in securely, and ensure that their expense data remains private.

### 7. NoSQL Database

The app utilizes a NoSQL database for storing expense records. This non-relational database provides scalability and flexibility, allowing the application to handle a growing volume of data without sacrificing performance.

### 8. Export and Share

Export your expense data to various formats like CSV or PDF for reporting or sharing with accountants, partners, or stakeholders.

### 9. Customizable Categories

Tailor expense categories to your specific needs. Add, edit, or delete categories to match your unique spending habits.

### 10. Open Source

The Expense Tracker App is open source, allowing developers to contribute to its improvement, customize it for personal use, or integrate it with other financial tools and services.

## Getting Started

To start using the Expense Tracker App, simply clone the GitHub repository and follow the setup instructions provided in the README. You'll be able to deploy the app on your local machine or a web server and begin managing your expenses effectively.


## Demo
![DEMO GIF](https://raw.githubusercontent.com/Sven-Bo/streamlit-income-expense-tracker/master/demo.gif)


## Run the app
```
# vanilla terminal
streamlit run app.py

# quit
ctrl-c
```

## Environment Variables
To run this project, you will need to add the following environment variables
`DETA_KEY`



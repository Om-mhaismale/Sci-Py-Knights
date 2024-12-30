# Sci-Py-Knights
# Finothon 2024: Real-World SMS Data Analysis

## Overview
Welcome to our project repository for **Finothon 2024**! This project focuses on analyzing real-world SMS data to derive insightful financial trends and relationships. We developed this project during the Finothon hackathon to showcase the potential of data analysis in improving financial literacy and decision-making.

## Project Objective
The primary goal of our project was to:
- Analyze SMS data to extract financial information related to credit and debit transactions, loans and EMI amounts.
- Visualize the relationships and patterns in the data using interactive and comprehensive graphs.
- Provide insights into user spending and earning trends.

## Tools and Technologies Used
- **Jupyter Notebook**: For exploratory data analysis (EDA)
- **Google Colaboratory**: For collaborative coding and data analysis.
- **Python**: The core programming language used for data processing and analysis.
- Libraries we used in Python:
  - **Pandas**: For data manipulation and analysis.
  - **NumPy**: For numerical computations.
  - **Scikit-learn**: For statistical modeling and machine learning
  - **Seaborn**: A Python library used for creating statistical data visualizations.

## Features
2. **Data Cleaning and Preparation**
   - Checking for null values, duplications, inconsistencies, proper data type, etc.
   - Process senders address by removing special characters.
   - Process SMS text by removing special characters, extra spaces, and links; converting text to lowercase; and handling inconsistencies in formatting.
   - Removing irrelevant data entries like personal chats.
     
1. **Data Extraction**
   - Frequently used keywords in the SMS.
   - Frequently received messages with senders address.
   - Separated each user SMS based on their phone number
   - Most used payment method and banks by the users
   - Categorizing SMS of each user based on bank related and not bank related
   - Categorized transactions as credit or debit based on keywords and patterns.
   - Calculated total credit and debit amounts, as well as ongoing loans and EMIs, for each user..
   - Most used app by the user.
   - Users expenditure on apps like swiggy, zomato, etc.

3. **Spam Detection**
   - Detection through keyword frequency and pattern matching.
   - Training model with commonly used keywords in spam messages
   
4. **Data Visualization**
   - Created various relational graphs to display:
     - Top 10 users with highest transactions and loan amount.
     - Trends in credited vs. debited amounts.
     - Spending patterns.
     - Correlations between transaction amounts and categories.
     - Bank and not bank related SMS
   - Used Seaborn for creating visually appealing and easy-to-understand graphs.

## Key Insights
- The data revealed user spending habits, peak spending days and the proportion of credited vs. debited transactions.
- Visualizations highlighted areas where users could optimize their financial management.
- Spam detection proved effective in identifying irrelevant messages.

## How to Run the Project
```bash
# Clone this repository
git clone https://github.com/shub15/sms_data_analysis.git

# Open the project in Google Colaboratory or Jupyter Notebook
# Upload your SMS dataset (CSV format) and run all cells
```

## Project Team
- **Team Members**: Shubham Maity, Om Mhaismale
- **Event**: Finothon 2024

## Future Scope
- Enhance the model to:
  - Handle larger datasets efficiently.
  - Improve scalability for diverse SMS patterns.
- Develop a web-based dashboard for real-time financial insights.
- Incorporate better spam detection with large dataset of keywords and integrating it with a system.

## Acknowledgments
We extend our gratitude to the Finothon 2024 organizers for hosting this incredible event and providing us with the opportunity to showcase our skills.

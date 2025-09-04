# Coffee Sales Data Analysis
This project involves an analysis of sales data from a coffee shop. The main objective is to understand customer purchasing behavior, identify popular menu items, determine peak sales periods, and uncover other interesting trends from the transaction data.
  
  # 1. Data Overview
The dataset used for this analysis contains transaction records for coffee and other beverages sold between March 1, 2024, and March 3, 2025. Each record includes the following details:    
  &nbsp;&nbsp;&nbsp;&nbsp;• **hour_of_day:** The hour the transaction occurred (24-hour format).    
  &nbsp;&nbsp;&nbsp;&nbsp;• **cash_type:** The payment method used (all transactions in this dataset are 'card').    
  &nbsp;&nbsp;&nbsp;&nbsp;• **money:** The price of the item.    
  &nbsp;&nbsp;&nbsp;&nbsp;• **coffee_name:** The name of the menu item ordered.    
  &nbsp;&nbsp;&nbsp;&nbsp;• **Time_of_Day:** A categorical division of the day (Morning, Afternoon, Night).    
  &nbsp;&nbsp;&nbsp;&nbsp;• **Weekday:** The day of the week.    
  &nbsp;&nbsp;&nbsp;&nbsp;• **Month_name:** The name of the month.    
  &nbsp;&nbsp;&nbsp;&nbsp;• **Date:** The full date of the transaction.    
  &nbsp;&nbsp;&nbsp;&nbsp;• **Time:** The precise time of the transaction.    

  # 2. Sample Data:
  
    |      |   hour_of_day | cash_type   |   money | coffee_name         | Time_of_Day   | Weekday   | Month_name   |   Weekdaysort |   Monthsort | Date       | Time            |
    |-----:|--------------:|:------------|--------:|:--------------------|:--------------|:----------|:-------------|--------------:|------------:|:-----------|:----------------|
    |    0 |            10 | card        |   38.7  | Latte               | Morning       | Fri       | Mar          |             5 |           3 | 2024-03-01 | 10:15:50.520000 |
    |    1 |            12 | card        |   38.7  | Hot Chocolate       | Afternoon     | Fri       | Mar          |             5 |           3 | 2024-03-01 | 12:19:22.539000 |
    |    2 |            12 | card        |   38.7  | Hot Chocolate       | Afternoon     | Fri       | Mar          |             5 |           3 | 2024-03-01 | 12:20:18.089000 |
    |    3 |            13 | card        |   28.9  | Americano           | Afternoon     | Fri       | Mar          |             5 |           3 | 2024-03-01 | 13:46:33.006000 |
    |    4 |            13 | card        |   38.7  | Latte               | Afternoon     | Fri       | Mar          |             5 |           3 | 2024-03-01 | 13:48:14.626000 |
    |    5 |            15 | card        |   33.8  | Americano with Milk | Afternoon     | Fri       | Mar          |             5 |           3 | 2024-03-01 | 15:39:47.726000 |

  # 3. Key Findings & Observations
From an initial exploration of the data, several interesting points have emerged:  
&nbsp;&nbsp;&nbsp;&nbsp;• **Payment Method:** All transactions within this dataset were paid by 'card'.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Peak Sales Times:** Sales occur throughout the day, with transactions recorded as early as 7 AM and as late as 10 PM.  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;◦ **Morning (Morning):** Busiest hours appear to be between 8 AM and 11 AM.  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;◦ **Afternoon (Afternoon):** This is a consistently busy period, with a high volume of sales from 12 PM to 4 PM.  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;◦ **Night (Night):** Sales continue into the evening, with a significant number of transactions occurring between 5 PM and 9 PM.  
&nbsp;&nbsp;&nbsp;&nbsp;• **Price Adjustments:** The prices of several menu items appear to change over time. This suggests dynamic pricing or updates to the menu.  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;◦ **Americano with Milk:** Initially priced at 33.8, it was later sold for 32.82, and eventually 30.86  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;◦ **Cappuccino:** Started at a price of 38.7, then was adjusted to 37.72, and later to 35.76  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;◦ **Espresso:** Showed multiple price points, including 24.0, 23.02, 18.12, and 21.06  
  # 4. How to Use This Project
  &nbsp;&nbsp;&nbsp;&nbsp;1. **Clone the repository:**  
  &nbsp;&nbsp;&nbsp;&nbsp;2. **Install dependencies** (e.g., if using Python for analysis):  
  &nbsp;&nbsp;&nbsp;&nbsp;3. **Run the analysis:** Open and run the Jupyter Notebook file to see the data processing and visualizations.  

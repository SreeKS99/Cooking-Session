
# Cooking Sessions

This project performs an exploratory data analysis (EDA) on a dataset containing user cooking sessions and orders. It generates visualizations, extracts key insights, and offers business recommendations based on the findings.



## Table of Contents

- Project Overview

- Installation

- Usage

- Data Structure

- Visualizations

- Insights and Recommendations

- Contributing

- License
## Project Overview

The goal of this project is to analyze the relationship between cooking sessions and user orders, identify popular dishes, and explore demographic factors influencing user behavior.

## Installation

1. Clone the repository or download the project files.

2. Navigate to the project directory.

3. Install the required libraries:

`pip install pandas matplotlib seaborn openpyxl`


4. Ensure the dataset merged.xlsx is in the project directory.



## Usage
Run the analysis script:
 
`python cooking_sessions_analysis.py`

The program will load the dataset, clean the data, generate visualizations, and display insights along with business recommendations.
## Data Structure
The dataset should include the following key columns:

### User Data:

- User ID, User Name, Age, Location, Registration Date, Phone, Email, Favorite Meal, Total Orders

### Cooking Sessions:

- Session ID, User ID, Dish Name, Meal Type, Session Start, Session End, Duration (mins), Session Rating

### Order Details:

- Order ID, User ID, Order Date, Meal Type, Dish Name, Order Status, Amount (USD), Time of Day, Rating, Session ID

## Visualizations

The following visualizations will be generated:

1. Orders vs. Cooking Sessions: Scatter plot showing the correlation between the number of cooking sessions and user orders.

2. Top 10 Most Ordered Dishes: Bar plot highlighting frequently ordered dishes.

3. Session Duration by Meal Type: Box plot comparing session durations.

4. Age Distribution by Meal Type: Box plot showing age distribution for different meal types.

## Insights and Recommendations

### Key Insights:

1. Cooking Sessions and Orders: A positive correlation exists—users participating in more cooking sessions tend to place more orders.

2. Popular Dishes: “Spaghetti” and “Grilled Chicken” are the most ordered dishes.

3. Age Demographics: Users aged 25-35 are more engaged in cooking and ordering.

4. Session Durations: Dinner sessions have longer durations compared to other meals.

5. Order Cancellations: Some users exhibit inconsistent behavior with canceled sessions.

### Business Recommendations:

1. Promote Popular Dishes: Increase marketing for “Spaghetti” and “Grilled Chicken.”

2. Loyalty Programs: Offer rewards to highly engaged users.

3. Target Young Users: Focus marketing efforts on users aged 25-35.

4. Reduce Cancellations: Address issues leading to canceled sessions.

5. Dinner Promotions: Offer special discounts for dinner orders.
## Contributing

Contributions are always welcome!

See `contributing.md` for ways to get started.

Please adhere to this project's `code of conduct`.


## License

[MIT](https://choosealicense.com/licenses/mit/)

### How the README Works:
- **Installation**: It provides the necessary steps to install Python dependencies and get the dataset in place.
- **Usage**: Explains how to run the Python script and what to expect from the program.
- **Data Structure**: Lists the columns from the dataset that the program will use for analysis.
- **Visualizations**: Describes the types of visualizations that will be created by the script.
- **Insights and Recommendations**: Summarizes the findings of the analysis and includes business recommendations.
- **Contributing**: Mentions that others can contribute to the project and provides the necessary instructions.
  
This `README.md` file provides a clear guide on how to set up, run, and understand the project. Let me know if you need any further modifications

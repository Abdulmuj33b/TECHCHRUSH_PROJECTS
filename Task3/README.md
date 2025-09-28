#Pizza Place Sales Analysis

##Project Overview

This project analyzes one year of sales data from a fictitious pizza place. The dataset includes order details, pizza types, sizes, prices, and ingredients. The goal is to uncover key insights, evaluate menu performance, and apply forecasting techniques to guide business decision-making.


---

##Dataset

The dataset comes from Pizza+Place+Sales.zip and contains:

Orders.csv → Order IDs, date, and time of orders.

Order Details.csv → Items ordered, linked to orders.

Pizzas.csv → Pizza names, sizes, and prices.

Pizza Types.csv → Categories and ingredients of pizzas.

Data Dictionary → Documentation of all fields.



---

##Key Analyses

1. Sales Performance

Total revenue, total orders, and total quantity sold.

Average pizza price.

Top 5 best-selling pizzas.

Pizza types and sizes that underperform.



2. Customer Behavior

Peak ordering hours.

Sales trends across days of the week.

Monthly and seasonal trends.

Association rules → frequent pizza combinations (bundle opportunities).



3. Forecasting

Future sales prediction for the top-selling pizza item.

Overall restaurant sales forecast.

Seasonality decomposition (weekly + yearly patterns).





---

##Tools & Libraries

Python (Jupyter Notebook)

Pandas / NumPy → Data cleaning and manipulation

Seaborn / Matplotlib → Visualizations

mlxtend → Association rules (Apriori algorithm)

Prophet → Time-series forecasting



---

##Business Insights

Thursday, Friday, Saturday → peak sales days.

Medium and Large pizzas drive the most revenue.

Some specialty pizzas (e.g., certain vegetarian types) perform poorly.

Frequent bundles (e.g., Pepperoni + Barbecue Chicken) can be offered as promos.

Forecasting shows steady growth ahead, with weekend spikes.



---

##How to Run

1. Clone this repository:

git clone https://github.com/your-username/pizza-place-sales.git
cd pizza-place-sales


2. Install dependencies:

pip install -r requirements.txt


3. Open the Jupyter notebook:

jupyter notebook Pizza_Sales_Analysis.ipynb




---

##Conclusion

This project demonstrates how data science + business intelligence can help optimize menu offerings, plan staffing and inventory, and drive strategic decisions in the food industry.


-© Abidoye Abdulmujeeb 


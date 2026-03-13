Used Car Price Analysis

- An exploratory data analysis project investigating the key factors that influence used car prices, conducted using a Kaggle dataset of 5,000 European car sales records.

-Tech Stack: Python | Pandas | NumPy | Matplotlib | Seaborn


- Problem Statement
  - What are the most significant factors that influence used car prices?

- Dataset

- Source: Kaggle — Car_Sales_Info
- Size: 5,000 rows × 7 columns
- Features: Manufacturer, Model, Engine Size, Fuel Type, Year of Manufacture, Mileage, Price


- Sub-Questions

  - How does car age and mileage affect vehicle prices, and which factor has a stronger impact on depreciation?
  - Which car manufacturers retain their value best over time?
  - How does fuel type influence the price of a car?


- Approach

  - Loaded and cleaned the dataset using Pandas
  - Conducted exploratory data analysis (EDA) to identify trends and relationships
  - Used correlation coefficients to measure the strength of relationships between variables
  - Visualized findings using Matplotlib and Seaborn


- Key Findings
Overall

  - Car age and mileage have the most dramatic impact on used car prices
  - Engine size has a positive relationship with price — larger engines command higher prices
  - Fuel type has minimal impact on price across the dataset

- Age vs. Mileage (Sub-question 1)

  - Both car age and mileage are negatively correlated with price — as either increases, price decreases
  - Correlation analysis determined that car age has a stronger impact on depreciation than mileage

- Brand Value Retention (Sub-question 2)

  - Luxury brands retain their value significantly better than mainstream brands
  - BMW and Porsche are the least affected by age and mileage in terms of price depreciation

- Fuel Type (Sub-question 3)

  - Fuel type does not significantly influence price, either positively or negatively
  - Price differences between fuel types were minimal across all manufacturers


- Limitations & Future Work

The dataset reflects European car sales, so findings may not translate directly to the U.S. market — a comparison with a U.S. dataset would strengthen conclusions
A limited number of manufacturers are represented; a broader dataset would provide a more complete picture of depreciation trends
Electric vehicles are absent from this dataset — as EV adoption grows, understanding how electric fuel type affects resale value is an important gap to fill in future analysis


- Screenshots:
![Screenshot](https://github.com/jb00753/Data-Analytics-Project1/blob/main/assets/Screenshot%20(175).png?raw=true)

![Screenshot](https://github.com/jb00753/Data-Analytics-Project1/blob/main/assets/Screenshot%20(176).png?raw=true)

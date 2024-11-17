# **Pizza Sale Data Analysis**

## **Project Overview**
This project aims to analyze pizza sales data and provide insights into the sales performance. By exploring the dataset, key trends and metrics are extracted that can help improve business decisions, like inventory management and marketing strategies.

## **Problem Statements**
The following key questions were addressed in this analysis:
1. **Total Sale of Pizzas**  
   - The total sale of pizzas is calculated by summing the `total_price` column across all records.
2. **Total Quantities Sold in 2015**  
   - The total number of pizzas sold in 2015 is calculated using the `quantity` column filtered by the year from the `order_date`.
3. **Month-wise Pizza Sales**  
   - Identifying which months have the highest pizza sales, utilizing the `order_date` and `total_price` columns.
4. **Pizza Size Analysis**  
   - Determining which pizza size is sold the most and the least by analyzing the `pizza_size` and `quantity` columns.
5. **Pizza Category Analysis**  
   - Identifying which pizza category is sold the most and the least using the `pizza_category` and `quantity` columns.

## **Insights**
- **Total Sale of Pizzas in 2015**: The total sale amount for pizzas in 2015 is **817,860.05**.
- **Total Quantities of Pizzas Sold in 2015**: A total of **49,574** pizzas were sold in 2015.
- **Month-wise Analysis**: More pizzas were sold in the following months:
  - January, March, April, May, July, November.
- **Pizza Size Analysis**: 
  - **Medium** size pizzas were the most sold.
  - **Large** and **Small** sizes had lower sales.
- **Pizza Category Analysis**:  
  - **Classic** pizzas were the most sold category.
  - Other categories had lower sales.

## **Technologies Used**
- **Python** (for data analysis and visualization)
- **Pandas** (for data manipulation and cleaning)
- **Matplotlib/Seaborn** (for data visualization)
- **Jupyter Notebook** (for interactive analysis)

## **How to Run the Project**
1. Clone or download this repository to your local machine.
2. Install necessary dependencies (if not already installed):
   ```
   pip install pandas matplotlib seaborn
   ```
3. Load the dataset (ensure it’s in CSV format) into a **Jupyter Notebook** or Python environment.
4. Execute the Python script or notebook to perform the analysis.


## **Future Improvements**
- Implement additional analysis, such as customer segmentation or geographic sales analysis.
- Use machine learning models to predict future pizza sales trends.

## **Contributions**
Feel free to fork this repository and contribute by improving the analysis, adding new insights, or enhancing the visualizations.

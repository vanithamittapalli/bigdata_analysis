# bigdata_analysis
Big Data Analysis Using PySpark
Project Overview
This project demonstrates Big Data Analysis using PySpark on a Retail Sales Dataset. The dataset is downloaded directly from Kaggle using the kagglehub library. PySpark is used to process and analyze the data efficiently, showcasing its ability to handle large datasets.
Objectives
Load and process a retail sales dataset using PySpark.
Perform descriptive statistical analysis.
Analyze sales performance across product categories.
Identify top-performing categories based on total sales.
Demonstrate scalable big data processing.
Technologies Used
Python
PySpark
KaggleHub
Pandas
Dataset
Dataset: Retail Sales Dataset
Source:
https://www.kaggle.com/datasets/mohammadtalib786/retail-sales-dataset
The dataset contains retail sales transaction information including product categories and sales amounts.
Features
Automatic dataset download from Kaggle.
Data loading using Spark DataFrames.
Dataset schema inspection.
Display of sample records.
Total record count calculation.
Descriptive statistics generation.
Category-wise sales analysis:
Total Count
Average Sales
Maximum Sales
Minimum Sales
Total Sales
Identification of top-performing categories.
Project Workflow
Create a Spark Session.
Download the retail sales dataset.
Load the dataset into a Spark DataFrame.
Display schema and sample data.
Calculate total records.
Generate descriptive statistics.
Perform category-wise aggregation.
Rank categories by total sales.
Display key insights.
Stop the Spark Session.
Sample Output
Total Records Processed
Average Sales per Category
Maximum and Minimum Sales
Total Sales by Category
Top Performing Product Categories
Key Insights
PySpark efficiently processes large datasets.
Sales trends can be identified across categories.
High-performing categories contribute significantly to total revenue.
Aggregation functions provide meaningful business insights.
Distributed processing improves scalability and performance.
How to Run
Install dependencies:
pip install pyspark kagglehub pandas
Run the Python script:
python big_data_analysis.py
Conclusion
This project demonstrates how PySpark can be used for scalable big data analytics. By leveraging distributed processing, organizations can efficiently analyze large retail sales datasets and extract actionable business insights.

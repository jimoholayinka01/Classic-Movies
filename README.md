# Data Analysis: Classic Movies Dataset

This repository demonstrates the process of cleaning a movie dataset, selecting classic movies released before 1935, visualizing the data using Seaborn, Big data analysis using PySpark and finally exporting the dataset into a semi-structured Json data file.

---
1. **Data Cleaning Process**

To ensure the dataset is ready for analysis, the following cleaning steps were performed:

## **2. Filtering for Classic Movies**

To focus on classic movies released before 1935, the dataset was filtered using:

This subset includes only movies that match the criteria for being considered "classic." This helps narrow the scope for a focused analysis.


## **3. Data Visualization with Seaborn**

The cleaned and filtered data was visualized to derive insights. Here are the key plots created:

## **4. Using PySpark to run the large dataset**
A subset of the dataset was runned on PySpark to simulate a process for large dataset to analyse


## **5. Exporting Data to JSON**

After processing and filtering, the cleaned dataset of classic movies was exported to a JSON file for further use:

Outputs data in newline-delimited JSON format, suitable for large datasets.

---

## **6. Conclusion**

This workflow highlights how to:
1. Clean a dataset for accurate analysis.
2. Focus on a specific subset of interest (classic movies before 1935).
3. Use Seaborn for effective visualizations to derive insights.
4. Export the processed data for sharing or further use.

Feel free to explore the code. Cheers

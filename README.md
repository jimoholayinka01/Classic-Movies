# Data Analysis: Classic Movies Dataset

This repository demonstrates the process of cleaning a movie dataset, selecting classic movies released before 1935, visualizing the data using Seaborn while conducting the Exploratory Data Analysis and finally exporting the dataset into a semi-structured Json data file. Recommendations were therefore made for the business based on the insights that was derived from the dataset.

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


## **6. Recommendations**

1. The business can increase audience engagement, by giving more focus and 
promotion to classic Movie title type as it is most engaging to many classic movie 
lovers than Shorts title type.
2. The top 10 highest rated movies can be used for headlining classic collection or 
premium content collection as it demonstrates to be audience favourites and 
critically acclaimed.
3. Drama Sci-Fi genre, Drama Romance genre, and Comedy Drama Family genre 
has large viewers engagement. The business can create genre specific collections 
based on this audience interest.
4. Business can align genre runtimes with audience preferences to recommend 
content for users.  This can simply be achieved by including the runtime data into 
algorithms to recommend films that fit a user’s time constraints or the user’s 
preferences.


---

## **7. Conclusion**

This workflow highlights how to:
1. Clean a dataset for accurate analysis.
2. Focus on a specific subset of interest (classic movies before 1935).
3. Use Seaborn for effective visualizations to derive insights.
4. Export the processed data for sharing or further use.

Feel free to explore the code. Cheers

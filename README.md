# Udemy

# Udemy Courses Data Analysis

This project involves performing data analysis on a Udemy courses dataset using Python and the pandas library.

## Dataset

The dataset used is `Project+7+-+Udemy+Dataset.csv`. It contains information about courses offered on Udemy, including details such as course ID, title, pricing, number of subscribers, reviews, lectures, level, content duration, and publication date.

## Project Goals

The primary goals of this project are to analyze the Udemy dataset using pandas. Specific operations include:

1.  Finding the different subjects for which Udemy is offering courses.
   
2.  Determining which subject has the maximum number of courses.
   
3.  Displaying all courses that are free of cost.
   
4.  Displaying all paid courses.
   
5.  Identifying the top selling courses.
   
6.  Identifying the least selling courses.
   
7.  Displaying all courses of Graphic Design with a price below 100.
   
8.  Listing all courses related to 'Python'.
   
9.  Determining which courses were published in the year 2015.
   
10. Finding the maximum number of subscribers for each level of courses.

## Libraries Used

* pandas

## Code Description

1.  **Import pandas:** The pandas library is imported for data manipulation and analysis.
   
2.  **Load the dataset:** The dataset is loaded into a pandas DataFrame.
   
3.  **Data Exploration:**
   * The code displays the first few rows of the dataset.
4.  **Subject Analysis:**
   * The code finds the unique subjects offered in the dataset.
   * The code counts the number of courses for each subject.
5.  **Filter Courses by Price:**
   * The code filters the dataset to display free courses.
   * The code filters the dataset to display paid courses.
6.  **Analyze Course Popularity:**
   * The code sorts the dataset by the number of subscribers to identify top-selling courses.
   * The code sorts the dataset by the number of subscribers in ascending order to identify least selling courses.
7.  **Filter Graphic Design Courses:**
   * The code filters the dataset to show courses in 'Graphic Design' with a price less than 100.
8.  **Search for Python Courses:**
   * The code filters the dataset to find courses with 'Python' in their titles.
9.  **Filter Courses by Year:**
   * The code converts the 'published\_timestamp' column to datetime objects.
   * The code extracts the year from the 'published\_timestamp' column.
   * The code filters the dataset to show courses published in the year 2015.
10. **Analyze Subscribers by Level:**
    * The code groups the data by 'level' and finds the maximum number of subscribers for each level.

## Results

* The project successfully analyzed the Udemy dataset to provide insights into course subjects, pricing, popularity, and publication years.
   
* Specific queries were addressed, such as identifying free and paid courses, top and least selling courses, and Python-related courses.

## Code Snippets

### Load Dataset

```python
import pandas as pd
data = pd.read_csv(r"C:\Users\gvrk1\Downloads\Project+7+-+Udemy+Dataset.csv")

# 🎢 Roller Coaster Data Analysis Project 📊💻

![Roller-Coaster](https://github.com/tanvirfau/Roller-Coaster-EDA/blob/main/roller-coaster.jpg)

# Objective:
The objective of this project is to explore and analyze a dataset of roller coasters using Python and its data science libraries. Key aspects include understanding roller coaster speeds, heights, locations, and their relationships to different features like inversions, G-forces, and opening years. This analysis is performed through visualizations and exploratory data analysis (EDA), using tools like Matplotlib, Seaborn, and Pandas.

# About the Dataset:
The dataset used in this project provides detailed information on roller coasters across various amusement parks worldwide. The data includes attributes such as:

* Coaster Name: Name of the roller coaster.

* Location: Park or region where the coaster is located.

* Status: Whether the coaster is operating, removed, or under construction.

* Manufacturer: Company that designed and built the coaster.

* Year Introduced: The year the coaster first opened.

* Speed: Maximum speed in miles per hour.

* Height: Maximum height of the coaster in feet.

* Inversions: Number of inversions the coaster has.

* G-force: The G-force experienced on the ride.

# Tools and Libraries Used:
* Python: Programming language used for data analysis.

* Pandas: Library used for data manipulation and analysis.

* Matplotlib & Seaborn: Libraries used for creating visualizations.

* Numpy: Used for numerical operations and data handling.

# Steps Taken:
* Step 1: Data Understanding
We started by exploring the dataset using basic functions such as head(), dtypes, and describe(). This helped in understanding the shape of the data, types of columns, and basic statistics such as the number of roller coasters by year, average speed, and inversions.

Key observations:

Data Shape: The dataset contains 990 rows and 13 columns.

Missing Values: Several columns have missing values, particularly Speed, Height, Location, and G-force.

* Step 2: Data Preprocessing
Dropping Irrelevant Columns: Columns that were not useful for analysis (such as opening dates and cost) were removed.

Handling Missing Values: We explored different methods to handle missing data and cleaned the dataset accordingly.

Removing Duplicates: We checked for and removed any duplicate records, ensuring data integrity.

* Step 3: Feature Exploration (Univariate Analysis)
Various univariate analyses were conducted on key features:

Distribution of Coaster Opening Years: A bar plot of the top 10 years when roller coasters were introduced.

Speed Distribution: Histograms, KDEs, and boxplots to understand the distribution of coaster speeds (mph).

Height Distribution: Visualizations for the distribution of coaster heights.

* Step 4: Feature Relationships (Bivariate Analysis)
We explored the relationship between different features using scatterplots and pair plots:

Coaster Speed vs. Height: Scatterplot to visualize how speed correlates with coaster height.

Pairplot: A pairplot was used to visualize correlations between features such as Speed, Height, Inversions, and G-force.

Key observations:

Data Shape: The dataset contains 990 rows and 13 columns.

Missing Values: Several columns have missing values, particularly Speed, Height, Location, and G-force.

Pairplot: A pairplot was used to visualize correlations between features such as Speed, Height, Inversions, and G-force.

* Step 5: Correlation Analysis
A correlation matrix and heatmap were generated to examine the relationships between the key numerical features (e.g., Speed, Height, G-force, Inversions). For instance, Speed and Height have a positive correlation, while Inversions negatively correlates with Speed.

* Step 6: Asking a Question about the Data
One of the business questions addressed in the analysis was:

"What are the locations with the fastest roller coasters (minimum of 10)?"

We filtered locations with at least 10 coasters and grouped them by the average speed. This provided insights into which amusement parks feature the fastest coasters.

# Key Visualizations:
Top 10 Years of Roller Coaster Introduced:

A bar plot showing the top 10 years when roller coasters were introduced, highlighting the most active periods in coaster development.

* Coaster Speed Distribution:

A histogram and KDE plot to visualize the distribution of coaster speeds in miles per hour (mph).

* Coaster Speed vs Height:

A scatterplot to examine the relationship between coaster speed and height.

* Average Speed by Location:

A horizontal bar plot displaying the average speed of roller coasters by location, considering only those locations with at least 10 coasters.

* Correlation Heatmap:

A heatmap showing the correlation between Speed, Height, Inversions, and G-force.

# Results & Insights:
* Speed Trends: We identified the average speeds of roller coasters across different parks and regions, highlighting the fastest coasters.

* Height vs. Speed: Coasters with higher speeds tend to be taller, but there is no direct linear relationship between these two features.

* G-force & Inversions: Coasters with higher G-force values tend to have more inversions.

# Conclusion:
This project provided valuable insights into the world of roller coasters, including trends in speed, height, inversions, and the locations of the fastest coasters. By visualizing these insights in Power BI, users can easily explore the fascinating world of roller coasters and make data-driven decisions for amusement park design and operations.

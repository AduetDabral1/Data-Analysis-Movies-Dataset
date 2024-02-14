# Data-Analysis-Movies-Dataset

The movie industry is a multi-billion-dollar industry that involves a diverse range of personnel and audiences. You are given a movie dataset. The aim is to explore the dataset and gain insights into various aspects of this industry. The analysis includes pre-processing and cleaning of the dataset, conducting exploratory data analysis, and using statistical techniques to uncover the relationships in the data. Furthermore, some data exploration is done through SQL queries on the Apache Spark platform. To conclude, the same dataset is visualized in the PowerBI.

This report delves into a movie dataset using various analytical techniques to identify factors influencing box office performance. Through data cleaning, exploratory analysis, correlation evaluation, and visualization, we uncover key insights impacting movie success.


## Methodology
<STRONG>1. Data Preparation:</STRONG>  
  - Imported the dataset and necessary libraries.
  - Cleaned data by handling missing values and duplicates.
    
<strong>2. Exploratory Data Analysis:</strong>
  - Analyzed summary statistics to understand data distribution.
  - Compared gross revenue with numerical variables using correlation coefficients and scatterplots.
  - Created a heatmap to visualize relationships between movie features.
    
<strong>3. Feature Engineering:</strong>
  - Converted categorical features to numerical representations for further analysis.

<strong>4. Key Findings:</strong>
  - Budget showed the strongest positive correlation with box office performance.
  - Weak link observed between box office success and critical acclaim via IMDb ratings.
  - Budget and critical score exhibited a negligible correlation.

<center>
  
[![Screenshot-2023-05-10-002056.png](https://i.postimg.cc/VNcYS2sS/Screenshot-2023-05-10-002056.png)](https://postimg.cc/212pMcZm)
</center>

    
## Insights
  - Bigger budgets tend to translate to higher box office returns, potentially due to increased marketing and advertising expenditures.
  - Critical reception (IMDb ratings) appears to have a limited influence on box office success.
  - The relationship between budget and critical score suggests financial resources don't guarantee critical acclaim.

<center>

[![Screenshot-2023-05-10-103418.png](https://i.postimg.cc/ZnDbCR0Z/Screenshot-2023-05-10-103418.png)](https://postimg.cc/4HVk0XzF)

[![Screenshot-2023-05-10-103439.png](https://i.postimg.cc/mZd2ddjq/Screenshot-2023-05-10-103439.png)](https://postimg.cc/MXQSHmhb)
</center>


## Visualization Summary
Users can acquire insights into numerous aspects of movies using the Movie Dataset Dashboard in Power BI, which is created to provide a thorough study of a movie dataset. An overview of the various graphs and visualizations made for the dashboard:

### 1. Distribution of Film Genres:
   This graph shows how various film genres are distributed visually. Understanding the dataset's general genre mix and identifying the most popular genres are both beneficial.

### 2. Top Revenue Generating Films:
   This graph lists the films that bring in the most money. It lists the movie names and their accompanying box office receipts. With the use of this visualization, it is possible to   determine which films have made the most money.
   
 ### 3. Performance of the Director:
   This graph examines the effectiveness of several directors. The names of the filmmakers how many films they have directed and how their films have performed can be visualized here. The most prolific directors in the dataset are easier to find thanks to this visualization.
   
### 4. Movie Production by Country:
   This graph illustrates the production of films in various nations. It displays the film-producing nations. The countries with the highest levels of film production can be found using this visualization.

<center>

[![Screenshot-2023-05-10-001718.png](https://i.postimg.cc/dtpQFLzj/Screenshot-2023-05-10-001718.png)](https://postimg.cc/ppQMYXVm)
</center>

While budget emerges as a crucial factor in box office success, this study highlights the complexity of predicting movie performance. By exploring additional data points and considering qualitative aspects, we can gain a deeper understanding of the multifaceted movie industry and its financial drivers.

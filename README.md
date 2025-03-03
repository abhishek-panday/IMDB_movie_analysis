# IMDB Movie Analysis

**Objective:**

This project analyzes the IMDB Movies dataset to uncover trends, popular genres, and factors influencing movie success. Using Python and libraries like Pandas, NumPy, Matplotlib, and Seaborn, the analysis delivers actionable insights through comprehensive data exploration and visualization.

# Dataset overview
- names: Movie titles
- date_x: Release dates
- score: IMDB ratings
- genre: Genres
- overview: Movie summaries
- crew: Cast and crew information
- orig_title: Original titles
- status: Release status (e.g., released, post-production)
- orig_lang: Original language
- budget_x: Production budgets
- revenue: Box office revenues
- country: Production country

# Analysis Tasks and Questions 

**1. Project Setup and Data Loading**

- What libraries are required for this project, and why are they useful in data analysis?
- Load the dataset. What is the shape of the dataset? What does each row and column represent?
**2. Data Overview and Basic Exploration**
- Use .info() to understand the data types and missing values. What potential issues can you spot?
- Describe the main characteristics of each column using .describe(). What can you infer from the mean, median, and distribution of numerical columns?
**3. Data Cleaning**
- Which columns contain missing values? How would you handle them?
- Are there any columns where data types need conversion (e.g., date, ratings)? Explain your decision.
**4. Univariate Analysis**
- Analyze the distribution of IMDB ratings (score) using a histogram and describe its shape
- What are the most common genres in the dataset? Use a bar chart to show their distribution.
**5. Bivariate Analysis**
- Explore the relationship between budget_x and revenue using a scatter plot.
- Compare IMDB ratings (score) across Country using a boxplot.
- Is there a correlation between the number of votes a movie received and its rating? Create a scatter plot and calculate the correlation coefficient. What can you conclude?
**6. Genre-Specific Analysis**
- Which genre has the highest average rating? Calculate the average rating for each genre and plot the results.
- How does the popularity of genres vary over time? Plot the number of movies released per genre each year.
- Compare budgets and revenues for specific genres.

**7. Year and Trend Analysis**

- How has the average movie rating changed over the years? Plot the average rating for each year.
- Which years had the highest and lowest number of movie releases? Plot the number of movies released each year
- Do certain years show a higher average budget? Analyze the average budget by year and observe any trends.
- Do certain years show a higher average runtime? Analyze the average runtime by year and observe any trends.

**8. Multivariate Analysis**
- Identify the most popular genres in each country using grouped bar charts.
- Analyze the influence of budget_x, genre, and country on revenues using a heatmap.

**9. Insights and Summary**
- Summarize three major insights from the analysis regarding movie trends, genre popularity, and factors affecting movie success.
- Propose additional questions or datasets that could enhance the analysis.
**Additional Questions Based on Dataset**
- Which countries produce the highest-rated movies on average?
- Does the original language (orig_lang) correlate with ratings?
- How does status (e.g., released, post-production) influence ratings or revenues?
# Tools and Libraries Used
- **Python**
- *Pandas*: Data manipulation and analysis
- *NumPy*: Numerical computations
- *Matplotlib*: Data visualization
- *Seaborn*: Advanced visualization




Findings of Some question (That were unable to upload)
# Based on your analysis, what are major insights you learned about movie trends, popular genres, or movie ratings?

**1. Budget and Revenue Correlation:**
There is a strong positive correlation (0.67) between budget and revenue, indicating that movies with higher budgets tend to generate more revenue. This suggests that investing more in movie production is likely to lead to higher financial returns. However, it is important to note that while a higher budget increases the chances of higher revenue, it does not guarantee success. Some high-budget films may still fail to generate expected returns, and there are mid-budget films that perform better than anticipated.

**2. Consistent Movie Ratings Over Time:**
From 1980 to 2020, the average IMDB ratings have remained relatively consistent, showing that movie quality, as measured by user ratings, has not drastically changed over time. However, there has been a slight decline after 2020, which could be attributed to shifting audience expectations, a decrease in movie-going experiences due to external factors (such as the pandemic), or a change in the types of content being produced. This trend suggests that while movie quality has remained stable, audience preferences and expectations are evolving.

**3. Genre-Specific Trends in Budget and Ratings:**
Certain genres like Fantasy, Drama, and Crime tend to receive higher average ratings, while Action movies often have lower budgets compared to Comedy and Drama films. This shows that more dramatic or fantasy-driven films may receive better audience ratings, possibly due to stronger narratives or unique storytelling. In contrast, Action films often have lower production costs but can still generate significant box-office returns, showing that action-based content might be more accessible or widely popular despite its lower production costs.

**4. Seasonal Release Trends and Scores:**
Movies released during summer or the holiday season tend to have higher box office earnings and audience ratings. These periods are strategically chosen for blockbuster films that cater to family and mass audiences.

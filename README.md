# **Exploring Popular Anime: Ratings, Genres, and Episode Counts**

## **Project Overview**

For this project, I analyzed a dataset with 78 popular anime titles. My goal was to explore the anime ratings, genres, episode counts, and anime types to find patterns and interesting similarities.

I wanted to investigate whether anime with more episodes tend to have higher ratings, which genres are the most common, and which anime have the highest scoring overall 

## **Dataset Description**

The dataset used for this was `pop_anime.xlsx`.

It contains 78 anime titles and 9 columns of information:

* Anime name  
* Genres  
* Anime type  
* Number of episodes  
* Airing status  
* Starting and ending dates  
* Episode duration  
* Anime score

**Data Cleaning**

I used Python and Pandas to clean this dataset.

* Checking for missing values.  
* Checking for duplicate records.  
* Removing duplicate rows if any were found.

The original dataset contained no missing values or duplicate rows, so no records needed to be removed.

## 

## **Data Manipulation**

**1\. Sorting**

I sorted the anime by score from highest to lowest to identify the 10 highest-rated anime.

**2\. Filtering**

I filtered the dataset to show anime with ratings above 9.0. This helped me focus on the highest-rated titles.

**3\. Grouping**

I grouped the anime by type, including TV, ONA, OVA, and TV Specials. I calculated the average score, average episode count, and total number of anime in each group.

These operations helped organize the dataset and made it easier to compare different categories.

## **Data Visualizations**

I created four visualizations using Matplotlib and Seaborn.

### **1\. Top 10 Highest-Rated Anime**

This horizontal bar chart compares the ratings of the 10 highest-rated anime.

### **2\. Most Common Anime Genres**

This bar chart shows which genres appear the most in the dataset. Action and Drama were tied for the most common genres.

**3\. Episodes vs. Ratings**

The scatter plot compares the number of episodes with anime ratings. Each point represents an individual anime.

### **4\. Correlation Heatmap**

The heatmap displays the correlation between episode counts and anime scores.

## **Statistical Analysis**

I used descriptive statistics to better understand the dataset.

### **Anime Scores**

* Mean: 8.78  
* Median: 8.73  
* Standard deviation: 0.15

### **Episode Counts**

* Mean: 25.49  
* Median: 13  
* Standard deviation: 30.17

### **Correlation Analysis**

### The correlation was approximately 0.359.

A weak/moderate positive relationship was found within the number of episodes and anime ratings. However, this does not mean that having more episodes causes an anime to get a higher score.

## **Key Findings**

Throughout my analysis, I discovered several interesting things:

1. Action and Drama were the most common genres, each appearing 36 times.  
2. The average anime score was approximately 8.78.  
3. The average number of episodes was approximately 25\.  
4. The correlation between episode counts and ratings was positive, but not particularly strong.

## **Conclusion**

This project helped me practice using Python, Pandas, Matplotlib, and Seaborn to analyze and visualize data.

I learned how to import an Excel dataset, check for missing values and duplicates, clean data, sort and filter information, and group data into categories.

One of the most interesting findings was that the relationship between episode counts and ratings was positive but relatively weak. Overall, this project helped me get a better understanding of how data analysis can be used to find patterns and communicate the findings through visualizations.


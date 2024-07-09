 # YouTube Trending Videos Analysis

## Project Overview
This project analyzes trending YouTube videos in the United States using data science techniques. It explores various aspects of video popularity, engagement metrics, and content characteristics to uncover insights about what makes a video trend on YouTube.

## Data Source
The analysis uses the "USvideos.csv" dataset, which contains information about trending YouTube videos in the United States. This dataset includes various features such as video ID, title, channel title, category ID, publish time, tags, views, likes, dislikes, comment count, and more.

## Key Features
1. **Data Loading and Preprocessing**
   - Utilizes pandas for efficient data handling
   - Cleans and prepares the data for analysis, including handling missing values

2. **Exploratory Data Analysis (EDA)**
   - Provides summary statistics of key numeric features
   - Analyzes the distribution of various video attributes

3. **Feature Engineering**
   - Creates new features like 'contains_capitalized' to indicate titles with capitalized words
   - Calculates title length for further analysis

4. **Visualization**
   - Employs matplotlib and seaborn for creating insightful visualizations
   - Includes pie charts, histograms, scatter plots, and heatmaps
   - Generates a word cloud to visualize common words in video titles

5. **Correlation Analysis**
   - Examines relationships between different numeric features
   - Visualizes correlations using a heatmap

## Key Insights
(You can add specific insights from your analysis here. For example:)
- X% of trending video titles contain capitalized words
- The average length of a trending video title is Y characters
- There's a strong positive correlation between views and likes

## Technologies Used
- Python
- Pandas for data manipulation
- Matplotlib and Seaborn for data visualization
- Scikit-learn for preprocessing
- WordCloud for text visualization


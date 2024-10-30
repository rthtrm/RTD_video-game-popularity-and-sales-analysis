# Video Game Popularity and Sales Analysis

## Project Overview
This project contains a comprehensive analysis of video game popularity trends and sales figures on an online store that offers video games for multiple gaming platforms. The goal of this analysis is to uncover patterns that help determine the success or failure of video games, ultimately providing strategic insights for the sales department to optimize sales strategies for the upcoming year.

### Key Focus Areas:
- **Correlation Between Review Scores and Sales**: Analyzing the relationship between game review scores (from both critics and general users) and their sales performance.
- **Regional Platform Preferences**: Exploring how game platform popularity varies by region, with a focus on platforms originating from specific regions.
- **Genre Preferences Across Markets**: Investigating the similarities and differences in genre preferences between key regions such as North America, Europe, and Japan.
- **Platform-Specific Review Patterns**: Evaluating differences in user-generated review scores across platforms, particularly XBOX 360 and PC.

## Key Objectives

### 1. Identify Factors Affecting Video Game Sales:
We aim to determine the factors most closely associated with high or low video game sales, including user and critic reviews, platform, and game genre.

### 2. Understand Platform Popularity Cycles:
The project seeks to reveal patterns in platform popularity over time. Given that most platforms take years to peak but often lose popularity quickly afterward, this analysis will provide insights into which platforms may still have potential in the coming years.

## Methodology

### Data Cleaning and Preprocessing:
Initial steps involved cleaning the dataset, handling missing values, and preparing the data for analysis. The dataset includes sales data and review scores for games across various platforms and regions.

### Exploratory Data Analysis (EDA):
We performed EDA to visualize sales and review score trends across game platforms, genres, and regions. Key plots were generated to display the relationship between review scores and sales, regional platform preferences, and genre popularity by region.

### Hypothesis Testing:
As part of my standard procedure, I first checked for normality of the data using the **Shapiro-Wilk test**, which allowed me to determine the appropriate statistical tests for further analysis. Since most datasets did not follow a normal distribution, I applied the **Mann-Whitney U test** for non-parametric comparisons:
- **Correlation Analysis**: Tested the correlation between game review scores and total sales figures.
- **Mann-Whitney U Tests**: Used to examine whether significant differences exist in review scores across platforms (e.g., XBOX 360 vs. PC) and genres (e.g., Action vs. Sports).

## Tools & Technologies Used

- **Python** (Pandas, Numpy, Scipy, Seaborn, Matplotlib)
- **Jupyter Notebook** (for code development and presentation)

## Key Findings

1. **Weak Correlation Between Review Scores and Sales**: There is only a weak linear correlation between game review scores (both from critics and general users) and total sales.
2. **Regional Platform Preferences**: Platforms tend to be most popular in their region of origin (e.g., PlayStation in Japan). Each market displays a clear preference for certain platforms.
3. **Genre Preferences by Market**: North American and European markets share similar genre preferences, particularly Action, Sports, and Shooting games. In contrast, the Japanese market favors Role-playing games.
4. **Review Score Differences by Platform**: XBOX 360 games received significantly different average user-generated review scores compared to PC games, as indicated by the Mann-Whitney U test.
5. **No Significant Genre Differences in Review Scores**: The Mann-Whitney U test revealed no significant difference between the average user-generated review scores for Action and Sports games.

## Conclusion

This analysis provides a data-driven understanding of video game performance trends. The findings suggest that while review scores have limited impact on sales, regional preferences for platforms and genres are critical to consider when planning future strategies. Additionally, understanding differences in user perception across platforms can aid in optimizing game releases by region and platform.

## How to Run This Project

1. Clone the repository: `git clone https://github.com/rthtrm/RTD_video-game-popularity-and-sales-analysis.git`
2. Install the required libraries: `pip install -r requirements.txt`
3. Open Jupyter Notebook: `jupyter notebook`

## Contact

If you have any questions or feedback, feel free to reach out to me via LinkedIn.

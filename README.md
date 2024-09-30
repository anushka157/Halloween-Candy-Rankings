# Halloween Candy Rankings - Power BI Dashboard
![image](https://github.com/user-attachments/assets/60acf5a8-6819-4e02-ab15-e9c430d30ad9)

## Project Overview

The **Halloween Candy Rankings** dashboard has been developed for the **Maven Halloween Challenge**. This project aims to identify the top three candies to distribute on Halloween based on a data-driven approach, utilizing online votes ranking 85 types of candy. The goal is to ensure that trick-or-treaters of all tastes find something they'll love.

## Data Description

The dataset used for this project includes information about 85 candies, featuring attributes such as:

- **Competitor Name**: The name of the candy.
- **Price Percent**: The price of the candy expressed as a percentage of the maximum price.
- **Win Percent**: The percentage of votes received by each candy.
- **Sugar Percent**: The sugar content of the candy expressed as a percentage.
- **Attributes**: Binary indicators for characteristics such as chocolate, caramel, fruity, etc.

## Dashboard Visualizations

The dashboard includes several visualizations that present key metrics:

1. **Top 3 Candies Based on Win Percent**
   - A bar chart illustrating the top three candies with the highest win percentage. This visualization helps identify the most popular candies based on user votes.
     - **Top Candies**:
       - Reese's Peanut Butter Cups
       - Reese's Miniatures
       - Twix

2. **Price Percent vs. Win Percent Comparison**
   - A scatter plot comparing `pricepercent` with `winpercent`. This visualization reveals trends in how price affects candy popularity.

3. **Candies Features Distribution**
   - A pie chart showing the distribution of candy attributes (e.g., chocolate, caramel, fruity). This provides a quick overview of common features among the candies.
     - **Feature Breakdown**:
       - Sum of Caramel: 14 (22%)
       - Sum of Chocolate: 38 (19%)
       - Sum of Fruity: 21 (11%)
       - Other features include bar, hard, nougat, peanut, and more.

4. **Top 5 Sugary Candies Based on Sugar Percent**
   - A bar chart highlighting the top five candies with the highest sugar content. This visualization helps identify the sweetest options.
     - **Top Sugary Candies**:
       - Reese's Stuffed with Pie: 0.99
       - Milky Way Simply Caramel: 0.96
       - Sugar Babies: 0.96
       - Skittles Original: 0.94
       - Skittles Wildberry: 0.94

5. **Distribution of Candy Attributes**
   - A stacked bar chart representing the distribution of various candy attributes across different candies. This helps understand which candies offer diverse characteristics.

6. **KPI Cards**
   - Key Performance Indicators (KPIs) displayed as cards, showing:
     - **Total Win Percent**: 4.28K
     - **Average Price Percent**: 39.85
     - **Average Sugar Percent**: 40.68

## Slicers

To enhance interactivity, the dashboard includes several slicers that allow users to filter the data dynamically:

1. **Filter by Price Percent** (`pricepercent`)
   - **Title**: "Filter by Price Percentage (1% - 100%)"
   - **Description**: Filters candies based on their price as a percentage of the maximum price.

2. **Filter by Win Percent** (`winpercent`)
   - **Title**: "Filter by Win Percentage (1% - 100%)"
   - **Description**: Allows filtering of candies based on their popularity (win percentage).

3. **Filter by Sugar Percent** (`sugarpercent`)
   - **Title**: "Filter by Sugar Percentage (1% - 100%)"
   - **Description**: Filters candies based on their sugar content.

4. **Filter by Candy Name** (`competitorname`)
   - **Title**: "Select Candy"
   - **Description**: Enables selection of specific candy names for focused analysis.

5. **Filter by Candy Attributes** (e.g., `chocolate`, `caramel`, `fruity`)
   - **Titles**: "Contains Chocolate", "Contains Caramel", "Contains Fruit Flavor", etc.
   - **Description**: Allows filtering of candies based on specific attributes.

## Instructions for Use

1. **Open Power BI Desktop**: Ensure that Power BI Desktop is installed on your computer.
2. **Load the Dataset**: Import the candy dataset into Power BI Desktop by selecting "Get Data" > "Excel" (or the relevant source) and choosing the dataset file.
3. **Interact with the Dashboard**:
   - Use the **slicers** located on the top right of the dashboard to filter candies by their attributes, including `pricepercent`, `winpercent`, `sugarpercent`, and candy attributes.
   - Hover over visualizations to access detailed tooltips that provide in-depth information about each candy.
4. **Monitor KPI Cards**: Keep an eye on the key metrics displayed in the KPI cards for an overview of the candy dataset.

## Project Objective

By utilizing this dashboard, users can determine the top three candies to distribute on Halloween, backed by comprehensive analysis of their attributes, popularity, price, and sugar content. This data-driven approach helps ensure that the selected candies appeal to a wide variety of tastes and preferences, making the house a favorite stop for trick-or-treaters.

## Conclusion

This Power BI dashboard serves as a valuable tool for presenting and analyzing the candy dataset effectively. By leveraging Power BI’s interactive features, users can explore data, compare attributes, and derive insights to make informed decisions for Halloween candy distribution.

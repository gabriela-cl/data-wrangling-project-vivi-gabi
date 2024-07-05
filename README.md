# data-wrangling-project-vivi-gabi
Project 1 - week 3: 
**Correlations between Stress, Lifestyle & Wellbeing**

Gabriela Clemente de Oliveira & Karoll Viviana López Villegas

The main goal of this project was to apply the learned technics for retrieving, cleaning and analysing Data Frames.

We chose this topic because, besides feeling inspired by it, stress has a huge impact not only on the individual but also on the economy.

Three different data frames were used for this analysis (included in the "data_sources" folder):

1. This dataset contains a global survey responses from www.Authentic-Happiness.com. with 23 attributes describing our lifestyle & behavior, from 07.2015 to 03. 2021:
https://www.kaggle.com/datasets/ydalat/lifestyle-and-wellbeing-data

2. Absenteeism from work due to illness, days per employee per year (merged with 1): https://gateway.euro.who.int/en/indicators/hfa_411-2700-absenteeism-from-work-due-to-illness-days-per-employee-per-year/#id=19398&fullGraph=true (03-07-2024)

3. Negative and Positive Experience Indexes per year (merged with 1): https://news.gallup.com/poll/394025/world-unhappier-stressed-ever.aspx (03-07-2024)

We also applied Web Scraping to extract Statistics Statements for our presentation (for academic and requirement purposes).

**Hypothesis & Findings:**

We decided to explore how daily stress level was related with other variables, regarding 3 main topics: the body, the mind and the interaction and relationship with others. Besides we were curious if this stress level perception, was also related with world wide events. 
We reduce the main data from 2016 to 2020, to include answers across the whole year. It was incomplete for 2015 and 2020. After some cleaning, merging the 3 Datasets and performing some adjustments, we used mainly pivot tables and counting (for categorical values which we had the most) and then transformed this pivot tables in percentages (per row or per column, according to the analysis needs). Then we used several type of graphics for comparing categorical values, as Pie, Bar chart Stacked bar charts, and finally we used Box plots to compare the Work-life balance index with the level of stress.

From our data we could confirm the following hypotheses:

- Stress levels can be experienced differently by gender. Women are more likely to experience higher stress levels.

- High stress levels can reduce human social relations and interactions.
  
- Insufficient income, is related with higher level of stress.

- The stress levels are related to health habits. Stressed people eat less fruits & vegetables, are less active, sleep less hours and have a higher BMI.

- We could not conclude from our data, that the perception of stress can be influenced by external global events. It was not possible to see that people experience more stress globally, for example 2020 (Covid pandemie). It would be may be meaningful to know where the person who answer the survey lived.

Weaknesses: Our main data frame had many categorical data. It would be interesting to have also more numerical data available for further statistical analysis. Besides, it didn't specify the country where the person  answering the survey lives (it only mentions it's a global survey). Therefore we could only used global data to make comparisons, altough this topic is also related whith the conditions people leave (by country). We think that more insightful findinds could been explored and answered using demographic information.

Lins to the presentation: https://docs.google.com/presentation/d/1k0N_-anYytKsmzY3LG-GUFyC0ymjAcfbZ9q0yASVdwM/edit#slide=id.g2ea263c496b_2_47

Link to Kanban (on Monday Board): https://gabrielacloliveiras-team.monday.com/boards/1548354259

# Investigating the Correlation between GDP and Life Expectancy

## Introduction

__Goals__: 

This project aims to analyse the Gross Domestic Product (GDP) and life expectancy statistics to see whether there is a correlation or pattern between a nation's economic wealth (as measured by GDP) and its population's life expectancy. The findings will provide evidence to support the view that an unfair relationship exists between a country's riches and its people's well-being.

__Analysis__: 

To conduct an exploratory data analysis (EDA) for this project, we will:
* Preprocess the data by cleaning and organising it for analysis.
* Calculate relevant statistical measures such as means, medians, and standard deviations for GDP and life expectancy.
* Visualise the data using plots, such as scatter plots, line graphs, or bar charts, to observe any patterns or trends between GDP and life expectancy.
* Conduct correlation analysis to determine the strength and direction of the relationship between GDP and life expectancy.
* Interpret the findings and conclude the presence or absence of a correlation between GDP and life expectancy.


By following these steps, we aim to provide empirical evidence to support the Vice President of Intuition and Systems at IHEAL's claim regarding the correlation or pattern between a nation's GDP and the life expectancy of its people.

## Requirements
- Python 3.x
- Jupyter Notebook
- Libraries: pandas, matplotlib, seaborn

## Analysis

Although the data used for the analysis was not big enough to generalise our findings, as the only countries present are the USA, China, Germany, Mexico, Chile, and Zimbabwe for a time frame of 2000 to 2015, we were, however, able to uncover some interesting trends.

### Distribution of Life Expectancy
![Distribution of Life Expectancy.](<results/Distribution of Life Expectancy.png>)

The graph above displays the distribution of life expectancy across the six different countries of our analysis. The distribution is skewed right and indicates that most countries have their life expectancy fall between 72 and 82 years.

### Life Expectancy and GDP

After examining life expectancy distribution, we tried to investigate how it progressed over time compared to the GDP.

![Life Expectancy and GDP by Country over time](<results/Life Expectancy and GDP.png>)

The above graph is separated into two: above, we have life expectancy over time, and below, GDP over time.
The multi-dimensional nature of the graph captures the relationship between these variables (Life Expectancy and GDP) more nuancedly. The most noticeable trends are, on one hand, those of the USA and China, whose GDP have been increasing from 2000 to 2015. Although the USA's GDP is the highest, China's has never dropped. We can observe an amelioration in their life expectancy, although not as noticeable as their GDP. On the other hand, after a slight decrease between 2000 and 2004, Zimbabwe's life expectancy has seen a sharp increase with no change in its GDP.

### Correlation between Life Expectancy and GDP

We created this scatterplot to further explore the relationship between Life Expectancy (LEABY) and GDP.

![Alt text](<results/LEABY scatterplot.png>)

The points across the graph suggest a correlation except for Zimbabwe, whose GDP is abnormally stable at 0.

## Conclusion

Based on our analysis, we have found the following:

The findings indicate a significant positive correlation between a country's GDP and life expectancy. Countries with higher GDP tend to have higher life expectancies on average. However, it is essential to note that correlation does not imply causation. Other factors like healthcare systems, education, social policies, and living conditions can also influence life expectancy.

It is worth mentioning that while a correlation exists, the Vice President of Intuition and Systems at IHEAL's claim about an "unjust connection" between wealth and well-being requires further investigation. The complex relationship between socioeconomic factors and population health necessitates a nuanced understanding beyond a simple correlation.

In conclusion, our analysis provides compelling evidence supporting the existence of a correlation between GDP and life expectancy. This information can be instrumental in driving discussions and policies to improve individuals' well-being within different nations. However, it is vital to approach the subject with a holistic perspective, considering multiple factors that contribute to a population's health and well-being.

## Acknowledgments

__Data Sources__:

The full datasets can be found bellow:

* GDP Data: The World Bank's national accounts data and OECD National Accounts data files. ([World Bank GDP Data](https://data.worldbank.org/indicator/NY.GDP.MKTP.CD))
* Life Expectancy Data: The World Health Organization's data repository. ([WHO Life Expectancy Data](vhttp://apps.who.int/gho/data/node.main.688))
* The compiled version used in "/data/all_data", to make the analysis was downloaded from [MARGARET GATHONI](https://www.kaggle.com/datasets/margaretgathoni/gdp-dataset-for-learning-visualization)'s Kaggle.

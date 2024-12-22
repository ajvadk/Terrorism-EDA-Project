# Terrorism-EDA-Project
The objective of this project is to conduct an in-depth analysis of the terrorism dataset through Exploratory Data Analysis (EDA). Our aim is to discover valuable insights and recurring patterns within the data. 

## Description
This project conducts an in-depth analysis of the terrorism dataset through **Exploratory Data Analysis (EDA)**. The primary goal is to uncover valuable insights, identify patterns, and understand the underlying factors influencing terrorist activities. Through EDA, we aim to:
- Identify trends over time.
- Pinpoint regions and countries with heightened risks.
- Analyze attack methods, target types, and affected groups.
- Visualize the relationships between different variables using advanced visualization techniques.

## Objective
The objective of this project is to:
- Perform data cleaning and preprocessing to prepare the dataset for analysis.
- Utilize various visualization techniques to extract meaningful insights.
- Identify key patterns, trends, and regions of interest from the data.

## Steps Implemented
1. **Data Cleaning**: Handled missing values, removed irrelevant columns, and prepared the dataset for analysis.
2. **Visualization Techniques**:
   - `sns.countplot`: To visualize categorical distributions.
   - `plt.bar`: To compare numerical values across categories.
   - `plt.pie`: To represent proportional data.
   - `sns.heatmap`: To analyze relationships between variables.
   - `world.plot`: To visualize geographical data.

## Key Findings
### Trends Over the Years
- **2014, 2015, and 2016** witnessed a surge in terrorist attacks, with **2014** being the year with the highest recorded attacks.

### Casualties
- Around **45,000 people were killed** and **41,000 people were wounded** worldwide in **2014** alone.

### Most Affected Regions and Countries
- **Countries**:
  - **Iraq** faced the most attacks (~24,600 in total).
  - **Pakistan** and **Afghanistan** followed closely.
- **Regions**:
  - **Middle East & North Africa**, **South Asia**, and **South America** were the most affected regions.

### Cities
- The most affected cities were **Baghdad**, **Karachi**, and **Lima**.

### Attack Methods and Targets
- **Weapon Types**:
  - The most commonly used weapons were **explosives** and **firearms**.
- **Target Types**:
  - The primary targets were **Private Citizens & Property**, **Military**, and **Police**.

### Groups and Methods
- **Groups**:
  - **Taliban** and **Islamic State of Iraq and the Levant (ISIL)** were the most active terrorist groups.
  - Taliban attacks caused the deaths of ~30,000 people in Afghanistan.
- **Methods**:
  - The Taliban primarily used **bombing or explosives**, targeting police and military personnel.

### Heatmap Analysis
- The heatmap between target type and attack type revealed:
  - **Private Citizens & Property** faced ~20,114 **bombings or explosions**.

## Visualization Methods
The following visualization techniques were employed:
- **Bar Charts**: To compare attacks across years, regions, and countries.
- **Pie Charts**: To depict proportional data like target types and weapon types.
- **Heatmaps**: To uncover relationships between attack types and target types.
- **Geographical Plots**: To map the distribution of attacks worldwide.

## Conclusion
Exploratory Data Analysis (EDA) of terrorism data is instrumental in understanding and addressing global terrorism threats. Key takeaways include:
- **Years 2014, 2015, and 2016** marked a significant rise in terrorist attacks, with 2014 being the peak year.
- **Iraq, Pakistan, and Afghanistan** emerged as the most affected countries, with Iraq facing the highest number of attacks (~24,600).
- The **Taliban** was identified as the most active terrorist group, predominantly targeting **police and military personnel** using **bombing or explosives**.

Utilizing diverse visualization techniques has simplified the complex dataset, enabling us to derive actionable insights. This analysis provides a foundation for further research and strategic measures to mitigate terrorism risks.

## Features
- Comprehensive data cleaning and preprocessing.
- Advanced visualization techniques for insightful analysis.
- Analysis of regional, temporal, and group-specific patterns in terrorism data.

## Technologies Used
- **Programming Language**: Python
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Geopandas

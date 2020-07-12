# A Study of Suicide Rates by Year and Country

**Last updated:** 12-Jul-2020

![Dark](https://www.sane.org/images/easyblog_images/143/a12228b73ec867e8092bb529c347c8be_XL.jpg)
**Source:** https://www.sane.org/


Welcome to my Suicide Rates Exploratory Data Anaylsis (EDA) Project, this is an integral part of my learning for the Intro to Python for Data Analytics course.
In this repository, I will be saving all of my data analytics work on the Suicide Rates Overview datasets.

### Australian Bureau of Statistics 2017 Data
![ABS2017](https://mindframemedia.imgix.net/assets/src/uploads/Infographic-National-summary.png?auto=compress%2Cformat&crop=focalpoint&fit=min&fp-x=0.5&fp-y=0.5&h=1440&ixlib=php-1.1.0&q=50&w=1920&s=09927d817ea2c29b5dc7ee16884d55e3)
**Source:** https://mindframe.org.au/suicide/data-statistics/abs-data-summary-2017

## I. Requirements

1. Go to [Kaggle Datasets](https://www.kaggle.com/datasets) and pick a dataset of your choosing. Preferrably in CSV or TSV format.
2. Open a new Jupyter Notebook and give this Mini Assessment a compelling title.
3. Add two to three paragraphs where you first describe the dataset and then the reason why you chose it.
4. Create a table of contents that holds the general steps of the data analytics cycle.
5. Create a section called **Load Data** and read in your data using pandas. Make sure you use at least one of the additional arguments of the method `.read_csv()`.
6. Create a new section and inspect your data. Finish that section with 4 or 5 sentences on what you what you saw in the data. Any Inconsistencies or issues that where easy to spot since the beginning.
7. Create a new section and get and deal with the missing values. At the end of the new section, write at least two paragraphs explaining the steps you took for dealing with missing values. Make sure you outlined any of the assumptions in your process, e.g. the distribution of X variable was highly skewed so I choose to fill in values using the median instead.
8. Describe and visualise your data. Call this Section Exploratory Data Analysis.
    - Create at least 2 pivot tables and describe what is in it. Your aggregation function, variables chosen, etc.
    - Use at least 2 `.groupby()` methods and explain your logic behind it.
    - Create 7 visualisations showing different variables and combinations of your variables. At least one of them has to be interactive. They should have a title, and labels where appropriate. Explain each one of your charts with at least a paragraph.
9. Write a concluding paragraph summarising what you have done.
10. Add a section called **Future Work** and add at least 5 hypotheses that would be interesting for you to test with that data later on.
11. Create a folder for this mini-assessment. Add a README.md file and explain what your notebook contains. Share the link to your repo with a classmate kindly requesting feedback. Send it to your instructor as well.


## II. Introduction

Suicide is a person's deliberate act of killing oneself. According to the World Health Organisation (2019), every year there are around 800,000 suicides and many more suicide attempts around the world. [Here is the link to access the WHO Suicide Factsheet](https://www.who.int/news-room/fact-sheets/detail/suicide). 

I will like to understand who is the most at risk and to investigate correlations of increased suicide rate amongst cohorts of various social-economic groups.

This compact dataset consists of data recorded from 101 countries spanning across 2 decades (from 1985 to 2016) and contains interesting fields such as:
- Human Development Index (HDI) for the year: A composite index measuring average achievement in three basic dimensions of human development—a long and healthy life, knowledge and a decent standard of living. Defintion sourced from: United Nations Development Program - [http://hdr.undp.org/en/indicators/137506](http://hdr.undp.org/en/indicators/137506).
- GDP for the year
- GDP per capita
- Generation

Besides my passion in data analytics, I am also a non-practising registered nurse (RN), and have an interest in Suicide Prevention and anything related to Mental Health, this is why I chose this dataset for the project.

## III. Table of Contents

I. Requirements
II. Introduction
III. Table of Contents
    1. Load Data
    2. Cleaning and Manipulation
    3. Exploratory Data Analysis
    4. Report Findings
IV. Future Work
V. Repository Structure


### 1. Load Data
The dataset we will be using in this project comes from Kaggle. [Here is the link to access that data.](https://www.kaggle.com/russellyates88/suicide-rates-overview-1985-to-2016)

### 2. Cleaning & Manipulation
This part will depend on the data available.

### 3. Exploratory Data Analysis
This will depend on the data available but we will definitely want to see trends, distributions, max and min values around the peak years, and many averages.

### 4. Report findings
From this EDA, I have learnt that male suicides are much higher than females. The predominate age group of highest suicide count is between 35-54 years.

In terms of change in suicide rate across the globe, there were 2 peaks across the 2 decades, both coinciding with financial crisis. This also aligns with the opposite correlation between suicides vs. GDP.

### IV. Future Work
I will like to carry out the following analyses in the future:

group the countries by continents to see if suicide rates are higher only in certain continents
to analysis if suicide rate is lower in countries with higher HDI
to analysis if suicide rate is higher in countries with lower GDP per capita
to link suicide data with suicide prevention data to see the success rate of intervention
to disprove an occupation with constant high level of stress is a leading factor towards to a suicidal tendency

## V. Repository Structure

[README.md](https://github.com/nsxmags/eda_suicides/blob/master/README.md)

[eda_suicides.ipynb](https://github.com/nsxmags/eda_suicides/tree/master/eda_suicides.ipynb) <-- This is the complete assessment workbook!

[Code Folder](https://github.com/nsxmags/eda_suicides/tree/master/code)
- [Cleaning](https://github.com/nsxmags/eda_suicides/tree/master/code/clean)
- [EDA](https://github.com/nsxmags/eda_suicides/tree/master/code/eda)

[Data Folder](https://github.com/nsxmags/eda_suicides/tree/master/data)
- [Clean Data]()
- [Raw Data](https://github.com/nsxmags/eda_suicides/tree/master/data/raw_data)
    
[EDA Folder](https://github.com/nsxmags/eda_suicides/tree/master/eda)
- [EDA](https://github.com/nsxmags/eda_suicides/tree/master/eda/eda)
- [Chart](https://github.com/nsxmags/eda_suicides/tree/master/eda/chart)
    
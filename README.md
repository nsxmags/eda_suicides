# A Study of Suicide Rates by Year and Country

**Last updated:** 11-Jul-2020

![Dark](https://www.sane.org/images/easyblog_images/143/a12228b73ec867e8092bb529c347c8be_XL.jpg)
**Source:** https://www.sane.org/


Welcome to my Suicide Rates Exploratory Data Anaylsis (EDA) Project, this is an integral part of my learning for the Intro to Python for Data Analytics course.
In this repository, I will be saving all of my data analytics work on the Suicide Rates Overview datasets.

![ABS2017](https://mindframemedia.imgix.net/assets/src/uploads/Infographic-National-summary.png?auto=compress%2Cformat&crop=focalpoint&fit=min&fp-x=0.5&fp-y=0.5&h=1440&ixlib=php-1.1.0&q=50&w=1920&s=09927d817ea2c29b5dc7ee16884d55e3)
**Source:** https://mindframe.org.au/suicide/data-statistics/abs-data-summary-2017

## I. Assessment Requirements

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


## II. Outline

### 1. Introduction

Suicide is a person's deliberate act of killing oneself. According to the World Health Organisation (2019), every year there are around 800,000 suicides and many more suicide attempts around the world. [Here is the link to access the WHO Suicide Factsheet](https://www.who.int/news-room/fact-sheets/detail/suicide). 

I will like to understand who is at risk and to investigate correlations of increased suicide rate amongst cohorts of various social-economic groups.

This compact dataset consists of data recorded from 101 countries spanning across 2 decades (from 1985 to 2016) and containts interesting fields such as:
- Human Development Index (HDI) for the year: A composite index measuring average achievement in three basic dimensions of human development—a long and healthy life, knowledge and a decent standard of living. Defintion sourced from: United Nations Development Program - [http://hdr.undp.org/en/indicators/137506](http://hdr.undp.org/en/indicators/137506).
- GDP for the year and GDP per capita
- Generation

Besides my passion in data analytics, I am also a non-practising registered nurse (RN), and have an interest in Suicide Prevention and anything related to Mental Health, this is why I chose this dataset for the project.

## III. Table of Contents

1. [Code Folder](https://github.com/nsxmags/eda-covide19/tree/master/code)
    -[Cleaning Folder](https://github.com/nsxmags/eda-covide19/tree/master/code/clean)
    -[EDA](https://github.com/nsxmags/eda-covide19/tree/master/code/eda)

2. [Data Folder]()
    - [Clean Data]()
    - [Raw Data]()
    
3. [Reports Folder]()
    - [Charts]()
    


### 2. Load Data
The dataset we will be using in this project comes from Kaggle. [Here is the link to access that data.](https://www.kaggle.com/russellyates88/suicide-rates-overview-1985-to-2016)

### 3. Cleaning & Manipulation
This part will depend on the data available.

[Make sure you outlined any of the assumptions in your process, e.g. the distribution of X variable was highly skewed so I choose to fill in values using the median instead.]

### 4. Exploratory Data Analysis
This will depend on the data available but we will definitely want to see trends, distributions, max and min values around the peak years, and many averages.

[Describe and visualise your data. Call this Section Exploratory Data Analysis.
    - Create at least 2 pivot tables and describe what is in it. Your aggregation function, variables chosen, etc.
    - Use at least 2 `.groupby()` methods and explain your logic behind it.
    - Create 7 visualisations showing different variables and combinations of your variables. At least one of them has to be interactive. They should have a title, and labels where appropriate. Explain each one of your charts with at least a paragraph.
   ]


### 5. Report findings
In the pipeline.

[Write a concluding paragraph summarising what you have done]

### Future Work

# World Happiness Report Analysis Project
I utilized Python (Jupyter notebooks and the Anaconda Libraries Manager) to perfoem Data Consistency Checks and Data Wrangling for datasets pertinent to World Happiness Report. I performed Exploratory Data Analysis(EDA) through different visualizations such as scatterplots, correlation heatmaps, pair plots and categorical plots). Subsequently, I created a Dashboard, presenting my findings using Tableau.

## Background
The World Happiness Report surveys happiness levels around the globe. This is an essential factor in shaping government policies. It assesses the current state of happiness worldwide and illustrates how the study of happiness can contribute to personal and national variations in happiness. 

## Key Questions
- Does the Mean Happiness Score vary from region to region? Are certain regions consistently happier than others?
- Which factor contributes the most towards the Happiness Score of a Country?

## Objectives
- Perform Geopspatial analysis using GeoJson file
- Perform Regression Analysis
- Cluster Analysis using K-Means Algorithm

## Data Source
- [World Happiness Report 2015 to 2023](https://www.kaggle.com/datasets/sazidthe1/global-happiness-scores-and-factors/data) is taken from Kaggle
- The original source is from [World Happiness Report](https://worldhappiness.report/)

## Data Collection
The primary data collection method is Surveys and Interviews. There are two ways this data is collected.
- Face to face interviews (usually for 1 hour)
- Telephone surveys (usually for 30 minutes)

## Sampling 
The number of people and countries surveyed varies year to year, but by and large more than 100,000 people in 130 countries participate in the Gallup World Poll each year. The typical World Poll survey includes at least 1,000 surveys of individuals. In some countries, oversamples are collected in major cities or areas of special interest. Additionally, in some large countries, such as China and Russia, sample sizes of at least 2,000 are collected. Although rare, in some instances the sample size is between 500 and 1,000. They are based entirely on the survey scores, using the Gallup weights to make the estimates representative.

## Limitations
Even though precautions are taken to reduce biasness, there is always a possibility of human error. Since the data is collected from surveys, there is always a possibility for non-response. While conducting surveys, the questions and answers are translated and hence, this is also subject to biasness. Depending on the country, there is always a issue of coverage (scarcely populated areas where transportation is lacking and the general population is not easily reachable).

## Python Libraries utlilized
- pandas
- NumPy
- matplotlib
- scipy
- seaborn
- plotly.express
- folium
- geopandas
- sklearnas
- pylab
- statsmodels.api

## Folders
- 01 Project Management: Project Background
- 02 Data (Data Files are not uploaded owing to their size):
   -  Original Data: Orginal Data in .csv format
   -  Prepared Data: Cleaned Data in .csv format and merged dataframes in .pkl format
- 03 Scripts: Jupyter Notebooks which are utilized as Source Code

## Deliverbles
- [Tableau Dashboard](https://public.tableau.com/views/WorldHappinessReportDataAnalysis_2/SpatialAnalysis?:language=en-US&publish=yes&:sid=&:display_count=n&:origin=viz_share_link)

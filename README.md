## ABOUT ME
Hello! I am Haruka Takagi, welcome to my data science portfolio. I am currently in my final year at the University of Toronto, St. George. In the progress of attaining an Honours Bachelor of Science Degree with a Double Major in Statistics & Economics, and a Minor in Mathematics in May 2023. I have been a Dean's List Scholar at UofT for 2020 & 2021. And was granted the University of Toronto Excellence Award for Research in 2022.

In industry, I have 1 year of experience working as a Machine Learning/Natural Language Processing Engineer at an AI Emotion Recognition company in Tokyo, Japan, as well as internship experience as an Analyst at Bloomberg L.P. 

In academia, I have 3 years of experience working as a Financial Data Analytics/ML/NLP Research assistant on 3 different university research projects with the University of Toronto Munk School of Public Policy, Department of Management and Department of Finance. Currently, I am working on a research project with Professor Charles Martineau, Professor Pat Akey, and Professor Vincent Gregoire as the only undergraduate Co-Author on a Finance working paper examining central bank communication by extracting agreement levels from FOMC transcripts using NLP methods.

I am open to new oppurtunites in Data Scientist roles in Toronto, Ontario, Canada! Please feel free to reach out to me via email if you think I would be a great addition to your team! I'd be happy to hop on a video or phone call to talk about my experiences and projects on this portfolio. I am also open to freelance data science work! Please also send me a message and request, and we can set up a meeting on the prospective projects. 

Resume/CV: [Haruka Takagi's Resume/CV](https://drive.google.com/file/d/1AEEoF__bIFtBDNBSTOxzLm36xlymo_lh/view?usp=sharing) <br />
Linkedin: [https://www.linkedin.com/in/haruka-takagi/](https://www.linkedin.com/in/haruka-takagi/) <br />
Email: haruka.takagi.datascience@gmail.com     
<br />

## TABLE OF CONTENTS

|        | Topic        | Project           |
| ------------- |-------------|-------------|
|1| Data/Statistical Analysis I     | [Housing Sale Price Analysis](https://haruka-takagi-datascience.github.io/data_analysis_I/) |
|2| Data/Statistical Analysis II      | [EU Powersector Analysis](https://github.com/haruka-takagi-datascience/data_analysis_II) |
|3| Econometrics      | [Partisanship & COVID-19](https://haruka-takagi-datascience.github.io/econometrics/) |
|4| Unsupervised Machine Learning      | [Cross Stich Creation from Images](https://haruka-takagi-datascience.github.io/unsupervised_ml/) |
|5| Data Collection      | [Question & Answer Forum Webscraper](https://haruka-takagi-datascience.github.io/data_collection/) |
|6| Data/Text Processing      | [Building a Special Furigana Machine](https://haruka-takagi-datascience.github.io/text_processing/) |
|7| Topic Modelling/Textual Analysis      | [Latent Dirichlet Allocation on FOMC Historical Materials](https://haruka-takagi-datascience.github.io/textual_analysis/) |
|8| Supervised Natural Language Processing      | [Agreement LSTM model on Federal Open Market Committee Meeting Transcripts](https://haruka-takagi-datascience.github.io/supervised_nlp/) |
|9| Static Data Visualization      | [Visualizing Bicycle Theft in Toronto](https://haruka-takagi-datascience.github.io/static_data_visualization/) |

<br />

## PROJECT OVERVIEWS
Below is a description and brief overview for each data science project!

[1. Data/Statistical Analysis I: Housing Sale Price Analysis](https://haruka-takagi-datascience.github.io/data_analysis_I/)<br />
This project explores data from the Toronto Real Estate Board (TREB) on detached houses in Toronto and Missisauga. We will use this dataset to estabilish a multiple linear regression model (MLR) which home buyers can use to predict the sale price of single-family, detached homes. The report settles on the Backwards AIC model for feature selection, and finds location to be the largest swayer of sale price, with the number of bedrooms at second most importance. We also found that taxes does not influence sale price as much as expected. <br />
<br />
**Subject Areas**: Data Manipulation, Exploratory Data Analysis, Feature Selection, Statistical Diagnostics <br />
<br />
<br />
[2. Data/Statistical Analysis II: EU Powersector Analysis](https://github.com/haruka-takagi-datascience/data_analysis_II)<br />
This project is an investigation into the European Union Power Section and its Clean Energy Status. The data used for this report is from EuroStat, and it investigated the 2019 statistics annual electricity data from 2016 to 2018 on the volumes of electricity that have been produced and supplied at the level of the European Union. The overarching finding was that clean renewable energy production integration is going very well and has progressed in the European Union. With specific findings such as, with 95% probability, the true proportion of EU countries that have met their target in 2018 is between 0.21 and 0.44 based on prior information. <br />
<br />
**Subject Areas**:  Data Analysis, Statistical Analysis, Goodness of Fit Test, Bayesian Credible Intervals, etc <br />
<br />
<br />
[3. Econometrics: Partisanship & COVID-19](https://haruka-takagi-datascience.github.io/econometrics/)<br />
In this project, I examine the impact of republican vote share in the US 2020 presidential election and full vaccination percentage on the number of Covid-19 Deaths per 100,000 post Jun 26th, 2021. Economic theory on vaccines as a public good predicts that vaccines will deliver an externality benefit, yielding decreasing returns. Examinations of the current political climate also suggest a bias in vaccine uptake with respect to partisanship. To test the predictions of this theory and public sentiment, I estimate the impact of republican vote share and vaccination rate on the Covid-19 death rate. Increases in republican vote share increase Covid-19 death rates. Increases in vaccination rates decrease Covid-19 death rates. These findings shed new light on the determining factors of individual vaccine decisions, and Covid-19 death prone populations. The project suggests that partisan anti-vaccine sentiment will directly affect their supporting populations negatively. <br />
<br />
**Subject Areas**: Econometrics, Stata <br />
<br />
<br />
[4. Unsupervised Machine Learning: Cross Stitch Creation from Images](https://haruka-takagi-datascience.github.io/unsupervised_ml/)<br />
This project is a vignette that covers functions that can be used to execute k-means clustering on images in a streamlines workflow. This tutorial will take you through the script and functions needed to create a cross stich guideline from any image. <br />
<br />
**Subject Areas**:  Unsupervised machine learning, R. <br />
<br />
<br />
[5. Data Collection: Question & Answer Forum Webscraper](https://haruka-takagi-datascience.github.io/data_collection/)<br />
In this application of webscraping, I built a web scraper that collects the question and best answer to questions from yahoo answers based on a list of search terms. A webscraper like this can be used for several different uses, such as expanding the corpus of an automatic speech recognition model to take into account domain specific words. I also output term frequency inverse document frequency (tf-idf) terms to prepare the corpus for analysis. <br />
<br />
**Subject Areas**: Webscraping, Data Collection, Python, Data Manipulation, Data Analysis. <br />
<br />
<br />
[6. Data/Text Processing: Building a Special Furigana Machine](https://haruka-takagi-datascience.github.io/text_processing/)<br />
In this project I will be creating a special furigana machine that will be able to put these readings on any combination of characters individually. For example, using this machine the program will be able to determine that 今日 is 今:きょ:kyo + 日:う:u. This will be useful to implement in Japanese learning textbooks or a new program that will help learners read any text. <br />
<br />
**Subject Areas**: Morphological Analysis, Text Processing, Python. <br />
<br />
<br />
[7. Topic Modelling/Textual Analysis: Latent Dirichlet Allocation on FOMC Historical Materials](https://haruka-takagi-datascience.github.io/textual_analysis/)<br />
In this project we execute a topic model; latent dirichlect Allocation on the Federal Open Market Committee Historical Materials. These historical materials from the FED cover different areas of monetary policy decision making information. In the end we find 4 topics that are well suited for the Greenbook Historical Materials. The topics are production, lending rates, demand, foreign relations. <br />
<br />
**Subject Areas**: NLP, Textual Analysis, Python, R, Topic Modelling, Data Collection, Data Cleaning, LDA <br />
<br />
<br />
[8. Supervised Natural Language Processing: Agreement LSTM model on Federal Open Market Committee Meeting Transcripts](https://haruka-takagi-datascience.github.io/supervised_nlp/)<br />
In this project we will be replicating a 2019 paper by Mikael Apel, Marianna Blix Grimaldi and Isaiah Hull from Sveriges Riksbank (Central Bank of Sweden), titled, “How Much Information Do Monetary Policy Committees Disclose? Evidence from FOMC’s Minutes and Transcripts.” This paper is in the field of central bank communication, monetary policy and machine learning. This paper does not have any scripts attached to it, so we will be intepreting the methedology from the paper to recreate their results. In the end we achieve a result of 72% in-sample accuracy and 63% out-out-sample accuracy, which is very similar to the out-of-sample accuracy as the paper.<br />
<br />
**Subject Areas**: Deep learning, NLP, Text Modelling, Python, LSTM, Classification Models <br />
<br />
<br />
[9. Static Data Visualization: Visualizing Bicycle Theft in Toronto](https://haruka-takagi-datascience.github.io/static_data_visualization/)<br />
In this project we will be investigating Toronto bicycle theft crimes with statis data visualization techniques using R. We investigate the seasonality and time patterns of bicycle thefts in Toronto. We also identify neighborhoods with the most bicycle theft cases.<br />
<br />
**Subject Areas**: Data analysis, Data visualization, R, Data cleaning <br /> 
<br />
<br />

## COMING SOON!
1. Unsupervised Natural Language Processing Project
2. Supervised Machine Learning Project
3. Finance: Investments Project
4. Finance: Corporate Finance Project
5. Dialogue Act Classification Project: Improved model for of Agreement/Disagreement LSTM model on FOMC Meeting Transcripts
6. Interactive/Dynamic Data Visualization


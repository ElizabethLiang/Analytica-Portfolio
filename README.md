# Analytica-Portfolio

## About Me

I am a data analyst with a background in business administration and experience across the retail, fashion apparel, and insurance industries. I enjoy drawing data from different sources, organizing it, and turning it into insights that drive impact — from improving decision-making and identifying opportunities to enhancing customer experience and supporting business growth.

Having lived and worked in multiple countries, and speaking several languages, I bring a global perspective and the ability to bridge cultural barriers. This helps me not only analyze data, but also interpret it in context and communicate insights effectively across diverse teams and markets. At VF Corporation and Pentland Brands, I worked within the EMEA market managing customer relationships, where I saw firsthand how aligning data with strategy leads to stronger results.

Currently completing the Data Analytics Career Accelerator program with the London School of Economics (LSE), I am on track for distinction. Through this program, I’ve gained advanced skills in SQL, Python, and data visualization, alongside practical frameworks for approaching problems with a data-driven mindset.

I am curious by nature and passionate about connecting people, systems, and insights. My goal is to help organizations turn complex data into clear stories and actionable strategies, combining analytical expertise with hands-on experience in business, marketing, operations, and finance.

# Table of Contents

- [About Me](#about-me)
- [Portfolio Projects](#portfolio-projects)

## Portfolio Projects

In this section I will list data analytics projects briefly describing the technology stack used to solve cases.

### NHS Capacity Analysis

**Business Problem:** The NHS has finite resources. In order to meet patient demand, the NHS must ascertain whether capacity must be expanded, or whether demand can be met by reallocating existing resources.

**Code:** [---)

**Presentation:** [pdf](---).

**Description:** The project sought to answer the question, "if NHS capacity was sufficient, what would it look like?", by drawing from NHS targets, namely: seeing patients within 14 days of booking, allocating 15 minutes per patient consultation and for attendance to be as high as possible. The dataset contained several hundred thousand rows of appointment data, ranging from January 2020 to June 2022 and included information on ICB (locality), consultation types and attendance. The data was cleaned and wrangled using Python library, and visualisations created using seaborn and matplotlib.

**Skills:** Data cleaning & wrangling, exploratory & descriptive analysis, structured thinking frameworks, formulating a problem statement, creating visualisations, presenting insights and recommendations.

**Technology:** Python: Pandas, Numpy, Seaborn, Matplotlib.

**Results:** Presented a range of insights and recommendations, supported by visualisations, namely:
- Patients were generally seen within 14 days and attended appointments at a very high rate. The main area of failure was appointment time allocated to each patient, symptomatic of a lack of staff.
- Adjusting the modality of appointments, depending on lag time between booking and consultation, to increase chance of attendance. Telephone consultations are well attended regardless of lag time.
- Attendance rate was greater in ICBs with fewer resources, suggesting an awareness and respect among the public for NHS resources.
             
### Console Games Retailer Analysis

**Problem Statement:** How can the retailer use existing data to predict customer behaviour and promote engagement?

**Code:** [Game_Retailer_Customer_Analysis.ipynb](---), [---)

**Presentation:** [pdf](---).

**Description:** A project focussed on exploring the customer behaviour of a console games retailer. The sales performance of the retailer was also examined. In both aspects of the project, the utility of predictive modelling was investigated. The datasets included customer data, containing information on age, gender, remuneration, spend score, education and loyalty points, as well as sales data, listing game sales by region between 1996 and 2015. The customer data was wrangled, explored and modelled using Python, while R was used to the same ends with the sales data.

**Skills:** Regression modelling (Linear & Binary), K-means clustering (elbow and silhouette methods), NLP(tokenisation, wordclouds, sentiment analysis), Decision Trees, Confusion Matrices, Data Visualisation, Data Wrangling, Shapiro-Wilk testing, Skewness, Kurtosis.

**Technology:** Python: Pandas, Numpy, Seaborn, Matplotlib, Statsmodels, Sklearn, Scipy, Nltk, TextBlob. R: Tidyverse, Skimr, Moments, Psych, Dplyr.

**Results:** Presented a range of insights and recommendations, supported by visualisations, namely:
- Customers could be classified as engagers (those that accumulate loyalty points), non-engagers (those that don't) and 'seeds' (those who have not yet become either).
- How to tailor communications with different customers, according to their income level and spending habits, in order to foster engagement.  
- The polarity of sentiment expressed in reviews, as well as the most frequently occurring words.
- An overview of sales performance across various regions, especially focussing on the prevalence of outliers in unique title sales and the overall decline post 2010, indicative of a shifting market and supporting a recommendation to explore new technologies and markets outside of console games.
- Demonstrated the power of predictive modelling, using North American and European sales, to predict overall sales.

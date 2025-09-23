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

### Supermarket Customer Analysis

**Business Problem:** The supermarket lack an understanding of their customer demographics, the products they purchase and the efficacy of their advertising channels. They also lack understanding of how these forces intersect.

**Project Report:** [2Market Customer Analysis](https://github.com/ElizabethLiang/Analytica-Portfolio/blob/main/2Market%20Customer%20Analysis.pdf).

**Recorded Presentation:** [MP4](https://github.com/ElizabethLiang/Analytica-Portfolio/blob/main/Customer%20Purchase%20Behavior%20Analysis.mp4).

**Tableau:** [Viz & Dashboard](https://github.com/ElizabethLiang/Analytica-Portfolio/blob/main/2%20Market%20Viz.twbx).

**Description:** A project focussed on exploring the customer demographics of a supermarket retailer as well as explaining customer behaviour and their responsivity to different advertisements. The dataset contained several thousand rows of customer data, including customer id, information on age, marriage status, family size, income level, nationality, online/in store preference and the proclivity to respond to advertisements. An additional dataset included a record of advertisements served via different mediums (mail/X/Instagram/Facebook). The data was initially cleaned and explored using Excel, further wrangled and explored using PostgreSQL and finally loaded into Tableau. Several dashboards were created to answer key business questions related to the problem statement.

**Skills:** Data cleaning, dealing with outliers, exploratory analysis, structured thinking frameworks, formulating a problem statement, creating visualisations, presenting insights and recommendations.

**Technology:** Excel, PostgreSQL, Tableau.

**Results:** Presented a range of business recommendations, including:
- The Customer: I advised the supermarket to foster relationships with those in their thirties and to sell to those between 45 and 75. Couples and families were the most lucrative demographic.
- The product: I recommended focussing in on two categories of item, as these were the most popular, regardless of country or online/in store.
- Advertisements: Presented insights around which advert mediums are most successful with each demographic, especially around age, education and family size.

### NHS Capacity Analysis

**Business Problem:** The NHS has finite resources. In order to meet patient demand, the NHS must ascertain whether capacity must be expanded, or whether demand can be met by reallocating existing resources.

**Code:** [NHS_Capacity_Analysis.ipynb](https://github.com/ARHilton/Data-Analysis-Portfolio/blob/main/NHS_Capacity_Analysis.ipynb)

**Presentation:** [pdf](https://github.com/ARHilton/Data-Analysis-Portfolio/blob/main/NHS_Capacity_Analysis_Slides.pdf).

**Description:** The project sought to answer the question, "if NHS capacity was sufficient, what would it look like?", by drawing from NHS targets, namely: seeing patients within 14 days of booking, allocating 15 minutes per patient consultation and for attendance to be as high as possible. The dataset contained several hundred thousand rows of appointment data, ranging from January 2020 to June 2022 and included information on ICB (locality), consultation types and attendance. The data was cleaned and wrangled using Python library, and visualisations created using seaborn and matplotlib.

**Skills:** Data cleaning & wrangling, exploratory & descriptive analysis, structured thinking frameworks, formulating a problem statement, creating visualisations, presenting insights and recommendations.

**Technology:** Python: Pandas, Numpy, Seaborn, Matplotlib.

**Results:** Presented a range of insights and recommendations, supported by visualisations, namely:
- Patients were generally seen within 14 days and attended appointments at a very high rate. The main area of failure was appointment time allocated to each patient, symptomatic of a lack of staff.
- Adjusting the modality of appointments, depending on lag time between booking and consultation, to increase chance of attendance. Telephone consultations are well attended regardless of lag time.
- Attendance rate was greater in ICBs with fewer resources, suggesting an awareness and respect among the public for NHS resources.

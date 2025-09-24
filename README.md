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

**Problem Statement:** The supermarket lacked clear visibility into its customer demographics, product preferences, and advertising-channel effectiveness—and how these dimensions intersected. In other words, there was no integrated view to show who buys what, through which channel, and where to invest for impact.

**Project Report:** [2Market Customer Analysis](https://github.com/ElizabethLiang/Analytica-Portfolio/blob/main/2Market%20Customer%20Analysis.pdf).

**Recorded Presentation:** [MP4](https://github.com/ElizabethLiang/Analytica-Portfolio/blob/main/Customer%20Purchase%20Behavior%20Analysis.mp4).

**Tableau:** [Viz & Dashboard](https://github.com/ElizabethLiang/Analytica-Portfolio/blob/main/2%20Market%20Viz.twbx).

**Description:** A project focussed on exploratory analysis and Tableau dashboard to optimize 2Market’s marketing spend across countries, channels, and customer segments. Focused on identifying who buys, what they buy, and which channels convert—so leaders can reallocate budget for higher ROAS and revenue. The project used a dataset with several thousand customer records—covering customer ID, age, marital status, family size, income, nationality, online vs. in-store preference, and ad responsiveness—plus a separate file tracking ads delivered across channels (mail, X, Instagram, Facebook, brochure). I performed initial cleaning and exploration in Excel, did deeper wrangling and analysis in PostgreSQL, then loaded the data into Tableau. There, I built multiple dashboards to address the core business questions from the problem statement.

**Skills:** Data cleaning, dealing with outliers, exploratory analysis, structured thinking frameworks, formulating a problem statement, creating visualisations, presenting insights and recommendations.

**Technology:** Excel, PostgreSQL, Tableau.

**Results:** Presented a range of business recommendations, including:
-Reallocate spend to digital (Facebook/Instagram/email/X); reduce/phase out brochures and reinvest to high-ROI channels.
-Segmented targeting of 32–48, partnered customers with family/bulk offers; U.S. singles campaign with individualized bundles and loyalty perks.
-Product bundling: prioritize Alcohol & Meat bundles for >$60K income segments; cross-sell secondary categories.
-Market focus: deepen penetration in Spain, then South Africa and Canada where returns are strongest.
-Track weekly (acquisition, conversion, CAC/ROAS) and run A/B tests via the dashboard.

### NHS Capacity Analysis

**Business Problem:** The NHS has finite resources. In order to meet patient demand, the NHS must ascertain whether capacity must be expanded, or whether demand can be met by reallocating existing resources.

**Report:** [NHS_Capacity_Analysis](https://github.com/ElizabethLiang/Analytica-Portfolio/blob/main/NHS_Capacity_Analysis_Report.pdf).

**Code:** [ipynb](https://github.com/ElizabethLiang/Analytica-Portfolio/blob/main/NHS_Capacity_Analysis.ipynb).

**Presentation:** [PPTX](https://github.com/ElizabethLiang/Analytica-Portfolio/blob/main/NHS_Capacity_Analysis_PPTX.pdf).

**Recording:** [View on Canva](https://www.canva.com/design/DAGz2A_FVOo/JBoYR37Pc1JYv69DkqyGIg/edit?utm_content=DAGz2A_FVOo&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton).

**Description:** The project sought to answer the question, "if NHS capacity was sufficient, what would it look like?", by drawing from NHS targets, namely: seeing patients within 14 days of booking, allocating 15 minutes per patient consultation and for attendance to be as high as possible. The dataset contained several hundred thousand rows of appointment data, ranging from January 2020 to June 2022 and included information on ICB (locality), consultation types and attendance. The data was cleaned and wrangled using Python library, and visualisations created using seaborn and matplotlib.

**Skills:** Data cleaning & wrangling, exploratory & descriptive analysis, structured thinking frameworks, formulating a problem statement, creating visualisations, presenting insights and recommendations.

**Technology:** Python: Pandas, Numpy, Seaborn, Matplotlib.

**Results:** Presented a range of insights and recommendations, supported by visualisations, namely:
- Patients were generally seen within 14 days and attended appointments at a very high rate. The main area of failure was appointment time allocated to each patient, symptomatic of a lack of staff.
- Adjusting the modality of appointments, depending on lag time between booking and consultation, to increase chance of attendance. Telephone consultations are well attended regardless of lag time.
- Attendance rate was greater in ICBs with fewer resources, suggesting an awareness and respect among the public for NHS resources.

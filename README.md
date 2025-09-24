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

**Results:** Outlined a set of strategic, actionable recommendations, including:
- Reallocate spend to digital (Facebook/Instagram/email/X); reduce/phase out brochures and reinvest to high-ROI channels.
- Segmented targeting of 32–48, partnered customers with family/bulk offers; U.S. singles campaign with individualized bundles and loyalty perks.
- Product bundling: prioritize Alcohol & Meat bundles for >$60K income segments; cross-sell secondary categories.
- Market focus: deepen penetration in Spain, then South Africa and Canada where returns are strongest.
- Track weekly (acquisition, conversion, CAC/ROAS) and run A/B tests via the dashboard.

### NHS Capacity Analysis

**Business Problem:** The NHS must balance the needs of a growing population with finite resources. Leaders need a clear, integrated view of demand seasonality, capacity utilization, attendance, and care modality to inform resource allocation and access policy.

**Report:** [NHS_Capacity_Analysis](https://github.com/ElizabethLiang/Analytica-Portfolio/blob/main/NHS_Capacity_Analysis_Report.pdf).

**Code:** [ipynb](https://github.com/ElizabethLiang/Analytica-Portfolio/blob/main/NHS_Capacity_Analysis.ipynb).

**Presentation:** [PPTX](https://github.com/ElizabethLiang/Analytica-Portfolio/blob/main/NHS_Capacity_Analysis_PPTX.pdf).

**Recording:** [View on Canva](https://www.canva.com/design/DAGz2A_FVOo/JBoYR37Pc1JYv69DkqyGIg/edit?utm_content=DAGz2A_FVOo&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton).

**Description:** The analysis set out to determine what “sufficient NHS capacity” would look like by benchmarking against NHS targets: patients seen within 14 days of booking, 15 minutes per consultation, and maximised attendance. It used several hundred thousand appointment records from January 2020 to June 2022, including ICB (locality), consultation type, and attendance fields. The dataset was cleaned and transformed in Python, and insights were visualised with Matplotlib and Seaborn.

**Skills:** Data cleaning & wrangling, exploratory & descriptive analysis, structured thinking frameworks, formulating a problem statement, creating visualisations, presenting insights and recommendations.

**Technology:** Python: Pandas, Numpy, Seaborn, Matplotlib.

**Results:** Presented a range of insights and recommendations, supported by visualisations, namely:
- Demand & timing: Appointments swing by season—autumn is busiest, spring/summer are quieter. Mondays are the heaviest day; weekends are light (Sundays closed; some Saturday spikes in autumn).

- Capacity fit: On average, capacity looked okay, but at peak times (especially autumn/winter) the combined demand can exceed capacity by ~10%, creating pressure points.

- Who delivers care: GPs handle ~50% of appointments; other practice staff ~47%, and at times outpace GPs—they’re critical to throughput.

- Attendance: >90% show up, about 5% don’t, and ~4% of records are unclear, which makes it harder to manage missed appointments.

- How care is delivered: ~60% face-to-face, telephone is the next biggest and most steady. Home/video together are underused (<10%).

- Wait times: 45% are seen the same day; 85% within two weeks. ~7% wait over three weeks, which increases the risk of cancellations or no-shows.

**Bottom line** Average capacity is fine, but peak weeks overflow. Focus staffing and scheduling on early-week, autumn/winter peaks and use phone/home/video more to smooth demand.

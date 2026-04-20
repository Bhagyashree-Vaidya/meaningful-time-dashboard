App Link - [Click here](meaningful-time-dashboard.vercel.app)

Meaningful Time in America, 2003-2024
An interactive data dashboard exploring how Americans experience meaningful time across 22 years and 200,000+ daily diaries from the American Time Use Survey (ATUS) Well-Being Module.

Key Findings
Income doesn't predict meaningful time. People across all income quartiles rate their days nearly the same on meaning and happiness.
Social connection does. Every single activity measured scores higher on meaning when done with someone else.
America is spending more time alone. Alone time rose from 39% to 47% of the day between 2010 and 2024, and meaningful time is falling with it.
The highest-return investments are community, care, and belonging. Shifting just 10 minutes from passive screen time to social time could measurably reverse the national trend.
Dashboard Features
22 years of real ATUS data (2003-2024) with yearly meaning scores, affect scores, social context share, and meaning-minutes
10 interactive Chart.js visualizations including income quartile comparison, meaning vs happiness divergence, social context premium, time series trends, activity decomposition, and demographic shifts
Dynamic filters for year range and comparison modes (Meaning vs Happiness, Together vs Alone, Before vs After COVID)
CSV export of filtered data
Print-friendly layout
Progressive disclosure with expandable deep-dive sections
Animated charts with staggered data point reveals
Scroll-triggered fade-in for cards and insight panels
Data Sources
All data comes from the ATUS Well-Being Module, a nationally representative survey conducted by the U.S. Bureau of Labor Statistics. Key tables used:

Source	Description
Headline Summary	Average meaning scores, affect scores, social share, meaning-minutes
Broad Decomposition	9 activity categories with meaning scores (pooled, with others, alone), time allocation, and contributions
Demographic Composition	Age, education, employment, parenthood, and sex composition shifts
Meaning Score Translation	Raw 0-6 to 0-10 scale conversion
Yearly Accounts (2003-2024)	Full 22-year time series for all headline metrics
Robustness Comparison	Cross-method correlation validation (r > 0.97 across all methods)
Tech Stack
Single-file HTML dashboard (no build step, no dependencies to install)
Chart.js 4.4.1 (CDN)
Vanilla JavaScript and CSS
Flaticon assets for section icons
Run Locally
Open index.html in any browser. No server required.

Credits
Bhagyashree Vaidya - University of Washington, MSIM, iSchool

Prof. German Gutierrez - Foster School of Business, Assistant Professor of Finance and Business Economics
April 2026

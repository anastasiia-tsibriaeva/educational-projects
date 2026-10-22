# Data Analytics Portfolio

Hi! I'm Anastasiia, a junior product analyst. These are projects I completed
during the Product Analyst program at Yandex Practicum.

Each notebook has a short description, the project goals, all the steps
of my work, and conclusions. You can see which tools I use and how I think.

**Tools:** SQL (PostgreSQL), Python (pandas, Matplotlib, seaborn, SciPy,
statsmodels), Jupyter Notebook, A/B testing, product metrics, unit economics

---

## Projects

### 1. Marketplace Product Analysis: Metrics, Unit Economics, and Growth Points
*Capstone project, part 1* ([part 2](AB%20Test%20of%20a%20First-Purchase%20Bonus%20for%20TikTok%20Users.ipynb))

[Open notebook](Marketplace%20Product%20Analysis%20-%20Metrics,%20Unit%20Economics,%20and%20Growth%20Points.ipynb)

**Task:** A fast-growing marketplace (5% commission on each purchase) wanted
to understand the state of the product: who comes, who stays, who pays,
which channels and product categories work, and where it can grow.

**What I did:**
- Cleaned and checked 4 datasets: users, orders, events, and marketing costs
- Calculated key metrics: revenue, DAU, AOV, conversion, retention,
  ARPU, ARPPU, LTV, CAC, ROI, and payback period by cohorts
- Built a product funnel and analyzed acquisition channels,
  user segments, and products
- Found data quality issues and suggested hypotheses for growth

**Results:**
- Revenue fell by about 46% from the May peak to December. The main reasons:
  low retention and a falling share of paying users, while buyers spend as before
- CAC grew about 6 times, and newer cohorts bring less money,
  so they pay back much slower
- The biggest funnel losses are at checkout and payment
- Affiliate and SEO are the best channels (ROI about 150–420%),
  TikTok never pays back
- 6 of the top 10 products by revenue are furniture

**Tools:** Python, pandas, Matplotlib, seaborn

---

### 2. A/B Test of a First-Purchase Bonus for TikTok Users
*Capstone project, part 2* ([part 1](Marketplace%20Product%20Analysis%20-%20Metrics,%20Unit%20Economics,%20and%20Growth%20Points.ipynb))

[Open notebook](AB%20Test%20of%20a%20First-Purchase%20Bonus%20for%20TikTok%20Users.ipynb)

**Task:** After my analysis showed that TikTok users rarely buy, the product team
tested a bonus on the first purchase. I needed to analyze
the A/B test results and give recommendations.

**What I did:**
- Checked the test: group overlap, group sizes, and conversion dynamics by week
- Compared first-purchase conversion (z-test) and ARPU, ARPPU,
  and AOV (Welch's t-test)
- Tracked how the p-value changed during the test

**Results:**
- First-purchase conversion grew from 1.06% to 7.51% (p < 0.001)
- ARPU grew about 10 times, average order value did not change
- I recommended calculating the bonus cost and comparing net revenue
  before rolling out the bonus

**Tools:** Python, pandas, SciPy, statsmodels, Matplotlib

---

### 3. Product Metrics in SQL for Yandex Books
[Open notebook](Product%20Metrics%20in%20SQL%20for%20Yandex%20Books.ipynb)

**Task:** Calculate key metrics for a reading and audiobook service
(data from September to December 2024) and explain the results.

**What I did:**
- Calculated MAU for authors and books, daily retention, LTV by city,
  and revenue per hour of reading or listening

**Results:**
- The top 3 books in November were all for children
- After an ad campaign, retention went down to 47% on day 5 and then grew again
- LTV in Moscow was about 4% higher than in Saint Petersburg
- Revenue per hour fell by about 17% from September to November

**Tools:** PostgreSQL (JOINs, CTEs, date functions)

---

### 4. Startup Investment Market Analysis
[Open notebook](Startup%20Investment%20Market%20Analysis.ipynb)

**Task:** An investment company wanted to understand how startups get funding
and where it is better to invest.

**What I did:**
- Cleaned a dataset with about 54,000 rows
- Grouped market segments into mass, mid, and niche
- Found outliers with the IQR method for each segment
- Made charts to compare funding types, segments, and trends over the years

**Results:**
- About 60% of startups got funding only once
- Venture funding was about 45% of all investments but gave 74% of all returns
- I recommended investing in venture deals in the Medical, Apps,
  and Internet segments

**Tools:** Python, pandas, Matplotlib

---

### 5. Data Cleaning for a Video Game Sales Dataset
[Open notebook](Data%20Cleaning%20for%20a%20Video%20Game%20Sales%20Dataset.ipynb)

**Task:** Prepare data about video game sales for an article
about the game industry in 2000–2013.

**What I did:**
- Filled in missing values using data about the same game on other platforms
- Fixed data types and removed 237 duplicates
- Grouped games by user and critic scores

**Results:**
- Kept about 98% of the original data
- Found the top 7 platforms by number of games for 2000–2013

**Tools:** Python, pandas

---

## Contact
- LinkedIn: [linkedin.com/in/anastasiia-tsibriaeva](https://www.linkedin.com/in/anastasiia-tsibriaeva)
- Email: czibryaeva98@gmail.com

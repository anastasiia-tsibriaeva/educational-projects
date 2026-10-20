# Data Analytics Portfolio

Hi! I'm Anastasiia, a junior product analyst. These are projects I completed
during the Product Analyst program at Yandex Practicum.

Each notebook has a short description, the project goals, all the steps
of my work, and conclusions. You can see which tools I use and how I think.

**Tools:** SQL (PostgreSQL), Python (pandas, Matplotlib, statsmodels),
Jupyter Notebook, A/B testing, product metrics

---

## Projects

### 1. A/B Test Analysis for an Online Store
[Open notebook](Analysis%20of%20AB%20testing%20results%20for%20online-shop.ipynb)

**Task:** An online store made a new, simpler website design. I needed to check
if the A/B test was done correctly and if the new design increased conversion.

**What I did:**
- Checked group sizes, duplicates, and users who were in two tests at the same time
- Checked that the sample was big enough
- Used a z-test for proportions to compare conversion in the two groups

**Results:**
- The new design increased conversion by 2 percentage points (p = 0.016),
  but the goal was 3 points
- I suggested building a funnel to find the step where most users leave

**Tools:** Python, pandas, statsmodels

---

### 2. Product Metrics in SQL for Yandex Books
[Open notebook](Calculating%20metrics%20in%20SQL%20and%20interpreting%20results%20for%20Yandex%20Books.ipynb)

**Task:** Calculate key metrics for a reading and audiobook service
(data from September to December 2024) and explain the results.

**What I did:**
- Calculated MAU for authors and books, daily retention, LTV by city,
  and revenue per hour of reading or listening

**Results:**
- The most popular books in November were all for children
- After an ad campaign, retention went down to 47% on day 5 and then grew again
- LTV in Moscow was about 4% higher than in Saint Petersburg
- Revenue per hour fell by about 17% from September to November

**Tools:** PostgreSQL (JOINs, CTEs, date functions)

---

### 3. Startup Investment Market Analysis
[Open notebook](Creation%20and%20analysis%20of%20charts%20for%20a%20financial%20company.ipynb)

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

### 4. Data Cleaning for a Video Game Sales Dataset
[Open notebook](Preprocessing%20data%20for%20analysis%20for%20online-game.ipynb)

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

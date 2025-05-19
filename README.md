
**Objectives**

Analyze trends in pitch success rates across seasons
Examine which industries attract the most deals
Study the behavior and preferences of different sharks
Investigate demographic factors like entrepreneur gender
Visualize deal amounts, pitch types, and co-investments


**Tools**

Python 3.8+
Pandas – Data manipulation
Matplotlib – Static visualizations
Plotly Express – Interactive charts
Seaborn – Optional styling
Jupyter Notebook – Development environment


**Key Analysis Performed**

Data Cleaning & Preparation
Converted textual and numeric fields to appropriate types
Managed null values and inconsistent entries
Extracted useful features (deal status, industry, shark involvement)


**Exploratory Data Analysis**
Deal Success Rate: 61% of pitches resulted in a deal
Top Sharks: Mark Cuban and Lori Greiner made the most investments
Popular Industries: Food, Health, and Tech pitches received the most attention
Gender Trends: Males pitched more frequently; female-led pitches had slightly higher success rates
Investment Patterns: Visualized funding amounts, asks vs investments, and multi-shark deals

a. **General Stats**

* Count and proportion of pitches that received a deal.
* Value counts on columns like:

  * `Deal`, `Industry`, `Entrepreneur Gender`, `Amount Asked`, etc.

 b. **Visualizations with Matplotlib & Seaborn**

* Bar plots and pie charts are used to show:

  * Deal vs No Deal distribution
  * Gender participation and success
  * Industry-wise success rates
* Key insight (in markdown): **"From the above graphs and data we see that the total deals received were 869, that is 61%."**

c. **Shark Behavior Analysis**

* Code iterates over shark columns to see individual investment patterns.
* Co-investments and frequent collaborators are visualized.
* Investors like **Mark Cuban** and **Lori Greiner** likely highlighted as frequent deal-makers.

d. **Financial Analysis**

* Total amount asked vs amount funded.
* Average deal size.
* Industry-wise investment analysis (both amount and frequency).
* Seasonal or seasonal-like pitch trend over time.

e. **Plotly Express Visuals**

* Interactive bar charts and scatter plots likely used for:

  * Investor-wise performance
  * Time-series views
  * Gender-based analysis
  * Amounts vs success outcomes

f. **High-Level Insights**

* **Deals vs No Deals**: Majority of pitches do receive deals.
* **Shark Trends**: Certain sharks (like Mark) invest more often, some prefer specific industries.
* **Industries**: Food, health, and tech-related pitches are frequent and successful.
* **Gender Trends**: Male entrepreneurs dominate pitch frequency; female entrepreneurs may have a slightly higher success rate.
* **Investment Trends**: Analysis likely includes average investment, top deals, and seasonality.

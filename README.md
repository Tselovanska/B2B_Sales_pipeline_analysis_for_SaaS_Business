# B2B Sales pipeline analysis for SaaS Business
Analyzing B2B sales data to uncover patterns that impact deal success and growth.

## Project Background

A mid-sized **B2B SaaS company** aimed to understand which factors most influence deal success and revenue generation across multiple sales channels and client segments.  

I analyzed **68,768 opportunities** from the company’s CRM to identify key drivers of success, evaluate **sales velocity**, and provide recommendations to improve conversion and efficiency.  

The insights generated from this project were designed to support:  
- **Sales Operations** - in optimizing deal pipelines,  
- **Marketing** - in targeting high-performing client segments,  
- **Product Management** — in aligning offerings with the most profitable customer groups.  

**Data source:** [Kaggle — Sales Pipeline Conversion at a SaaS Startup](https://www.kaggle.com/datasets/gauravduttakiit/sales-pipeline-conversion-at-a-saas-startup)


## Executive Summary

Key findings reveal three core patterns:

**1. Revenue concentration in small clients.**  
Over 60% of total revenue comes from businesses generating under $100K annually. This volume-driven model provides stability but limits scalability, as the company remains underrepresented in the enterprise segment.

**2. Heavy reliance on a single product type.**  
ERP Implementation drives nearly two-thirds of total revenue. While this product performs strongly, such dependence creates exposure risk — any slowdown in demand directly impacts overall sales performance.

**3. Inefficiencies in the sales process.**  
Most deals are lost between the 2nd and 6th iteration, indicating friction in the mid-funnel stage. The average win rate remains below 25%, suggesting that qualification or lead nurturing could be optimized to reduce attrition.

**Strategic implications:**  
- Diversify the product portfolio and client base to reduce dependency risk.  
- Refine mid-funnel processes to shorten sales cycles and improve conversion.  
- Strengthen data quality and competitor insight to support better deal outcomes.  

If implemented, these changes could increase overall win rate by 10–15% and unlock higher-value deals through improved channel targeting and segmentation.

# Insights Deep Dive

## Baseline Metrics
The dataset covers **68,768 B2B sales opportunities**, representing the company’s recent sales pipeline performance.  
Overall, the business achieved a **21% win rate**, with a total of **$367M in won revenue** and an **average sales velocity of 44 days**.  

While the topline figures indicate a solid revenue base, the relatively low win rate and moderate sales velocity highlight opportunities to optimize deal qualification, cycle efficiency, and channel performance.  

screenshot: KPI summary section 

---

## Sales Efficiency: Velocity & Iterations
Analysis of sales stage iterations shows that most successful deals close within **5–7 iterations**, while opportunities exceeding **10 iterations** almost never convert.  

Sales velocity refers to the number of days between the first contact with a potential client and the final outcome — whether the deal is won or lost. It serves as a key indicator of process speed and sales team responsiveness.  


### Deal Velocity
Deals were segmented by their average time to close to assess the relationship between speed and success:

| Velocity Category        | Avg. Deal Size (USD) | Observation                                  |
|---------------------------|----------------------|----------------------------------------------|
| High Velocity (<20 days)  | $31K                 | Smaller but more successful deals            |
| Medium Velocity (21–50 days) | $32K              | Balanced deal volume and success rate        |
| Low Velocity (>60 days)   | $33K                 | Larger potential value but lower conversion  |

**Insights:**  
1. Shorter deal cycles correlate with higher win rates.  
2. Extended negotiations tend to lose momentum, signaling inefficiencies in qualification and follow-up processes. Optimizing follow-up cadence and early qualification could increase both speed and win rate.  

screenshot: Velocity Impact 

### Sales Iterations
The number of sales iterations reflects how many times a sales team interacts with a client before closing a deal.  
Analysis shows that most winning opportunities close within **5–7 iterations**, while those exceeding **10 iterations** have a very low probability of success.  

**Insights:**  
1. Introducing a soft limit of 10 iterations can help identify when to disengage or requalify a lead.  
2. Monitoring this metric provides early warning signs of stalled opportunities and improves pipeline focus.  

screenshot: Impact of Sales Iterations

---

## Channel Performance
The channel analysis shows a clear revenue concentration in the two main acquisition streams — **Enterprise Sellers** and **Marketing**, which together generate over **96% of total revenue**.  
However, the relationship between deal volume and revenue share reveals an important distinction in channel efficiency.  

- **Enterprise Sellers:** 11,470 opportunities (46%) generating **$71.0M (54%)** of total revenue.  
- **Marketing:** 11,727 opportunities (47%) generating **$55.1M (42%)** of total revenue.  
- Smaller channels such as **Partners, Tele Sales, and Online Leads** collectively contribute less than **4% of total revenue**, with minimal strategic impact.  

**Insights:**  
- Enterprise Sellers account for more than half of total revenue but handle the most complex and resource-intensive deals. This concentration indicates a dependency risk — if this channel underperforms, total revenue could drop significantly.  
- Marketing contributes a smaller share of opportunities but delivers higher revenue efficiency, suggesting that these leads are better qualified.  
- Lower-performing channels should be re-evaluated for ROI or automated to reduce resource load.  

screenshot: Channel Performance Overview

---

## City Performance
The city-level analysis shows a moderate concentration of revenue across a few key regions. **Mumbai (27%)** and **Delhi (20%)** together account for nearly half of total revenue, making them the strongest-performing markets.  
Other cities: **Bengaluru (13%)**, **Hyderabad (12%)**, and **Kolkata (10%)** — contribute consistently, forming a stable mid-tier group, while **Pune** and **Chennai** show smaller but steady performance (around 8–9%).  

While Mumbai leads both in volume and total revenue, the data suggests that secondary markets deliver comparable efficiency, indicating a healthy geographic spread rather than dependence on a single region.  

**Insights:**  
1. Revenue is highly concentrated in top three cities, while conversion rates remain similar across regions. This indicates that the company’s growth is driven more by market size than by localized sales performance.  
2. Expanding sales operations into mid-tier regions could unlock additional revenue without major efficiency losses.  

screenshot: Revenue by City

---

## Product & Technology Performance
The analysis by product category shows a strong concentration of revenue in two technology lines. **ERP Implementation** generates **$236M (64%)** of total revenue, while **Technical Business Solutions** contribute another **$128M (35%)**.  
Together, they account for over **99% of all revenue**, confirming the company’s heavy reliance on these two primary offerings.  

By contrast, **Legacy Modernization ($1.9M)** and **Analytics ($0.9M)** represent less than **1% combined**, highlighting minimal commercial traction outside the core product lines.  

**Insights:**  
- The company’s dependence on ERP Implementation indicates a solid market position but also a potential revenue concentration risk.  
- Expanding Technical Business Solutions could help diversify revenue sources and reduce reliance on a single product line.  
- Low-performing areas such as Legacy Modernization and Analytics may be better suited for long-term innovation rather than short-term growth priorities.  

screenshot: Revenue by Primary Technology 

---

## Client Segmentation
The client analysis indicates a clear dominance of small-sized customers in the company’s revenue structure. Businesses with **up to 1K employees** and **annual revenue below $100K** account for the largest share of total income, generating approximately **$249.6M** in revenue.  
While larger clients, particularly those with **over $1M in annual revenue**, are present across several employee segments, their combined contribution remains significantly smaller.  

This suggests that the company’s growth so far has been driven by **volume-based sales to smaller clients**, rather than a few large enterprise accounts.  

**Insights:**  
- The current customer base shows a high dependency on small businesses, which ensures stability through diversification but limits high-value deal potential.  
- To increase long-term profitability, the company could target enterprise-level clients (>$1M revenue) and develop dedicated sales strategies for that segment.  
- Meanwhile, automating sales processes for smaller accounts could help maintain efficiency without increasing operational costs.  

screenshot: Main Paid Customers 

# Recommendations

Based on the insights from the analysis, several data-driven actions can help improve sales efficiency, profitability, and long-term growth.

1. **Optimize Deal Velocity**  
   - Establish an internal benchmark of **≤ 40 days** for deal closure to increase conversion.  
   - Set automatic alerts for deals exceeding **50 days** to trigger requalification or escalation.  
   - Implement a CRM dashboard tracking velocity by segment to identify recurring slow points.  

2. **Refine Sales Iteration Process**  
   - Introduce a soft cap of **10 interactions per opportunity**; deals beyond that threshold should be reviewed for relevance.  
   - Automate follow-up scheduling and track interaction outcomes to avoid over-engagement with low-potential leads.  

3. **Channel Strategy Adjustment**  
   - Maintain strong focus on **Enterprise Sellers ($71M)** and **Marketing ($55M)** channels, which together drive **96% of total revenue**.  
   - Improve collaboration between both teams: align marketing-qualified leads (MQLs) with sales qualification criteria (SQL) to shorten conversion time.  
   - Gradually scale down or automate **Partners, Tele Sales, and Online Leads** to reduce manual effort for low-yield channels.  

4. **Product & Portfolio Diversification**  
   - Reduce revenue dependency on **ERP Implementation (64%)** by expanding **Technical Business Solutions (35%)** and introducing modular add-ons.  
   - Pilot **Legacy Modernization** and **Analytics** offerings with selected enterprise clients to test profitability before scaling.  

5. **Client Segmentation & Targeting**  
   - Continue serving **small-business clients** for steady volume but create a dedicated strategy for **enterprise accounts (> $1M)**.  
   - Design separate pricing and onboarding flows for large clients to increase deal value and retention.  
   - Automate outreach and contract renewal for **low-revenue clients (<$100K)** to minimize administrative costs.  

6. **Regional Focus**  
   - Prioritize **Mumbai (27%)** and **Delhi (20%)** for strategic partnerships and customer expansion.  
   - Explore **Bengaluru** and **Hyderabad** as high-efficiency markets for new enterprise leads.

# Technical Process Overview

**Tools & Libraries Used**
1. Python: Pandas, Matplotlib, Seaborn
2. Tableau Public: Dashboard design and KPI visualizations

## **Data Preparation & Exploration in Python**  
   The dataset was first explored in Python using **Pandas** to understand its structure, key columns, and data types.  
   I reviewed missing values, category distribution, and basic summary statistics to identify potential outliers and inconsistencies.  

   ```python
   df.info()
   df.describe()
   df['Channel'].value_counts(normalize=True)
 ```
screenshot: Pandas output showing column types and descriptive statistics.

Next, using **Matplotlib and Seaborn**, I created simple visualizations to understand data distribution and early patterns — for example, deal volume by channel and average revenue per сity.
 ```python
win_rate = (
    data.groupby('b2b_sales_medium')['opportunity_status']
      .apply(lambda x: (x == 'Won').mean() * 100)
      .reset_index(name='Win Rate (%)')
)

win_rate_city = (
    data.groupby('city')['opportunity_status']
      .apply(lambda x: (x == 'Won').mean() * 100)
      .reset_index(name='Win Rate (%)')
)

win_rate_intel = (
    data.groupby('compete_intel')['opportunity_status']
      .apply(lambda x: (x == 'Won').mean() * 100)
      .reset_index(name='Win Rate (%)')
)


fig, axes = plt.subplots(1, 3, figsize=(18, 6))


sns.barplot(x='b2b_sales_medium', y='Win Rate (%)', data=win_rate, palette='crest', ax=axes[0])
axes[0].set_title('Win Rate by Sales Channel')
axes[0].set_xlabel('Sales Channel')
axes[0].set_ylabel('Win Rate (%)')
axes[0].tick_params(axis='x', rotation=30)


sns.barplot(x='Win Rate (%)', y='city',
            data=win_rate_city.sort_values('Win Rate (%)'),
            palette='coolwarm', ax=axes[1])
axes[1].set_title('Win Rate by City')
axes[1].set_xlabel('Win Rate (%)')
axes[1].set_ylabel('City')


sns.barplot(x='compete_intel', y='Win Rate (%)', data=win_rate_intel, palette='viridis', ax=axes[2])
axes[2].set_title('Win Rate by Level of Competitive Intelligence')
axes[2].set_xlabel('Compete Intel')
axes[2].set_ylabel('Win Rate (%)')


plt.tight_layout()
plt.show()
```
screenshot: 

## **Data Cleaning**
The cleaning process involved renaming columns, formatting date fields, and removing incomplete records.
I verified numeric variables (Revenue, Sales Velocity, Opportunity Size) and ensured categorical consistency across City and Primary Technology.
 ```python
data['Compete Intel'].value_counts(dropna=False)
data['Compete Intel'].value_counts(dropna=False, normalize=True) * 100
```
screenshot:

Once the dataset was validated, it was exported as a .CSV file and imported into Tableau Desktop for dashboard creation.

## Dashboard Development in Tableau
The cleaned dataset was connected to Tableau to design interactive dashboards that addressed key business questions.
Each visualization was designed around a specific analytical goal:

1. Sales Efficiency: relationship between deal velocity and win rate
2. Channel Performance: revenue vs opportunity share per channel
3. Regional Insights: city-level revenue distribution
4. Product & Client Segmentation: key contributors to total revenue
5. Custom calculated fields were created to measure Win Rate, Average Velocity, and Revenue Share.

**More:** [Tableau dashboard](https://public.tableau.com/views/SalespipelineanalysisforSaaSbusiness/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

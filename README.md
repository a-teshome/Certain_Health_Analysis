# Certain Health Marketing Campaign Performance Analysis
## Project Overview
### Company Background
Certain Health is a U.S.-based medical insurance provider founded in 2016, offering nationwide coverage through four customizable plans—Bronze, Silver, Gold, and Platinum—designed to meet a wide range of healthcare needs and budgets. In 2019, Certain Health launched a series of marketing campaigns centered on wellness, preventative care, and plan affordability to engage new and existing members. With a growing customer base and evolving campaign strategy, Certain Health is investing in data analytics to better understand how marketing efforts influence signups and subsequent claims activity. The 2024 marketing budget is geared towards two key objectives:
1.  Improve engagement efficiency
2.  Increase signup efficiency

### Dataset Structure
The dataset is made up of three tables containing information on marketing campaigns, customer signups and demographics, and filed claims and claim-related information.

<img width="630" height="430" alt="image" src="https://github.com/user-attachments/assets/dee4020d-f82b-4b2b-a551-5d71ec8602f6" />

### Stakeholder Request
The leaderdership team requested a dasboard to support quarterly business reviews and strategic marketing decisions at SureHealth by providing a comprehensive, interactive view of the to-date impact of marketing campaign categories launched in 2019. Specifically, the dashboard addresses:
- **Marketing and signup performance**: Display values for key metrics such as impressions, clicks, click-through-rates, signups, and signup rates, across campaigns.
- **Campaign effectiveness**: Compare marketing spend, signups, and subsequent claim behavior across campaign categories.
- **Trend analysis**: Visualize signups and claim amounts over time, with filters for campaign category, plan type, state, and campaign topic.
- **Category comparison**: Support side-by-side comparison of performance across campaign types.

The dashboard is intended to enable the marketing team to independently access, explore, and interpret campaign data in support of ongoing reporting and strategic planning. 

## Insights Summary
Campaign performance was evaluated on the following key metrics:
> #### Engagement
- **Click-Through-Rate (CTR):** The percentage of impressions that led to a user clicking on a campaign.
- **Cost per Click (CPC):** The average marketing spend required to generate one click.
> #### Signups
- **Click-to-Signup Rate (CTSR):** The percentage of clicks that result in a completed signup for a Certain Health plan.
- **Cost per Action (CPA):** The average marketing spend required to acquire a desired action (i.e., a signup) through a campaign.

### **Click-Through-Rate (CTR)**
- *Health For All* achieved the highest engagement across categories, with a CTR of 36% (4x the overall average), driven entirely by its *Health Awareness* campaign type (49% CTR, 43K clicks).
- *Golden Years Security* had the lowest CTR at 1.7% and only 6K clicks.
- *Family Coverage Plan* had no recorded clicks, suggesting missing or incomplete data.
- *Email* was the top performing platform with a CTR of 15%. Within this platform, *Health For All* campaign was the top performing category.

### **Cost per Click (CPC):**
- *Summer Wellness Tips* was the most cost efficient category, with the lowest CPC of $0.02 (half the average) and moderate engagement (17% CTR).
- *Health For All* had the strongest return per dollar, combining a CPC of $0.05 with high engagement (36% CTR).
- *Golden Years Security* was the least efficient category, with a high CPC of $0.48 (12x the average) and a low engagement (CTR 1.7%).
- *Email* was the most cost-effective platform (CPC of $0.03), while *Direct* was the most expensive ($0.06 CPC, $22K spend).

### **Click-to-Signup Rate (CTSR):**
- *Health For All* was the most impactful category with CTSR of 8.2% (4x the average) and 3.5K signups, driven entirely by its *Health Awareness* campaign type (CTSR 7.6%, 3.2K signups).
- *Summer Wellness Tips* despite high cost efficiency with CPC of $0.02, had poor conversion to signups (CTSR 0.2%).
- *Social Media* was the most effective platform (CTSR 1.3%, 9K signups). Within this platform, *Health For All* was the top performing category (CTSR 5.3%).

### **Cost per Action (CPA):**
- *Health For All* was the most cost-effective category (CPA $0.57, 3.5K signups), driven primarily by its *Health Awareness* campaign type ($0.36 CPA, 3.3K signups).
- *Golden Years Security* was the least efficient campaign, with the highest CPA of $124 (>50x the average) and only 23 signups.
- *Social Media* was the most cost-effective platform with $3.36 CPA and 9.5K signups, driven by #CoverageMatters ($0.82) and Health For All ($0.88) categories.
- Significantly high CPA (>$1.2K) observed for some _Covid Awareness_ campaign types. 

## Recommendations
- **Prioritize High-Performing Campaigns:** Scale up _Health Awareness_ campaign type within _Health for All_ category which delivered the highest CTR (49%), strong CTSR (7.6%), low CPA ($0.36) and high signup volume ($3.3K).
- **Reallocate Budget from Low-Efficiency campaigns** like _Golden Years Security_, which had (across categories) the lowest CTR (1.7%) and the highest CPA ($124) across categories with minimal signups (23) and _Benefit Updates_, which had the lowest CTSR (0.08%) and second highest CPA ($48) across categories.
- **Optimize platform spend:** Increase spend on _Social Media_ platform, which had best cost-efficiency with low CPA ($3.36) and the highest CTSR across all platforms (1.29%) and limit spend on _Email_, which had the lowest CTSR (0.01%), highest CPA ($255), and the lowest signup volume (37) across platforms.
- **Consider retiring high-cost campaign types** like _Covid Awareness_ campaign types within _Compare Health Coverage_ and _#CoverageMatters_ categories, which had significantly high CPA ($1.4K and $1.3K respectively), with low CTSR (0.01% and 0% respectively), and low signup volume (1).

## Dashboard
The dashboard is hosted on Tableau Public [here](<https://public.tableau.com/app/profile/a.t2948/viz/CertainHealthCampaignDashboard/Dashboard>) and supports filtering by plan, campaign type, and state. It highlights key trends and values in marketing, signup, and claim metrics.

<img width="917" height="915" alt="image" src="https://github.com/user-attachments/assets/1c24e525-cebf-48a7-8e47-3fd568737577" />

## Presentation Sample
A presentation was created for the marketing team to summarize insights and recommendations from 2019-2023 campaign performance to inform 2024 budget allocation. Below are a few relevant slides from the presentation.

<img width="917" height="517" alt="image" src="https://github.com/user-attachments/assets/e86d82bf-37ca-4ed3-9358-a702692b1981" />

<img width="917" height="520" alt="image" src="https://github.com/user-attachments/assets/3b3ec9b1-671a-4dfc-8c7b-c68c5c2447ef" />

<img width="916" height="517" alt="image" src="https://github.com/user-attachments/assets/4a28281d-47fa-4565-a705-70b5a6ffa872" />




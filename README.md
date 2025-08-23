# Performance Analysis_Telecom
Performance Analysis of a Telecom company in PowerBI, gathering insights and recommendations given for performance improvement. 

Link for PowerBI Live Dashboard - 
https://app.powerbi.com/groups/me/reports/728607b2-5a51-4880-a96a-30e96545c733/6edb1dd28d0040898eac?experience=power-bi

Welcome to the performance analysis of AtliQo Telecom. 

1. Let's understand the Problem Statement first-

AtliQo is one of the leading telecom providers in India and launched its 5G plans in May 2022, along with other telecom providers.
However, the management noticed a decline in their active users and revenue growth post 5G launch in May 2022. 
AtliQo’s business director requested their analytics team to provide a comparison report of KPIs between pre and post-periods of the 5G launch. 

The management is keen to compare the performance between these periods and get insights that would enable them to make informed 
decisions to recover their active user rate and other key metrics. 
They also wonder if they can optimize their internet plans to get more active users.  

I, as a junior data analyst, am assigned to this task.

2. In the following four dashboards I have compared performance before and after 5G of AtliQo Telecom.

(i) Dashboard 1: Key Metrics Comparison.

(ii) Dashboard 2: Trends Dashboard.

(iii) Dashboard 3: City-Level Performance.

(iv) Dashboard 4: Market Performance.

**3. Key Metrics Comparison** - In this dashboard the summary of the high-level KPI comparisons before and after 5G are shown using metric cards visuals.

<img width="1920" height="874" alt="Scrn_1" src="https://github.com/user-attachments/assets/9744732c-3cca-4db6-890d-d02e7a7024cb" />

The Insights from this dashboard are - 

**(i) Revenue:** Total revenue slightly declined from 26.63 Crores (before 5G) to 26.49 Crores (after 5G) which is a 0.50% decline. Total revenue: 3.19K (Crores unit of currency in India - 1 Crore = 10 Million)

→ This indicates that while Atliqo managed to sustain overall revenue, it has not able to capture the expected growth from 5G launch.

**(ii)	ARPU (Average Revenue per User) Metrics :** This means on average how much revenue AtliQo generated on single user for a given time period.

Here it increased from 190.23 to 211.25 which is a 11.05% growth. Average ARPU: 200.74.

→ It shows that customers who stayed are spending more showing willingness to pay for 5G services. 

**(iii)	Active Users:** Declined from 843.53 Lakhs to 773.70 Lakhs, which is a 8.28% decline. Total active users: 1.62K (Lakhs -  unit of currency in India - 1 Lakh = 100,000).

→ Significant loss happened in subscriber base which means revenue growth is not due to more users but higher spending by fewer customers.

**(iv)	Unsubscribed Users:** Rose from 56.33 Lakhs to 69.57 Lakhs which is a 23.50% increase. Total unsubscribed: 125.90 Lakhs. (Lakhs -  unit of currency in India - 1 Lakh = 100,000).

→ Customer loss/churn took place in large scale after 5G launch, which is a clear indicator of customer dissatisfaction or competitive migration.

**(v)	Other Metrics:** Plan revenue: 1.95K. % Change in active users: -8.28%. Unsubscribed growth is a concern.

**Overall scenario -** AtliQo is monetizing it's existing customers better (as higher ARPU), but the bigger problem is user loss and churn. Without fixing churn, revenue sustainability is at risk.

**4. Trends analysis** - In this dashboard time-period based trend analysis in KPIs are shown, alongwith comparison in sequential time periods (1-4) before and after 5G.

As per meta-data - months are starting from January to September except for May.

2 categories- Before 5G and After 5G. January to April represents the period before 5G implementation and June to September represents periods after 5G implementation.

time_period represents the unique sequence number ranging from 1 to 4. These time Periods are used to make respective months comparisons before and after 5G implementation (Example: Jan vs Jun, Feb vs Jul, Mar vs Aug and Apr vs Sep).

<img width="1910" height="867" alt="Scrn_2" src="https://github.com/user-attachments/assets/9ac70511-14df-4f83-a328-1beff2a87ada" />

**(i) Revenue Trends:** Revenue shows overall a -50.32% decline after 5G. Paired comparisons (Example: Jan vs. Jun, Feb vs. Jul) indicate initial post-5G drops but some stabilization. 
Overall this trend indicates that AtliQo failed to capitalize on the 5G launch compared to expectations.

**(ii) ARPU Trends:** ARPU grew +11.05% after 5G. The line chart shows a downward trend before 5G (Example: from 3037 to 2786). 
After 5G shows stabilization around 3143, with growth in later periods indicating that 5G customers are willing to pay more.

**(iii) Active Users Trends:** Active users declined -8.28% after 5G. The Bar chart shows before 5G growth (Example: in time-period 2 & 3 as 228-213), after 5G decrease (Example: in time-period 2 & 4 as 211-188), with consistent downward trajectory across time periods.

**(iv) Unsubscribed Users Trends:** Unsubscribed users grew +23.50% after 5G. The Bar chart indicates before 5G decrease (Example: 11.7-15.0), after 5G increase (Example: 18.6-16.8), highlighting accelerating churn in months like July and August. 
Overall the trend indicates Unsubscribed users are consistently higher post 5G, and the gap widens in later periods.

**Overall scenario -** The trends indicate that the Company's issue is not revenue per user but loss of users. While ARPU is steadily growing, the decline in active users and increase in unsubscribed users signals strong competitive pressure.

**5. City Level Performance analysis** - This dashboard breaks down KPIs by city, comparing before and after 5G periods.

<img width="1920" height="875" alt="Scrn_3" src="https://github.com/user-attachments/assets/088e80aa-2d4a-47fb-bba9-3f2dfa94c9a8" />


**(i) Revenue per City insights** - Overall revenue dipped slightly from 1,597.70 crores before 5G to 1,589.66 crores after 5G : -0.51% decline.

Growth observed in Cities: Lucknow : 1.79%, Gurgaon : 1.49%, Patna : 1.46%, Raipur : +1.13%. These are smaller or, Tier-2 cities showing growth.

Declining growth observed in Cities: Delhi :-2.91%, Chennai :-2.66% , Ahmedabad : -2.06%, Hyderabad : -1.31%. These are metro cities having revenue decline.

**(ii) ARPU per City insights:** Total ARPU increases from 11414 to 12675 increases 9.95%, indicating higher spending per user after 5G. 

Top growth cities are - Raipur : 18.20%, Ahmedabad : 17.93%, Patna : 16.85%, Bangalore : 16.39). From this table it is observed that mostly Tier-2 cities are contributing to ARPU growth.
   
Declining cities are Chennai : -2.65%, Pune : - 14.78% . Chennai, Kolkata, Mumbai, Delhi, Hyderabad - these metro cities show both revenue and ARPU declines which is double concern for AtliQo.

**(iii) Active Users per City insights -** Total active users fell from 843.53 Lakhs to 773.70 Lakhs :-9.03% decline. 

Only Cities like Pune : 15.30%, Lucknow :2.58% and Chennai :0.35% show Active User gain. Pune stands out as both revenue and user growth positive.

All other major metros are losing customers fast. 

**(iv) Unsubscribed Users per City insights :** Total unsubscribed users increased from 56.33 Lakhs to 69.57 Lakhs :+19.03%. 

Highest Churn in Cities: Lucknow : 43.79%, Pune : 35.61%, Jaipur : 34.41%,  Chandigarh : 31.33%, Chennai : 26.98%

Decline in churn: Mumbai : -14.46%, indicates that churn stabilized in this metro, possibly due to saturation.

**Overall scenario -** Tier-2 cities like Pune, Patna, Lucknow and Raipur are driving growth either in ARPU or active users. But major metros such as Delhi, Mumbai and Bangalore are losing large chunks of users, with Delhi alone dropping over 20% of its active base. Churn is especially severe in cities like Lucknow, Jaipur and Chennai. This tells us growth is happening in smaller cities while metros are slipping away.

**6. Market Performance analysis -** This dashboard provides an overview of KPIs across all plans, cities and time periods along with a focus on market share dynamics and revenue distribution by different plans of AtliQo and other companies.

<img width="1920" height="870" alt="Scrn_4" src="https://github.com/user-attachments/assets/2a766496-b595-497e-ac85-edbc2712926f" />

**(i) Overall Revenue and Market Metrics insights :** Total revenue across all plans stands at 1950.75 Crores, with a total market value of 83039.25 Crores. 
Atliqo's average market share is 20.00%, but its own specific share is slightly lower at 19.56%, indicating room for growth. Average revenue per AtliQo is 26.56 Crores.

**(ii) Market Share Trends Before and After 5G:** AtliQo's market share declined from 20.24% before 5G to 18.88% after 5G, representing a -7.17% change. This suggests that the 5G launch may have intensified competition with other Companies like PIO, Britel, DADAFONE which lead to market share erosion.

**(iii) Competitive Market Insights:** From the Bar chart it is observed that a) PIO leads with 35.42% share, showing strong gains after 5G.

b) Britel 2nd position holds with 27.49% market share.

c)	DADAFONE at 10.31% and Others at 7.23% are smaller players.

d) AtliQo slipped to no. 3 position in the market with 19.56% market share.

e) From the line chart for market share by month shows fluctuating trends, with AtliQo experiencing a downward trajectory after 5G - confirmed by visible dips in months like June, April, January, July, September.

**(iv) Revenue by Plans:** Revenue higher in top 3 plans : P1, P2, P3 , contributing majority of plan revenue. 

The smaller plans from P7 to P13 generate very little revenue which suggest an inefficient plan portfolio.

**Overall scenario -** AtliQo's market position is mid-level, but the after 5G decline in share indicates competitors like PIO and Britel may have captured more 5G users. 
Revenue is concentrated in higher plans from P1 to P6, suggesting a need to boost adoption of lower plans.

**7. Recommendations for Top-Level Board Members** - 

Based on the insights from the dashboards, here are actionable recommendations to address the after 5G decline in active users, revenue growth and market share while leveraging ARPU improvements:

(i) Optimize Internet Plans for customer retention by introducing bundle offers in 5G, value added service like data booster packs or streaming perks, aiming to take back the unsubscribed users.

(ii) Take city specific strategies based on city performnace by focusing on underperforming metros like Delhi, Mumbai and Chennai where active users dropped and revenue declined. Implement customer feedback surveys and improve customer service quality. 

(iii) Churn mitigation and user acquisition by implementing customer retention programmes like reward programmes or win-back marketing campaigns.

(iv) Data-Driven monitoring using internal customers with predictive analytics (Example: forecast ARPU vs. churn correlations) and tracking of KPIs monthly.

**8. Conclusion-**  5G rollout has improved AtliQo's revenue per user, but customer churn/loss has decreased the overall growth and market share. 
AtliQo has strength to fight back, however urgent action on customer churn and market competition needed, otherwise they risk losing long-term leadership in the Market.


--- End of analysis ---

Dataset obtained from Codebasics Resume Project challenge #3.



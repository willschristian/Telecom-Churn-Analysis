
# Telecom Customer Churn &amp; Behavior Analysis

Table of Contents

* Project Background
* Executive Summary
* Churn Report Insights
  * Usage Behaviors
  * Total Revenue
  * Competitor Network Preference
  * Loyalty Segment & Complaints Frequency
  * Network & Spend Key Patterns
* Recommendations
* Tools Used

***

## Project Background 
This personal project focuses on analyzing customer churn and usage patterns from a telecom dataset. The goal is to understand why users leave, who’s likely to churn, and how usage behavior connects to spend and loyalty.
The dataset captures how customers used the service; their call and data spend, complaint frequency, network transitions, and even competitor preferences. While this isn’t a live stakeholder project, it's treated as if I were delivering insights to telecom operations, marketing, and product teams keeping both accuracy and clarity in focus. The project builds churn-risk segments and user personas to guide decisions around retention, customer experience and loyalty strategy.


## Executive Summary
This telecom churn analysis of 1,400 users reveals that roughly 47.4% of users churned. Users were segmented by usage and spend patterns into actionable groups like Dormants, Dialers, Anchors, Surfers, and Mid-Rangers. Total data consumption across all user segments reached roughly 2.82 TB, while collectively making 282,538 unique calls.
A total revenue of  ₦31.6 million made, churned users accounted for ₦18.4 million in lost revenue, while active users brought in ₦13.2 million, underscoring the urgency of targeted retention. Dialers generate the highest retained revenue due to user volume, while Anchors lead in per-user value. Call revenue accounting for 90% of total earnings shows an income stream heavily driven by voice communication.
PQza and Mango networks are dominant among users' competitor preference, but Uxaa remains the top overall preference showing clear competitive threats.
Loyalty was highest among users with fewer complaints and longer tenure. Strengthening onboarding, loyalty, and retention programs around behavior and complaint signals can increase higher customer value and reduce churn loss.

***

## Churn Report

### Usage Behaviors 

Dormant(Low Consumers) represents our weakest engagement group. Averaging just 12 unique calls and 45 MB of data per user. The churn rate is highest here at 77% overall, driven mostly by short-term and offnet-heavy users. Off Net-heavy dormants alone account for 200 churned users, averaging just ₦2,231 in call spend, a clear churn hotspot.

Mid-Rangers(Balanced Consumers) are more involved, averaging 296 calls and 1.1GB of data, still they churn at 46%. Among those who churn, off net-heavy mid-rangers make up 82%, compared to just 14% for balanced and 4% for on net users. Interestingly, 58% of these offnet-heavy mid rangers lean to the Uxaa network.

Anchors(High Consumers) are the high and active group, with 566 calls and 7.9GB of data on average. Churn is relatively low at 39%, but spikes among Mid-Term anchors with 59.1%. Their offnet-heavy churners (25 users) show very high spend (₦71K) translates to key lost value.

Dialers(Voice Inclined) are heavy on calls - 270 calls, 73MB data per user, but with a fair churn rate at 41%. Off Net-heavy Dialers again pose a high churn risk, especially as over half lean to Uxaa, Mango or ToCall. Loyalty impact is visible here; Newbie Dialers churning at 31.7%, while Mid-Term users climb to 60.2%.

Surfers(Data Inclined) are our most stable and data-heavy group, with 12.2GB of use and just 52 calls on average. Churn is lowest at 33.3%, with very strong retention even among Newbies (38.1%). While some offnet Surfers (42 churned) still lean toward PQza (38%) and Uxaa (36%), their steady spend and loyalty make them prime for upsell and premium bundling efforts.

![Alt Text](https://github.com/willschristian/Telecom-Churn-Analysis/blob/924fc3839b65bfceb7c9452e608013639d703476/Screenshot%20(96).png)


### TOTAL REVENUE
 
The total telecom revenue across 1,400 users made approximately ₦31.6 million. Call revenue dominates accounting for nearly 90% with ₦30.1 million. Data and SMS contribute much smaller amounts with ₦82,000 and ₦39,000 respectively showing a user base still heavily driven by voice communication.
From this total, active users generated ₦13.1 million in call revenue, ₦33,553 in data, and ₦17,051 in SMS. However, churned users accounted for ₦18.4million in lost revenue, including ₦18.3 million from calls, ₦48,320 from data, and ₦25,500 from SMS.
 
  #### REVENUE GAINS BY USER SEGMENT
 * Dialers are our largest retained user group, with 331 active users still on the network. They are the most valuable group for retained revenue across all services (calls data SMS). Despite Anchors having the highest per-user spend, Dialers’ size makes them more valuable for consistent cash flow.
 * Dormant users represent the biggest financial leakage: ₦11 million in total losses across call, data, and SMS despite the minimal average usage. Their churn count (265 users) makes them the highest revenue loss by user segments.
 * Average Revenue Per User (ARPU) — There are noticeable differences across segments. Anchors lead with ₦51K per user on calls, Mid-Rangers follow at ₦27K. Surfers top the data ARPU chart with ₦113 per user. Dormant rank lowest across all service types, showing both weak revenue potential and high loss impact due to churn

   ![Alt Text](https://github.com/willschristian/Telecom-Churn-Analysis/blob/924fc3839b65bfceb7c9452e608013639d703476/Screenshot%20(98).png)
   ![Alt Text](https://github.com/willschristian/Telecom-Churn-Analysis/blob/be2c0d5318365e13fe72426b0051f9cb28f7124c/arpu%20comparison.png)


### COMPETITOR NETWORK PREFERENCE — KEY INSIGHTS
  The top 3 competitor network preference over 2 months gives the information about which other service provider users prefer and may likely move to.
* PQza leads churn destinations, attracting 40.2% of offnet-heavy churners up from 34.8% among general offnet-heavy users.  Uxaa dominates among onnet-heavy churners with 50.9% leaning towards the network and retains 52.4% overall among onnet users
* Mango rises as a competitor, now claiming 25.3% of offnet-heavy churners
* Dormants and Mid-Rangers heavily drive PQza's growth, they contribute 59% and 22% of offnet-heavy user switches respectively.  while Uxaa remains the top choice for Anchors (83%), Dialers (79%), and Mid-Rangers (58%) among offnet-heavy users.
* Over 70% of Anchors, Dialers, and Mid-Rangers changed preferred networks between Jan and Feb, showing high volatility among our most active users.

![Alt Text](https://github.com/willschristian/Telecom-Churn-Analysis/blob/485b95cd186ec2532adbcc9dcbbe1ad802b93e88/Screenshot%20(99).png)
![Alt Text](https://github.com/willschristian/Telecom-Churn-Analysis/blob/485b95cd186ec2532adbcc9dcbbe1ad802b93e88/Screenshot%20(103).png)


### LOYALTY SEGMENT AND COMPLAINTS  FREQUENCY (GROUPED BY CUSTOMER TENURE)

Total of 2,691 complaint calls across 1,400 users, averaging 2 calls per user. 
* Newbies (0–2 years) with a total of 1021 complaints made by 545 users show the highest churn rate at 55.6%. Dormant newbies dominate this tier with an 80% churn, suggesting a shaky early experience.
* Mid-Term users (2–5 years) contribute the most complaints (668) across 376 users, with churn at 50.3%. 
Long-Term users (5–7 years) made 497 complaints across 256 users. While some stability exists the churn rate is higher than expected with 49.2%, largely due to Dormants and Mid-Rangers.
* Loyal users (8+ years) remain the strongest base. Despite 502 complaints from 220 users, churn is just 35.9%. Surfers, Anchors and Dialers drive this low churn showing the best tolerance.
* Complaint frequency is steady across all tenure groups, but Dormants show weak value retention in every group.

![Alt Text](https://github.com/willschristian/Telecom-Churn-Analysis/blob/485b95cd186ec2532adbcc9dcbbe1ad802b93e88/churn%20by%20segment%20and%20loyalty.png)


### Network and Spend Key Patterns – Jan & Feb Spend and Transition Trends

- Most users remained static: 55% of users didn’t change network type, with 42% staying on 3G and 13% on 2G. Users with upgrades, downgrades, reactivation and disconnection make up the remaining 45%.
* Network downgrades and disconnection show the worst outcomes. Over 70% of downgraders and 50% of disconnected users churned.
* Dormant users dominate downgrade and disconnection transitions and they consistently returned the lowest average spend in January and February (₦74–₦230) with the highest churn rate 80–100% respectively.
* Reactivated users made up 4% of all users and showed churn rates below 40%, with an average spend between ₦600–₦760 in just 2 months (mostly Mid-Rangers and Dialers)
* Static 3G users proved reliable. They accounted for 42% of all users, showing stable behavior with average spend of ₦2.4K and churn around 46%.

![Alt Text](https://github.com/willschristian/Telecom-Churn-Analysis/blob/be2c0d5318365e13fe72426b0051f9cb28f7124c/Screenshot%20(104).png)


## Tools Used 
* Python (Pandas, Matplotlib, Seaborn)
* Microsoft Excel (EDA visuals and Data cleaning)
* Google Docs(Documentation)
* Jupyter Notebook
* GitHub for project hosting and documentation

# ClipBoardHealth_Staffing_Analysis
As part of Clipboard Health case challenge,I explored contractor staffing trends in U.S. nursing homes to identify where and why contractors are used and where strategic expansion is possible.

# Problem Statement
As Clipboard Health provides staffing solutions to Nursing Homes, I wanted to understand-
•	Where are contractors being used most?
•	Why do some facilities use more contractors than others?
•	Where are our biggest opportunities for growth?

# Data Sources
•	Payroll Based Journal (PBJ) Daily Nurse Staffing[Q2/2024]
•	Provider Information
•	Penalties

# Analysis steps
Step 1. State-Level Contractors Usage Analysis

First, I analyzed contractor usages across states and found that-

<img width="469" height="227" alt="image" src="https://github.com/user-attachments/assets/236ec082-2e15-436f-9318-a28837f81e97" />

High Usage States	Low Usage States
Vermont (27.9%)	Oklahoma (3.3%)
Maine (17.8%)	California (3.1%)
Montana (15.7%)	Florida (3.0%)
North Dakota (14.9%)	Alabama (1.6%)
Hawaii (13.1%)	Puerto Rico (1.1%)

Step 2. Providers Quality Investigation

To understand why there is stark difference between those states in High and Low states groups, I looked at Provider information data and found interesting patterns – 

<img width="468" height="224" alt="image" src="https://github.com/user-attachments/assets/78ec3ad5-af2d-4b86-946e-18f747eba2e0" />

Findings from the above chart- 
•	Overall Quality: Both groups have comparable ratings (3.0) 
•	Staffing Ratings: States with high usage rated better (3.7 vs 3.0) 
•	Nursing Staff Turnover: States with high usage experienced higher turnover than low usage states (50.3% vs 44.6%)

Step 3. Understanding Facility Characteristics

After observing the differences in quality in both groups, I looked at the type of facilities and ownership patterns across those states and found more interesting patterns -

•	High Usage States have smaller facilities (67-103 beds) [Vermont – 88 beds despite being highest contractor usage at 27.9%], with a mix of ownership types, including Non-profit Corporations (97 facilities), For-profit Corporations (83 facilities), & Government facilities which demonstrate strong performance

•	Low Usage States have larger facilities (96-121 beds) and are predominantly for-profit, including Profit LLCs (934 facilities), Profit Corporations (779 facilities), & a very limited number of non-profits

<img width="452" height="263" alt="image" src="https://github.com/user-attachments/assets/47c7c118-81b6-4363-83ff-7dc3cd2e1cdb" />


<img width="468" height="320" alt="image" src="https://github.com/user-attachments/assets/d8fd5134-e837-4b97-9ef1-15c278d98b46" />

Step 4. Regulatory Impact Analysis

To understand the relationship between contractor usage and penalty, I examined high & low states with their fine amount & staffing ratings along with the facility.

Key Findings:
1.	High Contractor Usage States: 
•	Higher average fines (approximately $23,000)
•	Better average staffing ratings (3.7)
•	This suggests that contractors are utilized to meet stricter regulations and maintain adequate staffing levels
2.	Low Contractor Usage States: 
•	Lower average fines (around $12,000, with some states like PR [$6,488]
•	Lower average staffing ratings (3.0)
•	This may indicate less rigorous enforcement or different regulatory priorities in certain states, but further investigation is necessary as other factors could be influencing these results

Interesting Revelation on Facility-Level:
•	Florida: Despite a low overall contractor usage rate (3%), multiple facilities with $30 Mn + fines.
•	Vermont: Two facilities with major fines- Facility ID 475030 [$38 Mn] Facility ID 475020 [$37.3 Mn]

Key Takeaway: Clear tradeoff states with high contractor usage, which tend to have higher fines but better staffing ratings, and states with low contractor usage has lower fines and poorer staffing ratings.
<img width="468" height="228" alt="image" src="https://github.com/user-attachments/assets/5946e5af-5bdc-4d18-98ff-24e351ba27c5" />

This is the table for Top 10 Facilities with High Penalties:
State	Facility ID	Fine Amount
FL	105407	$104,918,450
	105702	$58,912,672
	105965	$49,636,314
	106103	$45,866,093
	105394	$45,864,819
	105588	$43,223,453
	105250	$42,939,988
CA	555438	$39,765,453
VT	475030	$38,005,058
	475020	$37,342,305

Step 5. Occupancy Analysis
Finally, I examined capacity utilization with high and low usage states to analyze if contractor usage is influenced by occupancy rate.

Notable trends in High Usage States: 
•	ND: 90.77% occupancy [14.9% contractor usage]
•	ME: 84.87% occupancy [17.8% contractor usage]
•	VT: 78.97% occupancy [27.9% contractor usage]

Low Usage States: 
•	FL: 87.89% occupancy [3% contractor usage]
•	CA: 87.58% occupancy [3% contractor usage]

This shows that contractor usage is not influenced by occupancy rates but by other factors – state regulations, or staffing shortages.

<img width="468" height="223" alt="image" src="https://github.com/user-attachments/assets/3c89a578-f428-4208-862f-9a9cbc3a5d5c" />

# Recommendations
Based on the comprehensive analysis of Nursing home staffing trends, I uncovered few areas of opportunities for growth.

1.	Strategic Regional Expansion:
   Some states in Northeast and other regions have high nursing contractor staffing acceptance - potential opportunity to expand.
•	Vermont (27.9%) & Maine (17.8%) has high contractor adoption
•	States like Florida (2.97%) & California (3.05%), despite low contractor usage has high fines – Tailored strategy could be a game changer
•	Real success stories from high usage states benefits to enter similar markets

2.	Focus on Smaller Facilities for Higher Adoption:
Data from the analysis shows that smaller facilities typically with 67-103 beds are more open to contractor staffing.
•	Prioritize facilities with fewer than 100 beds
•	Create tailored solutions to Non-profits [ 97 successful results in High usage states], Government-owned, & Smaller for-profit facilities, looking for improving quality
•	Target occupancy rates between 75-90%, where there is flexibility for staffing adoption

3.	Position Nursing Contractors as Quality-driven:
High contractor usage states’ facilities have better staffing ratings (3.7 vs 3.0) compared with low contractor usage states.
Focus on facilities that has:
•	3+ overall ratings, seeking to maintain quality
•	High staff turnover rates (>45%) that need staffing support
•	Good compliance records and meet regulatory requirements

4.	Regulatory Compliance Strategy:
High usage states have better overall ratings despite stricter regulations.
•	Target states with higher regulatory fines (~$23000 average) and recently penalized
•	Focus on Low staffing ratings facilities but with high fines (like Florida)
•	Reinforce on compliance support to maintain staffing needs

5.	Unlock Growth in Low-usage states:
Some of the largest untapped markets have low contractor usage but significant staffing challenges.
•	Prioritize states that have large facility counts like (FL and CA)
•	Facility with high fines but low contractor usage- room for expansion
•	Lower staffing ratings facility where improvement is needed
•	Launch educational campaigns to show the benefits of contractors in reducing penalties and improving care.













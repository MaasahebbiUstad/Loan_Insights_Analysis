# Loan_Insights_Analysis
Explore loan-related insights from human-initiated voice calls using Python for data analysis and Excel for visualization. Uncover patterns in loan distribution, customer interactions, and EMI anomalies within the call system.


<p align="center">
  <img src="https://github.com/MaasahebbiUstad/Loan_Insights_Analysis/assets/137813961/b5c7e753-7144-4bea-b8ac-dc06b27010ca" width="700" height="320">
</p>


## <img src="https://github.com/yasmeenustad/Placements-Data-Analysis-Excel-Project/assets/112754746/030e1f21-e04f-4cbd-b301-3576c8c1acc3"  width="48" height="48">Project Aim:

* Analyze Organization automated voice calling dataset comprehensively
* Extract valuable insights to enhance understanding of customer interactions
* Generate actionable recommendations for improvements
* Present a detailed report for clients based on the data analysis
* Explore language-level collection rates to understand performance
* Examine demographic patterns for a deeper understanding of user profiles
* Identify and analyze additional relevant metrics to uncover hidden patterns
* Contribute to enhancements in the automated calling system
* Work towards improving collection rates through informed insights.

## <img src="https://github.com/yasmeenustad/Placements-Data-Analysis-Excel-Project/assets/112754746/057551de-877a-4a41-916c-d47e81053404"  width="48" height="48">Project Objectives:

- Make better decisions
- Continually enhance voice calling services.
  
## Tech Stack Used:

<img src="https://github.com/MaasahebbiUstad/1mg-Homeopathy-Data-Analysis/assets/137813961/065f1ca9-2b47-47b9-88b9-62a2fce746be" alt="Excel GIF" width="60" height="58">
&nbsp;&nbsp;&nbsp;
<img src="https://github.com/MaasahebbiUstad/1mg-Homeopathy-Data-Analysis/assets/137813961/7fc2a7c8-a736-4736-90cd-28e314aa31e6" alt="Python GIF" width="60" height="58">
&nbsp;&nbsp;&nbsp;
<img src="https://github.com/MaasahebbiUstad/Loan_Insights_Analysis/assets/137813961/1fcd01af-f140-44a1-ae38-fbbe8129f3bb" alt="Powerpoint GIF" width="64" height="62">

## Data Cleaning Steps:

* **Handling Null Values:**
  
  Identify columns with null values and choose a strategy for handling them.

* **Duplicate Removal:**

  Identify and analyze duplicates, deciding on a strategy for removal.

<p align="center">
  <img src="https://github.com/MaasahebbiUstad/Loan_Insights_Analysis/assets/137813961/44f6ddad-5cd7-47c3-b743-8b08767149d8"  width="800" height="520">
</p>


* **Addressing '-' in 'ptp_date‘ and ‘reason’:**

     Identify instances of '-' in 'ptp_date'  and reason field and apply appropriate handling.

<p align="center">
<img src="https://github.com/MaasahebbiUstad/Loan_Insights_Analysis/assets/137813961/0a9b60d5-f9af-429b-b381-4539b6d4de59" width="400" height="520"> <img src="https://github.com/MaasahebbiUstad/Loan_Insights_Analysis/assets/137813961/03220492-898a-440a-9635-a3cdf769295a" width="400" height="520">

<img src="https://github.com/MaasahebbiUstad/Loan_Insights_Analysis/assets/137813961/9601a4dc-3df7-44e8-a530-6db99878edff" width="800" height="520"> 

</p>

* **Data Type Conversions:**
  
     Check and convert data types for consistency (e.g., 'dialed_time' to datetime).

* **Duplicate Removal:**

  Identify and analyze duplicates, deciding on a strategy for removal.

## Data Snapshot:

- ### Dataset Size:
  
  Rows: 137,784
  
  Columns: 15

- ### Missing Values:
  
  ptp_date: 95,683 (69%)

  reason: 83,665 (61%)

  gender: 95,683 (69%)

- ### Significance:
  
  69% null values in crucial columns raise data quality concerns.

- ### Impact on Analysis:
  
  Addressing missing values is pivotal for reliable insights.

- ### Recommendation:
  
  Prioritize data cleaning to enhance dataset integrity.

  ## <img src="https://github.com/MaasahebbiUstad/1mg-Homeopathy-Data-Analysis/assets/137813961/1a839dfc-2edc-4981-bbed-fcd9b6912aba" width="50" height="48">Loan Insights Visualization Gallery:

 <p align="center">
   <img src="https://github.com/MaasahebbiUstad/Loan_Insights_Analysis/assets/137813961/71e93af0-d884-4fbd-a3d8-384376205d46" width="800" >
 </p>

 - Talk time patterns witnessed a notable increase since March 2023, following a peak in 1990, with a recent slight decline in December 2023. These shifts indicate evolving communication dynamics over time.

<p align="center">
  
 <img src="https://github.com/MaasahebbiUstad/Loan_Insights_Analysis/assets/137813961/5db410c2-5a8e-4bf6-a14b-09db870ba297" width="500" >
 
</p>

- The time spent talking with customers about loans (talk time) and the loan installment amounts (EMI) don't seem to have a clear connection. In other words, the length of conversations doesn't tell us much 
  about how much someone pays for their loan each month.

<p align="center">
  
 <img src="https://github.com/MaasahebbiUstad/Loan_Insights_Analysis/assets/137813961/d432cf0f-92c7-41c4-9bec-e30d04d717a8" width="600" >

</p>

- The analysis reveals comparable average EMI amounts for both 'ICD Finance' and 'Smart Finance' across 'postbounce' and 'predue' categories, suggesting relative consistency in payment patterns for these 
  finance companies.

<p align="center">
  
 <img src="https://github.com/MaasahebbiUstad/Loan_Insights_Analysis/assets/137813961/d09a6b3c-4692-42af-bec9-064ce108d8a3" width="800" >

 </p>

<p align="center">
  
 <img src="https://github.com/MaasahebbiUstad/Loan_Insights_Analysis/assets/137813961/e7227b05-7fdc-4b77-ac7c-9168bb3d2993"  width="800" >

 </p>

## Insights:

- ### Missing Information:
  
   Columns 'reason,' 'ptp_date,' and 'gender' have over 60% missing values, signaling potential gaps in information.

- ### EMI Amount Analysis:
  
  Total EMI sum is 2,405,425,114, with an average of 17,458.32, showcasing diversity in EMI values.
  Range spans from 1 to 2,675,991, revealing variability in payment amounts.

- ### Finance Companies Comparison:
  
  Comparable average EMI amounts for 'ICD Finance' and 'Smart Finance' across 'postbounce' and 'predue' categories, indicating payment consistency.

- ### Talk Time vs. EMI:
  
  No clear correlation between talk time and EMI, suggesting conversation length doesn't directly relate to loan payments.

- ### Loan Distribution Across Languages:

  Marathi leads with 82,726 loans, followed by Hindi (27,357), Kannada (13,764), and English (13,934), showcasing varied loan volumes.

- ### Language-Based Talk Time Analysis:

  Average talk times differ, with Kannada at 9062.8 and Hindi at 9232.2, hinting at communication dynamics variations.

- ### Customer Interactions and Dispositions:

  Diverse outcomes include 'No Answer' and 'Customer Hangup,' necessitating targeted communication strategies.

  Positive responses like 'Agree To Pay' highlight opportunities for successful engagement.

- ### Anomalies in EMI Amounts:

  Spikes on 3/11/2023 and 3/12/2023 (184,483 and 192,403) suggest exceptional events, warranting further investigation.

- ### Time Series Analysis of Talk Time:

  Notable changes over time, with high talk times in 1990, an exponential increase in March 2023, and a recent decline in December 2023.

- ### Reasons for Delays:

  Prevalence of 'Unknown,' "-", and 60% blank data indicates challenges in categorizing reasons for delays.

## <img src="https://github.com/MaasahebbiUstad/1mg-Homeopathy-Data-Analysis/assets/137813961/4d5c4735-a50c-4876-84c2-b19031384635" height="50" width="48">Conclusions:

  The data analysis highlights key insights, such as language-driven collection variations, diverse customer dispositions, and anomalies in EMI amounts. To improve our services, we'll address missing data      issues, refine loan distribution strategies, and enhance communication efforts. These steps will empower us to make better decisions and continually enhance our voice calling services.









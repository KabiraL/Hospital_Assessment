# What makes a high-value hospital?
#### A Medicare hospital value analysis in Python using 7 CMS public datasets (~5,000 hospitals), combining mortality, readmission, spending, effectiveness, and patient experience data to identify high-value providers.

<hr style="border:2px solid gray">

### The business questions:  
### Which hospitals achieve better outcomes at a lower cost?  Do they share particular characteristics?

<hr style="border:2px solid gray">

The availability and affordability of healthcare is the #1 concern for Americans, according to a March 2026 Gallup poll.  <sub><sup>[https://news.gallup.com/poll/707732/healthcare-reclaims-top-spot-among-domestic-worries.aspx]</sup></sub> People want cost-effective healthcare.

### This project provides a tool for choosing hospitals that deliver the best outcomes relative to their cost.

<hr style="border:1px solid gray">

## OVERVIEW

The Centers for Medicare & Medicaid Services (CMS) calculates hospital ratings annually and assigns each hospital a quality rating of 1-5 stars. They use 5 sets of data to do this.  

#### *My analysis takes the additional step of incorporating a cost metric in order to assign hospitals an outcome value score.*

This analysis has three parts:
1.	Every hospital's clinical quality is scored using the same 26 outcome measures the CMS uses in its star rating system. These measures cover patient mortality, readmissions, and hospital safety. 
2.	That quality score is combined with spending data to identify which hospitals deliver the best outcomes relative to their cost. All (~5,000) hospitals are divided into four value tiers. 
3.	The distinguishing characteristics of high-value hospitals are investigated. This involves testing whether factors like hospital size, ownership, patient satisfaction, and care processes (such as how quickly sepsis is treated) predict which tier a hospital falls into.

<img width="1024" height="768" alt="Hospital ERDs" src="https://github.com/user-attachments/assets/bf6614d4-869b-47a1-8953-bfca8882b41e" />










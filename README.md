# COVID-19-Organization-Engagement-Pulse-Survey

**PERSONAL AND/OR UNIQUE IDENTIFIERS HAVE BEEN REMOVED FROM ALL SAMPLE DATA** 

**Goal and Purpose:**

The purpose of this survey and analysis was to provide senior leadership a granular understanding of staff sentiment regarding the organization's preparation and response to the COVID-19 pandemic. As the lead data analyst for this project, I had to decide how we wanted to engage our staff, what variables we would consider, and finally how we presented our data. 

**Methodology:**

My methodology was as follows:

1) Engaged various departments and stakeholder groups to determine how we should survey our staff. 
    - Which questions would provide us the most meaningful feedback? 
    - How should these questions be phrased? Quantitative vs Qualitative. 
    - What data output should the questions produce? Should they be open-ended reponse questions? Quantitative response questions? Discrete? Continuous? 
    - What level of granuliarity should this data analysis seek to provide?
    
2) Implemented survey via Qualtrics to gather and procure the data. These were the questions we decided on. 
    a) My Company’s leadership has a clear plan of action.
    b) During this time, My Company cares about my well-being.
    c) I feel comfortable asking my manager for a flexible work arrangement during this time.
    d) I feel well-prepared to do my job.
    e) The leader of my team keeps me informed about what is going on.
    
All questions were scaled from Strongly Disagree, Disagree, Neither Agree nor Disagree, Agree, Strongly Agree (scaled 1-5). Then averaged for a single composite score. 
    
3) Cleaned data in R code (attached in .rmd above) to break and partition data for analysis.

4) Analysis and final visualizations broken down by demographic, titles, and departments. 

![Demographic Cuts](https://github.com/artwang31/COVID-19-Organization-Engagement-Pulse-Survey/blob/main/Demographic%20Cuts.png)

![Title Cuts](https://github.com/artwang31/COVID-19-Organization-Engagement-Pulse-Survey/blob/main/Title%20Cuts.png)

![Department Cuts](https://github.com/artwang31/COVID-19-Organization-Engagement-Pulse-Survey/blob/main/Department%20Cuts.png)

![Department Demographic Cuts](https://github.com/artwang31/COVID-19-Organization-Engagement-Pulse-Survey/blob/main/Department%20Demographic%20Cuts.png)


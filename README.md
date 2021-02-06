# Fintech_Project1

This project has been created by Youssef Abdelwahab , Carla Herrera , Vinay Anupindi , Kaushik Bose


•	Motivation & Summary

Recent events of covid have drastically changed society and the economy affecting employment, mobility and consumer habits. Our goal is to review these effects on the retail sector, by choosing a diverse set of companies and reviewing their stock price data and financial performance . 
![Drag Racing](Cor)
(INSERT PIC HERE)

•	Define the core message or hypothesis of your project.

 As part of analysis of the impact on covid on the retail , we wanted to explore how different retail business models performed differently. We hypothesize that Retail companies that were primarily digital or already had a significant digital presence fared better during the pandemic,and this is reflected in the company’s financials and stock price and those who ran a more traditional brick and mortar model have found themselves stuck in the mud and have performed worse than their mainly digital peers.

•	Describe the questions you asked, and why you asked them?
    Did the change in cases have an impact on peoples descions regarding leaving their households?
    How did covid affect unemployment insurance claims and the unemployment rate? 
    How did covid affect mobility and vehicular miles travelled, percentage changes to visits to the retail sector? 
    How did covid affect the financial perfromance of the companies chosen?
    How did covid affect the stock price and financial health of companies chosen?
    What correlations exists between the companies chosen and the impact covid had on mobility?
    How did these correlation change by quarter during the pandemic?
    What happened in each quarter for these co-relations to change?    
    
   We asked these questions because we felt they pointed us towards the right directions to pick the most apporopriate datasets for our research
    
•	Describe whether you were able to answer these questions to your satisfaction, and briefly summarize your findings.
  We were able to answer most of the questions. Generally speaking our hypothsis turned out to be correct and aligned with our initial predictions. In summary, as COVID began   to take a larger toll on the economy we saw a sharp decline in the financial perfromance of companies that did not have a strong e-commerce strategy. This is mainly due to   the fact that people were more inclined to limit their outings and interactions. After doing some market research we saw non-e-commerce established scramble to set up pick   in store services to try and adapt with the new covid induced lifestyles.
  
•	Elaborate on the questions you asked, describing what kinds of data you needed to answer them and where you found it.
We had a lot of promising idea intially. However we soon ran into the problem of not finding the right or availble datasets. To overcome this we had to apply reverse engineering and search for appropriate data that we would be able to conduct analysis with 
  Unemployment Data – FRED St.Louis
  Mobility Data – Google mobility 
  Stock financials – Quandl 
  Stock prices –  yahoo
  Covid Cases - WHO
  
•	Data Cleanup & Exploration
  - Finding appropriate and well defined data was difficult 
  - Finding data relating to other industry areas was difficult so we had to focus on one industry. For example we thought about analysing the airline industry
  - We ended up investing in a well established financial database to get all the information we need 
  

•	Describe the exploration and cleanup process.
 - Data clean up was very long so we created short algorithms to try to automate this process 
 - Financial data did not exsist for the first quarter of 2021
 - Midway we had to change one of our companies because it's stock data was not exsist
 - Had to group data quarterly to align with financial statement data


•	Discuss any problems that arose after exploring the data, and how you resolved them.
   - It was near impossible to try to find and visualize the correlation beteeen mobility data and financial statment data as mobility was daily and the latter was quartlery 
   - Certain groupby functions gave us future dates that did not exsist in our time yet
   

	##Data Analysis

•	Discuss any additional questions that came up, but which you didn’t have time to answer: What would you research next, if you had two more weeks?
 - Due to the fact that 50% of our time was devoted to finding appropriate data , we firmly state that we did have the sufficient time to write cleaner, and more fficient code as it would've included additional complexity and revision. We wouldve enjoyed to write better code however this was not possible. 
 
 - We wouldve wished to conduct a segmentation analysis on company revenues and where they have been impacted the most geographically as each state in the USA had different COVID restrictions 
 
 - We more we would have done a more in depth analysis and came up with more insightfull data 



# Introduction of a Comprehensive System to Prevent Rumors

Project Brief: 
We are tackling rumor spreading problem in the context of Bangladesh.
Our project detects rumor by integrating three steps- Crowdsourcing, Automated prediction & Campaigning. Here the first step works based on a browser extension & website to gather consumers’ report. The second step utilizes google search API  along with machine learning algorithm to predict genuineness of a news. Finally, the third step is an automated anti rumor campaigning.  
So we approach the solution in three steps:  
-Crowdsourcing  
-Automated Prediction  
-Automated Campaigning  

## Step 1: Crowdsourcing  
In this step, we gather feedback/reports from the mass people. For this purpose a web based solution is developed where anyone can give their opinion on the authenticity of a news. The solution consists of a browser extension & a website. The browser extension will be installed on the user’s device which will detect news on any social media the user is currently visiting. Then the user can cast vote on the news through the extension. There will be a website as well which will display all the probable rumors the system has predicted so far. Moreover, users can also cast vote on any currently undisputed news from that site.  
## Step 2: Automated Prediction  
In this step, we estimate the possibility of a news being rumorous in a completely automated approach. Firstly, we search the news using Google search API. The search results corresponding to a fake news are supposed to be different from that of a real one. For instance, there should be multiple appearance of a genuine news in the top rated news portals where the fake news will merely appear in social media and some low ranked news portals. This distinguishing search results can be used as an informative feature for training purpose in a machine learning algorithm which will be later used to determine the chance of a news being rumorous. At the end of this step, we score each news (out of 100) on the basis of its genuineness.  
## Step 3: Automated Campaigning  
Based on the results derived from previous two steps, the authority will eventually determine whether a news should be considered rumorous or not. If it is marked as a rumor then an automated anti rumor campaigning will be launched on social media to make people aware of the fact.  
## Flow Chart:  
![GitHub Logo](/images/logo.png)



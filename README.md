# Clustering Assignment

### Problem Statement: 
HELP International is an international humanitarian NGO that is committed to fighting poverty and providing the people of backward countries with basic amenities and relief during the time of disasters and natural calamities. It runs a lot of operational projects from time to time along with advocacy drives to raise awareness as well as for funding purposes.
After the recent funding program’s, they have been able to raise around $ 10 million. Now the CEO of the NGO needs to decide how to use this money strategically and effectively. The significant issues that come while making this decision are mostly related to choosing the countries that are in the direst need of aid.

### Objective: 
Our job is to categorize the countries using some socio-economic and health factors that determine the overall development of the country. Then we need to suggest the countries which the CEO needs to focus on the most.

### Technical Approach:

• Using Hierarchical Clustering to identify the optimal cluster value.
• Use Silhouette and Elbow method to validate the optimal cluster value.
• Use K-Means Cluster method to build the final cluster model.
• Identify appropriate cluster for Financial Aid using Cluster Mean method.
• Analyze the Final Cluster Statistics against other clusters.
• Decision making on the final list based on the Descriptive Statistics of our Final Cluster.
• Choose the Top-10 Countries from the Final Cluster based on the Higher Child Mortality, Lower Income and Low GDP.
• Present the Final Report.

### Cluster Summary
Cluster __'Under Developed Countries’__ has the highest average __Child Mortality__ rate of __92__ , when compared to other 3 clusters and average __GDPP__ and __Income__ of __1909__ & __3897__ respectively.
All these figures clearly make this cluster the best candidate for the Financial Aid from NGO.
We could see that cluster __'Under Developed Countries’__ comprises of __29 %__ of over all data and has 48 obs. In comparison to 167 total obs.

![Capture1](https://user-images.githubusercontent.com/85448559/126029501-7fdba019-99a1-4f1d-ad43-3902a93c89e6.JPG)

### Final List of Countries from 'Under Developed Countries'
We concluded on the top 10 countries from the final cluster ( Under Developed Country ’’) based on the cluster median values of Child Mortality, Income and GDPP.

We filtered the countries with:
• __Lowest GDP
• Lowest Income
• Highest Child Mortality__

![Capture2](https://user-images.githubusercontent.com/85448559/126029574-1c492b0a-79e5-4a69-9a10-ab9c3e0a859d.JPG)




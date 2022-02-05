# hurricanes_climate_pred
Applied Data Science: Climate Prediction Challenges Project 1 

We have all been affected by hurricanes. Even just this past summer when Hurricane Ida hit the United States, Kate’s family was hit in New Orleans and she, George, Haoyue, and Muji were all hit by Hurricane Ida in New York. In just a few days, Hurricane Ida in NYC stopped our travel, killed at least 16 people, and “easily surpassed the $30 million threshold required for… a so-called major disaster declaration” (New York Times, 2021). Across the country from New York City, New Orleans is still recovering from Ida in February. Some businesses are still closed and many residential roofs still need to be replaced (Times-Picayune, 2022). 

Seeing all of this hurricane damage across the country begs the question, what kind of economic impacts do these storm tracks have, and have these impacts been rising with a relationship to the changing climate? 


We used hierarchical clustering to make 4 different clusters of hurricanes, roughly one with high damage, one with low damage, one with volatile changes in amounts of damage, and one with a medium amount of damage. From these clusters, we found that the leading characteristic that defined how much damage a hurricane causes is the distance of the track that the hurricane travels on land. This was much more important than wind speed or location of impact. 

From this analysis, we conducted a principal component analysis to try to identify why certain outliers happened in our different clusters. We were able to find that the outliers have a relationship with sea surface temperature. In our cluster 3, which usually does not have the highest damage but includes high outliers in the dataset, the sea surface temperature anomalies correspond with their increased damage more than any of the other variables in the dataset. This shows that when a hurricane might cause an average amount of damage, being formed during a sea surface temperature anomaly could take it from being a Hurricane Henri to a Hurricane Ida. 

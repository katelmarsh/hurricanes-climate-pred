# Hurricanes tracks and their economic impacts in a changing climate
Applied Data Science: Climate Prediction Challenges Project 1 

We have all been affected by hurricanes. Even just this past summer when Hurricane Ida hit the United States, Kate’s family was hit in New Orleans and she, George, Haoyue, and Muji were all hit by Hurricane Ida in New York. In just a few days, Hurricane Ida in NYC stopped our travel, killed at least 16 people, and “easily surpassed the $30 million threshold required for… major disaster declaration” (Newman, 2021). Across the country from New York City, New Orleans is still recovering from Ida in February. Some businesses are still closed and many residential roofs still need to be replaced (McNulty, 2022). 

Seeing all of this hurricane damage across the country begs the question, what kind of economic impacts do these storm tracks have, and have these impacts been rising with a relationship to the changing climate? 


We used hierarchical clustering to make 4 different clusters of hurricanes, roughly one with high damage, one with low damage, one with volatile changes in amounts of damage, and one with a medium amount of damage. From these clusters, we found that the leading characteristic that defined how much damage a hurricane causes is the distance of the track that the hurricane travels on land. This was much more important than wind speed or location of impact. 

From this analysis, we conducted a principal component analysis to try to identify why certain outliers happened in our different clusters. We were able to find that the outliers have a relationship with sea surface temperature. In our cluster 3, which usually does not have the highest damage but includes high outliers in the dataset, the sea surface temperature anomalies correspond with their increased damage more than any of the other variables in the dataset. This shows that when a hurricane might cause an average amount of damage, being formed during a sea surface temperature anomaly could take it from being a Hurricane Henri to a Hurricane Ida. 


Citations
- Dare, R., & McBride, J. (2011). The Threshold Sea Surface Temperature Condition for Tropical Cyclogenesis. *Journal Of Climate*, 24(17), 4570-4576. doi: 10.1175/jcli-d-10-05006.1
- McNulty, I. (2022, January 19). What's ahead for restaurants, bars closed since Hurricane Ida? answers vary widely. NOLA.com. Retrieved February 5, 2022, from https://www.nola.com/entertainment_life/eat-drink/article_699723b2-74bc-11ec-8d6d-0ba9ad05bd40.html 
- Newman, A., & Ferré-Sadurní, L. (2021, November 12). As ida deaths rise, N.Y. leaders look toward future storms. The New York Times. Retrieved February 5, 2022, from https://www.nytimes.com/live/2021/09/03/nyregion/nyc-flooding-ida#:~:text=Even%20so%2C%20state%20leaders%20said,people%20were%20still%20without%20electricity. 
- Weinkle, J., Landsea, C., Collins, D., Musulin, R., Crompton, R., Klotzbach, P., & Pielke, R. (2018). Normalized hurricane damage in the continental United States 1900–2017. *Nature Sustainability*, 1(12), 808-813. doi: 10.1038/s41893-018-0165-2

Datasets Used
- IBTrACS version 04 (Knapp et al., 2010) Knapp, K. R., M. C. Kruk, D. H. Levinson, H. J. Diamond, and C. J. Neumann, 2010: The International Best Track Archive for Climate Stewardship (IBTrACS): Unifying tropical cyclone best track data. Bulletin of the American Meteorological Society, 91, 363-376. doi:10.1175/2009BAMS2755.1 
- ERSST (Huang et al., 2017) Boyin Huang, Peter W. Thorne, Viva F. Banzon, Tim Boyer, Gennady Chepurin, Jay H. Lawrimore, Matthew J. Menne, Thomas M. Smith, Russell S. Vose, and Huai-Min Zhang (2017): NOAA Extended Reconstructed Sea Surface Temperature (ERSST), Version 5. [indicate subset used]. NOAA National Centers for Environmental Information. doi:10.7289/V5T72FNM


This project was written on Google Collab, which is available [here](https://colab.research.google.com/drive/15e5MMJmi2RwVWZg9UV0wh5mKtxJjp82U?usp=sharing). The file is also available in this repository. 

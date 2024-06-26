# Ottawa Rental Market
1)	Provide one or more visualizations explaining how rental costs have changed in the Ottawa-Gatineau area over the last 10 years.


Prices followed a steady upward trend until 2018, and since then, there has been a noticeable shift in growth patterns, reflecting the dynamic nature of the market. A similar trend can be seen in all unit types.
![Image](Data/Ottawa_Gatineau_Area_Average_Rent_by_Year.png)
   

![Image](Data/rent_per_year_per_unit_type.png)


 

a.	How this change differs between Ontario and Quebec
In our data analysis, a notable challenge arises with city names, specifically the Ottawa-Gatineau area, which are labeled in three distinct ways: under Ontario, Quebec, and an unspecified category (Ontario/Quebec), leading to uncertainty about their precise geographic allocation for the last set.
Looking at the graphs, prices within the unspecified category closely align with Ottawa prices, consistently lower, suggesting a possible association with Ottawa's suburbs. It was decided to keep this data in a separate category to avoid any effect on the Ottawa  area data. As can be seen, one-third of our data is categorized in the unspecified category.


![Image](Data/Quebec_Vs_Ontario.png)  

The price trends in Gatineau and Ottawa closely mirror each other, yet consistently, the prices in Gatineau are lower across all types of units.

![Image](Data/Quebec_Vs_Ontario_bachelor.png)  

![Image](Data/Quebec_Vs_Ontario_one_bedroom.png)  

![Image](Data/Quebec_Vs_Ontario_Two_bedroom.png)  
 
![Image](Data/Quebec_Vs_Ontario_Three_bedroom.png)  

b.	Visualization(s) that clearly depict how the “Type of Structure” may or may not contribute to different rental pricing

Using the Seaborn library, a popular Python data visualization tool a heatmap was created, a graphical representation of data in a matrix format where colors represent correlation values. The visualizations clearly show that rental prices are primarily linked to the year and type of units, rather than the type of structure. This indicates that the type of building has minimal impact on rental rates.

 ![Image](Data/heatmap.png) 

In our analysis, we observed a notable price difference when it comes to row structures with three units or more, indicating a significant compared to other structure types. Interestingly, noted a distinct trend in this category, where prices experienced a drop from 2019 to 2020, followed by a rise in the following years. They are showing that the price effects of the unit structure are becoming less. The trend of price for the other types is the same and close to each other.
 
	
c.	How the overall average compares to Toronto, Montreal, and Vancouver areas
As we can see the rental prices in Ottawa-Gatineau, Toronto, Montreal, and Vancouver varied significantly. On average, Toronto and Vancouver tended to have higher rental costs compared to Ottawa-Gatineau and Montreal.

 ![Image](Data/Ottawa_Vs_Montreal_Vs_Toronto_VS_Vancouver.png) 

In this graph, the box plot of the rent data for each major city for a two-bedroom apartment from 2021 to 2022 is presented. As can be seen, the Ottawa-Gatineau area has the widest distribution in the rental market. This is caused by the difference in rental prices in Ottawa and Gatineau and affects the average rental in this area.
 
 

2)	Provide any additional findings you discovered and found interesting.

Ottawa is hiding in the data by representing itself as the Ottawa-Gatineau Area! Here you can see the two-bedroom apartment average rent for 2022 in each city. Ottawa should be ranked 7th but including Gatineau data it goes to 16th.

 


Surprise high rent city for me was Yellowknife with 1815$ for a two-bedroom in 2022 as you can see in the Tableau map below. 
 

You need to be at least 100 km away from Toronto to save 900$ on rent with the information from the 2022 dataset!
 



3)	Compare the rent growth to the Consumer Price Index (CPI)
Consumer Price Index was obtained from this website:   https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=1810000501
Full data was imported and compared to our data. The base year was 2002 so we had to bring 2002 to 2022 data for this analysis on both datasets.

 ![Image](Data/CPI_canada.png) 
 
 ![Image](Data/CPI_Ottawa_VS_canada.png) 


In the first graph, the all-item CPI of Canada is compared to the rent growth CPI that the initial data showed. In the second graph, the focus is the Ottawa-Gatineau area. As the CPI is calculated using whole Canada rent from 2002, the CPI for Ottawa-Gatineau starts from 140. It can be seen that the trend is similar up to 2019 and afterward, it rising more rapidly.

   





More investigation can be done in several fronts including inflation, rate increases and etc. It is important to know the audience and beneficiaries to perform further analysis.

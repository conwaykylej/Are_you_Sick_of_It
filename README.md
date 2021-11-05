# Are You Sick Of It? :thought_balloon: 
![Healthcare Costs ](https://user-images.githubusercontent.com/16246354/140255257-fd2f5861-984e-4a02-a475-963fd9aeab5a.jpg)

# Are You Sick Of It? - An Analysis of Happiness and Healthcare 

# Background: :earth_americas::earth_africa::earth_asia:

We investigated the impact Healthcare costs have on perceived happiness using data available from the World Bank and The World Happiness report for the year 2016. 

The World Happiness report contains survey data from over 150 countries where numerous variables were collected such as a country's GDP(per capita), and the average life expectancy . 

## Questions We Asked::speech_balloon:
We intuitively theorized that the quality of a country's healthcare would significantly contribute to their happiness score. A country with more resources could spend more on healthcare, thus effecting happiness. But, is it true? Can we prove that? If we can, which factors are more significant?

Given the amount of variables available in our dataset, we each narrowed our investigation. We branched off tackling more specific questions between two key factors. 

### Happiness::smile:
- What trends can we draw from the top 10 happiest countries and the bottom 10?
- Is there a relationship between health expenditure paid for by the public and happiness score? 
- Would paying out of pocket costs effect happiness?
- If a country had more physicians/nurses per 1000 people, would that correlate to happiness?

### Expenditures and GDP(per capita)::dollar:
- Would a country's GDP effect happiness? 
- Could GDP be related to life expectancy?
- How are these countries paying for total health expenditures overall? What percentage is funded publically versus out of pocket?
- When comparing regions, what percentage pay out of pocket versus government spending? 

# :page_facing_up:Our Data :bar_chart:

  **First, we tackled the top 10 happiest countries to discover what, if anything, they have in common with one another.**
  
  - After grouping the top 10 together, we compared factors such as GDP/Health Out of Pocket, Freedom/GDP, and Life Expectancy/Family. 
      
      - Almost none of the data displayed positive correlations at all.  Below is the graph for GDP and Health Expenditure Out of Pocket. At best, this shows a weak correlation. 
 
 ![image (1)](https://user-images.githubusercontent.com/16246354/140402984-653eb59a-7699-4b91-9a4d-ff13dbce2bcf.png)

 - Switching scopes, we grouped by upper and lower quartiles.
    
    - The below graphs demonstrate how weak our variables are correlated to one another. We compared the quantity of Healthcare providers(per 1000 people) to the                         Happiness Score. 

![Two graphs](https://user-images.githubusercontent.com/16246354/140404110-db03fef5-cf6b-46ec-a8e7-5cf832517ea5.png)

 - With the lack of concrete leads here, we decided to change our approach to the data. 
   
   - We changed the Happiness Score to Life Expectancy and compared it against the number of Healthcare providers. 
 
   - Here, we can see that the number of available providers is a good predictor of life expectancy. The more doctors and nurses that are available, the more likely you are to         live longer.

![Phy](https://user-images.githubusercontent.com/16246354/140409670-de3d9cf1-f823-487b-bf23-304dcce59941.png)![Nurses](https://user-images.githubusercontent.com/16246354/140409678-9e77f425-a99a-4e3d-acfc-59a65b2485a0.png)

**Next, we took a large scale view of the countries by grouping them into regions. We are looking at the relationships(if any) between Happiness, GDP and Life Expectancy.**
 - We can see that the happiest regions are: New Zealand/Australia, followed by North America and Western Europe. 

 - Looking at Life Expectancy on a regional scale we can see that the trend has changed. New Zealand/Australia retains the number 1 spot, but North America has been overtaken by    Western Europe and Eastern Asia leaving North America 4th overall.  
 
 ![happiness score by region](https://user-images.githubusercontent.com/16246354/140433778-0207d3a7-36f4-4b95-b13e-76e758a28809.png)![life expect by region](https://user-images.githubusercontent.com/16246354/140433783-f080c340-3470-40fc-b8c1-795a13a517d8.png)

 - With the previous graphs in mind, we dived into comparing the percentage of Out OF Pocket Health Expenditure vs Public Expenditure. We organized the regions by Happiness to     see where the top Happiest Regions spent their healthcare money. Once we saw the data, we can see there is a weak correlation between Regions using the Public option more so     than relying on Out of Pocket Expenses.  
 
    - In addition, we add another X variable, Life Expectancy. The results were surprising. We can see that the more Out Of Pocket Expenses were relied upon, the life expectancy       tended to decrease though it is only a weak correlation. (The percentages do not total 100%. This could be due to outside expenses not counted within either the public or           private option. Such as seeking treatment outside of one's residential country.) 
 
 
 ![download](https://user-images.githubusercontent.com/16246354/140437068-967cdb9b-dd34-406d-ad24-4bd7e4369ebc.png)

 
 **Following the trends from the previous data dive, we decided to take "snapshots" of random countries to draw insights using both the Top and Bottom ends of the Happiness       rank.**

- Using Happiness and Out of Pocket Expenditure we see a trend where the lower ranked countries have incredibly high Expenditure costs compared to their higher ranking             counterparts.  
![Snapshot of Happiness and Out of Pocket Expenditure](https://user-images.githubusercontent.com/16246354/140437790-b6d65e0f-a7af-4488-a0d6-9d272d7813f6.png)

- Once again, we took a look at the percentage of total Health Expenditure. This time we continued using "snapshots" and added two different X variable lines along the graph;     Freedom score & Life Expectancy. 

  - Weak trends again emerged, but with the added unexpected correlation of Freedom. It seems that Freedom followed along with Life Expectancy overall with the exception of         notoriously militant governments such as the Congo and Nigeria.
  
 ![Happiness and Health Expenditure by Public and Private](https://user-images.githubusercontent.com/16246354/140437400-bb6d8284-5dfb-411d-b701-94ff9451c8d2.png)

 
   **To better illustrate which countries scored higher for given variables, we generated the following Heatmaps:**
 
   - Heatmap of the Happiest Countries:

![Happiness Heatmap](https://user-images.githubusercontent.com/16246354/140405045-765ee2d8-e5ff-4a6e-8acc-c40a85b8f0e2.png)
    
   - Heatmap of Life Expectancy:
    
![Life Expectancy Heatmap](https://user-images.githubusercontent.com/16246354/140406597-99c29ea0-4bf6-42a3-b9fb-da9d572a8820.png)

  



# :question: What Does It All Mean :grey_question:

Well, it means that we can't definiteively say much. We worked off of theories that happiness would be affected by wealth like a country's GDP or spending habits regarding Healthcare. Though in some instances there are weak correlations such as the total Healthcare Expenditure percentages and Life Expectancy, the fact is, we can't make any statements concretely pointing to any cause. 

**Trends** that we did have some evidence for is the effect Life Expectancy had on the Happiness Score. Living longer is a decent reason to be happier overall. And that seems to bare out in the data. 


**Limitations** are a given when merging data from different organizations. As we investigated answers to our questions, we realized that a one year comparison just isn't long enough time to see common trends. We can make some general guesses, but as we've demonstrated, we were clearly overestimating how far removed these variables are from each other. To get a better understanding of happiness, we should look to include factors like government stability, education, and access to basic living necessities as equally important. 

- Another contending factor in our analysis is that we really don't know what social/political/ events occured that can skew the data for variables like Freedom or available       Physicians/Nurses. Also, there may be epidemics on a country wide scale that pushed countries lower on the ranking list for Life Expectancy.  




# Sources: :clipboard:
-  [The World Happiness Report Analysis on Kaggle](https://www.kaggle.com/alicjapiaskowska/world-happiness-report-20152020-analysis)
  - [FAQ World Happiness Report](https://worldhappiness.report/faq/)
  - [World Bank GDP Ranking Data on Kaggle](https://www.kaggle.com/theworldbank/world-bank-gdp-ranking)
  - [The World Bank on DataBank ](https://databank.worldbank.org/home.aspx)




#TeamViper:snake:![Viper 1](https://user-images.githubusercontent.com/16246354/140391645-78395674-b393-4dda-8ed8-ab80613a79ae.png):snake:

Thank you Amanda, Kyle, Jenny, and Lindsay for your hard work and analysis!

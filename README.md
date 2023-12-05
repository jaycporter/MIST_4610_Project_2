# Team 1 Mist 4610 Group Project 2

## Team Members 
1) Jessie Wong [@jw35468](https://github.com/jw35468)
2) Jessica Wang [@jw34666](https://github.com/jw34666)
3) Jayla Porter [@jaycporter](https://github.com/jaycporter)

## Dataset Overview 
This dataset was obtained through the provided website (https://catalog.data.gov/dataset) and provides data regarding car accidents in New York from 2016 to 2022. The dataset itself is extremely extensive and contains thousands of rows and 30 columns. Each row in the dataset represents a different collision and each column is a different characteristic of the collision. For example, the location, time of day, date, leading cause of the collision, and the number of people injured are all included. For the purposes of our analysis, we focused on the following features: Borough, Collision ID, Contributing Factor, Crash Date, Crash Time, and Number of Persons Injured. 

The breakdown of the data types is as follows: 

<img width="644" alt="Screenshot 2023-12-05 at 12 24 14 AM" src="https://github.com/jw34666/MIST_4610_Project_2/assets/145144734/c8017d11-40d0-4f5e-869a-8b56a7020801">

# Question 1

Car accidents are a major public safety issue that can have devestating impacts to all persons and properties involved. Specifically in urban areas such as New York, car accidents pose more complex patterns as there are more factors at play such as time of day, day of the week, and location. The dataset we chose provides a diverse set of information we've used to explore these different factors. We decided we wanted to understand whether the frequency and severity of these collisions increase at certain times of the day, potentially correlating with rush hours or late-night periods when driver alertness may vary. Additionally, we considered it crucial to investigate if the patterns of these incidents differ on weekdays compared to weekends, as traffic dynamics and driver behaviors can change between workdays and leisure days. Another aspect of this analysis involves discerning if these trends are consistent across different boroughs of New York or if specific areas exhibit a higher propensity for accidents, possibly due to factors like urban density, road design, or local traffic regulations. Ultimately, our goal is to identify the times and locations where the probability of getting into a crash is highest, offering insights that could be pivotal in guiding traffic management and urban planning decisions to enhance road safety.

This prompts us to ask the question: 

## Is there an increase in crashes depending on day and time of the week? If so, is it the same across all boroughs or specific ones? From this data, what time and location would give the highest probability of getting into a crash? 

Importance: 

The importance of understanding the variability in car collisions with respect to time and location is crucial as it directly impacts public safety, influences local governing policies, and guides city planning and development. Insight into when and where crashes most frequently occur can lead to more effective safety measures, allowing for strategic emergency response planning and better informed public safety initiatives. Preventative measures and messages can be spread to the local community to raise awareness for certain issues and this can also help to prevent future collision. For policymakers, such data is invaluable in creating more targeted and effective traffic regulations, while urban planners can leverage this knowledge to design safer roads and improve existing infrastructure. This information can be used to adjust signal timings and manage congestion more dynamically, potentially preventing accidents before they happen. Furthermore, this knowledge benefits insurance companies by refining risk assessments and contributes to raising driver awareness, encouraging safer driving practices at known high-risk times. Ultimately, the integration of these improvements can also yield environmental benefits by reducing congestion-related emissions, illustrating the why we considered this question to be of importance. 

<img width="1440" alt="Screenshot 2023-12-05 at 12 28 39 AM" src="https://github.com/jw34666/MIST_4610_Project_2/assets/145144734/0d5efb61-6ce1-4f73-b02c-beb820dc37bc">

Analysis: 


The graph depicting Total Crash vs Time of Day shows that there is a peak in crashes around 5pm and a significant dip in crashes around 4am. This can align with rush hour that suggests there is a higher volume of traffic that could cause some drivers to be hurried and crash. Because the graph fluctuates, there isn’t a steady number of crashes throughout the day which is better for law enforcement so they know what times to be on the road for patrolling. Looking at the Crashes By Borough graph, we see that the trend follows the same trend as the Total Crashes vs Time of Day graph with a high peak at 4pm. The graph separates the different lines by the different boroughs( the colors and corresponding borough is on the left legend) and we can see that Brooklyn has the highest number of crashes, totaling a peak of 1000 crashes at 5pm. Further analyzing the different boroughs, we may take into consideration that the reason Brooklyn is so high could also be due to their high population as well. According to the US census, Brooklyn averages 2 million in population whereas Staten Island has only 300 thousand. So this doesn’t necessarily mean that Brooklyn has its own unique attribute that causes more crashes, but may simply be because there is a higher population which leads to more crashes. Looking at the graph that depicts Crashes vs Days of the Week, we can see that the graph is pretty steady with a slight increase in crashes on Friday. This could be attributed to travel or people going out that could cause more reckless driving. However because there is a steady trend throughout the week, weekday doesn’t seem to be a strong variable that may indicate crash numbers as much as time. 

# Question 2

Going off of the information collected from our first question, we then wanted to consider what the leading cause of these accidents and which causes had the biggest impact on the wider community. Understanding this would be monumental in considering what preventative action can be taken by the local government in order to educate and protect the community. Our goal was to recognize what caused the most accidents and what factors caused the most damage in terms of persons injured. From this, we also wanted to consider if there were other outlying factors that affected the listed cause of collision such as time of day. We considered these factors to be important to the community in figuring out what steps should be taken by local governments or groups to prevent the most deadly types of accident. 

This prompted us to ask the question: 

## Q2: Of the accidents recorded, what were the leading causes? How many people were injured due to these types of accidents? Is there a correlation between a certain cause of accident and time of day?

Importance: 

The importance of this question leads into the causes of car accidents. In our dataset, it outlines over 7 different causes of car accidents. Knowing this type of information is crucial for law enforcement to be able to mitigate the risks of car accidents by knowing how likely certain risks are. In terms of a managerial point of view, some companies can implement more safety measures based on if there has been a higher risk of accidents. For example, car companies have already begun to implement auto drive to try to mitigate the risk of human error and driver inattention of its customers. Companies would also be able to use this information to create their measurable objectives when improving their next product. For example, if following too closely to the car in front was a common cause of accidents then a company could create their key objectives to mitigate this issue and more customers on the market would be more inclined to buy it for its safety measures. Our second set of graphs are more specific on analyzing the times at which a certain cause of accident occurs. Knowing the correlation between certain causes and time of day will also aid in reducing the risk of accidents. Being informed that driver inattention happens during a certain time will caution drivers to be more alert and safer during those times to avoid other driver error. Companies can also use this information when proposing important delivery times by avoiding these high accident times, since that would be more traffic for their deliveries. Knowing the specifics also allows law enforcements to be on patrol on certain times if they know the probability of an accident is more likely to happen. 

<img width="1440" alt="Screenshot 2023-12-05 at 12 28 48 AM" src="https://github.com/jw34666/MIST_4610_Project_2/assets/145144734/e0c6ec8d-c1cb-4c0b-b262-e26c2b52911b">

Analysis: 

According to the graph, driver distraction is the number one cause of accidents with a total of 15,746 people who have been involved with distraction related accidents. Due to the high volume of social media as well as messaging, it is not surprising that this has caused such a high volume of accidents. It is also crucial to note that the difference between the top cause of accidents (driver inattention) and the second and third causes (following too closely and failure to yield) have a significant relative difference. With driver inattention having a total of 15,746 causes accidents, failure to yield and following too following is only around 4,000. Another reason that driver inattention may be so high is that there is a correlation between driver inattention and other related causes. Meaning that failure to yield is because of driver inattention. Knowing this information and after doing a deeper analysis, we will know if the decrease in one cause will lead to the decrease in another. 
According to the detailed graphs on driver inattention vs time, it shows that 4-5 o’clock is where the highest number of accidents occur. This graph is a left skewed normal graph which indicates that the mean and median fall within the central peak region of the graph (around 4-5 o’clock). This means that on average, most accidents fall within this region. Because this graph is left skewed, it tells us that there tends to be more accidents near the lattar half of the day instead of the beginning half. This attribute could be due to rush hour and likely chance that more people will be checking their phones during traffic. 
Looking at the second detailed graph, the cause failure to yield has a graph shape that also falls closely with driver inattention. This means that there may be a correlation between driver inattention and failure to yield. We could analyze that because a driver is not paying attention as much that they are less likely to yield. This graph shows that they have peaks of highest accidents at the same time as driver inattention (4-5 o’clock) and that they are both left skewed, meaning there are more accidents on the second half of the day. 
Lastly, we looked at the detailed graph of alcohol consumption and crashes depending on the time of day. This graph is a concave U shape which indicates that the mean and median both lie on opposite sides of the x axis. This can tell the reader that the highest number of crashes occurs very early in the morning (4 am) and very late at night(10pm). We could see that the range of the highest chances of data fall between that 10pm-4am threshold. This could be attributed to the fact that these times are ‘going out time’ where the chances of alcohol consumption are greater. Another thing to note is that in relation to the other graphs, alcohol consumption is the leading cause of accidents on times that driver inattention and failure to yield is not. This information could be helpful for law enforcement so that they patrol differing areas at different times. For example, patrolling a bar at 4 am versus an office building near 5 pm. 


## Manipulations 
The main point of manipulation our team decided to perform on our dataset was to omit data we deemed unncessary. We did this by analyzing the overall data and deciding what was most relevant and what we wanted our questions to focus around. This mostly ended up being about the causes of collisions, and the trends of specific causes throughout a 24 hour period. By understanding what we wanted to answer, we were able to manipulate our dataset into one that displayed clear conditions. Without doing this, our dataset would be much larger and would carry more unncessary information that would make the purpose of our questions more difficult to understand. 

## Works Cited 

“America.” New York City Boroughs (USA): Boroughs - Population Statistics, Charts and Map, www.citypopulation.de/en/usa/newyorkcity/#google_vignette. Accessed 5 Dec. 2023. 

## Tableau Packaged Workbook 
The Tableau packaged workbook is attached to this repository. The visualizations are located on dashboards corresponding to their respective questions. 

## Sources 

“America.” New York City Boroughs (USA): Boroughs - Population Statistics, Charts and Map, www.citypopulation.de/en/usa/newyorkcity/#google_vignette. Accessed 5 Dec. 2023. 

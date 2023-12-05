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

Motor vehicle collisions are a major public health and safety issue, with impacts ranging from personal injury and property damage to significant societal costs. Motor vehicle collisions, a significant concern in urban areas, present complex patterns influenced by various factors such as time of day, day of the week, and geographical location. The dataset provides a rich source of information to explore these nuances. We seek to understand whether the frequency and severity of these collisions increase at certain times of the day, potentially correlating with rush hours or late-night periods when driver alertness may vary. Additionally, it's crucial to investigate if the patterns of these incidents differ on weekdays compared to weekends, as traffic dynamics and driver behaviors can change between workdays and leisure days. A crucial aspect of this analysis involves discerning if these trends are consistent across different boroughs of the city or if specific areas exhibit a higher propensity for accidents, possibly due to factors like urban density, road design, or local traffic regulations. Ultimately, our goal is to identify the times and locations where the probability of getting into a crash is highest, offering insights that could be pivotal in guiding traffic management and urban planning decisions to enhance road safety.

This prompts us to ask the specific question: 

## Is there an increase in crashes depending on day and time of the week? If so, is it the same across all boroughs or specific ones? From this data, what time and location would give the highest probability of getting into a crash? 

Importance: 

The significance of understanding the variability in motor vehicle collisions with respect to time and location is multifaceted, impacting public safety, influencing policy, guiding urban development, and optimizing traffic management. Insight into when and where crashes most frequently occur can lead to more effective safety measures, allowing for strategic emergency response planning and better informed public safety initiatives. For policymakers, such data is invaluable in creating more targeted and effective traffic regulations, while urban planners can leverage this knowledge to design safer roads and improve existing infrastructure.This information can be used to adjust signal timings and manage congestion more dynamically, potentially preventing accidents before they happen. Furthermore, this knowledge benefits insurance companies by refining risk assessments and contributes to raising driver awareness, encouraging safer driving practices at known high-risk times. Ultimately, the integration of these improvements can also yield environmental benefits by reducing congestion-related emissions, illustrating the impactfulness of answering such a pivotal question.  


<img width="1440" alt="Screenshot 2023-12-05 at 12 28 39 AM" src="https://github.com/jw34666/MIST_4610_Project_2/assets/145144734/4974bbf0-2ffe-4f7d-ae76-ab7e4c232dfd">

Analysis: 

The graph depicting Total Crashes vs Time of Day indicates a surge in collisions around 5 PM, aligning with the end of the workday and suggesting that rush hour traffic significantly influences crash likelihood, possibly due to increased traffic volume and hurried drivers. The Crashes by Borough graph reveals that Brooklyn, with its population of 2,590,516 as per the 2022 Census, records the highest number of crashes, which may be attributed to its dense population, more vehicles on the road due to a denser population, and potentially complex road networks. Further, the Crashes vs Days of the Week graph shows that Friday marginally leads in crash numbers, hinting that the end-of-week dynamics, such as weekend commutes or social outings, might increase traffic and impact driver focus, contributing to a rise in accidents.
From the data, the time and location with the highest probability of getting into a crash would be around 5 PM on a Friday in Brooklyn. This time reflects the rush hour conditions, and the day signifies the end-of-week traffic patterns, both of which appear to elevate the risk of collisions. Brooklyn, as the borough with the most crashes, represents the location with the greatest probability of an accident according to the data.


# Question 2

## Q2: Of the accidents recorded, what were the leading causes? How many people were injured due to these types of accidents? Is there a correlation between a certain cause of accident and time of day?

Importance: 

The importance of this question leads into the causes of car accidents and in our dataset, it outlines over 7 different causes of car accidents. Knowing this type of information is crucial for law enforcement to be able to mitigate the risks of car accidents by knowing how likely certain risks are and which risks need more thorough attention. In terms of a managerial point of view, some companies can implement more safety measures based on if there has been a higher risk of accidents. For example, car companies have already begun to implement auto drive to try to mitigate the risk of human error and driver inattention of its customers. Also knowing the correlation between certain causes and time of day will also aid in reducing the risk of accidents. Being informed that driver inattention happens during a certain time will caution drivers to be more alert and safe during those times to avoid other driver error. Companies can also use this information when proposing important delivery times by avoiding these high accident times, since that would be more traffic for their deliveries. 

<img width="1440" alt="Screenshot 2023-12-05 at 12 28 48 AM" src="https://github.com/jw34666/MIST_4610_Project_2/assets/145144734/e0c6ec8d-c1cb-4c0b-b262-e26c2b52911b">

Analysis: 

According to the graph, driver distraction is the number one cause of accidents with it averaging 15746 people who have been involved with distraction related accidents.  Due to the high volume of social media as well as messaging, it is not surprising that these causes have caused such a high volume of accidents. Following driver inattention is failure to yield to the right of way and following too closely. According to the detailed graphs on failure to yield vs time and driver inattention vs time, around four-five o'clock is when most of these accidents occur. Because most jobs get off at 4-5 pm, there is a higher risk of getting stuck in traffic hours which causes drivers to become distracted and ultimately reckless. 

## Manipulations 
The main point of manipulation our team decided to perform on our dataset was to omit data we deemed unncessary. We did this by analyzing the overall data and deciding what was most relevant and what we wanted our questions to focus around. This mostly ended up being about the causes of collisions, and the trends of specific causes throughout a 24 hour period. By understanding what we wanted to answer, we were able to manipulate our dataset into one that displayed clear conditions. Without doing this, our dataset would be much larger and would carry more unncessary information that would make the purpose of our questions more difficult to understand. 

## Tableau Packaged Workbook 
The Tableau packaged workbook is attached to this repository. The visualizations are located on dashboards corresponding to their respective questions. 

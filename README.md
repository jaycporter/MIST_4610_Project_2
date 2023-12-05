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

## Q1: Is there an increase in crashes depending on day and time of the week? If so, is it the same across all boroughs or specific ones? From this data, what time and location would give the highest probability of getting into a crash? 

Importance: 

<img width="1440" alt="Screenshot 2023-12-05 at 12 28 39 AM" src="https://github.com/jw34666/MIST_4610_Project_2/assets/145144734/4974bbf0-2ffe-4f7d-ae76-ab7e4c232dfd">

Analysis: 


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

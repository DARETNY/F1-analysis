
# F1 Analysis
![image](https://github.com/user-attachments/assets/c9aee1f2-f550-4e2f-b952-ab5952ef6b5e)


## Links

 [Google colab link](https://colab.research.google.com/drive/1TKFGAmsjlmM6NoIdwA08cjS7smdwJiDI?usp=sharing)

 [Kaggle lnik](https://www.kaggle.com/code/kadirallolu/f1-analysis)

## Road to the Championship in Formula 1: Speed ​​or Strategy?
 Formula 1 is one of the world's most exciting and competitive motorsport, where speed, strategy, engineering and human talent come together. So what separates an F1 champion from the rest? Speed ​​during pit stops or mastery of strategy? Is it just the speed of the vehicle or the intelligence and decision-making ability of a pilot that is more important?

 This project aims to conduct an in-depth analysis of F1 champions to understand their performance and race strategies. We will examine how pit stop times, race order, speed and even the driver's personal experiences affect the path of a champion. "What do the best do to be the best?" Answering the question is one of the most fundamental and interesting questions of this sport.

 This study aims to shed light on these important questions through analyzes conducted on F1 data sets. With this project, we will discover how not only speed, but also strategy and driver decision-making processes are a determining factor on the path to the championship.


### Our object
 This project aims to thoroughly examine the racing performances of Formula 1's 10 most successful drivers. Both speed and strategy play critical roles in these drivers' success. We will analyze these drivers' data to understand the relationship between pit stop times, strategic moves made during the race, and the drivers' overall performance. This data-based analysis will reveal that Formula 1 is a sport that requires not only speed but also accurate timing and strategies. This project will help you understand why and how the best drivers are so successful.


# **Overview of F1 Pilots:**
   ![image](https://github.com/user-attachments/assets/1fece513-9064-402c-be04-864557a637e4)

 This chart ranks the 10 most successful drivers in Formula 1 history by the number of races they won. **Lewis Hamilton** and **Michael Schumacher** stand out on the chart with over 100 races won. While Hamilton is considered one of the most successful drivers of today, Schumacher has been one of the strongest names in Formula 1 for years. The high victory numbers of these two drivers were shaped not only by their driving skills, but also by strategy, pit stop management and the support of their teams.

 Although other drivers have also achieved significant success, legendary names such as **Jackie Stewart**, **Juan Fangio**, and **Niki Lauda** are ranked lower in terms of the number of races they have won. However, each of them are names that left their mark on the history of Formula 1 by displaying dominant performances in their own periods.

 The ranking in the chart shows that the success of the drivers depends not only on their personal abilities, but also on the strategic aspects of Formula 1, which is a team sport. The number of races won helps us understand how strongly drivers finish their careers and how Formula 1 has evolved over time.

## **Overview of the Top 10 Drivers by Points:**
   ![image](https://github.com/user-attachments/assets/189e07fb-0cc4-44b8-b2f1-9754d690dfc1)


 This chart displays the top 10 drivers with the highest total points in Formula 1 history. Drivers like **Lewis Hamilton**, **Sebastian Vettel**, and **Max Verstappen** are at the forefront, consistently occupying top positions in the championship standings.

**Insights from the Chart:**
1. **Lewis Hamilton** leads with over 50,000 points, showcasing his consistent top-tier performances and dominance over the years, aided by competitive cars.
2. **Sebastian Vettel** and **Max Verstappen** are also prominent, collecting between 30,000 and 40,000 points, reflecting their ongoing competitive nature.
3. **Michael Schumacher** maintained a dominant performance over the years, amassing more than 20,000 points.
4. **Nico Rosberg** had a brief but intense period of competition, securing between 10,000 and 20,000 points.
5. Other drivers, who have spent more time in mid-tier positions, highlight the dynamic and competitive nature of Formula 1.

This chart emphasizes the importance of the points system and how consistency plays a key role in a driver’s success. It also demonstrates how every race and season presents different challenges, and how drivers must constantly fight for position throughout their careers.

*so lets look at others how their wins*:
   ![image](https://github.com/user-attachments/assets/84847fa0-e929-44f9-97fb-e1aab788b423)


# **Title: Overview of the Top 10 Formula 1 Constructors by Performance**

#  ![image](https://github.com/user-attachments/assets/45efbdad-df04-476e-9d12-0a65d0b54f3e)

In Formula 1, the performance of a constructor plays a pivotal role in shaping the results of the season. Constructors are the teams responsible for building the cars, developing the strategy, and ensuring the overall success of their drivers. The following analysis highlights the top 10 constructors in Formula 1, based on their cumulative performance across various seasons.

These teams have demonstrated exceptional engineering, innovation, and consistency, with many of them dominating both the constructors' and drivers' championships over the years. The top 10 constructors represent a mix of established teams with decades of success, as well as newer entrants who have quickly made their mark in the sport.

From the powerhouse of **Mercedes** and **Ferrari** to the ever-competitive **Red Bull Racing**, each team has contributed to shaping the modern era of Formula 1 racing. Understanding the performance of these constructors not only showcases their technical and strategic prowess but also emphasizes the crucial role that teamwork plays in the high-stakes world of Formula 1.

## Win Condition by Overview

This bar chart presents the top 10 Formula 1 constructors ranked by the number of wins they have secured in the first position. The chart highlights the dominance of **Ferrari**, which leads with an impressive 234 wins, followed by **McLaren** and **Mercedes**, with 165 and 145 wins respectively. 

The chart also showcases other highly successful teams, including **Red Bull** with 120 wins, and **Williams** with 114. These teams have been integral in shaping Formula 1 history, contributing to countless memorable races and championships.

On the other hand, constructors like **Renault**, **Team Lotus**, and **Benetton** follow with fewer wins, but still boast significant achievements in their time. The chart also includes historical teams like **Lotus-Climax** and **Cooper-Climax**, which had substantial impacts on the early years of Formula 1.

The striking color gradient in the chart emphasizes the varying levels of success among the constructors, with the darker shades representing teams with fewer wins. This visualization illustrates the shifting landscape of Formula 1 success, where some constructors have been dominant for long periods, while others have risen and fallen throughout the sport's rich history.

*Since the gain graph is directly proportional to the wins, it is as shown in the figure*:
![image](https://github.com/user-attachments/assets/77ddb0cd-1cc6-4844-85c5-8e62cf4c5040)



### Let's take a look at the racers and their teams with our data
As seen below, there is a section from our data set.
```
driverName | constructorName | win_count
83093 	Lewis Hamilton 	Ferrari	125
83197	Lewis Hamilton	Williams	125
83144	Lewis Hamilton	McLaren	125
83167	Lewis Hamilton	Red Bull	124
91573	Michael Schumacher	Ferrari	121
...	...	...	...
45567	George Abecassis	Red Bull	0
45566	George Abecassis	Rebaque	0
45565	George Abecassis	Racing Point	0
45564	George Abecassis	RE	0
136319	Óscar González	Zakspeed	0
```

*Let's comment on our knowledge so far and what we have achieved.*-->

 The dataset does provide valuable insights into the relationship between drivers and their constructors, but it's important to note that winning in Formula 1 is influenced by a combination of factors. Here's how we can break down the question of whether the **constructor** is the key to a driver's success:

### 1. **Constructor Impact:**
   - **Top Teams Dominate**: Teams like **Ferrari**, **McLaren**, **Mercedes**, and **Red Bull** have a history of producing competitive cars, which significantly boosts a driver's chances of winning. These teams have superior engineering, resources, and support, often providing their drivers with the best tools to succeed.
   - **Constructor Strength**: In Formula 1, the constructor's performance directly impacts a driver's success. A strong constructor provides a fast, reliable, and well-engineered car, which is a critical factor in securing wins.

### 2. **Driver Skill:**
   - While the constructor plays a crucial role, **driver skill** is equally important. The most successful drivers, like **Lewis Hamilton** and **Michael Schumacher**, have proven themselves capable of delivering exceptional performances regardless of the car's specifications, showcasing that talent, experience, and adaptability also contribute significantly to victories.
   - A skilled driver can extract maximum performance from the car, help with car development, and make tactical decisions that enhance race results. These abilities can sometimes even allow a driver to perform better than the car might suggest.

### 3. **Team Dynamics and Support:**
   - **Teamwork and Strategy**: F1 teams work closely with their drivers, offering strategic support during races. The interaction between the driver and the team, including race strategy, pit stops, and real-time adjustments, can influence the outcome. For example, a team that’s known for having a great strategy might give their driver a competitive edge even if their car is not the fastest on the grid.
   - **Resources and Experience**: Top constructors often have the resources to attract top-tier engineers and technical staff, which can lead to continuous improvements in car performance throughout the season.

### 4. **Historical Context:**
   - Many of the most successful drivers in F1 history have raced with multiple teams. For example, **Lewis Hamilton** has won with McLaren and Mercedes, while **Fernando Alonso** won with Renault and Ferrari. This highlights that while the constructor matters, the driver’s ability to adapt and perform with different teams also plays a significant role in their success.

### Conclusion:
 While the constructor plays a significant role in a driver’s success—providing a competitive car and strong technical support—the driver’s individual skill, experience, adaptability, and team dynamics are equally essential. Therefore, **constructors are key**, but they are **not the only factor** in winning races and championships. The best drivers are often those who can perform well regardless of their constructor, extracting the maximum performance from the car they are given.

 ![image](https://github.com/user-attachments/assets/cd2acf25-d0e4-4e17-af27-2888e305da64)


# The Role of Pit Stops in Formula 1 Success
 
 Pit stops are a crucial component of Formula 1 strategy, with their speed and precision often determining the outcome of a race. In F1, a pit stop is the moment when a car enters the pit lane to have its tires changed, refueled (if necessary), and adjustments made to ensure optimal performance for the remainder of the race. The efficiency of a pit stop can have a significant impact on a driver's ability to maintain or gain positions, and it can often make the difference between winning or losing a race.

#### Key Points:
 1. **Speed and Precision**:
   The faster a team can perform a pit stop, the better chance the driver has of maintaining their position or even improving it. A well-executed pit stop, typically taking around 2-3 seconds in modern F1, ensures that the driver loses minimal time compared to competitors. In some cases, a fraction of a second can make all the difference in competitive races.

 2. **Strategic Timing**:
   The timing of a pit stop is equally important. A team's strategy will dictate when the driver should enter the pits for tire changes, depending on track conditions, weather, and the overall race scenario. Teams constantly monitor tire wear, track temperature, and other factors to optimize their timing and minimize race time.

 3. **Team Coordination**:
   A pit stop involves a high level of coordination and teamwork. From the tire changers to the engineer managing the stop, every member of the crew must perform their job flawlessly. The ability of the team to work under intense pressure is essential, and teams that consistently perform fast, accurate pit stops often have a competitive edge.

 4. **Impact on Race Outcomes**:
   A slow pit stop, or an error such as a stuck tire or a miscommunication, can cost a driver precious seconds and even positions. On the other hand, a well-executed stop can allow a driver to leapfrog competitors and maintain or gain track position, which can be crucial in close races.

#### Conclusion:
 Pit stops are not just about changing tires; they are a vital aspect of Formula 1 strategy and race performance. Teams that excel in executing fast, strategic pit stops often have a significant advantage, highlighting the importance of both the driver’s skills and the team's ability to perform under pressure. In Formula 1, every second counts—both on the track and in the pits.

### *let's look at the pitstops table and compare their wins*->

 In Formula 1, pit stop time is a crucial factor that can significantly influence race outcomes. A faster pit stop can allow a driver to gain track position, while a slow pit stop can cost valuable seconds and potentially drop a driver down the order.
 Generally, there is a negative correlation between pit stop time and wins. This means that:

 * Faster pit stops are associated with a higher likelihood of winning. Teams with efficient pit crews and drivers who execute their pit entries and exits flawlessly tend to have a competitive advantage.
 * Slower pit stops are associated with a lower likelihood of winning. A slow pit stop can result in losing track position, making it harder to overtake and ultimately reducing the chances of winning.
 **Conclusion**:  
  Fast pit stops or slow pit stops will not lead us to victory. An average pit stop is always more ideal. As can be seen in the chart, the best teams like Ferrari have become the best by making average pit stops.
 as u can see in the graph : ![image](https://github.com/user-attachments/assets/480a2db6-42f0-475d-bba0-47cd180cbb29)


### Summary: Key Insights from the F1 Analysis

 In this analysis, we've explored several critical factors that determine success in Formula 1, focusing on both driver performance and team strategy. Here are the key takeaways:

 1. **Role of Constructors**:
   - Constructors, such as **Ferrari**, **McLaren**, **Mercedes**, and **Red Bull**, play  a significant role in shaping the outcome of races. These teams provide high-performance cars, superior engineering, and tactical support that greatly influence a driver’s success.
   - However, while the constructor's strength is crucial, **driver skill** remains equally important. A talented driver can extract the maximum potential from the car, making strategic decisions that often lead to victories even with different teams.

 2. **Driver Performance**:
   - The top drivers like **Lewis Hamilton**, **Michael Schumacher**, and **Sebastian Vettel** have demonstrated that consistent performance, adaptability, and decision-making are key factors in their success. These drivers are known not only for their speed but also for their race strategies and ability to make the right calls under pressure.

 3. **Pit Stops: A Game-Changer**:
   - **Pit stops** are integral to Formula 1 strategy, and their speed and efficiency often determine the outcome of a race. Teams with fast, precise pit crews gain valuable seconds, potentially making the difference between winning and losing. Faster pit stops correlate with higher chances of victory, but it’s the consistency and strategic timing that make the greatest impact.
   - Teams with average pit stop times, like **Ferrari**, have shown that while speed is important, precision and consistency are the keys to maintaining a competitive edge.

 4. **Team Strategy and Coordination**:
   - Formula 1 is a team sport. Success is not just about the car and the driver but about teamwork, strategy, and the ability to adapt during the race. A great team provides the support a driver needs to make the right calls, plan optimal pit stops, and execute race strategies that lead to victories.

 5. **Historical Context**:
   - The evolution of Formula 1 shows how both the engineering behind the cars and the performance of drivers have changed over time. Teams like **Ferrari** and **McLaren** have been historically dominant, but newer teams like **Red Bull** have emerged to challenge the established powers, reflecting the dynamic nature of the sport.

### Conclusion:
 Formula 1 success is a combination of factors—**constructor strength**, **driver skill**, **team strategy**, and **pit stop efficiency**. While the constructor's performance is critical, the driver’s ability to adapt, make quick decisions, and execute strategies effectively is equally important. The best drivers and teams are those that can balance these elements, showcasing why Formula 1 is a sport that requires both speed and strategy to reach the pinnacle of success.

 This analysis has provided insights into the complex interplay between these elements, showing that while speed may be important, it is often the strategy, teamwork, and execution that lead to championship victories.

![image](https://github.com/user-attachments/assets/beb3e58e-090a-4441-b8e2-feb8fbb58598)


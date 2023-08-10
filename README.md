# Final-Project-J124
# J124 Final Project: Understanding the factors that affect student's life
## By: Darren Chiang

_5 Questions with Step by Step Answers on the following Data Sheet_ <br/>
**Question 1: How do weekly study times (studytime) and free time after school (freetime) affect both workday alcohol consumption (Dalc) and weekend alcohol consumption (Walc)?** <br/>
1. First press on any cell and insert a pivot table by pressing insert and select pivot table and create table in new sheet.
2. Once the pivot table is open, select studytime as rows, freetime as columns, and Dalc and Walc using the average function on both as the values. This will allow us to see how weekly study times and freetime affect alcohol consumption on both weekdays and weekends.

* The Pivot Table with its selections should look like this.
![pivot table](Q1p1.png)
* The full table should look like this.
![pivot table](Q1p2.png)

* **As shown, the pivot table indicates that as studytime increases from 1 to 4, there is a general trend of reduced average workday alcohol consumption (Dalc) and weekend alcohol consumption (Walc).
This suggests that students who dedicate more time to studying tend to consume less alcohol on both weekdays and weekends. Additionally, we can conclude that students with not a lot of free time (freetime=1), there seems to be a decrease in average alcohol consumption as studytime increases. Conversely, for students with a lot of free time (freetime=5), the pattern of alcohol consumption remains relatively consistent across different studytime levels. It is evident that students who are able to make a healthy balance between study and leisure time (moderate studytime and freetime values) generally demonstrate moderate alcohol consumption. This could potentially infer that maintaining a healthy balance between academic commitments and personal time requires one to be more responsible with their alcohol consumption.

** <br>

**Question 2: Is there a relationship between the quality of family relationships (famrel) and students' health status (health), and does this association differ based on their romantic relationship status (romantic)?** <br/>
![pivot table](Q2.png)
* **From the pivot table below, we can see that students with better family relationships (higher famrel values) generally tend to have better health (higher health values). The counts of students with higher family relationship ratings (famrel 4 and 5) are more prevalent in the higher health status categories (health 4 and 5). This can be seen from the positive correlation between family relationship quality and student health. As family relationship quality improves, students' health status tends to improve as well. Moreover, students with both low and high family relationship ratings (famrel 1 and 5) tend to have fewer romantic relationships (romantic=no). However, we cannot strongly conclude that the presence of romantic relationships might not significantly affect the relationship between family relationship quality and health status. On the other hand, the data suggests that family relationships may play a central role in influencing the well-being of students, regardless of whether they are in romantic relationships. I would like to caveat that although there is strong, positive correlation that support my answer to this question, there is missing data (amrel 1 and health 2, 4) that could potentially make the correlation less strong. 

** <br>

**Question 3: How does the number of past class failures (failures) relate to students' weekly study times (studytime) and their internet access at home (internet)?** <br/>
![pivot table](Q3.png)

* **From the data above, we can see that students who have higher weekly study times (studytime 2, 3) and access to the internet at home (internet=yes) tend to have lower counts in the "failures'' category. This suggests that students who study more AND have internet access at home might be less likely to experience past class failures. Across all levels of weekly study times (studytime), students with fewer past class failures (failures 0) have higher counts compared to those with more past class failures (failures 1, 2, 3). Notice that the students with the highest counts of failure have missing data. Although the data does not directly show this, I believe that it is plausible that the reason why they have no data in study times of 3-4 is due to the fact that these students do not study as well, hence the greater amount of failures they have experienced in school. While there is a general trend of lower failures counts among students with internet access, it is worth noting that students with internet access still fall into all levels of past class failures. To reiterate, students with more frequent weekly study times (studytime 2, 3) seem to have relatively better academic performance, as indicated by their lower past class failures counts. While there is a relationship between past class failures and weekly study times, as well as internet access, this relationship doesn't necessarily imply causation because there are other factors that we must take into account to truly understand a student's failures.

** <br/>

**Question 4: What is the impact of extra educational support (schoolsup) and family educational support (famsup) on student absenteeism (absences), and does this pattern differ by their going-out behavior (goout)?** <br/>
![pivot table](Q4.png)
* **From the pivot table we have created above, we can see that in general, students who receive both extra educational support (schoolsup) and family emotional support (famsup) tend to have lower average absences compared to those who receive neither or only one of these types of support. This suggests that a combination of school-based and family-based support might contribute to better attendance. Similarly, for students who do not receive extra educational support or family emotional support (no-no), lower levels of going out behavior (goout) seem to correlate with fewer average absences. On the other hand, for students who receive both types of support (yes-yes), the relationship between going out behavior and absences is less consistent. Because we were only able to identify a general trend and not a very strong correlation, it is saef to assume that the impact of going out behavior on absences appears to vary based on whether students receive different combinations of support. While students receiving support might have generally higher absences with higher going out behavior (goout), the pattern is not as straightforward for every student. The relationship between going out behavior and absences is influenced by multiple factors, (including the presence of support systems) but whether or not an individual student is directly impacted by these support systems is also important to consider. Therefore, the complexity of these factors can make it challenging to predict absences solely based on going out behavior and support received.

** <br/>

**Question 5:**Question:** How does the student's home address type (address) influence their going-out behavior (goout) with friends, and how does this interaction affect both workday alcohol consumption (Dalc) and weekend alcohol consumption (Walc)?** <br/>
![pivot table](Q5.png)

* **From the pivot table above, we can see that students with urban home addresses (address=U) tend to have slightly higher average going out behavior (goout) compared to students with rural home addresses (address=R). This suggests that students living in urban areas might be more inclined to engage in social activities and spend time outside with friends. This is pretty reasonable since there is more access to malls, cafes, and convenient, local places to gather while kids who reside in rural areas might have other responsibilities that they are obligated to tend to. There is a general trend of higher average alcohol consumption, both workday alcohol consumption (Dalc) and weekend alcohol consumption (Walc), among students who have higher going out behavior (goout). Interestingly, regardless of home address type, students who go out more frequently tend to have higher alcohol consumption levels. In our previous questions, we learned that students who go out more tend to have more failures in school and tying in our data from this question, it is not a stretch to assume that going out and drinking alcohol negatively impacts their academics. To further strengthen this argument, we can see that students with urban home addresses (address=U) generally exhibit slightly higher average alcohol consumption (both Dalc and Walc) compared to those with rural home addresses (address=R). This could be due to the fact that students in urban areas might have easier access to social venues and experiences that could influence their alcohol consumption habits. It is important to keep in mind that the interaction between home address type, going out behavior, and alcohol consumption is dependent on multiple factors (some of which are not in the data). It involves individual preferences, local culture, and accessibility to social opportunities.

** <br/>



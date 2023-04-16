# FC-Cincinnati-Attendance-Analysis-and-Forcasting
#### Write Up available in PDF, Visualizations and Statistical Analysis available in Jupyter Notebook
## Introduction
This analysis aims to explore the effects of promotional nights, day of the week, and team performance on attendance at FC Cincinnati matches in the 2021 and 2022 seasons. To achieve this, data was gathered from various sources, including FBRef.com, then cleaned and processed using Python, NumPy, and Pandas, and then further visualized using matplotlib and seaborn, with additional insight from libraries such as statsmodels, scikitlearn, and scipy. The study employed data visualizations, descriptive analytics, hypothesis testing, and regression analysis to evaluate the impact of these factors on attendance. 

## Complete DataSet Screenshtot
![image](https://user-images.githubusercontent.com/87671757/232349661-76f52bb1-c754-4347-b3bb-7d34e8bdf51a.png)

## Top Attendance Promotions
![image](https://user-images.githubusercontent.com/87671757/232349710-7215710a-c25d-43c1-b7a0-c1bdf72c6bf6.png)


## Impact of Promotional Nights on Attendance
#### •	Average Attendances: 
	Promo Nights:          22590 
	Non-Promo Nights:      20868
![image](https://user-images.githubusercontent.com/87671757/232349689-620a3030-a088-42d6-bb96-1f2606d1e09e.png)

#### •	Statistical Significance 
A two-sample Welch t-test was conducted to determine if there was a significant difference in attendance between weekend and weekday matches. The t-statistic was 1.1927 and the p-value was 0.2498, indicating that there was no significant difference in attendance between the two groups. Hence, the data suggest that there is no statistically significant difference between the attendance for weekend and weekday matchups.

## Impact of Weekend vs. Weekday Matches on Attendance
#### •	Average Attendances: 
	Weekends:               21766
	Weekdays:               22010

#### •	Statistical Significance 
A two-sample Welch t-test was conducted to determine if there was a significant difference in attendance between weekend and weekday matches. The t-statistic was 0.8242 and the p-value was 0.2241, indicating that there was no significant difference in attendance between the two groups. Hence, the data suggest that there is no statistically significant difference between the attendance for weekend and weekday matchups.

## Impact of Team Performance on Attendance
#### Correlation between Current Win % on Attendance
##### Attendance Trend Line Equation: y = 9860.688829x + (18492.253261)
##### R-squared: 0.1691
![image](https://user-images.githubusercontent.com/87671757/232349732-074058bd-5ba2-41dc-b643-40bdb7b184ba.png)
![image](https://user-images.githubusercontent.com/87671757/232349736-762a987a-9978-4258-ab93-46afe0e3ab01.png)
![image](https://user-images.githubusercontent.com/87671757/232349741-8537ccdf-5c77-4436-a66b-72c4a50d8468.png)
![image](https://user-images.githubusercontent.com/87671757/232349745-7ec87c07-f672-49b5-a0a0-fdedb78c183a.png)

## Match-by-Match Attendance Forecast Model
#### Trendline Equation over 2 years vs seasonal trendline: 
	y = 133.54x + 19493.73 -> For 2023: x = 35 to 52 => 24168 to 26438
  ![image](https://user-images.githubusercontent.com/87671757/232349754-8ecefc5b-bb23-475e-8dc6-cbd7405bce69.png)
![image](https://user-images.githubusercontent.com/87671757/232349762-515f58e2-7477-4255-aa35-24828b27c273.png)

## Conclusion
In conclusion, the analysis found that promotional nights have a positive impact on attendance, but there was no significant difference in attendance between weekend and weekday matches. There is a positive correlation between team performance and attendance, but the relationship is weak. The forecast model predicts an average attendance of 24168 to 26438 for the 2023 season. If given more time, analyzing the impact of weather and player injuries, understanding fan preferences for promotions, and exploring the relationship between attendance and soccer statistics would provide additional insights. Overall, these findings can help FC Cincinnati improve fan engagement and drive attendance in future seasons.

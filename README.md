# yulu-analysis

[Yulu](https://www.yulu.bike/)  is India’s leading micro-mobility service provider, which offers unique vehicles for the daily commute. Starting off as a mission to eliminate traffic congestion in India, Yulu provides the safest commute solution through a user-friendly mobile app to enable shared, solo and sustainable commuting.

Yulu zones are located at all the appropriate locations (including metro stations, bus stands, office spaces, residential areas, corporate offices, etc) to make those first and last miles smooth, affordable, and convenient!

# Problem Statement

Specifically, they want to understand the factors affecting the demand for these shared electric cycles in the Indian market.

1. Which variables are significant in predicting the demand for shared electric cycles in the Indian market?
2. How well those variables describe the electric cycle demands.

# Business Insights

#```Insights```

1. By performing a 2-sample T-test on working and non-working days with respect to count, we can infer that the population count means of both categories are the same.

2. By performing an ANOVA test on different seasons with respect to count, we can infer that population count means under different seasons are not the same, meaning there is a difference in the usage of Yulu bikes in different seasons.

3. By performing an ANOVA test on different weather conditions except 4 with respect to count, we can infer that population count means under different weather conditions are the same, meaning there is a difference in the usage of Yulu bikes in different weather conditions.

4. By performing a Chi2 test on season and weather (categorical variables), we can infer that there is an impact on weather dependent on season.

5. The median temperature is noted at 20.5 degrees Celsius, while 75% of the data has been recorded at 26.24 degrees Celsius. The average temperature is noted as 20.36 degrees Celsius.

6. The Yulu has a median of 145 counted (casual + registered) users, with 75% of users totaling 284. The average number of counted users is 191.574. The maximum number of counted users is 977.

7. 68% of the data points are collected for the working day, which makes sense as a lot of people use public transportation on working days.

8. Very few data points are collected during light snow or light rain conditions; probably a lot of people don't use the service during heavy rain or thunder storms, which makes absolute sense.

9. The average temperature was 20.23 degrees Celsius, with 20.5 happening 50% of the time.

10. The maximum number of holidays can be seen during the fall and winter seasons.

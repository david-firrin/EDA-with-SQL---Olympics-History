# EDA-with-SQL---Olympics-History

In this notebook, my goal is to analyze a historical dataset covering both the Winter and Summer Olympics from 1896 to 2016. I primarily use SQLite queries to extract key insights from the data. The dataset was scraped from www.sports-reference.com, and I found it on Kaggle [here]( https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results?select=noc_regions.csv)

This dataset contains 2,711,116 rows and 15 columns. Each row represents an individual athlete's performance at a single event at a single Olympic games. The 15 
columns represent the following: <br>
1. **ID** - unique numerical code for each athlete
2. **Name** - athlete's name
3. **Sex** - M or F
4. **Age** - athlete's age at time of olympics
5. **Height** - in cm
6. **Weight** - in kg
7. **Team** - athlete's team/country name
8. **NOC** - National Olympic Committee 3-letter coe
9. **Games** - year and winter or summer
10. **Year**
11. **Season** - winter or summer
12. **City** - host city
13. **Sport**
14. **Event**
15. **Medal** - NA, Bronze, Silver, or Gold

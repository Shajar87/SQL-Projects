## Project: 120 Years of Olympic History Analysis Using SQL
### About The Project
**Tool used: MySQL**

In this project **"120 years of Olympic history"**, I used SQL queries to answer some fascinating questions about the Olympic games.
The dataset contains historical data of the modern Olympic Games, from **Athens 1896 to Rio 2016**. Each row corresponds to an individual athlete competing in an individual event, including the athlete's name, sex, age, height, weight, country, and medal, and the event's name, sport, games, year, and city.

| ID | Name                | Sex | Age | Height | Weight | Team   | NOC | Games         | Year | Season | City       | Sport     | Event                            | Medal |
|----|---------------------|-----|-----|--------|--------|--------|-----|---------------|------|--------|------------|-----------|----------------------------------|-------|
| 1  | A Dijiang           | M   | 24  | 180    | 80     | China  | CHN | 1992 Summer   | 1992 | Summer | Barcelona  | Basketball | Basketball Men's Basketball      | NA    |
| 2  | A Lamusi            | M   | 23  | 170    | 60     | China  | CHN | 2012 Summer   | 2012 | Summer | London     | Judo      | Judo Men's Extra-Lightweight     | NA    |
| 3  | Gunnar Nielsen Aaby | M   | 24  | NA     | NA     | Denmark| DEN | 1920 Summer   | 1920 | Summer | Antwerpen  | Football  | Football Men's Football          | NA    |

---

This case study provides an opportunity to know about the Olympics e.g. how the Olympics have evolved, including questions about the participation and performance of women, different nations, and different sports and events.

Used some of the common to advanced SQL concepts such as **joins, window functions, CTE, subqueries, etc.**.

**Some of the questions are as:**
1. List down all Olympics games held so far.
2. Mention the total no of nations who participated in each Olympics game.
3. Which year saw the highest and lowest no of countries participating in the Olympics?
4. Fetch details of the oldest athletes to win a gold medal.
5. Find the Ratio of male and female athletes who participated in all Olympic games.
6. Fetch the top 5 athletes who have won the most medals (gold/silver/bronze).
7. Fetch the top 5 most successful countries in the Olympics.
8. Identify which country won the most gold, silver, and bronze medals and the most medals in each Olympic game.
    
---
**Answers to a few of the above questions:**
- **France** and the **United States** have participated in all the Olympic games.
- Ratio of male and female athletes who participated in all Olympic games = **2.9795**
- the top 5 most successful countries by no of medals won in the Olympics are
  
| Team           | Medals Won | Rank |
|----------------|------------|------|
| United States  | 629        | 1    |
| Soviet Union   | 330        | 2    |
| Italy          | 284        | 3    |
| France         | 263        | 4    |
| Germany        | 233        | 5    |
   



**🔗Queries PDF Link:** https://github.com/Shajar87/Project_Portfolio/blob/main/Olympic%20History%20Analysis.pdf

**🔗Dataset Link:** https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results

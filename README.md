**Project Overview**

- This project has two parts that demonstrate the importance and value of data visualization techniques in the data analysis process. In the first part, you will use Python visualization libraries to systematically explore a selected dataset, starting from plots of single variables and building up to plots of multiple variables. In the second part, you will produce a short presentation that illustrates interesting properties, trends, and relationships that you discovered in your selected dataset. The primary method of conveying your findings will be through transforming your exploratory visualizations from the first part into polished, explanatory visualizations.

**Exploratory data analysis of FIFA-2019**

This dataset includes detailed attributes for every player registered in the latest edition of FIFA 19 database. It consists of 18207 observations, 88 features. Features included are FIFA 2019 players attributes like Age, Nationality, Overall, Potential, Club, Value, Wage, Preferred Foot, International Reputation, Weak Foot, Skill Moves, Work Rate, Position, Jersey Number, Joined, Loaned From, Contract Valid Until, Height, Weight, Skills …

The dataset can be found here: https://www.kaggle.com/karangadiya/fifa19

**Summary of Findings In the exploration:**

I started with a quick descriptive statistics and found that 75% of the players in the dataset are below 29 years old. The oldest player is 45yrs and the youngest is 16yrs. The highest player value is €118,500,000 and the lowest player value is €10,000. The mean wage is €9618 and the player with the highest earns €565000 weekly. Then I had a look at some of the variables like Age, Weight, and Height to see their distributions. It was interesting to see the age distribution slightly positively skewed.
I moved on to see correlations. My key findings are: Acceleration has a negative correlation with Weight. As expected Age has a negative correlation with a players Potential, Wage has a positive correlation with Release clause, Potential has a positive correlation with Release clause. Value has a positive correlation with Wage. Outside of the main variables of interest, I explored player’s skillset which dribbling ability has a strong relationship with finishing ability.

**Key Insights for the presentation:**

I looked further into AGE, to see what other relationship or influence it has with other variables like Weight, Work rate, Body type and Acceleration. I used Facet plot and Heat map to note these findings. Most of the younger players weighs lesser and they also have more of a lean body type. Players whose work rate is High/High, High/Medium have a high acceleration and the Low/Low have a lower acceleration.

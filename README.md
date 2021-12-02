# Microsoft Movie Analysis
<img src="./images/Microsoft_image.jpg" alt="Drawing" style="width: 900px;height:300px;float: left;"/>

**Author:** Benjamin Toler

## Overiview
This project uses exploratory data anlysis to produce insights about the movie industry. Analysis of a movie datasets from IMBD and The Numbers shows that the most profitable movies are those that use large production budgets, are of the animation, SciFi, or Adventure genres, and are realeased during the summer or holiday months. These insights can be used by Microsoft to guide the decision making in their new movie business.

## Business Problem
Microsoft is planning on starting their own movie studio, but they are lacking industry knowledge. Analysis of the movie elements that lead to success at the box office could help Microsoft's new studio make decisions about the types of movie they want to produce.

## Data
This project uses datesets from IMBD and The Numbers. The IMDB dataset conatains information on various movie attributes, including region of production, genre, and ratings. Each movie also has a unique ID, making the joining of different IMDB datesets easy. The Numbers provides data on movie release dates and  movie financials such as budget and gross profit.

## Method
The analysis deployed in this project includes using summary statistics for grouped categorcial data and correlations between numeric data. This generates and overall picture of what are the most profitable types of movies.

## Results
Animation, sci-fi, and adventure genres produce the greatest average gross and net profit, however mystery and horror movies provide the best average return on investment.
![genre_bar_charts](./images/genre_bar_charts.png) 

The summer months of May, June, and July see the highest profits for movies. There also a significant spike in movie profits at the beginning of the holiday season in November

![profit_by_month](./images/profit_by_month.png)

Production budget is most strongly correlated with profits and has a weaker positive correlation with movie ratings. There is no correlation between a movie's budget and its return on investment.
![production_budget_correlations](./images/production_budget_correlations.png)

## Conclusions
 - Focus primarily on larger budget movies that will generate higher total profits
 - Develop animated, sci-fi, and adventure movies. Fill out content with lower budget mystery and horror movies that provide a greater return on investment
 - Movies should be released during the summer or holiday months

## Next Steps
 - Determine what factors impact ratings
 - Explore the impact of cast and crew on movie profits
 - Analyze the impact that streaming services have had on box office profits





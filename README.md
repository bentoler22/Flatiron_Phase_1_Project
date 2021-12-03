# Microsoft Movie Analysis
<img src="./images/Microsoft_image.jpg" alt="Drawing" style="width: 900px;height:300px;float: left;"/>

**Author:** Benjamin Toler

## Overiview
This project uses exploratory data analysis to produce insights about what factors lead to a movie's success. Analysis of movie datasets from IMDb and The Numbers shows that production budget, genre, and release date play an important role in determining a movie's gross profit and return on investment. Microsoft can use this analysis to determine what types of movies to make, how much to invest in them, and when to release them.

## Business Problem
Microsoft is planning on starting their own movie studio, but they are lacking industry knowledge. To guide their decision making in their new studio, they need analysis of what types of movies perform well at the box office.

## Data
This project uses datesets from IMBD and The Numbers. The IMDb dataset contains information on various movie attributes, including region of production and genre. IMDb includes movies from 2010 and after, each with their own unique ID. The Numbers provides data on release dates and  movie financials from movies between 1915 to 2020.

## Method
The analysis deployed in this project uses trending and summary statistics to evaluate the impact of various elements on a movie's success. Success is measured by a movie's gross profit and/or return on investment (ROI).

## Results
Production budget is strongly correlated with movie gross profits; however, there is no correlation between budget and ROI.

![production_budget_vs_gross_and_ROI](./images/production_budget_vs_gross_and_ROI.png)

Animation, sci-fi, and adventure genres produce the greatest gross profit on average. Mystery and horror movies provide the best return on investment.

![gross_and_ROI_by_genre](./images/gross_and_ROI_by_genre.png)

The summer months from May to July and the holiday months from November to December have seen the greatest sum of profits in the last decade.

![sum_gross_by_month](./images/sum_gross_by_month.png)

## Conclusions
 - **Invest in large budget movies in the animation, sci-fi, and adventure genres:** Microsoft is a multi-trillion dollar company. For their new movie studio to have a substantial impact on their bottomline they will need to generate sizable profits. This is most likely to occur in large budget productions in the animation, sci-fi, and adventure genres.
 - **Fill out movie collection with lower budget mystery and horror films:** In addition to big budget movies, Microsoft will need to fill out its movie portfolio. Lower budget mystery and horror movies offer a great opportunity to do this as they can generate a substantial return on investment.
 - **Release new movies during the summer and holiday months:** May through July and November through December are the prime months for releasing new movies as people are taking time off for the summer and holidays.

## Next Steps
 - **Determine what factors impact ratings:** The analysis conducted evaluated the impact on various movie elements on gross profit and ROI. Another potential measure of success for movies is ratings. Future analysis should focus on identifying movie attributes that impact ratings.
 - **Explore the impact of cast and crew on movie success:** This analysis could identify which cast and crew positions (e.g. directors, actors, writers) are most crucial to the the success of a movie.
 - **Analyze the influence that streaming platforms have had on box office returns:** In recent years, streaming platforms have become more prevalent. Looking at the overall trend of box office gross profits could lend insight into the impact streaming has had on the movie industry.

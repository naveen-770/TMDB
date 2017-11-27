## Background
This dataset contains metatdata on the plot, cast, crew, budget, and revenue of several thousand movies (both feature films and television shows) from on IMDB via kaggle.com.

## Data
|Column       |       Description                    |
|-------------|--------------------------------------|
|Movie Id| Unique identifier (used to join genre data)|
|Movie Imdb Link| URL of IMDB page for movie|
|Movie Title| Title of the movie|
|Language| Primary spoken language in movie|
|Country| Country of production|
|Content Rating| MPAA rating (e.g. R, PG, ..., etc.)|
|Title Year| Year the movie was released (used to join CPI data)|
|Duration| Length of movie in minutes|
|Color| "Color" or "Black and White"|
|Aspect Ratio| nominal aspect ratio of film used (2.16 or 16mm)|
|Director Name| Credited director|
|Director Facebook Likes|
|Actor 1 Name| Top billed actor|
|Actor 1 Facebook Likes|
|Actor 2 Name| 2nd billed actor|
|Actor 2 Facebook Likes|
|Actor 3 Name| 3rd billed actor|
|Actor 3 Facebook Likes|
|Cast Total Facebook Likes|
|Movie Facebook Likes|
|Num Critic For Reviews| number of critics with reviews of the movie|
|Num User For Reviews| number of users with reviews of the movie|
|Num Voted Users| number of users rating the movie|
|Imdb Score| average 5star rating of the movie|
|Facenumber In Poster| numberof faces present in official movie poster|
|Budget| Budget in USD|
|Genre| most common pair of genres which describe the movie |
|Profit | Budget|
|Gross| worldwide revenue in USD|
|Adjusted Budget| Budget in 2017 dollars (Budget*CPI/Current_CPI)|
|Adjusted Gross| Gross in 2017 dollars (Gross*CPI/Current_CPI)|
|Profit| Adjusted Gross - Adjusted Budget|
|NegProfit| -Profit (used for sizing gantt bars downward)|
|Profit (group)| "Made money" or "Lost money"|
|ROI| Return on Investment |
|Profit/Budget| Table calculation for ratio of Profit to Budget |
|Adjusted Budget (bin)| bins for histogram|
|Profit (bin)| bins for histogram|
|AVGProfit| table calculation of Avg(profit)|
|Rank| table calculation of Index()|
|CPI| Consumer Price Index from Bureau of Labor Statistics|
|Current CPI| Consumer Price Index as of 2017|

## Files


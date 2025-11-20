# Games with the highest revenue on steam

## Table of Contents
* [Motivation](#motivation)
* [Questions](#questions)
* [Normalizing the Data](#normaling-the-data)
* [Problems and Challenges](#problems-and-challenges)
* [Technologies Used](#technologies-used)
* [Sources](#sources)

## Motivation:
As both an avid PC gamer and a finance graduate, I’m curious about the economics behind game genres. Specifically, why do some genres struggle to capture an audience, while others seem ubiquitous? What will the next big genre twist be? While revenue is frequently discussed, finding reliable primary sources is challenging.. To navigate this, I’ll limit my analysis to games on Steam and the top 100 games by revenue, though this may skew the numbers due to the absence of popular titles outside this platform. My general assumption is that, while shooters are common, they won’t dominate the revenue list—but the top revenue-producing game will likely be a shooter.

## Questions:
* What will be the next blockbuster genre for video games? What have been the most popular ones throughout the decades?
* What are the most lucrative Genres to make a game in?
* Is it better to do free to play with other ways to buy in game items or paid?


## Acquiring and Normalizing the Data
- Originally went to kaggle for similar datasets
- Scrubbed those datasets for their sources
- Most used vgchartz which gets data from all games. Problem lies in that it just has releases and units sold
- Pivoted to just using steam and found gamalytic which provides most of the data i wanted

## Problems and Challenges 
- Multiple websites I attempted to use had ranges rather than exact numbers.
- Data that I could use to answer most of these questions were paywalled, requiring manual additions to the data set.
- Data set was taken on October 31, 2025 thus the data would have to be updated to be more exact as time goes on.

## Technologies Used
1) Python/ Pandas: exploration and minor modifications to data
2) Excel: additions to the data set that were paywalled by the sources
3) powerpoint: for presentaion
4) git: for version control

## Data Sources

1) [main website for csv](https://gamalytic.com) 
2) used this API link

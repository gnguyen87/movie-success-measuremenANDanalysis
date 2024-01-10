# Measuring a Movie’s Success Beyond the Dollar: Are The Highest Grossing Movies of All Times Actually…Good?
Na Nguyen and Emma Malcolm.

Date: April 22, 2023

# Introduction

Ever since the “Golden Age” of cinema in the 1930s that marked silent film a thing of the past, the film industry has witnessed unparalleled success and growth. From the first technicolor movies like The Wizard of Oz and Gone With The Wind to the computationally animated The Matrix, Jurassic Park, and the first fully computer-animated film, Toy Story, the industry of motion pictures has contributed greatly not only to technology but also the global economy. Especially in the current challenging economy and there has been a sharp decline in theater audience—[shrinking by half in the last 4 years]https://en.wikipedia.org/wiki/IMDb), film distributors are hesitant to take on a movie unless they can see its success first hand. Therefore, box-office, or the entire earnings generated through movie ticket sales, has been recognized as one of the primary indicators to compare film success. Many rely on it to decide whether to both produce and watch a film. However, are high grossing movies actually… good? If so, what else can we use to measure them?  

# The current anatomy of a good movie: Can we do better?
One of the popular other indicators used worldwide to assess a movie is IMDb rating (or International Movie Database). IMDb rating allows [83 million](https://en.wikipedia.org) of its registered users  to cast a vote (from 1 to 10) on every released title in the database. These votes are then aggregated and summarized as a single IMDb rating visible on IMDb.com. Accessible to anyone, anywhere, these ratings are a simplified way to see what people all over the world think about movies and have been an often-used indicator for a film’s popularity/quality. This led us to wonder: *How do the most profitable movies rank on the IMDb website?* 

<img width="720" alt="Screenshot 2024-01-10 at 3 16 59 PM" src="https://github.com/gnguyen87/movie-success-measuremenANDanalysis/assets/134335069/47c1cb8b-ccdc-4b73-a1bb-305abad5a322">

From our visualization above, the top 20 grossing films have a range of scores from 6.2 to 8.4 stars. Conversely, the top 20 scored movies on IMDb globally grossed between 28,419,159 and 1,120,210,896 U.S. Dollars. When comparing the IMDbscore and amount of money grossed, we can observe that there isn’t much of a relationship between the rating of a film (or how “objectively good” a movie is) and the amount of money it makes.

On the other hand, to investigate opinions of films from professionals and trusted members of the film industry, we can turn to the Academy Awards.

![image](https://github.com/gnguyen87/movie-success-measuremenANDanalysis/assets/134335069/530909c3-f4e8-47f5-b332-144fad9df7f4)

It seems like a movie’s revenue is not a strong indicator for its accolades. Among the top 20 movies with the highest worldwide box office and their Oscars awards, only 11 movies had any nominations at all. Furthermore, this list gets even more narrowed down as we look into wins/loses. Titanic, Avatar, Black Panther, and Frozen are the only movies in the top 20 highest worldwide grossing movies to have had at least one nomination and won, with Titanic as the most prolific with 11 out of 14 categories (after grouping some of them together).

  The Oscars, however, are not an objective means of awardship. In 2015, the academy “awarded all 20 acting nominations to white actors for the first of two consecutive years, inspiring April Reign to create the hashtag #OscarsSoWhite” [(Ugwu, 2020)](https://www.nytimes.com/2020/02/06/movies/oscarssowhite-history.html). Leaving the determination of film success to the Academy seems to yield a celebration of white creators and artists, excluding a whole world of diverse cinema. 

  ![image](https://github.com/gnguyen87/movie-success-measuremenANDanalysis/assets/134335069/df69a06e-9901-418f-b299-e67a243d3909)

As of 2020, [almost half of the U.S. population (42.2%) are people of color](https://en.wikipedia.org/wiki/Race_and_ethnicity_in_the_United_States#:~:text=As%20of%202020%2C%20White%20Americans,minority%2C%20making%20up%2012.1%25). Yet, Hollywood fails to consider them when making movies. In the top 20 highest grossing movies of all time, only 2 movies featured a non-white main character—both of which were Black males. None of these movies are in the top 5 of this list in terms of profit and grossing while other underrepresented demographics (Latines, East/South/Southeast Asians, Native Americans, Afro Latinos, etc.) are left completely off the screen. 

  Furthermore, in the history of the Oscars only three women have won the coveted best director title. This reflects a gendered measure of success within the film industry, where most of the praise goes to films about and created by cis men. To measure the representation of women in films, we can turn to the [Bechdel test](https://bechdeltest.com/) which was popularized by Alison Bechdel. The test names three simple criteria: (1) it has to have at least two women in it, who (2) who talk to each other, about (3) something besides a man. Although this test seems easy enough, only 25% of the top scored films and 50% of the top grossing films passed. Interestingly enough, when comparing the two datasets to an average Bechdel test score breakdown, we can see that the highest grossing films all have women and an above average score of "ok" and "dubious". However, the highest scored films have less than average "ok" and dubious" scores. 
  
  <img width="685" alt="Screenshot 2024-01-10 at 3 18 40 PM" src="https://github.com/gnguyen87/movie-success-measuremenANDanalysis/assets/134335069/55a82933-ae81-42b8-a18b-1cbcd7346011">

  The trend we have identified here is strong: movies that make the most money are most often than not white-, male-, and Euro-centric. Even looking beyond the dollar, we can see how scoring systems and awards are biased towards this demographic as well. Although the American movie industry continues achieved commercial success, it historically has, and continues to, lack sufficient representation. While Hollywood has undoubtedly created notable films like The Wizard of Oz, Gone With The Wind, The Matrix, and Jurassic Park, the industry's focus on white males has resulted in a significant loss of diverse perspectives and cinematic experiences. It seems like when we are trying to judge a movie, we should have a broader repertoire of measurements for how *good* it is other than just money.  
  
## Data
All of our datasets was scraped from public domains such as [kaggle.com](https://kaggle.com/) and [fivethirtyeight](https://fivethirtyeight.com/). In total, we used 4 datasets to support our research paper: 

1.  The Oscar Award, [1927 -
    2023](https://www.kaggle.com/datasets/unanimad/the-oscar-award):
- 10,765 Oscar nominations
- scraped from the Official Academy Awards
- 7 variables: year, name, film, categories, win,… 

2. Movie Industry: Four decades of movies,
    [1986-2016](https://www.kaggle.com/datasets/danielgrijalvas/movies):
- 6820 movies in the dataset (around 220 movies per year)
-  15 variables: budget, company, country, director, genre, name,…. 

3. All Time Worldwide Box Office,
    [1939-2021](https://www.kaggle.com/datasets/kkhandekar/all-time-worldwide-box-office):
- contains the top movies based on the cumulative worldwide box office
- 7512 movies and 6 variables: rank, worldwide-international-domestic box office,… 

3. Bechdel Test, 1970-2013 (from library(fivethirtyeight))
- tests whether movies meet the following criteria: There are ≥ 2 (named) female characters;these women talk to each othe; about something other than a man.
1794 movies, 15 variables: movie, result, grossings, …

# Limitations

## Data 

  There are some limitations in the datasets. Firstmost, when comparing the worldwide grossing amount of movies, we were unable to account for inflation. The dataset “All Time Worldwide Box Office” scraped the the amounts of international grossing from 1939 to 2021, but IMDb states that ["all figures are not adjusted for inflation"](https://help.imdb.com/article/contribution/titles/business-imdbpro-only/GEJUWSBB6WXH3RZ6#). 
<br>
  According to a Minnesotan inflation calculator [1 U.S. Dollar in 1939 is worth $19.48 today](https://www.minneapolisfed.org/about-us/monetary-policy/inflation-calculator), which means that the amount of money occurring in different time periods is not scaled to size. Additionally, in the dataset used for the racial distribution of Oscars winners, the dataset only contained the racial identities of best directors, actors, and actresses. This excludes 21 other award categories, which could have given more accurate insight into the demographics of Oscars winners across the entire award ceremony.   
<br>
  Furthermore, we used IMDb ratings to investigate how movies of various grossing amounts are scored, but it is worth noting that the website calculates an overall score from registered users casting their votes. However, there has been a larger discussion around the methodology of this system of movie-rating, with some people deeming online movie voting systems to be ineffective. Additionally, it was found that “most IMDb voters are male, which seems to skew the ranking in favour of films that are aimed more towards men” [(Reynolds, 2017)](https://www.wired.co.uk/article/which-film-ranking-site-should-i-trust-rotten-tomatoes-imdb-metacritic). It is worth acknowledging that IMDb ratings are a biased system of ranking a film, however, this further aids our research question in illustrating the complications that come with determining whether a movie is “good”. 
<br>
  Another limitation of this project is using The Bechdel test as a measure of gender equality in film. The Bechdel test is an infamous measure of Hollywood’s gender imbalance, however it is an oversimplified means of analyzing the role of women in film. It asks three questions of a movie, and while astonishingly many films do not pass that bar, the simplicity of this test “doesn’t address the core inequalities in Hollywood films” [(Hickey et al, 2017)](https://projects.fivethirtyeight.com/next-bechdel/). In the dataset we used, there were many instances of “dubious” where the role of women in the film were debated, and therefore, the pass/fail score couldn’t be determined. To create a more holistic analysis of gender equality in Hollywood in the future, it is worth researching new tests that include non-binary people, and expand the requirements. For ideas, we can turn to “We pitted 50 movies against 12 new ways of measuring Hollywood’s gender imbalance” which suggests new tests that look beyond white women, and the cast and crew of the film. 

## Visualizations/ Overall Research

  Our attempt throughout this research is to suggest different metrics to compare and conclude a movie quality and public performance other than its revenue and profit returns. Despite the various indicators we have included to offer other avenues in determining a good movie, our "tests" are simply not enough. With the limited scope of available and "perfect" data, our research face real world limitations that fail to ascertain the severity and array of Hollywood's inequalities that are beyond the white male population. It also leaves out the population that stands behind the camera in movie production such as screenwriters, producers, set designers, etc. All of these are, hence, reflected in our visualizations. However, we hope that our research can serve as an incentive for the film industry as well as its audience to be more critical of movies and movie making.     


# movie-success-measurement

## The current anatomy of a good movie: Can we do better?

<p align="center">
<img width="560" alt="image" src="https://github.com/gnguyen87/movie-success-measuremenANDanalysis/assets/134335069/3e80174e-7b06-4acb-ad70-4ac463c014b7">
<img width="400" alt="image" src="https://github.com/gnguyen87/movie-success-measuremenANDanalysis/assets/134335069/1cedacc7-96bd-49b8-a372-f83294a21412">
</p>

Ever since the “Golden Age” of cinema in the 1930s that marked silent film a thing of the past, the film industry has witnessed unparalleled success and growth. From the first technicolor movies like The Wizard of Oz and Gone With The Wind to the computationally animated The Matrix, Jurassic Park, and the first fully computer-animated film, Toy Story, the industry of motion pictures has contributed greatly not only to technology but also the global economy. Especially in the current challenging economy and there has been a sharp decline in theater audience—[shrinking by half in the last 4 years]https://en.wikipedia.org/wiki/IMDb), film distributors are hesitant to take on a movie unless they can see its success first hand. Therefore, box-office, or the entire earnings generated through movie ticket sales, has been recognized as one of the primary indicators to compare film success. Many rely on it to decide whether to both produce and watch a film. However, are high grossing movies actually… good? If so, what else can we use to measure them?

Our attempt throughout this research is to suggest different metrics to compare and conclude a movie quality and public performance other than its revenue and profit returns. Despite the various indicators we have included to offer other avenues in determining a good movie, our “tests” are simply not enough. With the limited scope of available and “perfect” data, our research face real world limitations that fail to ascertain the severity and array of Hollywood’s inequalities that are beyond the white male population. It also leaves out the population that stands behind the camera in movie production such as screenwriters, producers, set designers, etc. All of these are, hence, reflected in our visualizations. However, we hope that our research can serve as an incentive for the film industry as well as its audience to be more critical of movies and movie making.



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

## Available resources
All of codes and datas can be found in the files provided as well as a html file of our research.


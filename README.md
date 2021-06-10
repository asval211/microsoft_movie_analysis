# Microsoft Film Production: Data Analysis & Strategy Recommendations

**Authors**: Alex Valencia, Warren Umbach, Jordan Johnson

## Overview

This project analyzes the question "What makes a successful movie?" for Microsoft, which is making a movie studio but not well-versed in the filming industry. With our analysis, we found the best people to hire to make a movie based on how popular they are and how much money their movies make. We outline the best decisions to make to maximize profits and movie ratings.

## Business Problem

Microsoft is deciding how to make a movie. Part of the process is figuring out who to hire and when to release the movie. We used available movie data to find the best people to hire based on profits and what kind of movie is the most popular.

We can provide some good options to choose from for a few different categories. These categories are:

* Genres of movie to make
* Directors, actors, and actresses to hire based on ratings 
* Directors, writers, actors, actresses, and movie release month based on profitability

## Data

We used data from Box Office Mojo, IMDB, Rotten Tomatoes, TheMovieDB.org and, the-numbers.com. This data contains information that:

* Describes how popular movies are
* The people who worked on the movies
* Their professions
* Movie genre
* Release date
* Monetary info like budget and gross sales.

## Methods

First, we combined existing data into one dataframe and then we dropped some columns that we didn’t need.
Next, we cleaned the data by reformatting some columns like the budget and gross columns to remove commas, dollar signs, and other delimiters.
Finally, we each made our own barplots to visualize the data

## Results

We would suggest picking a genre of movie to make based on what is popular. 
Then, pick from a list of directors, actors, and actresses who are both popular and profitable.
Next, pick some writers who are profitable.
Finally, pick a release date based on the genre.

Here is an example of how to embed images from your sub-folder:

### Visual 1
![graph1](./images/PopGenres.png)

![graph2](./images/TopPopDirectos.png)

![graph3](./images/ProfitableDirectors.png)

![graph4](./images/ProfitableActorsActresses.png)

![graph5](./images/ProfitableWriters.png)

## Conclusions

We recommend: 
* Making an Adventure movie. 
* Hire someone like Leonardo DiCaprio and Idina Menzel to star in the movie. 
* Ask Christopher Nolan to direct the movie.
* Hire writers Steve Carell and Jack Kirby. 
* Release the movie at the beginning of June.


***
Questions to consider: 
* What would you recommend the business do as a result of this work?
* What are some reasons why your analysis might not fully solve the business problem?
* What else could you do in the future to improve this project?
***

## For More Information

Please review our full analysis in [our Jupyter Notebook](./dsc-phase1-project-template.ipynb) or our [presentation](./DS_Project_Presentation.pdf).

For any additional questions, please contact **name & email, name & email**

## Repository Structure

Describe the structure of your repository and its contents, for example:

```
├── README.md                           <- The top-level README for reviewers of this project
├── dsc-phase1-project-template.ipynb   <- Narrative documentation of analysis in Jupyter notebook
├── DS_Project_Presentation.pdf         <- PDF version of project presentation
├── data                                <- Both sourced externally and generated from code
└── images                              <- Both sourced externally and generated from code
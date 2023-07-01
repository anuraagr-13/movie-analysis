# Movie Database analysis to check for societal impact
The focus of the project is the social impact of movies and TV shows.

I have grown up watching a lot of movies and the fact of the matter is that it has certainly played a role in shaping my personality. So,in the past few years, I was thinking about the importance of societal awareness that certain movie plots carry and the lack of appreciation received by such movies in the mainstream audience.  

**Hence, I am interested in finding out whether movies that tackle social issues/hard-hitting topics get their share of recognition.**

1. The first part is the Data Processing and Analysis using Spark SQL and MapReduce. The flowchart of this process is provided.

<img width="694" alt="Data Processing Flowchart" src="https://github.com/anuraagr-13/movie-analysis/assets/32942643/2258abb0-9ec9-442e-9c06-0b24f1220a3a">

The general questions that I am planning to answer are follows:

- Whether the number of socially aware movies have increased across the years with more awareness?
- Do audiences prefer certain themes of movies over others. Are there certain themes thataudience do not want to see on the big screen?
- Do socially aware movies get low budgets and box office collections?

2. The second part is Exploratory data analysis on the data big data combined using PySpark.

The major questions that I am going to address in this section are:

- Exploring the average user ratings across various movie genres as well as social issue categories.
Are certain themes are more popular than others? Are certain social issues more palatable to the
public?
- What is the distribution of revenue and budget values? Does this distribution change for indie
movies? Further, are revenue and budget values genre specific in nature?
- Using linear regression , predict the average user ratings using the multitude of columns in the data.
The idea is to see if the major variables have any bearing on the average user rating.
- There are tags for each movie left by a reviewer, these tags are analysed using a tag genome for
their actual relation to the movie. We check the distribution of this genome score, what is the
relevance rating for tags to movies?

The output plots from the analysis are in the "Plots" folder.

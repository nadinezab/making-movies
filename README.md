# Making Movies Project

This project was completed as part of Flatiron School's Data Science Bootcamp (Module 1 Final Project).

## Problem statement
In January 2020, Microsoft Inc. ("the Company") decides to enter the movie industry and creates a movie studio. The company approaches consultancy XYZ to provide a data-driven understanding of the industry and characteristics of a successful movie.

The Company is after actionable insights to shape their new venture.

## Components

* **Jupyter Notebook**

The <a href="https://github.com/nadinezab/making-movies/blob/master/Making%20Movies.ipynb">Jupyter Notebook</a> is our key deliverable and contains details of our approach and methodology, data mining and cleaning, visualisations and insights and recommendations.

* **Presentation**

The presentation gives a high-level overview of the methodology, findings and recommendations for non-technical stakeholders. It is aimed to be between 5 and 10 minutes long.

* **Data**

The data can be found in the ZippedData folder. It was originally provided in the following <a href="https://github.com/learn-co-students/dsc-mod-1-project-v2-1-onl01-dtsc-pt-012120/tree/master/zippedData">repository</a>.

## Technologies
* Python version: 3.6.9
* Matplotlib version: 3.0.3
* Seaborn version: 0.9.0
* Pandas version: 0.24.2
* Numpy version: 1.16.2
* BeautifulSoup version:
* WordCloud version:
* Glob version:

## Our Approach
We will first seek to provide an insight into the movie industry by examining:
- The number of movies produced
- How profitable are movies

We will then explore the characteristics of a successful movie and seek to answer the following questions:
- What budget should be allocated? 
- What movie genres are currently performing best? 
- How long should the movie be? 
- When should the movie be released? 

We will draw our attention to two particular scenarios:
- Online distribution of movies, examining Netflix original movies
- Movies based on video games, as the Company has successful existing franchises

## Key Findings
**Profit and Profit Margin**
- Profit can be seen as worldwide gross less production budget but note that this is a simplified approach as does not account for other revenue streams and costs. 
- We found a high correlation between profit and worldwide gross.
- Median profit for a top 100 grossing movie post 2010 is \\$600 million.
- Profit margin for a top 100 grossing movie post 2010 is around 80%.

**Budget**
- Strong negative correlation between budget and profit margin.

**Runtime**
- Average runtime is 100 minutes.
- Top movies are longer, around 120 minutes.
- No direct correlation between runtime and worldwide gross, nor runtime and production budget

**Genre**
- Over half of movies produced can be described as drama.
- More than 80% of the top 100 grossing movies post 2010 can be described as adventure movies and 60% fall into action.
- An action and/or adventure movies costs on average $45 million more.
- Action movies rose to popularity in 2010 and have been outperforming non-action movies since. Adventure movies have consistantly outperformed non-adventure movies since 2009.
- Future movies for which data are already available are mostly drama and comedy.

**Release date**
- Most successful months are May/June and November.
- Most movies are released on a Friday.

**Netflix Original Movies**
- Characteristics differ for an online distribution model.
- Around 70 movies released per annum (based on 2018 and 2019).
- Runtime of around 99 minutes.
- Comedy and drama dominate.

**Movies based on video games**
- Between 1 and 3 such movies released each year.
- Average worldwide gross of $135 million.
- Average budget of $50 million.
- Action and Aventure dominate.
- Company's existing franchises to leverage: Halo, Forza and Minecraft.

## Actionable Insights

1. Have a **budget** of at least $50 million and ideally $150-200 million.
2. Produce a long movie, with a **runtime of at least 2 hours**.
3. Produce an **action/adventure** type of movie.
4. Aim for a release date in **May/June** or **November**
5. Decide whether to pursue Box Office or online distribution as characteristics differ
6. Consider utilising existing video games franchises to benefit from existing fanbase

## Contributors:

|Name     |  GitHub   |
|---------|-----------------|
|Nadine Amersi-Belton |https://github.com/nadinezab|

## Contact

* If you have any questions, you can contact me at nzamersi@gmail.com

# MOVIE RECOMMENDATION ANALYSIS 
#  DESCRIPTION
Microsoft intends to establish a lucrative film studio as part of its decision. The financial performance of various genres is shown through descriptive analysis of box office income, budget, ratings, and genres. Microsoft can use this data to determine the kinds of movies it wants to make.
## BUSINESS PROBLEM
Microsoft aims to establish a profitable film studio. To help them choose what kinds of movies to make, they would like to know what kinds of movies are currently doing the best in the film industry. I examined which genres had the biggest return on investment, which ones have the most reviews, and which ones do well in both domestic and international markets using data from IMDB and The Numbers. This will facilitate Microsoft's profitable entry into the film industry.
### DELIVERABLES
A GitHub repository
A Jupyter Notebook
A non-technical presentation
## DATA
IMDB tracks movie titles, release year, length, and genres. They have several databases that link movies by ID. IMDB also allows users to rate movies, and keeps track of the average rating and number of reviewers per movie.
## FINDINGS
The Numbers tracks release date, production budget, domestic gross, and worldwide gross for movies.
Animation, adventure, and sci-fi are the three highest performing genres in the worldwide market, with median worldwide gross values significantly higher than median production budgets. Median domestic gross for adventure is below the median production budget, and the median domestic gross for animation is only slightly higher than median production budget. Therefore, we should focus on releasing movies worldwide.

In addition, horror movies have very low production budgets but high domestic and world gross revenue. For this reason, I recommend also making movies in the horror genre.

Horror and Animation have the highest median worldwide return on investments, followed by adventure, mystery, and sci-fi.
## CONCLUSIONS
We have essentially the same top 3, but what in the world happened to our "musical" category we were looking at just a moment ago? From the visualization, we can see that calculating the median of these movies revealed what we believed to be true; your "average" popularity musical film does not seem to do so well as far as profits are concerned. Some outliers in this category are skewing the mean heavily.
From our analysis, our top 4 highest-rated genres are (in order):
Documentary,
Music,
History,
Animation
![image](https://github.com/pseudocmd/LEARN-DSC-PHASE-1/assets/151546592/1d0f562b-06b7-4115-899b-a5628700b9a0)
![image](https://github.com/pseudocmd/LEARN-DSC-PHASE-1/assets/151546592/d0249624-eaef-4ad5-8ac9-0fb13658b606)


Unfortunately, there are some limitations to this. This conclusion was only determined based on a single dataset. To add more robustness to this conclusion, I would recommend that another ratings dataset be cleaned and visualized; the IMDB dataset would be excellent for this. Additionally, there was a minimum ratings filter set to 5 for this visualization. In doing so, this removed about half our datapoints. However, since we are an extremely large company (Microsoft) trying to get into the movies space, we are likely targeting larger scale movies. If our movies are recieving less than 5 ratings, we might be in trouble. So, perhaps the data we filtered out is not as relevant to us and there is no issue with our methodology here.
From our analysis, top 3 most profitable genres are clearly:
Animation,
Adventure,
Sci-Fi.
## FUTURE IMPROVEMENTS
Return on investment data would be extremely useful for investors. Unfortunately, my data has limitations- I only calculated if movies for a certain genre at least broke even (aka technically profitable). If a movie budget was 100 million dollars and we only made a profit of one dollar, it's TECHNICALLY still profitable, but that is probably not considered a successful box office killing. Return on investment would be more relevant for scenarios like this.

The dataset I used for ratings was somewhat limiting. Investigating another dataset such as the IMDB would provide another perspective to potentially confirm this data. Different types of users browse, use, and give different ratings on different sites. There's no telling what the differences in preference might be.

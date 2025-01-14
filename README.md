![](static/tt_logo.png)

## A weekly social data project in R

A weekly data project aimed at the R ecosystem. As this project was borne out of the `R4DS Online Learning Community` and the `R for Data Science` textbook, an emphasis was placed on understanding how to summarize and arrange data to make meaningful charts with `ggplot2`, `tidyr`, `dplyr`, and other tools in the `tidyverse` ecosystem. However, any code-based methodology is welcome - just please remember to share the code used to generate the results.

***

Join the `R4DS Online Learning Community` in the weekly `#TidyTuesday` event! Every week we post a raw dataset, a chart or article related to that dataset, and ask you to explore the data. While the dataset will be “tamed”, it will not always be tidy! As such you might need to apply various `R for Data Science` techniques to wrangle the data into a true tidy format. The goal of `TidyTuesday` is to apply your R skills, get feedback, explore other’s work, and connect with the greater `#RStats` community! As such we encourage everyone of all skills to participate! 

We will have many sources of data and want to emphasize that **no causation** is implied. There are various moderating variables that affect all data, many of which might not have been captured in these datasets. As such, our guidelines are to use the data provided to practice your data tidying and plotting techniques. Participants are invited to consider for themselves what nuancing factors might underlie these relationships. 

The intent of Tidy Tuesday is to provide a safe and supportive forum for individuals to practice their **wrangling** and **data visualization** skills independent of drawing conclusions. While we understand that the two are related, the focus of this practice is purely on building skills with real-world data.

All data will be posted on the data sets page on Monday. It will include the link to the original article (for context) and to the data set. 

We welcome all newcomers, enthusiasts, and experts to participate, but be mindful of a few things:

1. The data set comes from the source article or the source that the article credits. Be mindful that the data is what it is and Tidy Tuesday is designed to help you practice **data visualization** and **basic data wrangling** in R.  
2. Again, the data is what it is! You are welcome to explore beyond the provided dataset, but the data is provided as a "toy" dataset to practice techniques on.  
3. This is NOT about criticizing the original article or graph. Real people made the graphs, collected or acquired the data! Focus on the provided dataset, learning, and improving your techniques in R.  
4. This is NOT about criticizing or tearing down your fellow `#RStats` practitioners or their code! Be supportive and kind to each other! Like other's posts and help promote the `#RStats` community!  
4. Use the hashtag #TidyTuesday on Twitter if you create your own version and would like to share it.
5. Include a picture of the visualisation when you post to Twitter.  
6. Include a copy of the code used to create your visualization when you post to Twitter. Comment your code wherever possible to help yourself and others understand your process!  
7. Focus on improving your craft, even if you end up with something simple!  
8. Give credit to the original data source whenever possible.  

***

## Submitting Datasets

`TidyTuesday` is built around open datasets that are found in the "wild" or submitted as [Issues](https://github.com/rfordatascience/tidytuesday/issues) on our GitHub.

If you find a dataset that you think would be interesting, you can approach it through two ways:

## Two Ways to Contribute

1. **Submit the dataset as an [Issue](https://github.com/rfordatascience/tidytuesday/issues)**  
a. Find an interesting dataset  
b. Find a report, blog post, article etc relevant to the data   
c. Submit the dataset as an [Issue](https://github.com/rfordatascience/tidytuesday/issues) along with a link to the article  

2. **Create an entire TidyTuesday challenge!**  
a. Find an interesting dataset  
b. Find a report, blog post, article etc relevant to the data (or create one yourself!)  
c. Let us know you're found something interesting and are working on it by filing an [Issue](https://github.com/rfordatascience/tidytuesday/issues) on our GitHub  
d. Provide a link or the raw data and a cleaning script for the data  
e. Write a basic `readme.md` file using the minimal template below and make sure to give yourself credit! 

#### `readme.md` template

```
# INPUT THE SUBJECT TITLE OF THE DATASET

The data this week comes from [SOURCE_OF_DATA](URL_TO_DATA). 

This [ARTICLE_SOURCE](LINK_TO_ARTICLE) talks about SUBJECT TITLE in greater detail.

Credit: [YOUR NAME](Twitter handle or other social media profile)
```

## Submitting Code Chunks
Want to submit a useful code-chunk? Please submit as a [Pull Request](https://github.com/rfordatascience/tidytuesday/tree/master/community_resources/code_chunks) and follow the [guide](https://github.com/rfordatascience/tidytuesday/blob/master/community_resources/code_chunks/readme.md).

***

# DataSets
## [2018](data/2018) | [2019](data/2019) | [2020](data/2020)  

| Week | Date | Data | Source | Article
| :---: | :---: | :--- | :--- | :---|
| 1 | `2019-12-31` | Bring your own data from 2019! | | |
| 2 | `2020-01-07` | [Australian Fires](data/2020/2020-01-07/readme.md) | [Bureau of Meteorology](http://www.bom.gov.au/climate/data/stations/)| [NY Times](https://www.nytimes.com/interactive/2020/01/02/climate/australia-fires-map.html) & [BBC](https://www.bbc.com/news/world-australia-50951043) |
| 3 | `2020-01-14` | [Passwords](data/2020/2020-01-14/readme.md) | [Knowledge is Beautiful](https://docs.google.com/spreadsheets/d/1cz7TDhm0ebVpySqbTvrHrD3WpxeyE4hLZtifWSnoNTQ/edit#gid=21) | [Information is Beautiful](https://informationisbeautiful.net/visualizations/top-500-passwords-visualized/) |
| 4 | `2020-01-21` | [Song Genres](data/2020/2020-01-21/readme.md) | [`spotifyr` ](https://www.rcharlie.com/spotifyr/) | [Kaylin Pavlik](https://www.kaylinpavlik.com/classifying-songs-genres/) |
| 5 | `2020-01-28` | [San Francisco Trees](data/2020/2020-01-28/readme.md) | [data.sfgov.org](https://data.sfgov.org/City-Infrastructure/Street-Tree-List/tkzw-k3nq) | [SF Weekly](https://www.sfweekly.com/news/feature/trees-of-life/) |
| 6 | `2020-02-04` | [NFL Attendance](data/2020/2020-02-04/readme.md) | [Pro Football Reference](https://www.pro-football-reference.com/years/2002/index.htm) | [Casino.org](https://www.casino.org/record-and-attendance/) |
| 7 | `2020-02-11` | [Hotel Bookings](data/2020/2020-02-11/readme.md) | [Antonio, Almeida, and Nunes, 2019](https://www.sciencedirect.com/science/article/pii/S2352340918315191#bib5) | [`tidyverts`](https://tsibble.tidyverts.org/) |
| 8 | `2020-02-18` | [Food's Carbon Footprint](data/2020/2020-02-18/readme.md) | [nu3](https://www.nu3.de/blogs/nutrition/food-carbon-footprint-index-2018) | [`r-tastic` by Kasia Kulma](https://r-tastic.co.uk/post/from-messy-to-tidy/) |
| 9 | `2020-02-25` | [Measles Vaccination](data/2020/2020-02-25/readme.md) | [The Wallstreet Journal](https://github.com/WSJ/measles-data) | [The Wall Street Journal](https://www.wsj.com/graphics/school-measles-rate-map/) |
| 10 | `2020-03-03` | [NHL Goals](data/2020/2020-03-03/readme.md) | [HockeyReference.com](https://www.hockey-reference.com/leaders/goals_career.html) | [Washington Post](https://www.washingtonpost.com/graphics/2020/sports/capitals/ovechkin-700-goals/?utm_campaign=wp_graphics&utm_medium=social&utm_source=twitter)|
| 11 | `2020-03-10` | [College Tuition, Diversity, and Pay](data/2020/2020-03-10/readme.md) | [TuitionTracker.org](https://www.tuitiontracker.org/) | [TuitionTracker.org](https://www.tuitiontracker.org/school.html?unitid=228778) |
| 12 | `2020-03-17` | [The Office](data/2020/2020-03-17/readme.md) | [`schrute`](https://bradlindblad.github.io/schrute/index.html) | [The Pudding](https://pudding.cool/2017/08/the-office/) |
| 13 | `2020-03-24` | [Traumatic Brain Injury](data/2020/2020-03-24/readme.md) | [CDC](https://www.cdc.gov/mmwr/volumes/68/wr/mm6810a1.htm) | [CDC Traumatic Brain Injury Report](https://www.cdc.gov/mmwr/volumes/68/wr/mm6810a1.htm) |
| 14 | `2020-03-31` | [Beer Production](data/2020/2020-03-31/readme.md) | [TTB](https://www.ttb.gov/beer/statistics) | [Brewers Association](https://www.brewersassociation.org/insights/cans-bottles-craft-beer-packaging-trends/) |
| 15 | `2020-04-07` | [Tour de France](data/2020/2020-04-07/readme.md) | [`tdf` package](https://github.com/alastairrushworth/tdf) | [Alastair Rushworth's blog](https://alastairrushworth.github.io/Visualising-Tour-de-France-data-in-R/) |
| 16 | `2020-04-14` | [Best Rap Artists](data/2020/2020-04-14/readme.md) | [BBC Music](http://www.bbc.com/culture/story/20191007-the-greatest-hip-hop-songs-of-all-time-who-voted) | [Simon Jockers at Datawrapper](https://blog.datawrapper.de/best-hip-hop-songs-of-all-time-visualized/) |
| 17 | `2020-04-21` | [GDPR Violation](data/2020/2020-04-21/readme.md) | [Privacy Affairs](https://www.privacyaffairs.com/gdpr-fines/) | [Roel Hogervorst](https://blog.rmhogervorst.nl/blog/2020/04/08/scraping-gdpr-fines/) |
| 18 | `2020-04-28` | [Broadway Musicals](data/2020/2020-04-28/readme.md) | [Playbill](https://www.playbill.com/grosses) | [Alex Cookson](https://www.alexcookson.com/post/most-successful-broadway-show-of-all-time/) |
| 19 | `2020-05-05` | [Animal Crossing](data/2020/2020-05-05/readme.md) | [Villager DB](https://github.com/jefflomacy/villagerdb) | [Polygon](https://www.polygon.com/2020/4/2/21201065/animal-crossing-new-horizons-calm-mindfulness-coronavirus-quarantine) |
| 20 | `2020-05-12` | [Volcano Eruptions](data/2020/2020-05-12/readme.md) | [Smithsonian](https://volcano.si.edu/) | [Axios](https://www.axios.com/chart-every-volcano-that-erupted-since-krakatoa-467da621-41ba-4efc-99c6-34ff3cb27709.html) & [Wikipedia](https://en.wikipedia.org/wiki/Volcano)|
| 21 | `2020-05-19` | [Beach Volleyball](data/2020/2020-05-19/readme.md) | [BigTimeStats](https://bigtimestats.blog/data/) | [FiveThirtyEight](https://fivethirtyeight.com/features/serving-is-a-disadvantage-in-some-olympic-sports/) & [Wikipedia](https://en.wikipedia.org/wiki/Beach_volleyball#Skills)|
| 22 | `2020-05-26` | [Cocktails](data/2020/2020-05-26/readme.md) | [Kaggle](https://www.kaggle.com/ai-first/cocktail-ingredients) & [Kaggle](https://www.kaggle.com/jenlooper/mr-boston-cocktail-dataset) | [FiveThirtyEight](https://fivethirtyeight.com/videos/we-got-drunk-on-margaritas-for-science/) |
| 23 | `2020-06-02` | [Marble Races](data/2020/2020-06-02/readme.md) | [Jelle's Marble Runs](https://www.youtube.com/channel/UCYJdpnjuSWVOLgGT9fIzL0g)| [Randy Olson](http://www.randalolson.com/2020/05/24/a-data-driven-look-at-marble-racing/) |
| 24 | `2020-06-09` | [African-American Achievements](data/2020/2020-06-09/readme.md) | [Wikipedia](https://en.wikipedia.org/wiki/List_of_African-American_inventors_and_scientists) & [Wikipedia](https://en.wikipedia.org/wiki/List_of_African-American_firsts) | [David Blackwell](https://www.stltoday.com/news/local/obituaries/david-blackwell-fought-racism-became-world-famous-statistician/article_8ea41058-5f35-5afa-9c3a-007200c5c179.html) & [Petition for David Blackwell](https://www.change.org/p/american-statistical-association-rename-the-fisher-lecture-after-david-blackwell?recruiter=1107887809) |
| 25 | `2020-06-16` | [African-American History](data/2020/2020-06-16/readme.md) | [Black Past](https://www.blackpast.org/donate/) & [Census](https://www.census.gov/content/dam/Census/library/working-papers/2002/demo/POP-twps0056.pdf) & [Slave Voyages](https://slavevoyages.org/) | [The Guardian](https://www.theguardian.com/news/2019/aug/15/400-years-since-slavery-timeline) |
| 26 | `2020-06-23` | [Caribou Locations](data/2020/2020-06-23/readme.md) | [Movebank](https://www.movebank.org/cms/movebank-content/about-movebank) | [B.C. Ministry of Environment](https://www2.gov.bc.ca/assets/gov/environment/plants-animals-and-ecosystems/wildlife-wildlife-habitat/caribou/science_update_final_from_web_jan_2014.pdf)  |

***  

# Useful links

| Link | Description |
| --- | --- |
| [:link:](https://www.rfordatasci.com) | The R4DS Online Learning Community Website|
| [:link:](http://r4ds.had.co.nz/) | The R for Data Science textbook |
| [:link:](https://carbon.now.sh/) | Carbon for sharing beautiful code pics |
| [:link:](https://github.com/MilesMcBain/gistfo) | Post gist to Carbon from RStudio |
| [:link:](https://github.com/yonicd/carbonate) | Post to Carbon from RStudio |
| [:link:](https://github.com/join) | Join GitHub! |
| [:link:](https://guides.github.com/activities/hello-world/) | Basics of GitHub |
| [:link:](https://happygitwithr.com/) | Learn how to use GitHub with R |
| [:link:](http://ggplot2.tidyverse.org/reference/ggsave.html) | Save high-rez `ggplot2` images |

# Useful data sources

| Link | Description |
| --- | --- |
| [:link:](https://docs.google.com/spreadsheets/d/1wZhPLMCHKJvwOkP4juclhjFgqIY8fQFMemwKL2c64vk/edit#gid=0) | Data is Plural collection |
| [:link:](https://github.com/BuzzFeedNews/everything/blob/master/README.md) | BuzzFeedNews GitHub |
| [:link:](https://github.com/theeconomist/) | The Economist GitHub |
| [:link:](https://cran.r-project.org/web/packages/fivethirtyeight/fivethirtyeight.pdf) | The `fivethirtyeight` data package 
| [:link:](https://github.com/TheUpshot) | The Upshot by NY Times |
| [:link:](https://github.com/baltimore-sun-data) | The Baltimore Sun Data Desk |
| [:link:](https://github.com/datadesk) | The LA Times Data Desk |
| [:link:](https://github.com/OpenNewsLabs/news-graphics-team) | Open News Labs |
| [:link:](https://t.co/BMvJO2dT1o) | BBC Data Journalism team |

***

# Data Viz/Science Books

Only books available freely online are sourced here. Feel free to add to the list

| Link | Description |
| --- | --- |
| [:link:](https://serialmentor.com/dataviz/) | Fundamentals of Data Viz by Claus Wilke |
| [:link:](https://bookdown.org/rdpeng/artofdatascience/) | The Art of Data Science by Roger D. Peng & Elizabeth Matsui |
| [:link:](https://www.tidytextmining.com/) | Tidy Text Mining by Julia Silge & David Robinson |
| [:link:](https://geocompr.robinlovelace.net/) | Geocomputation with R by Robin Lovelace, Jakub Nowosad, Jannes Muenchow |
| [:link:](https://socviz.co/index.html#preface) | Data Visualization by Kieran Healy |
| [:link:](http://www.cookbook-r.com/Graphs/) | `ggplot2` cookbook by Winston Chang |
 [:link:](https://medium.com/bbc-visual-and-data-journalism/how-the-bbc-visual-and-data-journalism-team-works-with-graphics-in-r-ed0b35693535) | BBC Data Journalism team |

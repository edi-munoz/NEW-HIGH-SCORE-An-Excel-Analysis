# NEW HIGH SCORE: An analysis of meta critic scores in video games from 1995-2021
## [Data cleaning and visualization through Excel]
### Introduction (This is my first project in data analysis and my first repository on GitHub.) 
This repository contains my end-of-course case study from Coursera's "Google Data Analytics Professional Certificate," where I was instructed to choose and analyze a public dataset that peaked my interest. I decided on video games, because they have been with me since I was little as video games have helped me in decompressing from stress and forming connections with others. Using the framework of *Ask, Prepare, Process, Analyze, Share, Act*, I began to think about my most important resource as a gamer: time. I thought, *As I get older, I feel like I get less time to play video games, and I want to experience games that are stunning and well worth the time.* So I then decided to start asking some questions that address me (the stakeholder) and my curiosity of what other people have enjoyed. 
---
### Ask 
- What are the top ten highest rated games to play, according to critics?
- What are the top ten most popular games to play, according to gamers?
- What are the must play games by platform?
---
### Prepare
The next step involved me finding a dataset. I found a public dataset titled "[Top Video Games 1995-2021 Metacritic]"(https://www.kaggle.com/datasets/deepcontractor/top-video-games-19952021-metacritic?resource=download) by a user named "Deep Contractor," with a usability of 10.0. (For those not familiar with Kaggle's [usability rating](https://www.kaggle.com/product-feedback/93922), it is a numeric value indictating how user-friendly is the dataset based on a number of factors such as documentation and metadata.) A [metacritic score](https://www.metacritic.com/faq#item11) is the average of reviews from critics and publications, which are converted into numeric values on a 0-100 point scale. There are 6 columns which have details surrounding specific games. Below are the first few rows:

| name                                 | platform      | release-date       | summary                                              | meta_score | user_review |
|--------------------------------------|---------------|--------------------|------------------------------------------------------|------------|-------------|
| The Legend of Zelda: Ocarina of Time | Nintendo 64   | November 23, 1998  | As a young boy, Link is tricked by Ganondorf ...     | 99         | 9.1         |
| Tony Hawk's Pro Skater 2             | Playstation   | September 20, 2000 | As most major publishers' development efforts ...    | 98         | 7.4         |
| Grand Theft Auto IV                  | Playstation 3 | April 29, 2008     | [Metacritic's 2008 PS3 Game of the Year; ...         | 98         | 7.7         |
| SoulCalibur                          | Dreamcast     | September 8, 1999  | This is a tale of souls and swords, transcending ... | 98         | 8.4         |
---
### Process
I needed to clean up this data, so I could analyze it to answer my questions. I made the following changes to the original data:
- Deleted 'summary' column
- Resized columns
- Added border under header row
- Removed duplicates
- Used proper casing for header row
- Cleared formatting
- Trimmed 'platform' column
- Formatted 'release_date' column
- Filtered out 'TBD' from 'user_review' column
- Formatted numbering in 'user_review column
- Sorted Z-A in both 'meta_score' and 'user_review'
- Added a 'Parent_Company' column
- Converted 'Parent_Company' to values ONLY, replacing customized nested IF functions
- Split 'release_date' into 'Release_date' and 'Release_Year' columns
- 

(My list of changes are influenced by a compiled list of cleaning steps in Excel that I created from researching articles online.)
---
### Analyze




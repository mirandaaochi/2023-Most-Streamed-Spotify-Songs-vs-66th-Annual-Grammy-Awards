# 2023-Most-Streamed-Spotify-Songs-vs-66th-Annual-Grammy-Awards

## Executive Summary
The goals of this exploratory data analysis project were:
* To investigate artist and song cross-platform performance to reveal most popular artists and songs of 2023.
* To analyze cross-platform performances and audio feature patterns to understand trends and preferences in Grammy nominations.
Business Problem

This Kaggle dataset "contains a comprehensive list of the most famous songs of 2023 as listed on Spotify." There is also information about each song’s presence on Apple, Deezer, and Shazam. We want to explore this dataset to answer the following questions:
* How do songs perform across different streaming services?
* How do artists perform across different streaming services?
* Are there any trends or preferences in the audio features of popular songs?

Similarly, although “Recording Academy Voting Members shall not allow their choices to be suggested, directed or influenced by anything other than their own analysis of merit, including, but not limited to: personal friendships, company loyalties, regional preferences or sales volume/popularity,” are there any patterns between who wins and their popularity?

## Methodology

1. Dataset Exploration
  * Cross-Platform Presence: Investigating how songs perform across different streaming services.
  * Artist Performance & Cross-Platform Presence: Investigating artist performance across different streaming services.
  * Music Analysis: Exploring audio features to understand trends and preferences in popular songs.

2. Grammy Analysis
  * Best Pop Solo Performance: Popularity Analysis
  * Song of the Year: Audio Analysis
  * Best New Artist: Popularity Analysis
  * Record of the Year
    * Popularity Analysis
    * Audio Analysis
  * Album of the Year
    * Popularity Analysis
    * Audio Analysis

Python
1. Import libraries and dataset. Clean the dataset.
2. Exploratory analysis and visualization using numpy, pandas, seaborn, and matplotlib libraries.

SQL & Tableau
1. Import dataset to Google Sheets and remove special characters from dataset (pgAdmin would not import otherwise).
2. SQL queries to extract, clean, and transform the data from the database to perform exploratory analysis.
3. Build visualizations in Tableau to illustrate key findings.

## Skills

Python: numpy, pandas, seaborn (box plots, gradients, bar plots, histograms, scatterplots), matplotlib

SQL: filters, aggregate functions (MIN(), MAX(), COUNT(), SUM(), AVG(), STDDEV())

Tableau: bar graphs, scatter plots

## Results

**Cross-Platform Presence**

*Top 10 Songs*
| Rank | #1 | #2 | #3 | #4 | #5 | #6 | #7 | #8 | #9 | #10 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Spotify | "Seven (feat. Latto) (Explicit Ver.)" by Latto, Jung Kook | "As It Was" by Harry Styles | "Flowers" by Miley Cyrus | "vampire" by Olivia Rodrigo | "I Wanna Be Yours" by Arctic Monkeys | "What Was I Made For?" by Billie Eilish | "Dance the Night" by Dua Lipa | "Cruel Summer" by Taylor Swift | "Daylight" by David Kushner | "Sprinter" by Dave, Central Cee |
| Apple | "Last Last" by Burna Boy | "Mary On A Cross" by Ghost | "Seven (feat. Latto) (Explicit Ver.)" by Latto, Jung Kook | "What Was I Made For?" by Billie Eilish | "Ella Baila Sola" by Eslabon Armado, Peso Pluma | "Flowers" by Miley Cyrus | "Sprinter" by Dave, Central Cee | "Cupid - Twin Ver." by Fifty Fifty | "fukumean" by Gunna | "Cruel Summer" by Taylor Swift |
| Deezer | "Flowers" by Miley Cyrus | "As It Was" by Harry Styles | "I'm Good (Blue)" by Bebe Rexha, David Guetta | "Calm Down (with Selena Gomez)" by Rema, Selena Gomez | "Dance the Night" by Dua Lipa | "Cold Heart - PNAU Remix" by Dua Lipa, Elton John, Pnau | "I Ain't Worried" by OneRepublic | "STAY (with Justin Bieber)" by Justin Bieber, The Kid Laroi | "Shakira: Bzrp Music Sessions, Vol. 53" by Shakira, Bizarrap | "Heat Waves" by Glass Animals |
| Shazam | "Makeba" by Jain | "Daylight" by David Kushner | "What Was I Made For?" by Billie Eilish | "MONTAGEM - FR PUNK" by Billie Ayparia, unxbected | "Barbie World (with Aqua)" by Nicki Minaj, Aqua, Ice Spice | "Popular (with Playboy Carti & Madonna)" by The Weeknd, Madonna, Playboi Carti | "Flowers" by Miley Cyrus | "fukumean" by Gunna | "The Next Episode" by Dr. Dre, Snoop Dogg | "vampire" by Olivia Rodrigo |

**Artist Performance & Cross-Platform Presence**

*Top 20 Artists by # of Songs in Dataset*


Of the 348 songs in the dataset, 67 songs were released in 2023. Peso Pluma released the most with 12. There were 185 songs released in 2022 Bad Bunny released the most with 24.

 *Top 10 Songs by Streams*

| Rank | #1 | #2 | #3 | #4 | #5 | #6 | #7 | #8 | #9 | #10 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Song | "Blinding Lights" by The Weeknd | "Shape of You" by Ed Sheeran | "Someone You Loved" by Lewis Capaldi | "Dance Monkey" by Tones and I | "Sunflower" by Post Malone, Swae Lee | "One Dance" by Drake, WizKid, Kyla | "STAY (with Justin Bieber)" by Justin Bieber, The Kid Laroi | "Believer" by Imagine Dragons | "Closer" by The Chainsmokers, Halsey | "Starboy" by The Weeknd, Daft Punk |
| Steams | 3703895074 | 3562543890 | 2887241814 | 2864791672 | 2808096550 | 2713922350 | 2665343922 | 2594040133 | 2591224264 | 2565529693 |

*Top 20 Artists by # of Streams*


The Weeknd had the most streams overall.

*Artists in the Most Playlists*

| Rank | #1 | #2 | #3 | #4 | #5 | #6 | #7 | #8 | #9 | #10 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Spotify | The Weeknd | Eminem | Ed Sheeran | Taylor Swift | Bad Bunny | Dua Lipa | Kendrick Lamar | Harry Styles | Coldplay | Dr. Dre |
| Spotify Playlists | 233079 | 155091 | 142877 | 137766 | 137562 | 119490 | 113963 | 110026 | 105218 | 104608 |
| Apple | The Weeknd | Dua Lipa | Bad Bunny | Taylor Swift | Ed Sheeran | Harry Styles | Drake | Justin Bieber | Calvin Harris | Doja Cat |
| Apple Playlists | 3023 | 2118 | 2016 | 1899 | 1857 | 1741 | 1370 | 1369 | 1232 | 1151 |
| Deezer | Eminem | Ed Sheeran | Coldplay | Dr. Dre | Linkin Park | Nirvana | The Weeknd | Snoop Dogg | Daft Punk | Adele |
| Deezer Playlists | 24524 | 17833 | 15419 | 15408 | 14149 | 13564 | 12474 | 12075 | 10660 | 9299 |

 *Songs in the Most Playlists*

#Finish this

| Rank | #1 | #2 | #3 | #4 | #5 | #6 | #7 | #8 | #9 | #10 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Spotify | 301 | 283 | 290 | 286 | 289 | 285 | 287 | 287 | 272 | 276 |
| Apple | 301 | 283 | 290 | 286 | 289 | 285 | 287 | 287 | 272 | 276 |
| Deezer | 301 | 283 | 290 | 286 | 289 | 285 | 287 | 287 | 272 | 276 |
| Shazam | 301 | 283 | 290 | 286 | 289 | 285 | 287 | 287 | 272 | 276 |


**Music Analysis**

*Audio Features Distributions*

![Distributions of Audio Features](https://github.com/user-attachments/assets/806a3f4e-7756-462c-ba5f-7ccad0d0046c)

*Key and Mode*

![Key and Mode](https://github.com/user-attachments/assets/124b3367-66ab-4e0d-9a96-3de7b7e0de9b)

*Audio Features Correlations*

*Audio Features vs. Streams*

![Audio Features vs Streams (w: Trend Lines)](https://github.com/user-attachments/assets/097f81ec-5f63-482c-ab35-620c19cd7e18)




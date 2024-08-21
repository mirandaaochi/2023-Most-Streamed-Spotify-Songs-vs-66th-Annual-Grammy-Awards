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
   * Record of the Year: Popularity Analysis
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

*Top 10 Songs Across Platforms*
| Rank | #1 | #2 | #3 | #4 | #5 | #6 | #7 | #8 | #9 | #10 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Spotify | "Seven (feat. Latto) (Explicit Ver.)" by Latto, Jung Kook | "As It Was" by Harry Styles | "Flowers" by Miley Cyrus | "vampire" by Olivia Rodrigo | "I Wanna Be Yours" by Arctic Monkeys | "What Was I Made For?" by Billie Eilish | "Dance the Night" by Dua Lipa | "Cruel Summer" by Taylor Swift | "Daylight" by David Kushner | "Sprinter" by Dave, Central Cee |
| Apple | "Last Last" by Burna Boy | "Mary On A Cross" by Ghost | "Seven (feat. Latto) (Explicit Ver.)" by Latto, Jung Kook | "What Was I Made For?" by Billie Eilish | "Ella Baila Sola" by Eslabon Armado, Peso Pluma | "Flowers" by Miley Cyrus | "Sprinter" by Dave, Central Cee | "Cupid - Twin Ver." by Fifty Fifty | "fukumean" by Gunna | "Cruel Summer" by Taylor Swift |
| Deezer | "Flowers" by Miley Cyrus | "As It Was" by Harry Styles | "I'm Good (Blue)" by Bebe Rexha, David Guetta | "Calm Down (with Selena Gomez)" by Rema, Selena Gomez | "Dance the Night" by Dua Lipa | "Cold Heart - PNAU Remix" by Dua Lipa, Elton John, Pnau | "I Ain't Worried" by OneRepublic | "STAY (with Justin Bieber)" by Justin Bieber, The Kid Laroi | "Shakira: Bzrp Music Sessions, Vol. 53" by Shakira, Bizarrap | "Heat Waves" by Glass Animals |
| Shazam | "Makeba" by Jain | "Daylight" by David Kushner | "What Was I Made For?" by Billie Eilish | "MONTAGEM - FR PUNK" by Billie Ayparia, unxbected | "Barbie World (with Aqua)" by Nicki Minaj, Aqua, Ice Spice | "Popular (with Playboy Carti & Madonna)" by The Weeknd, Madonna, Playboi Carti | "Flowers" by Miley Cyrus | "fukumean" by Gunna | "The Next Episode" by Dr. Dre, Snoop Dogg | "vampire" by Olivia Rodrigo |

*Artists in the Most Playlists Across Platforms*
| Rank | #1 | #2 | #3 | #4 | #5 | #6 | #7 | #8 | #9 | #10 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Spotify | The Weeknd | Eminem | Ed Sheeran | Taylor Swift | Bad Bunny | Dua Lipa | Kendrick Lamar | Harry Styles | Coldplay | Dr. Dre |
| Spotify Playlists | 233079 | 155091 | 142877 | 137766 | 137562 | 119490 | 113963 | 110026 | 105218 | 104608 |
| Apple | The Weeknd | Dua Lipa | Bad Bunny | Taylor Swift | Ed Sheeran | Harry Styles | Drake | Justin Bieber | Calvin Harris | Doja Cat |
| Apple Playlists | 3023 | 2118 | 2016 | 1899 | 1857 | 1741 | 1370 | 1369 | 1232 | 1151 |
| Deezer | Eminem | Ed Sheeran | Coldplay | Dr. Dre | Linkin Park | Nirvana | The Weeknd | Snoop Dogg | Daft Punk | Adele |
| Deezer Playlists | 24524 | 17833 | 15419 | 15408 | 14149 | 13564 | 12474 | 12075 | 10660 | 9299 |

 *Songs in the Most Playlists Across Platforms*
| Rank | #1 | #2 | #3 | #4 | #5 | #6 | #7 | #8 | #9 | #10 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Spotify | “Get Lucky - Radio Edit” by Pharrell Williams, Nile Rodgers, Daft Punk | “Mr. Brightside” by The Killers | “Wake Me Up - Radio Edit” by Avicii | “Smells Like Teen Spirit - Remastered 2011” by Nirvana | “Take On Me” by a-ha | “Blinding Lights” by The Weeknd | “One Dance” by Drake, WizKid, Kyla | “Somebody That I Used To Know” by Gotye, Kimbra | “Everybody Wants To Rule The World” by Tears For Fears | “Sweet Child O’ Mine” by Guns N' Roses |
| Spotify Playlists | 52898 | 51979 | 50887 | 49991 | 44927 | 43899 | 43257 | 42798 | 41751 | 41231 |
| Apple | “Blinding Lights” by The Weeknd | "One Kiss (with Dua Lipa)" by Calvin Harris, Dua Lipa | "Dance Monkey" by Tones and I | "Don't Start Now" by Dua Lipa | "STAY (with Justin Bieber)" by Justin Bieber, The Kid Laroi | "Senorita" by Shawn Mendes, Camila Cabello | "Someone You Loved" by Lewis Capaldi | "Watermelon Sugar" by Harry Styles | “One Dance” by Drake, WizKid, Kyla | "As It Was" by Harry Styles |
| Apple Playlists | 672 | 537 | 533 | 532 | 492 | 453 | 440 | 437 | 433 | 403 |
| Deezer | “Smells Like Teen Spirit - Remastered 2011” by Nirvana | “Get Lucky - Radio Edit” by Pharrell Williams, Nile Rodgers, Daft Punk | "The Scientist" by Coldplay | "Numb" by Linkin Park | "In The End" by Linkin Park | "Shape of You" by Ed Sheeran | "Creep" by Radiohead | “Sweet Child O’ Mine” by Guns N' Roses | "Still D.R.E." by Dr. Dre, Snoop Dogg | "Can't Hold Us" by Ray Dalton, Ryan Lewis, Macklemore |
| Deezer Playlists | 12367 | 8215 | 7827 | 7341 | 6808 | 6808 | 6807 | 6720 | 6591 | 6551 |

**Artist Performance**

*Top 20 Artists by # of Songs in Dataset*

![Top 20 Artists x Songs](https://github.com/user-attachments/assets/67336a56-9a5a-492b-b996-b06db59405e1)

 *Top 10 Artists by # of Songs Released in 2023 (included in dataset)*
| Rank | #1 | #2 | #3 | #4 | #5 | #6 | #7 | #8 | #9 | #10 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Artist | Peso Pluma | Morgan Wallen | Taylor Swift | Metro Boomin | Karol G | Feid | Junior H | Bizarrap | Quevedo | Jimin |
| # of Songs | 13 | 10 | 8 | 7 | 6 | 6 | 5 | 5 | 5 | 5 |

*Top 20 Artists by # of Streams*

![Top 20 Artists x Streams](https://github.com/user-attachments/assets/c9e03560-793a-4515-a7bb-c1cf4f8dd68b)

Bad Bunny had the most songs and streams!

 *Top 10 Songs by # of Streams*
| Rank | #1 | #2 | #3 | #4 | #5 | #6 | #7 | #8 | #9 | #10 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Song | "Blinding Lights" by The Weeknd | "Shape of You" by Ed Sheeran | "Someone You Loved" by Lewis Capaldi | "Dance Monkey" by Tones and I | "Sunflower" by Post Malone, Swae Lee | "One Dance" by Drake, WizKid, Kyla | "STAY (with Justin Bieber)" by Justin Bieber, The Kid Laroi | "Believer" by Imagine Dragons | "Closer" by The Chainsmokers, Halsey | "Starboy" by The Weeknd, Daft Punk |
| Steams | 3703895074 | 3562543890 | 2887241814 | 2864791672 | 2808096550 | 2713922350 | 2665343922 | 2594040133 | 2591224264 | 2565529693 |

**Audio Feature Analysis**

*Audio Features Distributions*

![Distributions of Audio Features](https://github.com/user-attachments/assets/806a3f4e-7756-462c-ba5f-7ccad0d0046c)

*Key and Mode*

![Key and Mode](https://github.com/user-attachments/assets/124b3367-66ab-4e0d-9a96-3de7b7e0de9b)

*Audio Features Correlations*

![Screenshot 2024-08-21 at 12 31 39 PM](https://github.com/user-attachments/assets/9fbeea66-d56f-4c4c-a5c5-1c670502ae2b)

*Audio Features vs. Streams*

![Audio Features vs Streams (w: Trend Lines)](https://github.com/user-attachments/assets/097f81ec-5f63-482c-ab35-620c19cd7e18)

**Grammy Analysis**

*Best Pop Solo Performance: Popularity Analysis*

Winner: "Flowers" by Miley Cyrus

Nominees:
 * "Anti-Hero" by Taylor Swift
 * "Vampire" by Olivia Rodrigo
 * "What Was I Made For? [From The Motion Picture "Barbie"]" by Billie Eilish
 * "Paint The Town Red" by Doja Cat

Analysis:
 * "Paint the Town Red" is not contained within our dataset.
 * "Flowers" appears to be the most popular in terms of streams and playlist adds.
 * "Flowers" has the most chart numbers for Spotify and Deezer.
 * "What Was I Made For?" has the most chart numbers for Apple and Shazam.

*Song of the Year: Audio Analysis*

Winner: "What Was I Made For? [From The Motion Picture "Barbie"]" by Billie Eilish O'Connell & Finneas O'Connell, songwriters (Billie Eilish)

Nominees:
 * "vampire" by Daniel Nigro & Olivia Rodrigo, songwriters (Olivia Rodrigo)
 * "Kill Bill" by Rob Bisel, Carter Lang & Solána Rowe, songwriters (SZA)
 * "Flowers" by Miley Cyrus, Gregory Aldae Hein & Michael Pollack, songwriters (Miley Cyrus)
 * "Dance The Night (From Barbie The Album)" by Caroline Ailin, Dua Lipa, Mark Ronson & Andrew Wyatt, songwriters (Dua Lipa)
 * "Butterfly" by Jon Batiste & Dan Wilson, songwriters (Jon Batiste)
 * "Anti-Hero" by Jack Antonoff & Taylor Swift, songwriters (Taylor Swift)
 * "A&W" by Jack Antonoff, Lana Del Rey & Sam Dew, songwriters (Lana Del Rey)

Analysis:
 * "What Was I Made For?" had the least streams, but the most acousticness and the least amount of valence, energy, instrumentalness, and speechiness.
 * "Dance The Night" had the most valence, energy, and liveness, as well as the least amount of acousticness and instrumentalness.
 * "Flowers" also had the least amount of istrumentalness and liveness, as well as the most speechiness.
 * All tracks had an instrumentalness prediction of 0% except for "Kill Bill."

*Best New Artist: Popularity Analysis*

Winner:  Victoria Monét

Nominees:
 * Jelly Roll
 * The War and Treaty
 * Noah Kahan
 * Coco Jones
 * Ice Spice
 * Fred again..
 * Gracie Abrams

Analysis:
 * This dataset only contains songs from Ice Spice.
 * Therefore, we cannot reach a conclusion in this case.

*Record of the Year*

Winner: "Flowers" by Miley Cyrus

Nominees:
 * "Worship" by Jon Batiste
 * "Anti-Hero" by Taylor Swift
 * "vampire" by Olivia Rodrigo
 * "On My Mama" by Victoria Monét
 * "Not Strong Enough" by boygenius
 * "What Was I Made For? [From The Motion Picture "Barbie"]" by Billie Eilish
 * "Kill Bill" by SZA

*Popularity Analysis*

* Only 5 of those songs are included in our dataset: “Flowers”, “Kill Bill”, “Anti-Hero”, “vampire”, “What Was I Made For?”
* "Flowers" has the most streams, chart appearances, and playlist adds.

*Audio Analysis*

 * "vampire": fastest BPM; highest liveness percentage
 * "Flowers": highest danceability, valence, speechiness; the lowest liveness
 * "Kill Bill": highest energy, instrumentalness; lowest acousticness
 * "What Was I Made For?": slowest BPM; highest acousticness; lowest danceability, valence, energy, speechiness
 * "Anti-Hero": tied with "vampire", "Flowers", and "What Was I Made For?" for lowest instrumentalness at 0%
 * All 5 tracks are in a major key, but the actual key varies.

*Album of the Year*

Winner: "Midnights" by Taylor Swift

Nominees:
  * "World Music Radio" by Jon Batiste
  * "GUTS" by Olivia Rodrigo
  * "the record" by boygenius
  * "SOS" by SZA
  * "The Age of Pleasure" by Janelle Monáe
  * "Did You Know That There's A Tunnel Under Ocean Blvd" by Lana Del Rey
  * "Endless Summer Vacation" by Miley Cyrus

*Popularity Analysis*

![Screenshot 2024-08-21 at 12 29 55 PM](https://github.com/user-attachments/assets/c7aef4a7-418f-4953-a6f1-6e3825cae3ea)

  * SZA had the most songs become "popular" with 19 off of "SOS". However, Taylor Swift had the most streams with "Midnights".
  * It does not appear that the date of release affects streaming numbers. This can be seen with "Flowers", which leads in terms of streams but was released in the middle. In addition, "vampire" has more streams than latest "Midnights" songs but was released later.

*Audio Analysis*

The following visualizations show the average attributes for the popular songs from each album.

![Screenshot 2024-08-21 at 12 30 03 PM](https://github.com/user-attachments/assets/4c3dc4f1-2d0f-4f92-9412-dbb354a76eb1)

![Screenshot 2024-08-21 at 12 30 09 PM](https://github.com/user-attachments/assets/5845f71b-f6ce-42ce-ba27-f4b3004a5c19)

**Limitations**
 * Missing Data: This dataset was last updated in August 2023 (missing August - December)!
 * Data Cleaning: Special characters in the Kaggle set didn’t translate well into our CSV file → had to clean dataset by hand to get rid of characters!
 * Chart Clarify: What charts are we talking about for each platform? Global? Local? All? 

## Next Steps

1. Update Data: We could add data for August-December 2023. 

2. More Predictions: We could analyze traits of popular music overall versus those nominated for a Grammy.

3. Audio Analysis Over Years: We could compare audio attributes and popularity of Grammy winners for different years.

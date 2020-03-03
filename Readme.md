# Research Question

We’ve all heard of the Jazz Age, when Jazz music and dancing gained nationwide popularity in the US, reflecting unprecedented economic growth and political development of the time. There is also the hippie movement in the 60s and 70s, when psychedelic rock became hugely popular following the outbreak of the Vietnam war, civil rights movement, and the spread of psychedelic drugs. However, we do not hear too much about what happened in the musical trends during the time of, for example, economic depression. Is it true that socio-economic state of a country affects the musical trends, or are musical historians making unwarranted claims? If it is true, in a time when we hear more and more about faltering economic conditions and increasing conflicts both internationally and internationally, would angrier or gloomier music gain more popularity?

# Repository Structure

	.
	|-- Code                             # R codes
	|-- Data                             # Data files
	|   |-- Clean                        # Cleaned data for analysis
	|   |-- Raw                          # Raw data
	|-- Midterm Presentation             # Rmd for Midterm presentation
	|-- Final Presentation               # Rmd abd pdf for Final presentation
	|-- Highlights                       # Figures and images for final presentation
	|-- Figures                          # Figures and images


# Expected Impact

 1. Address commonly made claims that do not have solid evidences
 2. Music trend prediction
 3. Will be of interest to musical historians, the music industry, and lovers of music

# Data Sources

 1. ~~[Billboard Year-End Hot 100 Singles](https://www.billboard.com/charts/year-end/2018/hot-100-songs)~~
 Decided to use instead: [Billboard Weekly Hot 100 Singles](https://data.world/kcmillersean/billboard-hot-100-1958-2017): Weekly Hot 100 singles chart between 8/2/1958 and 12/28/2018
 2. [Spotify Audio Feature Object API](https://developer.spotify.com/documentation/web-api/) which includes metrics such as 'danceability', 'energy' and 'valence' for each songs.
 3. ~~[Genius Lyric API](https://docs.genius.com/#songs-h2)~~
 ~~Decided to use instead: [Musixmatch API](https://developer.musixmatch.com/)~~
 Decided to not use Musixmatch API
 4. [NRC Word-Emotion Association Lexicon](https://saifmohammad.com/WebPages/NRC-Emotion-Lexicon.htm) which is a list of English words and their associations with eight basic emotions and two sentiments.
 5. Indices for measuring socio-economic impact: GDP growth rate, happiness index, economic optimism index, etc.
  	5.1 ~~World Bank GDP growth rate~~
	  Decided to use insted: [GDP growth rate from FRED ](https://fred.stlouisfed.org/tags/series?t=annual%3Bgdp)
  
# Required Skills and Analysis Plan

 * Requesting and using API data
 * Cleaning data retrieved from different sources
 * NLP for lyrics, comparing them to the NRC lexicon
 * Creating a happinness index using the Spotify music features (dimension reduction)
 * Check correlation between the GDP data and the happinness index
 * Granger Causality Test between GDP and the happinness index
 * [Supervised Learning Approach](https://www.ijcai.org/proceedings/2018/0282.pdf) to causal inference in time series

# Related Readings

 * [How Music Has Responded to a Decade of Ecnomic Inequality](https://www.vox.com/culture/2018/7/30/17561470/music-of-inequality)
 * [Creativity Connects: Trends and Conditions Affecting U.S. Artists](http://creativz.us/report-creativity-connects/)

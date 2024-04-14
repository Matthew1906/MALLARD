# MALLARD: MyAnimeList Labelled Anime Review Dataset
Authors: Bryan Djoni, Matthew Adrianus Mulyono, Kevin Bennett Haryono,  Rhio Sutoyo

## Abstract
In recent years, anime has experienced a surge in global popularity, providing viewers with abundant watching options. Anime reviews are a common way for viewers to express their thoughts and offer valuable insights about their opinions to other viewers.  Typically, each review includes a sentiment, such as recommended, not recommended, or mixed feelings. While several anime review datasets were already available, they did not include sentiment attributes.  This work aims to compile a comprehensive dataset of anime reviews, including their corresponding sentiment. This work collected 99,393 distinct anime reviews from 9,510 anime titles, categorized into 21 anime genres. This dataset is essential for creating an anime recommendation system. Additionally, the sentiment attributes can be utilized to enhance the system's results.

Keywords: Anime movie review; Recommendation system; Sentiment analysis; Text processing; Natural language processing

## Data description
* MALLARD contains 99,393 anime reviews from 9,510 anime titles across 21 genres. It is ready to be used to build a recommendation system.
* Each anime review in MALLARD includes a single sentiment class, i.e., recommended, not recommended, and mixed feelings. It can be utilized to enhance the recommendation system result using sentiment analysis.
* Researchers and data scientists interested in anime-related studies can use these data to conduct in-depth analyses, identify trends, and draw insights about user opinions on various anime titles.
* Educators and students in data science can use this dataset as a real-world case study for hands-on practice and learning how to work with sentiment analysis data in a specific domain.

## Data format
* JSON (Cleaned)
* CSV (RAW)

## How the data were acquired
 The anime reviews were collected from the MyAnimeList (MAL) website. Python and Selenium were chosen to build the website scraping algorithm. The dataset consists the attributes listed in the following table:

| Attribute | Description |
|-----------|-------------|
| Anime | Title of anime being reviewed |
| Genres | List of genres commonly associated with the anime being reviewed |
| Rating | Rating of the anime given by the reviewer |
| Body | Contents of the review |
| Status  | Sentiment label (Recommended, Mixed Feelings, and Not Recommended) |

## Data source and distribution
The review dataset is sourced directly from the MyAnimeList (MAL) website and contains reviews for 9,510 anime titles across 21 genres. The distribution of genres and sentiment label are as follows:

| Genre         | Recommended | Mixed Feelings | Not Recommended | Total  |
|---------------|------------:|---------------:|----------------:|-------:|
| Sci-Fi        |       10,209|           4,905|            3,630|  18,744|
| Comedy        |       16,996|           7,556|            5,156|  29,708|
| Fantasy       |       13,810|           7,619|            5,594|  27,023|
| Award Winning |        2,486|           1,197|              801|   4,484|
| Adventure     |       10,596|           5,240|            3,583|  19,419|
| Ecchi         |        4,300|           2,461|            2,180|   8,941|
| Gourmet       |          614|             250|              121|     985|
| Avant Garde   |          558|             312|              315|   1,185|
| Hentai        |          489|             232|              236|     957|
| Action        |       18,843|          10,186|            7,804|  36,833|
| Horror        |        2,402|           1,480|            1,330|   5,212|
| Supernatural  |        8,291|           4,073|            2,931|  15,295|
| Erotica       |          170|              96|              137|     403|
| Mystery       |        5,165|           2,629|            1,857|   9,651|
| Sports        |          860|             338|              232|   1,430|
| Drama         |       13,416|           6,411|            4,841|  24,668|
| Boys Love     |          777|             328|              369|   1,474|
| Romance       |       12,359|           6,421|            4,766|  23,546|
| Suspense      |        1,632|           1,023|              866|   3,521|
| Slice of Life |        3,289|           1,089|              567|   4,945|
| Girls Love    |          853|             379|              294|   1,526|
| **Total**     |  **128,115**|      **64,225**|       **47,610**|**239,950**|

## Supporting documents and repositories
- [MyAnimeListScraper](https://github.com/Matthew1906/MyAnimeListScraper): Repository containing web scraping algorithms used to scrape data from MyAnimeList, along with the raw data.
- [MALLARD Data Integration](https://colab.research.google.com/drive/1cFCckFmDApEkeBJTm1xdZyIWM5DsvB3S?usp=sharing): Google Colaboratory Notebook containing the code to process the raw data into an integrated review JSON file.

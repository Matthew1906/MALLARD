# MALLARD: MyAnimeList Labelled Anime Review Dataset

Processed scraping result containing sentiment labeled anime review dataset.

The reviews dataset comprised the attributes listed in this table:

| Attribute | Description |
|-----------|-------------|
| Anime | Title of anime being reviewed |
| Genres | List of genres commonly associated with the anime being reviewed |
| Rating | Rating of the anime given by the reviewer |
| Body | Contents of the review |
| Status  | Sentiment label (Recommended, Mixed Feelings, and Not Recommended) |

Supporting documents and repositories:
- [MyAnimeListScraper](https://github.com/Matthew1906/MyAnimeListScraper): Repository containing web scraping algorithms used to scrape data from MyAnimeList, along with the raw data.
- [MALLARD Data Integration](https://colab.research.google.com/drive/1WYLwb-q6NTjlSnnyIFSgaf3vbpovqEO8?usp=sharing): Google Colaboratory Notebook containing the code to process the raw data into an integrated review JSON file.


# You are required to scrap data from IMDb top 250 movies page. It should only have fields movie name, year, and rating

You need to use the following lines of code:

```python
from bs4 import BeautifulSoup
import requests
import sys

url = 'http://www.imdb.com/chart/top'
response = requests.get(url)
soup = BeautifulSoup(response.text)
tr = soup.findChildren("tr")
tr = iter(tr)
next(tr)

for movie in tr:
title = movie.find('td', {'class': 'titleColumn'} ).find('a').contents[0]
year = movie.find('td', {'class': 'titleColumn'} ).find('span', {'class': 'secondaryInfo'}).contents[0]
rating = movie.find('td', {'class': 'ratingColumn imdbRating'} ).find('strong').contents[0]
row = title + ' - ' + year + ' ' + ' ' + rating

print(row)
```

## Additional information

`IMDb` - It is an online database of information related to films, television programs, home videos, video games, and streaming content online – including cast, production crew and personal biographies, plot summaries, trivia, ratings, and fan and critical reviews.

You can scrap or extract data from IMDb website.Just you need to go to the detailed page of any movie, open the Parsers extension and click on the data you want to extract. 

You can select several types of data on the page, for example: title movies, duration, release date, Image URL, description. Just click Add New Field. Next Start data extraction in the Parsers extension.

## References

[Code to extract the data](https://forums.wikitechy.com/question/you-are-required-to-scrap-data-from-imdb-top-250-movies-page-it-should-only-have-fields-movie-name-year-and-rating-2/)

[Extract data from IMDb](https://parsers.me/post/do-you-scrape-extract-data-from-imdb/)

[IMDb](https://en.wikipedia.org/wiki/IMDb)

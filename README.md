# Twitter analysis of Game of Thrones Episodes

This is code for twitter analysis of **Season 8** of Game of Thrones.

So far I've implemented a simple mechanism to count tweets per minute for each of the main characters of the final season.

- Also included is the scraper script. Add your twitter app credentials and change the scraping dates.
- The timestamps are in UTC time as is the default in the twitter API.
- After you have the latest twitter data in the `data` folder, run the notebook to generate relevant images in the `images` folder.
- You will need to make some episode specific changes to the code to create the graphics, like chossing the characters to show, time of airing of the show.

## Python Requirements

- Python (>3.6)
- Pandas
- Matplotlib
- NLTK
- Tweepy
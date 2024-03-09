The News Scraper is a Python script that retrieves top headlines from the News API based on the specified country. It utilizes the requests library to fetch data from the News API and returns a list of headline titles and descriptions.

Example: To get top headlines from the United States:

``print(get_news(country='us'))``

You need to obtain an API key from the News API [https://newsapi.org/](url) and replace the default API key in the script with your own key for authentication.

The script returns a list of dictionaries, each containing the title and description of a top headline article.

``[
  {
    'title': 'Article Title 1',
    'description': 'Description of Article 1'
  },
  {
    'title': 'Article Title 2',
    'description': 'Description of Article 2'
  },
  ...
]
``

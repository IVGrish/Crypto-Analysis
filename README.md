# Crypto API Project
This Python-based project fetches real-time cryptocurrency data from the CoinMarketCap API, stores it in a CSV file, and visualizes the results using pandas, seaborn, and matplotlib.

##### How It Works
  * The script sends a GET request to the CoinMarketCap API to retrieve the latest data for the top 15 cryptocurrencies.

  * The response is normalized into a pandas.DataFrame and a timestamp is added.

  * The data is saved (or appended) to a CSV file (API.csv).

  * The script runs in a loop, fetching data every 20 seconds (3 times total).

  * Aggregated analysis is performed on percentage price changes over different periods (1h, 24h, 7d, etc.).

##### Visualizations include:

  * A point plot of mean percent changes across different time intervals.

  * A line plot showing Bitcoin price trends over time.<br><br>

**P.S.** This project was built with the help [Alex The Analyst](https://www.youtube.com/@AlexTheAnalyst).

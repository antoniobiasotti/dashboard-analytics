![Project Badge](https://img.shields.io/badge/Web%20Scraping-Python-green)
    <h1 align="center">
        Web Scraping with Beautiful Soup(bs4) for<br>Dashboard Analytics
    </h1>
<!-- Linguagens -->
![Python Badge](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=fff&style=flat-square)
![Plotly Badge](https://img.shields.io/badge/Plotly-3F4F75?logo=plotly&logoColor=fff&style=flat-square)
![Jupyter Badge](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=fff&style=flat-square)

<p style="text-align: justify; font-size: large;">In this project I used Beautiful Soup to extract financial data like historical <b>share prices</b> and quarterly revenue reports from Tesla, Amazon, AMD, and GameStop. After collecting the data I displayed it on a dashboard to identify patterns or trends using Plotly - another Python Library for data visualization. 
A company's stock share is a piece of the company; more precisely:<br><br>
<i>A stock (also known as equity) is a security that represents the ownership of a fraction of a corporation. This entitles the owner of the stock to a proportion of the corporation's assets and profits equal to how much stock they own. Units of stock are called "shares."</i><br><br>
Determining the stock price is complex; it depends on the number of outstanding shares, the size of the company's future profits, and much more. The stock ticker is a report of the price of a certain stock, updated continuously throughout the trading session by the various stock market exchanges. 
<br><br>I used the  yfinance API to obtain the stock ticker and extract information about the stock.
yfinance is an open-source tool that offers a reliable method of downloading historical market data from Yahoo! Finance's API.
The format that the data is returned is in a Pandas DataFrame.<hr>
<h3>Bs4 vs Selenium</h3>
Although BeautifulSoup in most of the cases runs faster, it's only limited to static pages. On the other hand, Selenium supports scrapping from dynamic pages, wich usually have more complex structures.</p>
 
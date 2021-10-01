# Investment in a Movie Creates a Chance for Blockbuter
Edward Kerr
<br>
## Abstract
Making a movie is a very costly investment. By looking at just how much a budget is a factor in the profitabiliy of a movie will be covered here. There are other features that can be a factor. As in which markets are the movies playing. The more profitable movies have done well in the foreign market as well as the domestic market. This also factors into the budget of the movie.
## Design
The application of Regression was to find a model that can predict how much of a factor budget is in profitability. By looking as the World Wide Profit movies, the foreign market also is a factor of how much money a movie makes. As well the the type of genres the movie will fall under will play a roll on who will watch it. 
## Data
Was collected from https://www.boxofficemojo.com. The data collected was World Wide Profit from 2011 and highest grossing genre and the number of titles that were produced in those genres.
## Algorithms
The first step was to webscrap the data from online sources. https://www.boxofficemojo.com was the main source of information. Then used BeautifulSoup and Selenium to scrap the data and pandas to create a dataframe with the data collected. Then used apply LinearRegression to the data to try to get the best model.
## Tools
- BeautifulSoup and Selenium were used to web scrap
- Pandas and SciKit Learn were the primary libaries used in the program
- For graphs, Seaborn was implimented.

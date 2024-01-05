# data_manipulation_analysis_and_hypothesis_testing
Statistic analysis of videogame global sales, including hypothesis testing, where I observe patterns on successful sales to identify the potential on new games in the market.

Data is stored in a CSV file.

Libraries used in this repository: Pandas, NumPy, Matplotlib, Seaborn, Plotly and SciPy.

**Data overview**
* Name
* Platform
* Year_of_Release
* Genre
* NA_sales: North American sales in millions of U$D
* EU_sales: European sales in millions of U$D
* JP_sales: Japan sales in millions of U$D
* Other_sales: sales in other countries in millions of U$D
* Critic_Score: maximum 100
* User_Score: maximum 10
* Rating (ESRB)
*The dataset contains the abbreviation ESRB. The Entertainment Software Rating Board evaluates a game's content and assigns an age rating, such as Teen or Mature.*

**Data Pre-processing**
* Replaced column names (turning everything lowercase).
* Converted the data to more adequate types.
* Handled missing values
* Performed feature engineering

**Data Analysis**
* Games released in different years
* Sales from platform to platform and for each year
* Platforms popularity through time and their life span 
* Box plot for global sales of all games, broken down by platform
* Impact of user and professional reviews on sales
* Correlation between reviews and sales
* Compared sales of the same games in different platforms
* Genre profitability

**Breakdown of global sales**
* User profile for each region (North America, European Union & Japan), showing the main platforms and genres
* Impact of ESRB ratings on sales per region

**Hypothesis Testing**
Checking if:
* Average user ratings for Xbox One and PC platforms are the same.
* Average user ratings for the Action and Sports genres are different.

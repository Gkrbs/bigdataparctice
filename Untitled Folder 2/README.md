This dataset was taken from: [Video Game Sales](https://www.kaggle.com/kedokedokedo/vgsales)

Within this dataset, there is a listing of video game sales per country.  Each video game listed is labelled with a genre, year, publisher, and platform.

Attributes:
- Rank: The ranking of the video game sales overall
- Name: The name of the video game.
- Platform: The platform the game was sold under.  This is interesting to show the difference in popularity between platforms.
  I may also want to normalize sales per platform to better compare how successful games were.
- Year: The year the game was released.  Interesting to gauge popular platforms per year, as well as various genres and overall sales
  per year.
- Genre: The official genre of the game.  Interesting because different regions may prefer different genres.  Various genres may
  perform differently across different platforms.  Moreover, various genres may be more or less popular over time.
- Publisher: The publisher of the game.  Could be used to draw similarities about performances of games released under the same
  developer.
- NA_Sales: Sales in North America.  Good to compare total sales, console popularity, and genre popularity.
- EU_Sales: Sales in the European Union.  See NA_Sales.
- JP_Sales: Sales in Japan.  See NA_Sales.
- Other_Sales: Sales not in North America, the European Union, or Japan.  See NA_Sales.
- Global_Sales: Total global sales.  Interesting to compare overall success of a game.

Tasks and Questions:
- Which regions prefer which platform the most for playing video games?
- What is the most popular platform for playing video games?
- How to annual video game sales vary per year in each country?
- Which platforms for playing video games have been the most popular each year?
- Which regions prefer which genre the most?
- Which genres have been more or less popular with the passing of time?
- Which publishers have consistent success?  Which publishers are hit or miss with games?
- Which region purchases the most video games?
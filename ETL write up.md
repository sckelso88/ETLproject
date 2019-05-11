# ETLproject

For our ETL Project we have decided to scrape movie review data from two different movie database websites.

We extracted our data from two different moview critic webistes formatted in html: Rotten Tomatoes (https://www.rottentomatoes.com/top/bestofrt/) and IMDB (https://www.imdb.com/list/ls006332872/). 

For the next phase of our ETL project we transformed the data by scraping these websites using the 'html parser' in Beautiful Soup and then proceeded to isolate and filter the data we were looking for such as titles, average rating and number of reviews. This step was done so that we can load the data to our non-relational database.

Our last phase of the project involved loading our databse into our non-relational database. We do this so that our data is a more readibly accessed format. The method we chose was to merge our datasets into pandas dataframe and then load onto MongoDb. We merged the datasets on the index in order to show the 'Top 100' movies from each data source, as well as their corresponding ratings and total number of reviews and votes. 

 


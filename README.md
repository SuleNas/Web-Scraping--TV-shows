# Web-Scraping--TV-Shows
## Introduction:
Web scraping, web harvesting, or web data extraction is data scraping used for extracting data from websites. It is about downloading structured data from the web, selecting some of that data, and passing along what you selected to another process.

The idea is to go through a website of interest and, using special python programming libraries, extract relevant data/information that can be presented as a DataFrame.
This project was carried out as part of a Data Science Bootcamp i participated in on Jovian.ai.
## Procedures:
This web scraping project explores the 200 most popular TV Shows on themoviedb.org in descending order. Since each page of the website contained only 20 shows, it means i had to scrap 10 pages to get up to 200 TV Shows.
Below are the steps that were taken:

- download the web page using requests library.

- parse the HTML source code using BeautifulSoup.

- Extract show name, release date and web link.

- Get links and information of 9 other pages to complete 200 TV shows.

- Create a Dataframe and save the information as a CSV file.

- Get info about a TV series using its web link.

- Create a dataframe containing some TV Show's details.

- Scrape all shows and create their csv files containing some of their info.

- Create a folder to store all the created csv files.

## Language and Libraries Used:
As stated above, this project was carried out using the **Python** programing language and its libraries including *requests* library for sending HTTP requests using Python which returns a **response object** with all its response data. The *BeautifulSoup* python library was also used for pulling data out of HTML and XML files gotten from the request object. I also used the popular *Numpy* and *Pandas* library for data wrangling and dataset creation.

## Future work
Presently, the project has been completed with all 200 show titles having a csv file containing their information such as the Title, cast, genre, e.t.c, there will be a need to create a single csv file containing all 200 shows with their details.

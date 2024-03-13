In this assignment there are two parts
1. Scrape titles and preview text from Mars news articles
   -use automated browsing to visit the Mars News site to scrape the elements
   -create a Beautiful Soup object and use it to extract text elements from the site
   -extract the titles and preview text of the news articles that you scraped. Use the data using python.
2. scrape and Analyze Mars Weather data
   -Use automated browsing theo visit the Mars Temp Data site and scrape elements
   -Create a Beautiful Soap object and use it ot scrape the data in the HTML table.
   -Assemble the scraped data into Panda DataFrame the columns should have the following headings:
       -id: the identification number of a single transmission from the Curiosity Rover
       -terrestrial_date: the date on Earth
       -sol: the number of elapsed Martian Days since rover's landing
       -ls: the solar longitude
       -month: the Martian month
       -min_temp: the mini temp in Celsius of a single Martian day
       -pressure: the atmospheric pressure at the location
   -Examin the data types that are currently associated with each column. Convert data to appropriate data types
   -Analyze your dataset by using Pandas functions to answer the following questions
       -How many months exist on Mars?
       -Mow many Martian days worth of data exist in the dataset?
       -What are the coldest and warmest months on Mars?
       -Which months have the lowest and highest atmospheric pressure on Mars?
       -About how many terrestrial days exist in a Martian year?
   -Export the DataFrame to a csv file

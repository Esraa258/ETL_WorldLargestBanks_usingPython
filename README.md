# Acquiring & processing information on the world's largest banks

- 1- Extract real-world data from a public website using WebScraping and Requests API in Python              
  (Extract the list of the top 10 largest banks in the world ranked by market capitalization in billion USD)       
  URL: https://web.archive.org/web/20230908091635/https://en.wikipedia.org/wiki/List_of_largest_banks
- 2- Transform the data as per the problem statement                                                          
  (Transform the data frame by adding columns for Market Capitalization in GBP, EUR, and INR, rounded to 2 decimal places, based on the exchange rate information in the CSV file)
- 3- Load the data in a CSV  file
- 4- Load the data in an SQLite database for further processing and querying
- 5- Query the database to retrieve filtered information from the table
- 6- Log the entire process of execution


- Libraries used: Pandas, NumPy, BeautifulSoup, Requests, SQLite3, Datetime                                 
  requests: used for accessing the information from the URL.                                                     
  bs4: The library containing the BeautifulSoup function used for web scraping.                                   
  pandas: used for processing the extracted data, storing it to required formats, and communicating with the databases.       
  SQLite3: The library required to create a database server connection.                                                   
  NumPy: The library required for the mathematical rounding operation.                                                         
  datetime: The library containing the function datetime used for extracting the timestamp for logging purposes.

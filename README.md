# GDP_WEBSCRAPING
Extract data from a website using webscraping and reqeust APIs process it using Pandas and Numpy libraries.

# Project Scenario:
An international firm that is looking to expand its business in different countries across the world has recruited me. I have been hired as a junior Data Engineer and are tasked with creating a script that can extract the list of the top 10 largest economies of the world in descending order of their GDPs in Billion USD (rounded to 2 decimal places), as logged by the International Monetary Fund (IMF).

The required data is available on the URL mentioned:URL: https://web.archive.org/web/20230902185326/https://en.wikipedia.org/wiki/List_of_countries_by_GDP_%28nominal%29

# Objectives
- Use Webscraping to extract required information from a website.
- Use Pandas to load and process the tabular data as a dataframe.
- Use Numpy to manipulate the information contatined in the dataframe.
- Load the updated dataframe to CSV file.

# Set up
- pandas for managing the data.
- numpy for mathematical operations.

## Task1:
Extract the required GDP data from the given URL using Web Scraping.
URL="https://web.archive.org/web/20230902185326/https://en.wikipedia.org/wiki/List_of_countries_by_GDP_%28nominal%29"
- Extract tables from webpage using Pandas. Retain table number 3 as the required dataframe.
- Replace the column headers with column numbers
- Retain columns with index 0 and 2 (name of country and value of GDP quoted by IMF)
- Retain the Rows with index 1 to 10, indicating the top 10 economies of the world.
- Assign column names as "Country" and "GDP (Million USD)

## Task 2:
Modify the GDP column of the DataFrame, converting the value available in Million USD to Billion USD. Use the round() method of Numpy library to round the value to 2 decimal places. Modify the header of the DataFrame to GDP (Billion USD)
- Change the data type of the 'GDP (Million USD)' column to integer. Use astype() method.
- Convert the GDP value in Million USD to Billion USD
- Use numpy.round() method to round the value to 2 decimal places.
- Rename the column header from 'GDP (Million USD)' to 'GDP (Billion USD)

## Task 3: 
Load the DataFrame to the CSV file named "Largest_economies.csv"


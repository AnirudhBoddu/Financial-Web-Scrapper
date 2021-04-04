# Financial-Web-Scrapper
Web Scraping is a technique to simulate the behavior of a website user to effectively use the website itself as a web service to retrieve data. Scraping can gather data/information from World Wide Web and you can get data as per your requirements. Investors need to have a comprehensive data of similar companies and their corresponding stock values which appear in the stock market every day. Web Scraper software can be used to keep a constant watch on this data. You can get all the required information from a financial source at the click of a button. In this project we scraped financial data from a financial website. The scraped data is parsed using Beautiful soup object. The extracted information is emailed in the form of pie chart and used by investors for analysis.

* Language/s used: Python

* Project Specifications:
1. Identify website which you want to scrape
2. Identify patterns in URL and inspect objects
3. Take input in file as with every addition of ticker symbol we don’t have to change
code
4. Use your Gmail account to send email
5. Email body should contain stock symbols and its current price in the form of pie-
chart.
6. Subject should be : “Stock Report”
7. Mail should go with proper ‘From’ name and not with email id
8. To should have a recipient mail address

* Libraries used:
1. Requests
2. Beautiful soup
3. Urllib.request
4. Smtplib
5. Csv
6. Email
7. Matplotlib

* Execution Procedure:

1. Provide the input stock symbols in the csv format. Note: Only stock symbols should be given Eg: GOOG for Google.
2. In the code enter the credentials details 'From' address and 'To' address. Note: For from address you need to specify the login credentials.
3. The output will be shown in the pie chart file in PNG format.

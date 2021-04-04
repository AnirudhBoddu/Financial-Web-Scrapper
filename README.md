# Financial-Web-Scrapper
Web Scraping is a technique to simulate the behavior of a website user to effectively use the website itself as a web service to retrieve data. Scraping can gather data/information from World Wide Web and you can get data as per your requirements. Investors need to have a comprehensive data of similar companies and their corresponding stock values which appear in the stock market every day. Web Scraper software can be used to keep a constant watch on this data. You can get all the required information from a financial source at the click of a button. In this project we scraped financial data from a financial website. The scraped data is parsed using Beautiful soup object. The extracted information is emailed in the form of pie chart and used by investors for analysis.

-> Language/s used: Python

-> Project Specifications:
 Identify website which you want to scrape
 Identify patterns in URL and inspect objects
 Take input in file as with every addition of ticker symbol we don’t have to change
code
 Use your Gmail account to send email
 Email body should contain stock symbols and its current price in the form of pie-
chart.
 Subject should be : “Stock Report”
 Mail should go with proper ‘From’ name and not with email id
 To should have a recipient mail address

-> Libraries used:
 Requests
 Beautiful soup
 Urllib.request
 Smtplib
 Csv
 Email
 Matplotlib

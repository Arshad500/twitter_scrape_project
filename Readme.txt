Twitter Scraping Project
This project allows you to scrape tweets from Twitter based on various parameters such as hashtags, usernames, and dates. The scraped data can be saved in a MongoDB database and also downloaded in CSV and JSON formats.

Installation
To install the necessary dependencies, run the following command in the project directory:


pip install -r requirements.txt
Usage
To initiate the Twitter scraping process, run the following command in the project directory:

streamlit run twitter.py
This will launch a Streamlit app that allows you to enter the parameters for the Twitter scraping process, such as the hashtags, usernames, and dates to search for.

Once you have entered the parameters, click on the "Scrape" button to initiate the scraping process. The scraped data will be saved in a MongoDB database, and you can also download the data in CSV and JSON formats by clicking on the "Download CSV" and "Download JSON" buttons respectively.

Parameters
The following parameters can be specified when initiating the Twitter scraping process:

Hashtags: Enter one or more hashtags separated by commas to search for tweets containing those hashtags.
Usernames: Enter one or more usernames separated by commas to search for tweets from those usernames.
Start Date: Enter a start date (in YYYY-MM-DD format) to search for tweets starting from that date.
End Date: Enter an end date (in YYYY-MM-DD format) to search for tweets up until that date.
Saving Data to MongoDB
The scraped data is saved in a MongoDB database with the following collections:

tweets: Contains the raw tweet data as returned by the Twitter API.
processed_tweets: Contains the processed tweet data, including the tweet text, user information, and any other relevant metadata.
Downloading Data
To download the scraped data in CSV or JSON format, click on the "Download CSV" or "Download JSON" buttons respectively. The downloaded file will be saved in the project directory.


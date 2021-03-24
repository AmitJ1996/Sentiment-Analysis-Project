# Sentiment-Analysis-Project

Case Study for Machine Learning Internship

# Task: Scrape the customer reviews for 10 mobile phones listed on Amazon.in

Steps : I followed the following procedure to complete the task 

Requirements to install libraries :

pip install python-dateutil pip install requests pip install selectorlib

Visited the Amazon.in and copy the urls of 10 Mobile Phones and Product urls to urls.txt

I used the Python and selectorlib* for scraping and extracting the reviews.

I created selectors.yml file to reads this YAML file and extracts the data that marked up on the page.

I run the main.py to store the extracted data into data.csv. I used encoding 'utf-8' to handle emoji.

Selectorlib is a tool that makes selecting, marking up, and extracting data from web pages visual and easy.

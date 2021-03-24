Case Study for Machine Learning Internship

Task-1 : Scrape the customer reviews for 10 mobile phones listed on Amazon.in

Steps : 
I followed the following procedure to complete the task 1 

1. Requirements to install libraries : 
       
    pip install python-dateutil
    pip install requests
    pip install selectorlib

2. Visited the Amazon.in and copy the urls of 10 Mobile Phones and Product urls to urls.txt

3. I used the Python and selectorlib* for scraping and extracting the reviews.
4. I created selectors.yml file to reads this YAML file and extracts the data that marked up on the page.
5. I run the main.py to store the extracted data into data.csv. I used encoding 'utf-8'  to handle emoji.

* Selectorlib is a tool that makes selecting, marking up, and extracting data from web pages visual and easy.



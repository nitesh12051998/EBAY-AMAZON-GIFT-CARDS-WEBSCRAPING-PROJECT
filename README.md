# **PART 1: Are Amazon Gift Cards are sold above the listed face value???**

To address this objective, we will scrape the first 10 pages of Ebay's search results containing "Amazon gift card" with a filter "Sold"

The notebook contains the code to address the problem. The steps followed to solve the problem are listed below.

  *STEP 1*: Go to https://www.ebay.com and search for "amazon gift card". On the left-hand side of the page, find “Show only” and select “Sold Items” (you may have to scroll down a little bit). Then use this URL and write code that loads eBay's search result page containing sold "amazon gift card". Save the result to file. Give the file the filename "amazon_gift_card_01.htm".

  *STEP 2*: Take your code in (a) and write a loop that will download the first 10 pages of search results. Save each of these pages to "amazon_gift_card_XX.htm" (XX = page number). IMPORTANT: each page request needs to be followed by a 10 second pause.  Please remember, you want your program to mimic your behavior as a human and help you make good purchasing decisions.

  *STEP 3*: Write code that loops through the pages you downloaded in (b), opens and parses them to a Python or Java xxxxsoup-object.

  *STEP 4*: Using your code in (step 3) identify and print to screen the title, price, and shipping price of each item.

  *STEP 5*: Now using RegEx, identify and print to screen gift cards that sold above face value. e., use RegEx to extract the value of a gift card from its title when possible (doesn’t need to work on all titles, > 90% success rate if sufficient). Next compare a gift card’s value to its price + shipping (free shipping should be treated as 0).  If value < price + shipping, then a gift card sells above face value.

  *STEP 6*: What fraction of Amazon gift cards sells above face value? Why do you think this is the case?
  
  
There are three files required for this project:

project.py - Contains all the Python code for web scraping and sport betting.

answers.txt - Contains concise answers to the questions asked during web scraping.

screen.txt - Contains the screen output from the web scraping process.





# **PART 2: Are Amazon Gift Cards are sold above the listed face value???**

Sport Betting - This section involves logging into a sports betting website, fctables.com, using Python requests, and verifying the login status. The following tasks were performed during sport betting:

Creating an account on fctables.com and selecting a football game to place a virtual bet.

Analyzing the network tab in the browser and answering questions related to logging in and verifying the login status.

Writing code to log in to the website using Python requests and verifying the login status by checking whether the word "Wolfsburg" appears on the page. To run the project, the user needs to execute the project.py file. The screen output will be saved to screen.txt. The answers to the questions asked during web scraping will be saved to answers.txt.


NOTE: This script is for educational purposes only. Scraping websites without permission may be illegal or against the terms of service of the website. The code may need to be modified to work with changes to the website's HTML or CSS. The downloaded product pages can be used for further analysis, such as sentiment analysis or topic modeling.

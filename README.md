# WebScraping_Indeed.com

A customized web scraper to facilitate filtering hundreds of job listings in a few minutes from the well known job site Indeed.com,
finally making room for an efficient job search!!
This script makes use of  Python's BeautifulSoup, nltk and requests packages.

class JobSearch has 4 fuctions:
  The constructor initializes the searchCriteria and numPages variables based on the user's input
  
1) getJobData() 
    Fetches the pages and internally invokes the getJobDetails function to populate the details of each job
    Returns a list of lists
2) getJobDetails
    Returns the details of a particular job
3) makeJobFile
    Writes the results to a csv file in the specified location
4) printData
    Prints the searchCriteria and the numPages values

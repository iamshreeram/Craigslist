# Crawl and Scrap

This projects helps in crawling and scrapping the details of cheapest price for requested project. Each version of the project will include multiple vendors. Current project support only single vendor.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisities

You need to install below applications and how to install them

```
* Python

Below modules of python
* threading 
* urllib3 
```

### Set up environment variables

After installation of python and respective modules, Set up environment variables.

### Running the code

Below are the steps for running the app

```
python cheap_crawler.py
```

Enter below details based on application request 

```
1. Product name that you need
2. Price range and
3. Location
```

Application processes your request the records and opens webpage with list of urls that are in the prices range.

## **Future Plans**
1. Adding multi-threading to speed up the process
2. Crawling and Scraping for places that are near by user location
3. Using exception block for all required modules to display proper error to user
4. Running the application in cloud to ensure the ip is not getting blocked
5. Making the application as loosely coupled
6. Adding logger to debug the issue and identify the performance of each module

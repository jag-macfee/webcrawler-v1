# webcrawler-v1

### Reading ###
Before starting development, it is best to know what is out there and how to go about doing this.

#### Data Structures #### 
[Quora](https://www.quora.com/How-can-I-build-a-web-crawler-to-crawl-web-for-pricing-for-a-product-or-item-number) says that it's just a BFS on urls.
It'll be best also to store the urls in alphabetical order so binary search can be used to find the visited urls more efficiently.

#### Packages ####
[Scrapy](https://doc.scrapy.org/en/latest/intro/tutorial.html): tool for online web scraping.
Numpy/ pandas would also be useful to store data in spreadsheets.

### v1 - primitive beginnings ###
To start with, we will create a very primitive webcrawler. This will attempt to track one product and input its values over time into a spreadsheet to track prices.

# Google Image Search Scraper

This script utilizes python, selenium, and Google chrome with webdriver to search for a query and download a specified number of full-size images. Google has implemented a limit on the number of images that load for a given search. To address this issue, queries can be passed to this program as a python dict, and the corresponding URLs and images are saved.

For example, {'flower': ['lavender', 'lilac'] } would search for lavender and lilac, and store both image sets under a 'flowers' folder.
 

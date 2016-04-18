# clscan
A bash version of a craigslist keyword scraper

Obviouisly you can change the city (default pittsburgh) and for-sale category (default gms, garage sales) to whatever you want to scrap. 

The regex portion has the keywords that are checked for. This can be in all lowercase, as all the text is case-ignored.

This does rely on gawk to work, as opposed to the standard awk. 

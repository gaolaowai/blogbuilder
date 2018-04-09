# BlogBuilder.py -- Static Blog Website Generator

This repo is to hold/share code which I use for generating/updating my blog for my business website. It doesn't include any CSS, as the script focuses solely on the HTML structure. Styling is left to the end-user.

# Assumptions
This script assumes that you have the site structure of:
"www" ---> "blog" ---> "index.html"  (where index.html is the directory list for your blog). I have included an example based off what I use for my site, www.maxya-it.com/blog

# Requirements
This was written in python 3+; except for stdlib, this also uses lxml library for parsing/manipulating HTML pages. It can be installed solo via pip3, or is often included with Beautiful Soup.

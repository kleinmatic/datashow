# Downloading Web Data Without Scraping

### Michelle Minkoff and Scott Klein, NICAR Denver 2016

## Software to Install

**Google Chrome**: Internet Explorer and Firefox both have excellent developer tools but the Web Inspector in Chrome will be basis of our examples. Some examples use Firefox extensions, but if you don’t have it, no worries.

**JSONView Chrome Extension**: http://goo.gl/njpwwh

**CSVKit**: [http://csvkit.readthedocs.org/en/latest/index.html](http://csvkit.readthedocs.org/en/latest/index.html)

Requires Python. Mac/Linux comes with Python installed. Use Anthony DeBarros’s great guide to install Python on Windows. Install Python 2.7.x because CSVKit doesn’t work with Python 3. http://goo.gl/Nm90gD

**Google Spreadsheets**: You can import an HTML table directly by typing =ImportHTML(“url”, “elementtype”, numberElement on page)

```Ex: =ImportHTML(“http://www.atlanta.k12.ga.us/Page/832”, “table”, 2)```

## Tools we’re using

**Open Refine**: [http://openrefine.org/](http://openrefine.org/)

Tool to inspect and manipulate spreadsheet files, allowing to run queries on it to manipulate it the way you would like.

**Scraper**:
[https://chrome.google.com/webstore/detail/scraper/mbigbapnjcgaffohmbkdlecaccepngjd?hl=en](https://chrome.google.com/webstore/detail/scraper/mbigbapnjcgaffohmbkdlecaccepngjd?hl=en)

Click on a type of information (names, emails, URLs, etc, and then right-click (control-click) and Scrape Similar. There’s an option to bring the results into a Google spreadsheet.

**Tabula**:
[http://tabula.nerdpower.org/](http://tabula.nerdpower.org/)

Tabula turns tabular PDF data into tables. Free software from the Knight-Mozilla OpenNews project.

**DownThemAll**:
[https://addons.mozilla.org/en-US/firefox/addon/downthemall/](https://addons.mozilla.org/en-US/firefox/addon/downthemall/)

A Firefox extension that detects what types of assets you might want to download on a page and allows you to download them, well, all. Doesn’t work for everything, but a good quick one to try.

**OutwitHub**:
[https://addons.mozilla.org/en-us/firefox/addon/outwit-hub/](https://addons.mozilla.org/en-us/firefox/addon/outwit-hub/)

Break your page down into its elements that it is made up of. Grab all pictures on a page at once, create a scraper using various HTML elements as start and end points. This is quite powerful, if you learn how to use it well. More robust than  DownThemAll.

**Import.Io - Like Outwit, but less code required**
[https://import.io/](https://import.io/)

Break your page down into its elements that it is made up of. Click on elements to "train" the program as to what you want in a certain column. Crawl through multiple paginated results. Solid tutorial here: http://www.interhacktives.com/2014/03/06/scrape-data-without-coding-step-step-tutorial-import-io/

**JQ**:
[http://stedolan.github.io/jq/download/](http://stedolan.github.io/jq/download/)

Helpful command line utility for working with JSON files.

**JSON Viewer**:
[http://jsonviewer.stack.hu/](http://jsonviewer.stack.hu/)


## Other Important Links

**Dan Nguyen’s Terrific Web Inspector Guide**:
http://dannguyen.github.io/NICAR/2012/02/25/nicar-2012-inspect-the-web-with-your-browsers-web-inspector/

## Example Sites

**_When grabbing data, please remember to make sure you have permission to get the information you are grabbing. Just because you can take photos off a site, doesn’t mean you can use them for your project. With great power comes great responsibility!_**

1. Denver elected officials – for html table -- [https://www.denvergov.org/content/denvergov/en/denver-elections-divison/voter-election-information/current-elected-officials.html#8eef4c9d-881f-402e-bb77-59dc06991b05](https://www.denvergov.org/content/denvergov/en/denver-elections-divison/voter-election-information/current-elected-officials.html#8eef4c9d-881f-402e-bb77-59dc06991b05),
1. Denver university list – for Scraper - [http://www.hometodenver.com/stats_denver.htm](http://www.hometodenver.com/stats_denver.htm)
1. Denver image search - [https://www.google.com/search?q=denver&source=lnms&tbm=isch&sa=X&ved=0ahUKEwiL2p_6qbTLAhWBPCYKHRCfC0EQ_AUIBygB&biw=1440&bih=801](https://www.google.com/search?q=denver&source=lnms&tbm=isch&sa=X&ved=0ahUKEwiL2p_6qbTLAhWBPCYKHRCfC0EQ_AUIBygB&biw=1440&bih=801)
1. ProPublica’s Recovery Tracker [http://projects.propublica.org/recovery/](http://projects.propublica.org/recovery/)
1. ProPublica’s Intern Lawsuits Tracker [http://projects.propublica.org/graphics/intern-suits](http://projects.propublica.org/graphics/intern-suits)
1. White House Recovery Act Projects [https://www.whitehouse.gov/anniversary-map](https://www.whitehouse.gov/anniversary-map)
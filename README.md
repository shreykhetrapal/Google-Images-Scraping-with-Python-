# Google-Images-Scraping-with-Python-

Thanks to https://towardsdatascience.com/image-scraping-with-python-a96feda8af2d

### Added the functionaility to read from csv files and scrape images
```
with open('BookNames.csv') as csvfile:
    readCSV = csv.reader(csvfile, delimiter=',')
    for row in readCSV:
        # print(type(row[0]))
        search_and_download(search_term=row[0],driver_path=DRIVER_PATH)
```        


Download the Google Chrome  web driver from [here](https://chromedriver.chromium.org/downloads) 

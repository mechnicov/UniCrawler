## Site Crawler 

#### Intented to work with [Parser Manager](https://github.com/mechnicov/parser-manager)

### Description

Crawler gets PDF, DOC, DOCX or HTML files from site and sends them to API of Parsing manager.

Implemented in Python 3.9.7 using Scrapy and Requests.

### Launching

1. Download or clone repo. Install all dependencies
   
2. Run Parsing Manager
   
3. Set your crawler settings, if nedded.
   
   **Currently no speed or total amount limit is set!**

4. Launch

    '''bash
    $ cd uni_parsing
    $ scrapy crawl uni_crawler
    '''

### License

MIT 
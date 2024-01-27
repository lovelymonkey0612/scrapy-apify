# You need to replace <project_name> with the actual name of your project. For example, the next command will create a new Scrapy project named "scrapyproject".

scrapy startproject scrapyproject

# To generate your first spider, you need to change your current directory to this “scrapyproject” folder using the cd scrapyproject command. Now, you can generate a new spider with the following command:

scrapy genspider <spider_name> <url_domain>

ex: scrapy genspider books books.toscrape.com

# You can execute the Scrapy project by issuing a crawl command from the command terminal:

scrapy crawl books

# We can also give a file name with the -o option to write the output to a file.

scrapy crawl -o out.csv books

# The book spider is now self-contained, making it straightforward to execute it. Just navigate your “spiders” folder in the Scrapy project and double-click the `books.py` file. Alternatively, you can open the command terminal in the “spiders” folder and run the scrapy runspider books.py command to run the spider. 


# ref url
https://oxylabs.io/blog/scrapy-web-scraping-tutorial

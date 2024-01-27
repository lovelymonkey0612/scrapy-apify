# You need to replace <project_name> with the actual name of your project. For example, the next command will create a new Scrapy project named "scrapyproject".

scrapy startproject scrapyproject

# To generate your first spider, you need to change your current directory to this “scrapyproject” folder using the cd scrapyproject command. Now, you can generate a new spider with the following command:

scrapy genspider <spider_name> <url_domain>

ex: scrapy genspider books books.toscrape.com

# You can execute the Scrapy project by issuing a crawl command from the command terminal:

scrapy crawl books

# We can also give a file name with the -o option to write the output to a file.

scrapy crawl -o out.csv books

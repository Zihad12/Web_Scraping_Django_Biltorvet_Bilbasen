# To run the Project

## To Run Django Server

## First got to manage.py file directory

cd .\web_scraping_django\

## Then run django using Following commands

### First run migrate the database

python .\manage.py makemigrations

python .\manage.py migrate

### Then run Django Server

python .\manage.py runserver

## To run Bilbasen and Biltorvet Scrapper to get data

## First Go to there scrapper python file

cd .\web_scraping_django\scrapper\Bilbasen\ (For Bilbasen)

cd .\web_scraping_django\scrapper\Biltorvet\ (For Biltorvet)

## Then run both of this scrapy spider python file to get new data

### For Bilbasen

scrapy runspider .\bilbasen_scrapper.py -O bilbasen_data.json

### For Biltorvet

scrapy runspider .\biltorvet_scrapper.py -O biltorvet_data.json

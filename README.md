# who-ebola-scraping
how to scrape this who ebola data: http://apps.who.int/gho/data/view.ebola-sitrep.ebola-summary-latest?lang=en

see notebooks how to do it and `requirements.txt` for required python packages

1. scrape available dates: `getdates.ipynb`
2. use this data to download actual files: `getfiles.ipynb`
3. merge all files into one dataset (and try to cleanup some stuff): `merge_csv.ipynb`

# Myntra E-Commerce Dataset

## Overview
This dataset contains information on products scraped from Myntra, an online fashion retailer. The data includes various attributes such as product name, rating, price, search query, and brand. This dataset was created as part of the DA323: Multi-Modal Data Processing and Learning-II course project.

## Contents

### Data
- `raw_data.csv`: File containing the dataset with the following columns:

    - name: Name of the product.
    - brand: Brand of the product.
    - price: Price of the product.
    - rating: Rating of the product on Myntra.
    - search_input: The search query used to find the product.
- `preprocessed_data.csv`: Processed version of `raw_data.csv`. Preprocessing techniques have been decribed in the "Datasheet".

### Code

- `scrap_test.ipynb` : Contains the scraping script and all the categories used to generate the data.

- `preprocess.ipynb` : Code to preprocess the data generated in previous step.

- `eda.ipynb` : Some basic exploratory data anlysis (EDA).

## Data Collection

The data was collected by legally scraping Myntra's website using web scraping techniques. The scraping process involved retrieving product information from diverse categories and search queries, all of which were publicly accessible.

<hr>


<p xmlns:cc="http://creativecommons.org/ns#" >This work is marked with <a href="https://creativecommons.org/publicdomain/zero/1.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC0 1.0 Universal<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/zero.svg?ref=chooser-v1" alt=""></a></p>
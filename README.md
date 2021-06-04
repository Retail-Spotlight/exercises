# Exercises

## Sample problems

### task 01

In the programming language of your choice load the `test_data\test_cases.csv` file into a data structure that you can work with.

- Clean the data that can be cleaned e.g. remove new line in description
- Log errors

Output cleaned file
Output log file include errors and information messages

### task 02

Display contents of `test_data\items.dat` in grid/table web page.
Use a control that gives extra grid functions.

### task 03

- set-up a database server of your choice, we use postgreSQL
- create table for the data in `test_data\items.dat`
- load data from `test_data\items.dat` into the table you have created
- write a queries to:
    - Find the number of sites in each region
    - Find the site or sites that charges to most for the product `5035766063919` `Heineken`
    - Find the transaction_id or transaction_ids with the highest gross sales value
    - Find the site or sites with the highest number of units

## Background on the data

### test_data\test_cases.csv

A small data file with various issues with source data that needs to be cleaned.

### test_data\items.dat

| Column name | Description |
|-|-|
|site_id | site identifier |
| post_code_char | Post code Sector |
| region | UK region |
| transaction_id | transaction identifier |
| date_of_day | transaction date |
| time_of_day | transaction time |
| barcode | EAN |
| product_name | Product description |
| category | Sales category |
| units | units sold of the product |
| gross_value | Amount sold for |

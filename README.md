# Exercises

## Sample problems

### Task 01

In the programming language of your choice load the `test_data\test_cases.csv` file into a data structure that you can work with.

- Clean the data that can be cleaned e.g. remove new line in description
- Log errors
- Output cleaned file
- Output log file include errors and information messages

### Task 02

Display contents of `test_data\items.dat` in a web page using a data grid component that gives the ability to manipulate the data.

### Task 03

- set-up a database server of your choice, we use postgreSQL
- create table for the data in `test_data\items.dat`
- load data from `test_data\items.dat` into the table you have created
- write a queries to:
    - Find the number of sites in each region
    - Find the site or sites that charges to most for the product `5035766063919` `Heineken`
    - Find the transaction_id or transaction_ids with the highest gross sales value
    - Find the site or sites with the highest number of units

### Task 04

In the file `test_data\items.dat` more than one product can appear with the same transaction id e.g. the transaction `6582190-3146-5e0a-8534-d45b7d0ff913`

In the programming language of your choice write a program to:

- load data from `test_data\items.dat` into memory
- find all the transaction ids that do *not* have the `Heineken` product in
- write into a new file the list of all the transaction ids found in the step above

### Task 05

Terraform

Supply terraform file(s) to create a VPC in a region define by a parameter:

- create a private and public subnets in 2 availability zones
- create a single DMZ public subnet that has no internal access to both the private and public subnets

### Task 06

Linux command line

With the file `test_data\items.dat` using linux command line:

- How many lines in the file
- How many unique transaction ids
- Find a transaction with 3 rows
- Create a copy of the file without the line with the gross_value `13.0.35`

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

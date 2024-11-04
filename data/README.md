# Data
There are two files in this directory that contain real customer data in CSV format. You can use these files (if you wish) to see what customers have ordered in the past and compare them to a potential new customer.
Additionally, we've provided a file of example customers that you can use to simulate a new or existing customer calling for either a support reason (poor Internet connection or low speed, etc.) or to upgrade their service.
## Current Customers
This zipped file contains ~800k rows collected on a single day from our network. It contains multiple columns of network data, geographic location, and some of the products they've purchased.<br><br>
You can find this data in [```current_customers.csv.zip```](current_customers.csv.zip).
## Example Networks
This file contains 10,000 rows collected on a single day from some of the customers in our network. These two files **do not overlap** but were collected on the same day. They do not contain any products (outside of their current speed).<br>
You can find this data in [```example_networks.csv```](example_networks.csv)

> **Note** - This will allow you to use the file as example networks you may run into but __you do not have to use this file.__ You are free to make up your own "customers". Feel free to use your own personal experiences with your Internet provider if you like
## Data Dictionary
The [Data Dictionary](Data_Dictionary.md) provides column names and types of both files.
## Product Catalog
The [Product Catalog](Product_Catalog.md) will provide you a list of possible products you could offer a customer based on their network data.
## Network Metrics Overview
One last [file](Network_Metrics.md) is some helpful tips on how network metrics impact a customer's experience. These can be useful when trying to decide, for example, if a customer needs another extender.

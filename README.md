# Data Challenge
This repo is intended for the 2019-2020 course Data Challenge 2. 

# Data description
There are four tables in the `data` directory.

transactions.csv contains all the transaction data. There are three columns:
- week: The week number in which the transaction took place
- transaction: The transaction number.
- product_id: The products bought in the specified transaction


promotion.csv contains information about the promotions that took place:
- week: The week number in which the promotions were relevant
- product_id: The product that was in discount
- discount: Discount percentage relevant for this product

products_priced.csv contains information about the products
- category: The overarching group this product falls in
- product_id: The product identifier
- description: Short description of the product
- std_sales_price: The non-discounted, default price that the products are sold for
- bio: 1 if the product is a biological product, 0 else
- basic: 1 if the product is a basic (generics; no-name) good, 0 else
- purchase_price: The price we purchase the product for.

stock_level.csv contains three columns:
- week: Week number. Week 0 means the last week of previous year
- product_id: The product identifier
- stock: Number of items in stock for a given week, measured at the end of the week. 

# Data Challenge
This repo is intended for the 2019-2020 course Data Challenge 2. 

# Data description
There are three tables in the `data` directory.

transactions.csv contains all the transaction data. There are three columns:
- week: The week number in which the transaction took place
- transaction: The transaction number.
- product_id: The products bought in the specified transaction


promotion.csv contains information about the promotions that took place:
- week: The week number in which the promotions were relevant
- product_id: The product that was in discount
- discount: Discount percentage relevant for this product

products_price.csv contains information about the products
- product_id: The product identifier
- std_sales_price: The non-discounted, default price that the products are sold for
- purchase_price: The price we buy the product for.

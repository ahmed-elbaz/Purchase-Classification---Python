# Purchase-Classification---Python
## Introduction

The target of this project is to predict the category of the purchased product based on some features related to customer behavior before purchasing a certain product.

## Data

The data for this project is added to this repository under the name of **purchases.xlsx** and the variables included in the dataset are as below

- User_id : ID of the customer.
- Bi_category_one : Category of the purchase made on 2000-01-01 and this column represents the labels while all other columns represent the features.
- Phones_carts : Number of products added to cart from category “phones” in the previous 42 days.
- Phones_carts_recency : Recency of the last products added to cart in category “phones”.
- Phones_purchases : Number of products purchased from category “phones” in the previous 104 days.
- Phones_purchases_recency : Recency of the last products purchased from category “phones”.
- Phones_views:  Number of products viewed from category “phones” in the previous 12 days
- Phones_views_recency: Recency of the last products viewed from category “phones”

Please note that **purchases.xlsx** file includes 2 tabs one called training_set and will be used for training and the other called testing_set which will be used for testing.

## Repository contents

The repository includes

1. purchases.xlsx which includes training and testing data.
2. Purchases Classification notebook which is the python code for this project.



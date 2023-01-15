# SnapIt

## Problem Statement

SnapIt is an online reselling platform where local sellers can list their products for sale and obtain the right amount of money from items they might not need anymore.<br>
We are the new employees hired by SnapIt to solve their main issue - deciding the selling price of their products. Most sellers do not know how to reasonably price their products and would like to be able to choose an optimum selling point. The problem here is that a user can list any item for sale or even a group of items from various categories.
Based on data provided about each item by the seller, we must choose a selling price for the specified product.

## Dataset:
PRODUCT_ID - id of the product<br>
PRODUCT_NAME - this is the name of the product provided by the seller<br>
PRODUCT_CONDITION - a number signifying the condition of the product<br>
CATEGORY - product category<br>
PRODUCT_BRAND - brand the product belongs to<br>
SHIPPING_AVAILABILITY - if the product is paid by the seller to be shipped or not (0 if not paid 1 otherwise)<br>
PRODUCT_DESCRIPTION - the description of the product provided by the seller<br>
PRODUCT_PRICE - this is the label; The value which is to be predicted<br><br>
Refer First Presentation for Data Preprocessing

## Results:
<img width="646" alt="Screenshot 2022-12-13 at 7 54 38 PM" src="https://user-images.githubusercontent.com/57355958/212553487-06632612-efeb-473d-bb67-2649a5db81f8.png">

## Deployment:
The SVM model with the best relative results is deployed using AWS.<br>
You can access it at http://snapit.ml/
### Input:
<img width="481" alt="Screenshot 2022-12-13 at 7 59 24 PM" src="https://user-images.githubusercontent.com/57355958/212553788-92b90fca-7ad7-40e9-955b-eea70db7c1e2.png">

### Output:
<img width="594" alt="Screenshot 2022-12-13 at 7 59 38 PM" src="https://user-images.githubusercontent.com/57355958/212553836-5fd0057c-38fc-4c00-8ce2-47d80ca4c6b4.png">

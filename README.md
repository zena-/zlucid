# Lucid developer application Shopify theme

Theme: Debut 17.11.00

This repo is for developers to use as part of the Lucid application process.

## Application test process

### What do you need to do??
There are two parts to settings up this test, the Github repository and the Shopify store.

#### For the Github repository
1. Clone this repository (don't fork it).
2. Create your own public repository on your own personal Github account. Make sure it is public so we can access it.
3. Create a development branch.
4. Make changes detailed below in your development branch.
5. Create a pull request for your branch but do not merge.

#### For the Shopify store
1. Create a Shopify development store. You will need to create a Shopify partner account for this if you don't already have one.
2. Set this theme with your work as the publsihed theme for the store.
3. Populate the stores products by uploading the [supplied CSV file](https://github.com/lucidnz/developer-application-shopify/blob/master/dummy_product_data.csv).

### What do you need to deliver?
When you are ready to deliver please provide the following:
- A link to the pull request on your repository.
- A public link to a Shopify development store where the changes have been made.
- A note about how long it took to complete the tasks. 

## Application tasks

### Task 1: Minimum order quantity — Product Page
Each product has a tag on it specifiying its minimum order quantity. The tag is `moq:N` where N is the minimum number of items that can be added to the cart.
On the product template make the necessary customizations to ensure when the item is added to the cart it will not add a quantity less than the specified minimum order quantity.

### Task 2: Minimum order quantity — Cart 
Following on from task 1 make the necessary customizations to the cart template so that the items in the cart can not have the quantity edited to be less than the minimum order quantity for that product.

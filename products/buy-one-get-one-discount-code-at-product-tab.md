### CREAT BUY X GET Y COUPON

If you would like to apply Coupon Code with detail following setup:

- Discount code: xyz
- Discount type: Buy X Get Y
- Customer buys: 2 ALPHADOM PRODUCT SAMPLE product with product handle alphadom-product-sample -> Product X
- Customer gets: 3 Black Fashion Zapda Shoes product with product handle black-fashion-zapda-shoes
- AT A DISCOUNTED VALUE: 70%

From your Shopify admin, go to **Discount** click **Creat Discount** and following setting


### USING BOGO COUPON CODE TO CREAT PROMOTION AT PRODUCT PAGE

#### 1. Add Meta Field Settings
Add 5 Custom metafields following instruction: [Shopify Metafield name Bundle Product ](/shopify-metafield.md)

```
- namespace: c_f
- key: buy_x_get_y
- value: DISCOUNTED VALUE: Discount percent

- namespace: c_f
- key: product_y
- value: Product Y Handle

- namespace: c_f
- key: discount_code_x_y
- value: discount code buy x get y

- namespace: c_f
- key: number_discount_x
- value: Quantity product X customer buy to apply Buy X get Y Coupon

- namespace: c_f
- key: number_discount_y
- value: Quantity product Y customer gets when apply Buy X get Y Coupon

```
#### 2. Setting Product Custom Field - Metafield

Navigate to Product page, add custom field for product page with detail.
[You may following instruction here to know how to add custom field](/shopify-metafield.md)

![](/assets/product-bogo-metafield.png)

Click **Save Custom Field** and **Save** product

#### 3. Show Promotion BOGO to Product Detail Page.

From your Shopify admin, go to 

1. Find the theme that you want to edit and click **Customize**.
2. **From the top bar drop-down menu, select the type of page to edit: Product pages.**
3. Click **Sections** tab > **Product pages** > **Metafields**
4. Tick show buy 1 get 1 & Select Promotion Title. Click **Save**

![](/assets/buy-one-get-one.png)

#### Mass Edit All Products Metafields


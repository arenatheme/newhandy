Take a look at the demo to see how it should end up functioning: 
https://arena-Handy.myshopify.com/products/blue-bandeau-bikini-top

## Set Product templates

The theme only support bundle style for product use follow templates:
* Product default with bundle product: `product.default-bundle`
* Product Big image with bundle product: `product.big-image-bundle`


## Step 1: Add Metafields data for Bundle Product

You may following instruction [Shopify Metafield name Bundle Product ](/shopify-metafield.md)

![](https://media.giphy.com/media/xT9IgsIcmG9yPuYXXG/giphy.gif).

The Bundle product meta field require add  2 [product handle](https://help.shopify.com/en/themes/liquid/basics/handle) to folowing field

```
- namespace: c_f
- key: bundle_1
- value: Add your product handle #1!

- namespace: c_f
- key: bundle_2
- value: Add your product handle #2!

```
### Step 2. Edit Product

#### Option 1: Edit Product by Custom Field Chrome App

You may follow at [Metafields Instruction](/shopify-metafield.md)

![](/assets/thelook-bundle.png)

### Option 2: Mass Edit All Products Metafields add Bundle Product.

#### Steps
1. Go to this link: [https://shopify.com/admin/bulk?resource_name=Product&edit=metafields.c_f.bundle_1:string,metafields.c_f.bundle_2:string](https://shopify.com/admin/bulk?resource_name=Product&edit=metafields.c_f.bundle_1:string,metafields.c_f.bundle_2:string)

2. Add Product handle to Bundle 1 & Bundle 2 field. If you would like to add product 3 products
Replace shopify.com by your website url.

![](/assets/bundle-image-mass.png)

Eg.
 * Go to Product 1: Add bundle1=handle product 2, bundle2= handle product 3
 * Go to Product 2: Add bundle1=handle product 1, bundle2= handle product 3
 * Go to Product 3: Add bundle1=handle product 1, bundle2= handle product 2

> Handle product must follow handle strings in Shopify, refer https://help.shopify.com/themes/liquid/filters/string-filters\#handle-handleize. Eg : you have color is “Color1”, just add group-color1


You may also edit product by other Shopify app: https://apps.shopify.com/search?q=metafield


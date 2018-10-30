Take a look at the demo to see how it should end up functioning: 
https://arena-artemis.myshopify.com/products/blue-bandeau-bikini-top

We only support group for 3 products.
### Add 2 Metafields for Bundle Product
You may following instruction [Shopify Metafield name Bundle Product ](/shopify-metafield.md)

The Bundle product meta field require add  2 [product handle](https://help.shopify.com/en/themes/liquid/basics/handle) to folowing field

```
- namespace: c_f
- key: bundle_1
- value: Add your product handle #1!

- namespace: c_f
- key: bundle_2
- value: Add your product handle #2!

```
![](/assets/thelook-bundle-product-metafield.png)

#### Edit Product by Custom Field Chrome App

You may follow at [Metafields Instruction](/shopify-metafield.md)
![](/assets/thelook-bundle.png)

#### Mass Edit All Products Metafields add Bundle Product.


1. You may go to this link: [https://shopify.com/admin/bulk?resource_name=Product&edit=metafields.c_f.bundle_1:string,metafields.c_f.bundle_2:string](https://shopify.com/admin/bulk?resource_name=Product&edit=metafields.c_f.bundle_1:string,metafields.c_f.bundle_2:string)

2. Add Product handle to Bundle 1 & Bundle 2 field. If you would like to add product 3 products
Replace shopify.com by your website url.

![](/assets/bundle-image-mass.png)


 * Go to Product 1: Add bundle1=handle product 2, bundle2= handle product 3
 * Go to Product 2: Add bundle1=handle product 1, bundle2= handle product 3
 * Go to Product 3: Add bundle1=handle product 1, bundle2= handle product 2

> Handle product must follow handle strings in Shopify, refer https://help.shopify.com/themes/liquid/filters/string-filters\#handle-handleize. Eg : you have color is “Color1”, just add group-color1





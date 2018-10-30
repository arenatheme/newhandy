Take a look at the demo to see how it should end up functioning: https://arena-artemis.myshopify.com/products/womens-striped

Just follow below steps, you will have a product with product images are grouped by color.


### Product Alt Image

We use product alt image of product to mix and max color variant group. The images are featured image of variant will be grouped to color of corresponding variant

* From Shopify admin, go to **Products** > Select **Product** you would like edit.

* Scroll to “images” and “variants” boxes.
* Select the image relate to Variant. You can do it one by one. Hover to the image and Click **Edit alt text**
* You will see a popup,add content follow syntax:

> 1. Alt: **group-handle-string-color**.
> Handle string color must follow handle strings in Shopify, refer https://help.shopify.com/themes/liquid/filters/string-filters\#handle-handleize. Eg : you have color is “Color1”, just add group-color1
> 2. Alt: **group-all**

![](/assets/edit alt text.png)
    
![](/assets/group-image.png)

We will call “group-color1” is “**grouping images formula**“. 

Notes :

* When you use **group-handle-string-color**, the images without **group-handle-string-color** wont show in product thumbnail when you click any variant.

* The images which alt contains “group-all” will be shown in product thumbnail for all variant you click

  



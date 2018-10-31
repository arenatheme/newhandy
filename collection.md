You can group your products into collections to make it easier for customers to find them by category. Here are a few examples of collections that you might create:

* clothes for men, women, or children
* items of a certain type, such as lamps, cushions, or rugs
* items on sale
* items in a certain size or color
* seasonal products, such as holiday cards and decorations

After you create a collection, it can be shown on your online store as a webpage with a gallery of the products that are in the collection. Your customers can then click a product image on the collection page to visit a specific product's page. You can help customers find and view collections by [adding links](https://help.shopify.com/en/manual/products/collections/make-collections-findable) to the collections in a menu in your store's navigation.

The exact layout and appearance of collection pages depends on your theme.

## Collection alternate templates:

1. Default template `collection`
2. Infinity Collection: `collection.infinite`
   Set template with Infinity load product
   eg. [https://arena-handy.myshopify.com/collections/kitchen-things](https://arena-handy.myshopify.com/collections/kitchen-things)
3. Quick order form collection: collection.quick-order
   eg. [https://arena-handy.myshopify.com/collections/kitchen-things](https://arena-handy.myshopify.com/collections/kitchen-things)

This will allow you to view a collection or page on an alternative template by adding the templates name to the URL of the page. The format we would use here is `view=alternative_template_name`  
and this would be added to the end of the page URL.

You could assign a collection from the admin:

![](/assets/assigncoltemplate.png)

---

## Customize Collection Page by Sections

#### Steps

* From your Shopify admin, go to **Product** &gt; **Collection**. Creat or Select a collection to assign template.

* Assign template to collection  
      Eg.  
      I assign collection infinite to collection  
      [https://arena-handy.myshopify.com/collections/kitchen-thing](https://arena-handy.myshopify.com/collections/kitchen-thing).  
      Collection handle: kitchen-things

![](/assets/handlecol.png)

From your Shopify admin, go to **Online Store &gt; Themes**

* Find the theme that you want to edit and click **Customize**
* From the top bar drop-down menu, select the type of page that you want to edit. **Select** **Collection pages**
* Change collection templates to Customize by add at the end of URL at browser

**Note:** 

* Shopify only support for only **1 Collection page template** to customize at Section **Select**.
* Collection is not support to use `view=alternative_template_name` when you customize Sections. 

In order to customize collection template, you should change right handle collection as template.

```
  Eg. .../editor#/collections/birthday-gifts
  -> customize collection default
  Eg. .../editor#/collections/kitchen-things
  -> customize collection infinite (as I assign kitchen-things to display Infinite template before)
```

#### Options: depend on collection templates

There are 3 Static Section: **Header \(apply for all pages\), Collection \(collection detail\), Bottoms \(below collection detail\), Footer \(apply for all pages\). **

* Collection pages
  * Products per page: Set the number of products show on each collection page
  * Show collection mode view: Show select option mode view Grid/List
  * Show collection Sort by
  * Collection description position
  * BREAKCRUMB
  * **SIDEBAR** PLACEMENT
  * CONTENT: Setting contents for **SIDEBAR**
  * **Theme Settings**: Setting from this part will effect to the whole website.
##### CONTENT
    * Sub collection: Display Sub Collection to Collection page.
    * Toggle Filter: Filter for your Collection page
    * Sidebar Collection Menu: Collection Nestest Navigation show at Sidebar.
    * Sidebar Banner: Banner at sidebar
    * Sidebar Product: Product featured as sidebar

---




{% method %}

In your theme customize window, you can select page to config at:

![](/assets/how to choose page.png)

Most pages are supposed to have respective static sections for configuration, so always remember to check **Sections**.

The following will only mention pages that have static sections.

{% sample lang="Product Templates" %}

There are 6 product templates:
 * product
 * product.bundle
 * product.full
 * product.stick-description-v1
 * product.stick-description-v2
 * product.v2
 
In order to select a template for your product, at the very bottom of the most right column of your product admin window, please find section '**Theme templates**'

![](/assets/choose-product-template.png)

They use static sections for configuration so depending on which template you choose, there will be a corresponding static section.

![](/assets/static-sec-product-general.png)

Their settings mostly are the same. Let's explore their general settings and particular ones

## General Settings
 * Layout: **Full width** or **Boxed**. If **Full width**, your product page will set its width based on Site Width Mode at [Theme settings](theme-settings.md) > **Color & Styles**  
 
 (**NOTE:** **_product.full_** does not have this option)
 
 * Background color
 * Show dynamic checkout button: When purchase product by clicking this button, customers will be take directly to checkout page for checkout process
 
 ![](/assets/but-it-now-btn.png)
 
 (**NOTE:** **_product.bundle_** does not have this option)
 
 * Product Code - SKU, Product Tags, Product Collections, Show social sharing
 
 ![](/assets/sku-tag-col-sharing.png)
 
 (**NOTE:** **_product.v2_** does not have options for _Product Code - SKU_, _Product Tags_, _Product Collections_)  

 * Use variant images for swatch color:
  - If turn on:
  
   ![](/assets/use-variant-image-on.png) 
   
  - If turn off:
  
  ![](/assets/use-variant-image-off.png)
  
 * Show in stock / out stock message: 
 
 ![](/assets/in-out stoci.png) 
 
 In order for this option to work, in your inventory configuration, you have to:
      
 ![](/assets/inventory-to-show-out-in-stock.png)
    1. Use option 'Shopify tracks this product's inventory'.
    2. Turn off 'Allow customers to purchase this product when it's out of stock'.
    3. Your quantity must bigger than 0.
    
 (**NOTE:** **_product.bundle_** does not have this option)   

 * Color and Size Swatches: Choose to display your color and size whether as _Swatch_ or _Dropdown_ 
 * Metafield: Please refer to [How to install metafields](https://arenathemes.freshdesk.com/solution/articles/6000178729-how-to-install-meta-fields-shopify-theme-by-arenathemes), [Shopify Custom Fields](https://freakdesign.com.au/pages/shopify-custom-fields) and [Shopify FD](https://freakdesign.com.au/pages/shopifyfd) to get knowledge of what metafield is.
 
 Our theme supports the following metafields:
  - Video Meta Field:
    * namespace: c_f
    * key: video_url
    * value: Add your amazing video!
    
    ![](/assets/video-metafield.png)  

  - Size Chart Meta Field:
    * namespace: c_f
    * key: size_chart
    * value: Add your image size chart url!
    
    ![](/assets/size-chart-meta.png)

  - Short Description Meta Field:
    * namespace: c_f
    * key: description_excerpt
    * value: Add the product short description!
    
    ![](/assets/short-des-meta.png)
  
  - Countdown Timer Meta Field:
    * namespace: c_f
    * key: countdown_timer
    * value: Please use mm/dd/yyyy
    
    ![](/assets/countdown-meta.png)  
    
  - Sale Meta Field: This metafield is used together with **Countdown Timer Metafield**
    * namespace: c_f
    * key: sale_number
    * value: Set up an original number for product's quantity.
    
    ![](/assets/sale-meta.png)
  
 * Product tabs: Product tabs will use **Content** for data.
 
 ![](/assets/product-tabs.png)  
 
 If you use Content type '**Description**', in order to use multi-tabs with heading 5 tag, please refer to [this](https://arenathemes.freshdesk.com/solution/articles/6000177903-product-multi-tab-description-tab-missing-problem-arenathemes)
 
 (**NOTE:** **_product.stick-description-2_** does not have option for _Product tab alignment_)            

 * Related Product: show a product slider on product page for products related to the main product.
 
 ![](/assets/related-product.png)

## Particular Settings For Each Product Templates
 
 ### product
  * Thumbnail Images Position: 3 position
   - Bottom:
   
   ![](/assets/thumbnail_bottom.png)
   
   - Left:
   
   ![](/assets/thumbnail_left.png)
   
   - Right:
   
   ![](/assets/thumbnail_right.png)
   
  * Sidebar 
  
### product.bundle
  * This template allows user to add 2 more products besides the main one, so customers to the site can choose to buy only 1 main product or with 1 or both additional products.
  
  ![](/assets/product-bundle.png)
  
  * In order to add 2 additional to this product, please use 2 metafields:
  
   - Product Bundle 1 Meta Field:
     * namespace: c_f
     * key: bundle_1
     * value: Add your product handle #1!
     
   - Product Bundle 2 Meta Field:
     * namespace: c_f
     * key: bundle_2
     * value: Add your product handle #2!

### product.v2
  * Policies: to customize this function, please use Content's type named 'Policy'.



{% sample lang="Collection Templates" %}

There are 3 collection templates:
 * collection
 * collection.infinite
 * collection.order-form

In order to select a template for your collection, at the very bottom of the most right column of your collection admin window, please find section '**Theme templates**'

![](/assets/col-templates.png)

They use static sections for configuration so depending on which template you choose, there will be a corresponding static section.


### collection

![](/assets/col-settings.png)

![](/assets/col-settings-short-des.png)

 * Filter
 * Sidebar Settings:
  * Sidebar Placement
  * Sidebar Categories
  * Sidebar Product List
  
### collection.infinite

Basically, this template's settings are all the same to **collection **template, except it won't show all products and only display some of them when you scroll to collection's bottom (keep scrolling and it will continue to show up products until no products left to show).

![](/assets/col-infinite.png)

### collection.order-form
Display as many products as you would like and your customers can select many of them to buy at once.

![](/assets/col-order-form.png)
                    
      
                                  
                    
{% sample lang="Other Templates/Pages" %}
### Collection List
This is a default Shopify page. At its static section, you can choose to display all collections or selected ones.  

### Blogs
### Blog Posts
### 404 Page

{% sample lang="Page Templates" %}

You need to create page in order to use page templates.

![](/assets/how to create page-1.png)

![](/assets/how to create page-2.png)

There are 4 special page templates:
 * page.about
 * page.contact
 * page.lookbook
 
(Other template, **page**, is Shopify's default template) 

### page.about
In **page.about** static section, you can customize **Testimonial**, **Logo List**, **Our Team** and **Banner & Text**.
Please use **Content** to input respective data.

 ### page.contact
 ### page.lookbook


{% common %}


{% endmethod %}
## Adding Requirement Shopify Metafield to your store.

You can use metafields to add custom fields to objects such as products, customers, and orders. Metafields are useful for storing specialized information, such as part numbers, customer titles, or blog post summaries.

Eg. Add a short description, video embedded, 3D product embed... for each product page. Add Sub collection for Collection page.

More detail [https://help.shopify.com/en/manual/products/metafields](https://help.shopify.com/en/manual/products/metafields)

---

### Adding supported Meta field for Theme

#### Steps

1. Currently, **custom field extensions** only support **Chrome browser** so to use you must install this browser. [Download and install here](https://www.google.com/intl/en/chrome/browser/desktop/index.html)

2. Download & Install [**ShopifyFD Dashboard Tool Chrome Extension**](https://chrome.google.com/webstore/detail/shopifyfd-dashboard-tool/lffljkleilfpjlmcdnoaghhcbnemelge?hl=en)

3. Add **New meta field** on the shop.

   * From your Shopify admin, go to **Settings &gt; General**
   * Click ** ShopifyFD Dashboard Icon** at Top Bar Chrome Browser.
     The Store Metafield will showup.
     ![](/assets/ShopifyFD.png)
   * **Add New Metafield** & **click Save**
   
   ![](https://media.giphy.com/media/xT9IgsIcmG9yPuYXXG/giphy.gif).

4. List of **Meta field** Arena support use

![](/assets/metafield Handy.png)

**Collection Page**

* _**New: Add Sub-collection**_

```
    - namespace: c_f
    - key: subcategory
    - value: Add menu handle item to display subcategory
```

**Product Page**

* _**New: Add Bundle Product**_

  ```
    - namespace: c_f
    - key: bundle_1
    - value: Add your product handle #1!

    - namespace: c_f
    - key: bundle_2
    - value: Add your product handle #2!
  ```

* _**New: Add Progress bar: Only x left in stock**_

  ```
    - namespace: c_f
    - key: sale_number
    - value: Total number of products you have in stock at the open sale
  ```

* _**New: Add Exit Intent Popup Product**_

  ```
    - namespace: c_f
    - key: discount_code
    - value: Add your Coupon code for the product

    - namespace: c_f
    - key: discount_percent
    - value: Display percent of discount
  ```

* _Add Countdount Timer_

  ```
    - namespace: c_f
    - key: countdown_timer
    - value: Date format is mm/dd/yyyy
  ```

* _Add Short Description_

  ```
    - namespace: c_f
    - key: description_excerpt
    - value: Add the product short description!
  ```

* _Add Product Image 360 Description_

```
    - namespace: c_f
    - key: image360
    - value: Add your image url!
```

* _Add Product Video Description_

  ```
    - namespace: c_f
    - key: video_url
    - value: Add your amazing video!
  ```

* **It's ready to use to add Custom Field for the Theme**

---

### Using** Custom field to add content Shopify Metafield**

1. Download & Install [**Custom Fields for Shopify** **Chrome Extension**](https://chrome.google.com/webstore/detail/custom-fields-for-shopify/alfplfpobekffinigeidgmmfjollghln?hl=en-GB)

   This extension will help Shopify store owners edit content easier by using Custom Fields.

2. Go to objects such as **products**, **collection** you would like to add custom field.  
   ![](/assets/collection-noncustom.png)

3. Click icon Load Custom Field at the top right you browser.  
   ![](/assets/add load customfield.png)

4. Now Custom field will ready for you to add content

![](/assets/custom-field.png)** **

**Click Save Custom Field** to save your data

![](/assets/save customfield.png)

---

### Bulk editing product metafield

As we’ve seen, metafields have three components: **a namespace, a key, and a value**. Once you know the namespace and key for your metafield, you can display it in [the bulk editor](https://help.shopify.com/en/manual/productivity-tools/bulk-editing-products) by making small changes to the URL of the bulk editing page in the Shopify Admin.

Eg. Collection page: [https://shopify.com/admin/bulk?resource\_name=Collection&edit=metafields.c\_f.subcategory:string](https://shopify.com/admin/bulk?resource_name=Collection&&edit=metafields.c_f.subcategory:string)

In this URL, **c\_f** is the **metafield’s namespace** and **subcategory** is its key. You can replace these with values to match your use case. The **string** part of the URL tells Shopify about the type of data that we want to store in the metafield. The bulk editor is able to display **five types of metafields** – **string, money, boolean, select and number.**


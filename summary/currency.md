## Converting currencies in your store

You can use the multiple currencies script in your theme to show your prices in a currency that your customers are familiar with.

The multiple currencies script can be used to help your customers view product prices in a currency that they are familiar with, but the currency will always switch back to your store's currency at checkout. Your store's currency is the currency that you have set up on the [General settings](https://www.shopify.com/admin/settings/general) page of the admin.

From your Shopify admin, go to

1. Click**General**.

2. In the**Standards and formats**section, click the**Change formatting**link.

3. In the**HTML with currency field**, wrap the existing content in an HTML span element with a class name set to`money`.
   If your store currency is United States Dollars \(USD\), then the format will look like this:  
   ```
   <span class=money>${{amount}} USD</span>
   ```
4. In the HTML without currency field, enter the exact same content that you entered in the HTML with currency field. Adding the currency descriptor to both formats will help to differentiate between currencies that use the dollar sign ($).
   If your store currency is United States Dollars (USD), then the format will look like    this:
   ```
    <span class=money>${{amount}} USD</span>

   ```
![](/assets/currrency.png)


  




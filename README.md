# Woocommerce additional product identifiers
This little helper plugin adds missing Product identifiers to Woocommerce products. It will add 4 important product identifiers Brand, MPN, UPC, EAN, GTIN to simple and variabel products required for sales channels

This will make it easier for the customers from woocommerce product feed manager (wpmarketingrobot.com) to add the important product identifiers to their Woocommerce webshop and are able to select the identifiers in our Product Feed Manager.

Next to the Product identifiers we have added a optimised title field so you can create special optimized titles to your products and use them in you feeds.

# Use this plugin
* Step 1. Click the green button (top right) "Clone or Download"
* Step 2. Click download ZIP
* Step 3. Inzip the file
* Step 4. The plugin directory is named "woocommerce-additional-product-identifiers-master" Remove -master from the name
* Step 5. .zip the file to woocommerce-additional-product-identifiers.zip
* Step 6. Install the plugin in your Wordpress Woocommerce shop like an ordinary plugin. 

And your done. You will find extra fields with eacht prouct you can fill in with the right data.
If you would like to use the fields in your theme you can retreive data with the Wordpress get_post_meta() function.
Like: `<?php echo get_post_meta( get_the_ID(), '_wpmr_gtin', true ); ?>` (in this case showing the GTIN number.)

# Change log
= version 1.2.0 = 
* Removed woocommerce version check because it was giving en E-notice and we want users to use the latest version of woocommerce any way.

= version 1.1.0 =
* Added title field so we can use a custom/optimized title for products and product variations in the channels.

= version 1.0.3 = 
* Solved bug with naming function redeclarition

= version 1.0.2 = 
* Solved bug mixing PI values
	
= version 1.0.1 = 
* Layout bug opgelost
* Ondersteuning Wordpress lager dan 2.4.4
	
= version 1.0.0 =
* Initial resease

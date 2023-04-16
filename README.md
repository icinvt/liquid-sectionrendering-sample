# liquid-sectionrendering-sample
A simple sample of Shopify's section rendering API. You can check it out in the custom liquid of the DAWN theme.


1)
Change part of main-product.liquid.
"Search for "when 'inventory'", comment out most of it, and change "product.selected_or_first_available_variant.inventory_quantity" to "<span>" tag and enclose it (with "realtime" as the id) and add.

2)
Save.

3)
Open the theme customiser.

4)
Next, open the product page.

5)
Add two custom liquid blocks to the product information.

6)
Paste script-a.liquid and script-b.liquid into each block.

7)
Save.

Try changing the inventory stock of the product and see if the inventory stock on the product page changes.

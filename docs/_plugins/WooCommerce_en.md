---
title: WooCommerce (EN)
position: 1
---

**You use WordPress with the WooCommerce plugin ? Follow those steps :**

1. Install the Zei plugin on WordPress
  * Go to "Plugins" > "Add New" and search "zei", then "Install"
  * Or [dowload the plugin here](https://wordpress.org/plugins-wp/zero-ecoimpact-woocommerce/)
  and install it : "Plugins" > "Add New" > "Upload Plugin"
  * Or upload [this repository](https://github.com/zei-world/api-woocommerce){:target="_blank"} inside a "zei-wc" directory on "/wp-content/plugins/" from your WordPress installation (by FTP for example)
2. Go to [Zei](https://zei-world.com){:target="_blank"} > your company Public Profile > "My Tools" > "API management"
3. Then, in your WordPress admin panel, go to "WooCommerce" > "Settings" > "Integration" and fill in your ZEI API credentials (API key and API secret)
4. From there, you'll be able to manage your offers in two ways : (for your rewards, refer to the section below)
  * You can link all your products to an offer by setting "Global offer" in "WooCommerce" > "Settings" > "Integration".
  * You can link a specific product to an offer by setting "Zei offer" in the "General" tab when you edit a product.
5. Let the magic begin !

**Coupon codes for rewards**

Edited codes on ZEI must work on your online shop, so you need to edit some WooCommerce coupon codes : 

1. First of all, you need to know your reward id (they are listed in your API page on ZEI)
2. In your WordPress admin panel, go to "WooCommerce" > "Coupons" > "Add Coupon"
3. Name it EXACTLY as following : "zei_reward_42" (42 being your reward id)
4. Edit the coupon like you want (according to your ZEI reward)
5. Let the magic happen again !

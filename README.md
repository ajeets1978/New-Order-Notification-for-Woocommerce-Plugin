# Woocommerce New Order Notification Plugin

Woocommerce custom order page for showing a popup notification with sound when a new order received. 

Usage: 

- Download the current version from release folder and upload it to wp-content/plugins using FTP or using Admin Panel -> Plugins -> Add New -> Upload Plugin, then extract there.

or

- Download: https://wordpress.org/plugins/new-order-notification-for-woocommerce/

or

- Wordpress Admin Panel -> Plugins -> Add New -> Search -> "New Order Notification for Woocommerce" -> Install -> Activate

---

Version 1.0.0:

- New Order Notification Popup with Sound effect in a custom order page at admin panel.
- Settings for New Order Notification Popup strings, refresh time of order controller and music file url.

Version 1.0.1:

- Small bug fixes.
- CSS additions.
- README is more detailed now.

Version 1.0.2:

- Settings field for selection of order statuses that the plugin will notify.
- CSS fixes.
- Small bug fixes.

Version 1.0.3:

- "Alert only for orders that contain specific products" option is added.
- You may enter the product ids one by one from the related settings field.
- Small bug and CSS fixes.
---

Version 1.1.0:

- Reported bug fixed for WooCommerce Shops that have not received any (0) or enough (<10) orders yet.
- An information message is added for WooCommerce Shops that have not received any orders.
- Auto refresh with every 5 seconds to detect the first order of a very new WooCommerce shop.
---

To-Do: 
- A video tutorial for example usage.
- Audio file upload button instead of link field
- Setup option for activating on standard order page or using a custom order page
- Separate tab for settings page.
- Access control: Shop manager can access only the New Order Notification page, Administrator can access the New Order Notification page and Settings page.
- Print a warning message if WooCommerce plugin itself is not active for now while activating the New Order Notification for WooCommerce plugin. (+)

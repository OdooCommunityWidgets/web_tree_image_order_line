product_image_list_view
=======================

Product Image List View allows for the display of the default Odoo product image in list view.

Product Image List View

<H4>Please use the 8.0 branch:</H4> 
    sudo git clone -b 8.0 https://github.com/OdooCommunityWidgets/product_image_list_view.git

This will provide you with the latest working 'stable' version of the module built for the 8.0 branch. Please be advised this module is still under development.

<H3>Live Line Edit Demo:</H3>
<img src="https://cloud.githubusercontent.com/assets/2337666/5467578/dc092834-85fc-11e4-828b-c2ea1ec38852.png"/>

<H3>Live Line Edit Saved Demo:  (Work in progress)</H3>
<img src="https://cloud.githubusercontent.com/assets/2337666/5467579/dc0ad602-85fc-11e4-8429-cbcc3aae2091.png"/>

TODO: master
===================
* Fix view_list.js for backend to allow Live Line Edit Saved to display a product image thumbnail after save.
  * view_list.js needs to be added correctly to the backend javascript to allow for proper display of the thumbnail after save.
  * Add functionality for multi-image
    * Add compatibility (without dependency) with website_multi_image
      * Add modal box view for choosing which image to use on order line
    * Add compatibility (without dependency) with product_image_report_order_lines for allowing for sync of printed reports and live order line view.
* Move product image to far left after product_id
  * Add support for different image sizes (eg. 50 x 50, 150 x 150, etc.)  

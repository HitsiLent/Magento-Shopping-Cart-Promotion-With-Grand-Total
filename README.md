# Magento-Shopping-Cart-Promotion-With-Grand-Total

This is a easy way make Magento add condition with Subtotal with discount(Grand Total)

### Reference List 

* http://www.magebuzz.com/blog/magento-shopping-cart-promotion-grand-total/
* http://stackoverflow.com/questions/11393617/magento-free-shipping-shopping-cart-rule-help-needed

###  Known Issue Fixed

Follow http://www.magebuzz.com/blog/magento-shopping-cart-promotion-grand-total/ will cause payment amount double issue, cuz $address object already has a property called base_grand_total, recommended use Subtotal with discount instead of Grand Total

Custom Price
============

Overview
````````

This extension allows the store admin to create products with editable prices. This extension will allow customers to negotiate the product price.

Customers can enter a custom price on the product detail page in the box, proceed to checkout, and place an order with that price.

.. note::
    Hope you are able to successfully install the module.

How to Configure
````````````````

#. Open Admin Panel, go to ``Logicrays > Settings > Configuration``

    .. figure:: img/Dashboard-Magento-Admin.png
        :alt: Configuration Settings.

#. Now here you can see all the configure fields of the module. I'll explain them one by one at the end of the image.

    .. figure:: img/Configuration-Settings-Stores-Magento-Admin.png
        :alt: module configuration fields

    :guilabel:`General`
        * **Module Enable**: Choose ``Enable`` to use the functions of this module.
        * **Frontend Label**: In this field enter text whatever you want to be as a label. 
        * **Show Allowed Price**: If you select ``Yes``, then it will display the allowed price set by admin for a particular product. If you select ``No`` then it will display only a message.
        * **Custom Price Validation Message**: Write your validation message here.

.. note::
    Now save the configuration and cache flush.


#. Now we have to select some products to enable the functionality of this module.
    
    go to ``Catalog > Products`` see below image.

    .. figure:: img/Dashboard-catalog-product.png
        :alt: Catalog Product

#. Here you can see a list of products, and from here you can open a product in Edit mode.

    .. figure:: img/Products-Inventory-Catalog-Magento-Admin.png


#. Scroll down after opening a product in Edit mode to see the product's section that is ``Custom Price``.
    
    .. figure:: img/Joust-Duffle-Bag-Products-Inventory-Catalog-Magento-Admin.png

    :guilabel:`As per above image there are two config`
        * **Allow Custom Price**: If you want to display the custom price of this product, then check ``Yes``.
        * **Set Minimum Price**: If you want to set the minimum price of this product, then enter the price in this field.

    .. note::
        Now save the product and flush the cache. You can enable the ``Custom-Price`` functionality on any product in the same way.

#. This is the ``product view page``, check below image.

    .. figure:: img/Joust-Duffle-Bag-frontend.png

#. You can check the error message as well when the user enters the below price as set by the admin for that product. see below image.
    
    .. figure:: img/Joust-Duffle-Bag-error-message.png


    .. note::
        After placing an order with a custom price successfully. The ``Custom Price`` extension will manage grids for those orders that are placed by custom price.
        
        go to  ``Logicrays > Custom Price Orders > Manage Custom Price Order``

    .. figure:: img/Custom-Price.png

    .. figure:: img/Manage-Custom-Price-Orders-Custom-Price-Orders-LogicRays-Magento-Admin.png

#. After opening the product in view mode, you can see the price difference on the sales order grid. see below image

    .. figure:: img/Operations-Sales-Magento-Admin.png


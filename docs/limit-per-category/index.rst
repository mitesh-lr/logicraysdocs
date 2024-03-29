Limit Per Category
==================

Overview
````````

This extension allows for every customer group to place restrictions on the product quantity ordered from each
category

.. note::
    Hope you are able to successfully install the module.

How to Configure
````````````````

#. Open Admin Panel, go to ``Logicrays > Extensions & Notifications > Manage Extensions``

    .. figure:: img/Dashboard-Magento-Admin.png
        :alt: Configuration Settings.

#. Now here you can see all the configure fields of the module. I'll explain them one by one at the end of the image.

    .. figure:: img/Configuration-Settings-Stores-Magento-Admin.png
        :alt: module configuration fields

    :guilabel:`General`
        * **Enable**: Choose ``Yes`` to use the functions of this module.
        * **Min Qty Error Message**: You have to specify the error message for the minimum quantity.
        * **Max Qty Error Message**: You have to specify the error message for the maximum quantity.
        * **Qty Threshold**: This is the dynamic row in this; you have to choose below.

                ``Customer group`` : Which customer group to allow this function.

                ``Category`` : Which category to allow this function.

                ``Min Qty value`` : Enter the minimum quantity value to raise the error and show the error message, whatever you enter above.

                ``Max Qty Value`` : Enter the maximum quantity value to raise the error and show the error message, whatever you enter above.

    .. note::

        Now save the configuration and cache flush.

.. note::
    Now we'll look at the front-end functionality of this module.

#. Open any product in front-end.

    and enter the quantity; after that, try to ``Add to Cart`` that product. see below image.

        **When you enter the minimum quantity specified from the admin side configuration, then you can see an error message.**

        .. figure:: img/Wayfarer-Messenger-Bag.png
            :alt: product image

        **When you enter the maximum quantity specified from the admin side configuration, then you can see an error message.**

        .. figure:: img/Wayfarer-Messenger-Bag_max_qty.png
            :alt: product image
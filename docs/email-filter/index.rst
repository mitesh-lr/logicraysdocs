Email Filter
============

Overview
````````

This extension allows you to prevent unauthorised access to certain domains or email addresses on your store.

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
        * **Email Domain Restriction**: In this field, you have to specify which domain or which types of email you restrict on your website.

        :guilabel:`Apply on Pages`
            * **Customer Account Registration**: If you select ``Yes``, you can avoid entering an unwanted email address on the Register Page.
            * **Checkout Page**: If you select ``Yes``, you can avoid entering an unwanted email address on the Checkout Page.
            * **Contact Us Page**: If you select ``Yes``, you can avoid entering an unwanted email address on the Contact Us Page.
            * **Newsletter Subscribe**: If you select ``Yes``, you can avoid entering an unwanted email address on the Newsletter.

.. note::
    Now save the configuration and cache flush.


.. note::

    Now we have applied EmailFilter to some front-end default forms; see the images below.

:guilabel:`Register Form`

    .. figure:: img/Create-New-Customer-Account.png
        :alt: Register Form

:guilabel:`Contact-Us Form`

    .. figure:: img/Contact-Us.png
        :alt: Contact-Us Form

:guilabel:`Checkout Page`

    .. figure:: img/Checkout.png
        :alt: Checkout Page

:guilabel:`Newsletter`

    .. figure:: img/Newslatter.png
        :alt: Contact-Us Form
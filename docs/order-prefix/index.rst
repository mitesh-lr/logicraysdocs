Order Prefix
============

Overview
````````

This extension allows you to add your custome prefix at ``Order Id``, ``Shipment Id``, ``Invoice Id``, and ``Creditmemo Id``.

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
        * **Order ID Prefix**: Whatever you enter here will be added before the ``order Id``.
        * **Invoice Id Prefix**: Whatever you enter here will be added before the ``Invoice Id``.
        * **Shipment Id Prefix**: Whatever you enter here will be added before the ``Shipment Id``.
        * **Creditmemo Id Prefix**: Whatever you enter here will be added before the ``Creditmemo Id``.

.. note::

    Now save the configuration and cache flush.


#. Make an order first, and then whatever you enter in the admin side prefix in the Order ID field will show here, as shown in the image below.

    This is ``Success Page``

    .. figure:: img/Success-Page.png
        :alt: Success Page
    
    Go to ``My Account > My Order`` Section.

    .. figure:: img/My-Orders.png
        :alt: My Orders Page
    
    Create an ``invoice`` from the admin side first.

    .. figure:: img/Invoice.png
        :alt: Invoice Page
    
    Create an ``Shipment`` from the admin side first.

    .. figure:: img/shipment.png
        :alt: Shipment Page
    
    Create an ``Creditmemo`` from the admin side first.

    .. figure:: img/Credit-memo.png
        :alt: Creditmemo Page
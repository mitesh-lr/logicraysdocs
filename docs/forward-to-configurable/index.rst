Forward To Configurable
=======================

Overview
````````

Sometimes, a website shows simple products in the category listings, but the configurable products for these items are in a hidden category.

And they want to add some functionality, so when a customer clicks on one simple product, it redirects them to the configurable product with attributes already selected.

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
        * **Enable**: Choose ``Yes`` to use the functions of this module.

.. note::
    Now save the configuration and cache flush.

#. Now we have to select some products to enable the functionality of this module.

    go to ``Catalog > Products`` see below image.

    .. figure:: img/Dashboard-catalog-product.png
        :alt: Catalog Product

#. After that, you are redirected to the product grid, and in that, you have to select a configurable or simple product.
    How? Let me explain.

        First, filter the product by SKU or any other thing. then press **Apply Filter**.

        Then you can see a list of products with the main products; here you have to choose your product. I'm choosing the **Chaz Kangeroo Hoodie-XS-Grey** in XS size and Grey colour.

        Open in ``Edit`` mode.

    .. figure:: img/Products-Inventory-Catalog-Magento-Admin.png
        :alt: Products-Inventory-Catalog-Magento

#. After opening the product in ``Edit`` mode, you must change the visibility to ``catalog,Search``.

    .. figure:: img/Chaz-Kangeroo-Hoodie-XS-Gray-Products-Inventory-Catalog-Magento-Admin.png
        :alt: Chaz-Kangeroo-Hoodie-XS-Gray-Products-Inventory-Catalog-Magento-Admin

    .. note::
        Now save the product. and open in the frontend.

#. The image below appears when you view the product on the ``category listing`` page.

    .. figure:: img/Tops-Men.png
        :alt: Tops-Men

#. Simply open the product in the ``Product Detail Page``, then you have to redirect with selected options as shown in the video below.

    .. figure:: img/Peek_2023.gif
        :alt: video
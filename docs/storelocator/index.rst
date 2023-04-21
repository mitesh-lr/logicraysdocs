Store Locator
=============

Overview
````````
Store Locator enables you to create and display an unlimited number of shop locations on Google map. Specify the information you want to show, and the spot will be automatically added to the map.

Store Locator allows customers to easily find the nearest location of your store. It helps to find the proper store location where you can buy what you're looking for.

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
        * **Store Locator Url**: Enter your store-locator Url.
        * **Store Locator Name**: Enter your store-locator name.
        * **Add link in Main Menu**: Choose ``Yes`` if you want to show link in main menu.

    :guilabel:`Meta Configuration`
        * **Meta Title**: Enter meta title.
        * **Meta Description**: Enter meta description.
        * **Meta Keywords**: Enter meta keywords.

    :guilabel:`Map Settings`
        * **Select Template**: Select template according to your requirement. There are 3 types of templates
                **i** Full Width with Sidebar Options.

                **ii** Page Width with Sidebar Options.

                **iii** Page Width with Top Options.
        * **Enter Google Map Api Key**: Enter Google API key.
        * **Store Locator Style Maps**: Here you have to choose style for your store locator maps.
        * **Map Pin Icon**: Upload your map pin icon image.
        * **Unit of Length**: Choose length of unit either kilometres or miles.
        * **Ask for Location**: If you want to ask the location of the user when page was load then choose ``Yes``.
        * **Zoom**: Set map zoom setting between 1 to 20.
        * **Latitude**: Enter Latitude of your store.
        * **Longitude**: Enter Longitude of your store.
        * **Radius**: Enter Radius of your store in km.

    :guilabel:`Radius Style`
        * **Radius Stroke Weight**: Enter Stroke weight when user searches a location. Expects integer or float.
        * **Radius Stroke Opacity**: Enter Stroke opacity when user searches a location. Expects integer or float.
        * **Radius Stroke Color**: Enter Stroke color when user searches a location. Expects hex value.
        * **Radius Fill Opacity**: Enter opacity when user searches a location. Expects integer or float.
        * **Radius Fill Color**: Color when user searches a location. Expects hex value..

    :guilabel:`Individual Store Page`
        * **Zoom on Store Details**: Enter Zoom level when loading the map, default is 16. Insert values between 1 and 20.
        * **Other Stores Slider Enable**: If this is enabled then on the individual store page a slider of other stores will appear. It uses the slick slider.

.. note::
    Now save the configuration and cache flush.

.. important::
    Now you have to add your store location details from admin side.
        Let's start.

#. Go to the ``Logicrays > Store Locator`` path first. as illustrated in the first step.
    Here you can see a list of your stores. Now, if you want to create your store locator, click ``Add New Store``.

    .. figure:: img/Add-New.png
        :alt: Add-New.

#. After clicking ``Add new store``, you have to fill in details about your store's location, as shown in the below image.

    .. figure:: img/Configuration-Settings-Stores-Magento-Admin.png
        :alt: Configuration-Settings-Stores-Magento-Admin.

#. Now if you don't want to add store location manualy then you can add store location details from csv files you have to just click on Import CSV button.
    see below video for better understand.

    .. figure:: img/video.gif
        :alt: video

#. After adding store location details, we are now ready to see our website. Let’s see

    Just open your website and see the below image.

    .. figure:: img/Home-Page.png
        :alt: Home-Page

#. When you click on ``Store List`` or ``Store Locator``, it will redirect to the Store List page.
    See below image.

    .. figure:: img/magento237-storelocator-.png
        :alt: Home-Page

Restrict Fake Registration
==========================

Overview
````````

This extension restricts fake registrations on your store with specified criteria from the admin side.
Using this, you can restrict by IP address, domain, or even dummy customer's name.

.. note::
    Hope you are able to successfully install the module.

How to Configure
````````````````

#. Open Admin Panel, go to ``Logicrays > xtensions & Notifications > Manage Extensions``

    .. figure:: img/Dashboard-Magento-Admin.png
        :alt: Configuration Settings.

#. Now here you can see all the configure fields of the module. I'll explain them one by one at the end of the image.

    .. figure:: img/Configuration-Settings-Stores-Magento-Admin.png
        :alt: module configuration fields

    :guilabel:`General`
        * **Enable**: Choose ``Yes`` to use the functions of this module.

        :guilabel:`Email Domain Restriction`

            * **Enable**: Choose ``Yes`` to use the functions of this module.
            * **Restriction Type**: In this, if you choose

                ``Inclusive List`` then whatever you enter in the domain list field is considered to allow registration in this store.

                ``Exclusive List`` then whatever you enter in the domain list field is not considered to allow registration in this store.

            * **Email Domain List**: Enter the domain names you want to restrict to registration.
            * **Restrict Message**: Enter whatever message you want to display when a domain name is successfully found.

        :guilabel:`Customer Name Restriction`
            * **Enable**: Choose ``Yes`` to use the functions of this section.
            * **First Name Max Characters**: Enter a number for the length of the customer's first name.
            * **First Name Restrict Message**: Enter whatever message you want to display when a restricted first name is entered.
            * **Last Name Max Characters**: Enter a number for the length of the customer's last name.
            * **First Name Restrict Message**: Enter whatever message you want to display when a restricted last name is entered.
            * **Word Exclusion list for Customer Name**: If you want to restrict some default customer names, then enter those names here. with commas seperated.
            * **Word Exclusion Restriction Message**: Enter whatever message you want to display when a specified customer name is found.

        :guilabel:`IP Restriction`
            * **Enable**: Choose ``Yes`` to use the functions of this section.
            * **IP Blacklists**: Enter the IP addresses you want to prevent from registering.
            * **Restrict Message**: Enter whatever message you want to display when a restricted IP is found.

    .. note::
        Now save the configuration and cache flush.

    .. note::
        Now we check the functionality from the front-end side.

#. First of all open Registration page in your store.

    After that, try filling up Fome with some customer names that you have specified in the admin configuration. See below image.

    .. figure:: img/Customer-name.png
        :alt: Configuration Settings.

    As you can see, I'm using ``user`` as a customer name. Now it will fake the customer name and restrict registration, as shown in the image below.

    .. figure:: img/Customer-Name-Error.png
        :alt: Configuration Settings.

    Now we fill in the form with some restricted domain names that you have specified in the admin configuration. See below image.

    .. figure:: img/Domain-Error.png
        :alt: Configuration Settings

    As you can see, I'm using ``.com`` as a domain name. Now it will restrict customers to registration, as shown in the image below.

    .. figure:: img/Domain-error-message.png
        :alt: Configuration Settings

#. Now suppose you enter the proper details for registration, but if your IP address is restricted, you will also not be able to register in this store. see below image.

    .. figure:: img/IP-Error-Message.png
        :alt: Configuration Settings

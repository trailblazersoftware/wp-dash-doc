.. WP Dash Documentation documentation master file, created by
   sphinx-quickstart on Sun Oct  8 04:26:46 2017.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to WP Dash's documentation!
=================================================

.. toctree::
   :maxdepth: 4
   :caption: Contents:



Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

#. :ref:`Overview <overview>`
#. :ref:`Singing Up <signing_up>`
#. :ref:`How Do I Launch A Site <launch_a_site>`
#. :ref:`Managing An Existing Site <managing_an_existing_site>`

.. _overview:

Overview
--------
Welcome to **WP Dash**, the easy to use yet robust *WordPress* hosting platform. Here, you'll find all the
information you need to get started hosting you site. Of course, if you need further assistance (or if you simply prefer) you can always
chat with one of our engineers for support. Yes, you read it right. Us being a startup, and to offer you and even better support,
the guys and gals who provide you support are the very guys who built the platform.

.. _signing_up:

Signing Up
----------
To sign up, simply click on the **Signup** menu option (in the top right corner of the homepage) and fill out the form.
|signup_gif|

.. _launch_a_site:

How Do I Launch A Site
-----------------------------
This assumes that you have already puchased a domain name through one of the domain registrars such as Namecheap, or GoDaddy.

#. From almost all the pages of the dashboard, you'll see a big plus sign on the left side of the page. Click on it. |image|
#. **The "New Site" popup will appear. Provide the appropriate information.** |new_site_modal|

    * **Subscription**: If you already have a valid and unused subscription, you will not see this field. WP Dash will simply use that subscription. If you do not have a valid subscription, then please chose one of the three subscriptions we offer:

        * *Monthly*: This subscription costs $3.99 per month. Your credit/debit card will be billed every month. It offers you 1 site. We highly recommand you to subscribe to the yearly package which will save you 25% per year.
        * *Yearly*: This subscription costs $35.88 per year. It offers you 1 site.
        * *Developer*: This subscription costs $69.99 per year. This is the best value package as it offers your **4** sites for the price of 2.

    * **Name**: A descriptif text that will allow you to identify this site from any other sites you wi'll have. For example, ``Bob's Blog``.
    * **URL**: The domain name you want to host. For example, ``bob.com``.
    * **WP Username**: The username you want to use to login into your *WordPress* dashboard.
    * **WP Password**: The password you want to use to login into your *WordPress* dashboard.
    * **WP Password confirmed**: The same password as above to unsure that it's really what you want.

#. Click on Create. Upon successfuly provisioning your your site, you'll be redirected to your new site's dashboard.
    .. warning::
        The dashboard will display the IP address of the server where you site has been deployed. You must login into your domain registrar's account (Namecheap, GoDaddy, etc.) and enter that IP address in the DNS record for that domain. This must be done for traffic you be sent the server hosting your site.

.. _managing_an_existing_site:

Managing An Existing Site
-------------------------
WP Dash provides you with a very simple dashboard to manage the hosting component of your site. Once you log into your accout, click on **Sites** in the top left side of the menu.
That will take you to the list of your sites currently launched.
|sites_list|

.. |image| image:: https://wpdash-assets.nyc3.digitaloceanspaces.com/docs/blank-sites-page-circled.png
.. |new_site_modal| image:: https://wpdash-assets.nyc3.digitaloceanspaces.com/docs/getting_started_v1.0/new_site_modal.png
.. |signup_gif| image:: https://wpdash-assets.nyc3.digitaloceanspaces.com/docs/wp-dash-signup-1-short.gif
.. |fill_out_signup_gif| image:: https://wpdash-assets.nyc3.digitaloceanspaces.com/docs/wp-dash-signup-fill-form.gif
.. |site_dash_ip_circled| image:: https://wpdash-assets.nyc3.digitaloceanspaces.com/docs/getting_started_v1.0/running_site_dashboard_general_info_ip_circled.png
.. |sites_list| image:: https://wpdash-assets.nyc3.digitaloceanspaces.com/docs/getting_started_v1.0/sites_list_view.png
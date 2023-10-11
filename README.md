# Payinnov payment plugin for WooCommerce

<p align="center">
  <img alt="logo" src="./assets/Payliko.svg" width="50%" />
</p>
Copyright (c) 2021-2023 PayInnov
<br>
<br>
<p>
  <a href="./LICENSE">
      <img
        alt="license:MIT"
        src="https://img.shields.io/badge/License-MIT-blue"
      />
  </a>
  <img
      alt="Language:Php"
      src="https://img.shields.io/badge/Language-Php-purple"
  />
</p>

## Requirements

This plugin requires the following:

* [Wordpress](https://wordpress.org/) Version 1.6...

* [WooCommerce](https://woocommerce.com/) Version 7.2..
* A PayInnov merchant account 

# How to install Payinnov payment plugin in WooCommerce

 - Backup your database before installing plugins. Please make sure you create backups.
 - Download the file payinnov_plugin.zip
 - Go to your WordPress admin panel **Plugins** / **Add New**.
 - Click **Upload Plugin Zip File**, then click **Select file**, find the payinnov_plugin.zip file, select it and click **Upload Now**.

Another way is to unzip payinnov_plugin.zip and copy payinnov_plugin folder in /var/www/html/wordpress/wp-content/plugins

## How to use
When the installation is completed:

 - Enable the plugin.
 - Go to **Plugins** / **Installed Plugins**.
   Activate the "Payinnov payment WooCommerce"

 - Go to your WordPress admin panel **WooCommerce** / **Settings**.
   In the **Payments** tab of the Payinnov plugin, you can **Manage** the parameters enter your Retailer credentials a Payinnov administrator password and then click **Save changes**.

## API credentials
To create a new Retailer' certificate, you should sign up as a Business account in the <a href="https://payliko.com/#/signup">Payinnov Dashboard</a>, then go to the CMS page, and copy the uuid string.

<p>
  <img
      alt="new Retailer credentials"
      src="./assets/CreateBusinessAccount.jpg" width="320" 
  />
  <img
      alt="CMS-page"
      src="./assets/CMS-page.jpg" width="640" 
  />
</p>

Use the uuid string as a Retailer'certificate in the plugin configuration page.

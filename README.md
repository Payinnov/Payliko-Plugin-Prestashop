# Payinnov payment plugin for PrestaShop

<p align="center">
  <img alt="logo" src="./assets/logo.svg" width="256" />
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

In order to setup Payinnov plugin:

* The [PrestaShop](https://www.prestashop.com/en) 1.7.x or 8.0.x version is required
* Create a business account and validate the registration process using this link https://payliko.com/

# How to install Payinnov payment plugin in PrestaShop

 - Backup your database before installing the plugin. Please make sure you create backups.
 - Download the file payinnov_plugin.zip see Github release
 - Go to your PrestaShop admin panel **Modules** / **Module Manager**.
    - Click **Upload a module**, then click **Select file**, find the payinnov_plugin.zip file, select it and click **Open**.

## How to configure the plugin

When the installation is completed:

 - Enable the plugin.
 - Click **Configure**.
   In the **Configure Settings** tab of the Payinnov Module, you should enter your Retailer credentials and then click **Save**.

## API credentials

To create a new Retailer' certificate, you should sign up as a Business account in the Payinnov Dashboard, then go to the CMS page, and copy the uuid string.

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

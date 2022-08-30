# Payliko payment plugin for PrestaShop

<p align="center">
  <img alt="logo" src="./assets/logo.svg" width="256" />
</p>
Copyright (c) 2021-2022 PayInnov
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

In order to setup Payliko plugin you need :

* [PrestaShop](https://www.prestashop.com/en) 1.7.x
* A Payliko business account see https://payliko.com/

# How to install Payliko payment plugin in PrestaShop

 - Backup your database before installing plugins. Please make sure you create backups.
 - Download the file payinnov_plugin.zip see Github release
 - Go to your PrestaShop admin panel **Modules** / **Module Manager**.
 - Click **Upload a module**, then click **Select file**, find the payinnov_plugin.zip file, select it and click **Open**.

## How to use

When the installation is completed:

 - Enable the plugin.
 - Click **Configure**.
   In the **Configure Settings** tab of the Payliko Module, you should enter your Retailer credentials and then click **Save**.

## API credentials

To create a new Retailer'certificat, you should register a Business account on the PayLiko Dashboard, then go to the CMS page, and copy the uuid string.

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

Use that uuid string as a Retailer'certificat in the plugin configuration page.

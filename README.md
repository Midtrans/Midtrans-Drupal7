Midtrans Drupal Commerce Midtrans Payment Gateway Module
=======================================================

Midtrans :heart: Drupal!

Let your Drupal Commerce store integrated with Midtrans payment gateway.

### Description
This is the official Midtrans extension for the Drupal Commerce E-commerce platform.

### Version
7.x-1.1 
(for Drupal v 7.x)

### Requirements
The following plugin is tested under following environment:

* PHP v5.6.x or greater
* MySQL version 5.0 or greater
* Drupal v7.x
* [Drupal Commerce 7.x-1.11 ](http://www.drupal.org/project/commerce)

#### Installation Process
The manual installation method involves downloading our feature-rich plugin and uploading it to your webserver via your favourite FTP application.

1. Download the plugin file to your computer and unzip it, rename folder to ``commerce_veritrans``
2. Using an FTP program, or your hosting control panel, upload the unzipped plugin folder to your Drupal modules installation's ``[Drupal folder]/sites/all/modules/`` directory. 

(Refer to this link for more info on installing module for drupal: [Drupal module install ](https://www.drupal.org/node/70151))

#### Plugin Configuration
1. Open drupal admin page, open menu **modules**.
2. Look for **Commerce Veritrans** and **Veritrans Web** modules under COMMERCE (PAYMENT) group, enable both by ticking the checkboxes.

3. Scroll down and click **Save Configuration**
4. Go to **store > configure store > payment methods**
5. Look for **Veritrans VT-Web** and click it

6. Click **Settings**, tick **active**, then click save changes

7. Click **Enable payment method: Veritrans VT-Web** under Tab Actions
8. Fill the following config fields as instructed on each settings description

9. Click save.
10. Now VT-Web should appear as a payment options when your customer checkout.

#### Veritrans Map Configuration
1. Go to **Settings > Configuration**
2. Insert ``http://[your web]/commerce_veritrans/ipn`` as your Payment Notification URL in your MAP
3. Insert ``http://[your web]`` link as Finish/Unfinish/Error Redirect URL in your MAP configuration.

#### Get help
* [Midtrans sandbox login](https://dashboard.sandbox.midtrans.com)
* [Midtrans production login](https://dashboard.midtrans.com)
* [Midtrans registration](https://account.midtrans.com/register)
* [Midtrans documentation](http://docs.midtrans.com)
* Technical support [support@midtrans.com](mailto:support@midtrans.com)
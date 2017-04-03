## Magento 2 Dutch Language Pack

Let archive Translation Guides from **Magento 2 Dutch Language Pack**! You will get the way to download and install Dutch Langugage Package, then Dutch Language can be used as the default language on your magento 2 store. It is an ideal tool to prompt your business closer to the target clients in Netherlands.

Read more [Magento 2 Dutch Language Pack](https://www.mageplaza.com/magento-2-dutch-language-pack.html)


## Overview

- Download & Contribute
- Install Dutch Language Pack
- How to Install Dutch Language Pack

## Download & Contribute to Dutch Language Pack

Below are two active buttons which are required operations before installing the language package. Let's hit them to download and contribute Magento 2 Dutch Language Pack immediately!

**Download packages**:

- [Download .zip](https://github.com/mageplaza/magento-2-dutch-language-pack/archive/master.zip)
- [Download .tar.gz](https://github.com/mageplaza/magento-2-dutch-language-pack/tarball/master)
- [Copy & paste package](https://crowdin.com/project/magento-2/nl.zip)


Find other [language packs here]({https://www.mageplaza.com/kb/magento-2-language-pack/)

## How to Install Dutch Language Pack

There are 3 different methods to install this language pack.

### #1. Composer method
Install the Dutch language pack via composer is never easier.

**Install Dutch pack**:

```
composer require mageplaza/magento-2-dutch-language-pack:*
php bin/magento cache:clean
php bin/magento setup:static-content:deploy nl-nl

```


**Update  Dutch pack**:

```
composer update mageplaza/magento-2-dutch-language-pack:*
php bin/magento cache:clean
php bin/magento setup:static-content:deploy nl-nl

```

#### Authentication required (Optional)

[Authentication required](https://i.imgur.com/dmryiPk.png)

If you have not added this authentication, you can follow [this guide](http://devdocs.magento.com/guides/v2.0/install-gde/prereq/connect-auth.html)


### #2. Copy & Paste method

This method suitable for non-technical people such as merchants. Just download the package then flush cache.

**Overview**

- Step 1: Download the Dutch language pack
- Step 2: Unzip Dutch pack
- Step 3: Flush Magento 2 Cache

#### Step 1 : Download the Dutch language pack

You can download the language pack from above link

#### Step 2: Unzip Dutch pack

Unzip the Dutch language pack to Magento 2 root folder. In this guide, we extract to `/var/www/html/`
Your Magento 2 root folder can be: `/home/account_name/yourstore.com/public_html/`

```
unzip fr.zip /var/www/html/
```

You also can unzip locally and upload them to Magento 2 root folder.

#### Step 3: Flush Magento 2 Cache

Follow this guide to [Flush Cache on your Magento 2 store](https://www.mageplaza.com/kb/how-flush-enable-disable-cache.html)


### #3. Download and install manually

To download and install Dutch pack manually, you have to access to your server via FTP or SFTP.

#### Step 1: Download the package

- [Download .zip](https://github.com/mageplaza/magento-2-dutch-language-pack/archive/master.zip)
- [Download .tar.gz](https://github.com/mageplaza/magento-2-dutch-language-pack/tarball/master)

#### Step 1: Unzip and upload

Unzip the compressed file and upload file `nl_NL.zip` into `app/i18n/mageplaza/nl_NL/nl_NL.csv`

#### Step 2: Flush cache

Follow this guide to [Flush Cache on your Magento 2 store](https://www.mageplaza.com/kb/how-flush-enable-disable-cache.html)


## How to active language pack

Now time to active the language pack for your Magento 2 store. From Magento 2 admin panel, navigate to `Stores > Configuration > General > Locale Options`
![{{Magento 2 Dutch language pack}}](https://i.imgur.com/aPSUA0l.png)


## Translation process of Dutch Language Pack
![process](http://progressed.io/bar/80)

Contribute to this language at https://crowdin.com/project/magento-2/nl

## Supported Magento versions

- Magento v2.0.0
- Magento v2.0.1
- Magento v2.0.2
- Magento v2.0.3
- Magento v2.0.4
- Magento v2.0.5
- Magento v2.0.6
- Magento v2.0.7
- Magento v2.0.8
- Magento v2.0.9
- Magento v2.0.10
- Magento v2.0.11
- Magento v2.1.0
- Magento v2.1.1
- Magento v2.1.2
- Magento v2.1.3
- Magento v2.1.4
- Magento v2.1.5



## Language package authors

- [Magento official translations project for Magento 2](https://crowdin.com/project/magento-2)
- Language packages built by [Mageplaza team](https://www.mageplaza.com/)


References:
- https://www.mageplaza.com/magento-2-dutch-language-pack.html
- https://www.mageplaza.com/kb/magento-2-language-pack/
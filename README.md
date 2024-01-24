# Hyvä Buy Now

**Hyvä Buy Now is a part of MageINIC Buy Now extension that adds Hyvä features.** This extension extends Buy Now definitions.

## 1. How to install

Run the following command in Magento 2 root folder:

```
composer require mageinic/hyva-buy-now

php bin/magento maintenance:enable
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy
php bin/magento maintenance:disable
php bin/magento cache:flush
```

**Note:**
Magento 2 Buy Now requires installing [MageINIC Buy Now](https://github.com/mageinic/buy-now) in your Magento installation.

**Or Install via composer [Recommend]**
```
composer require mageinic/buy-now
```

## 2. Get Support

- Feel free to [contact us](https://www.mageinic.com/contact.html) if you have any further questions.
- Like this project, Give us a **Star**

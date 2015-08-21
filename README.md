# MagentoSnippets
Magento Front End Snippets, plugin for Sublime Text.

This tool serves to aid the productivity during the Magento's theme development through snippets. These snippets brings partial codes belonging the Magento framework. These code that we used everyday, but never memorized because they are often complex and lengthy.

## Installation
Install via [Package Control](https://packagecontrol.io/installation)

## How do I use it?
The tab trigger of this plugin is "mg-*".

In some editors just the tab key don't trigger the snippet, so you have to press control+space to make the things happen:

![MagentoSnippets: example of use](http://www.magefront.com.br/wp-content/uploads/2015/01/MagentoSnippets-sample.gif)

## Suggestions
If you have something to improve these snippets, please create a [issue](https://github.com/MageFront/MagentoSnippets/issues/new)

**For how to do your own snippet and contribute for this tool see the [contribution text](https://github.com/MageFront/MagentoSnippets/blob/master/contribute.md)**

## Avaiable Snippets

### XML

1. `mg-insert` :: Insert block Method
1. `mg-local-xml` :: Writes the basic structure to a new local.xml file
1. `mg-ref` :: Add reference tag
1. `mg-removeItem` :: Remove head items by xml
1. `mg-rm` :: XML to removes a block
1. `mg-set-template` :: Action to set a new root template
1. `mg-unsetchild` :: Unset Child Method
1. `mg-xml-cms-block` :: CMS Block in XML
1. `mg-xml-css` :: Adds CSS in XML
1. `mg-xml-setcolumn` :: Add number of columns in product list
1. `mg-xml-skinjs` :: Add skin js in XML
1. `mg-xml-text` :: Free text in XML

### PHTML

1. `mg-select-country` :: Create select input from countries collection
1. `mg-debug-layout-handles` :: Debug layout handles
1. `mg-format-price-currency` :: Format Price
1. `mg-getAttrText` :: Get Attribute Text in product view
1. `mg-getchildhtml` :: Get Child Html Method
1. `mg-get-messages-grouped-html` :: Messages Block (grouped HTML)
1. `mg-img` :: Image Skin Url
1. `mg-php-cms-block` :: CMS Block in PHTML(PHP+HTML)
1. `mg-productTypeId` :: Get Type Product Id
1. `mg-script` :: Adds script/javascript tag
1. `mg-store-code` :: Get store code
1. `mg-storeInfo` :: Get store information
1. `mg-translate-phtml` :: Adds the translator helper output
1. `mg-url-asec` :: Get Array Secure Url
1. `mg-url-media` :: Get Media Url
1. `mg-url` :: Get Url
1. `mg-vars` :: Get Variable from admin
1. `mg-viewport` :: Viewport metatag to load media-queries


### PHP
1. `mg-cart-get-items` :: Get all items from cart
1. `mg-collection-categories` :: Get all first level categories
1. `mg-collection-products` :: Get all active products
1. `mg-currency-symbol` :: Get currency symbol
1. `mg-customer-group-id` :: Get customer group ID
1. `mg-customer-logged-in` :: Get customer session status
1. `mg-debug-zend` :: Debug SELECTION with Zend_Debug::dump
1. `mg-exception-error` :: Throw exception if developer mode is on else log error
1. `mg-log` :: Log something to system.log
1. `mg-product-load-all` :: Load all products by SKUs
1. `mg-product-load-attributes` :: Load all product attributes sets and get ids
1. `mg-set-admin-stores` :: Set current store as ADMIN
1. `mg-stores-array` :: Get array of all stores
1. `mg-websites-array` :: Get array of all websites

### HTML (email templates variables)
1. `mg-email-css-inline` :: Get email template css inline
1. `mg-email-footer` :: Get email footer section
1. `mg-email-header` :: Get email header section
1. `mg-email-var-store-frontname` :: Get email store frontname

### JS

1. `mg-anon-func-jquery` :: Adds JS anonymous function passing jQuery as parameter
1. `mg-console-log` :: Add console.log for debug
1. `mg-prototype-dom-ready` :: Adds Prototype DOM ready

### SCSS

1. `mg-clearfix` :: Creates a placeholder selector to fix floats

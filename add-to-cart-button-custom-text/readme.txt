=== Add to Cart Button Custom Text ===
Contributors: enriquejros
Donate link: https://www.paypal.me/enriquejros?country.x=US&locale.x=en_US
Tags: add to cart, woocommerce, button, change
Requires at least: 6.0
Tested up to: 6.5
Stable tag: 4.0.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Allows to customize the Add to cart button text in WooCommerce by product type in both archive and single product pages.

== Description ==

This plugin allows you to change the *Add to cart* text shown on the button used to buy a product in WooCommerce. You will be able to use different custom texts for:

Single product page:

* Simple product (default: *Add to cart*)
* External/Affiliate product (default: *Buy product*)
* Grouped product (default: *Add to cart*)
* Variable product (default: *Add to cart*)
* Bookable product (WooCommerce Bookings) (default: *Book now*)

Archive pages (shop, category, tags...):

* Simple product (default: *Add to cart*)
* External/Affiliate product (default: *Buy product*)
* Grouped product (default: *View products*)
* Variable product (default: *Select options*)
* Bookable product (WooCommerce Bookings) (default: *Book now*)

So **you could choose up to ten different texts as per the type of product and the place it's displayed**. Just activate it and go to *Settings > Add to Cart Button* to choose your preferences. Default WooCommerce texts are used for default configuration. **ASCII emojis are supported**.

Supports bookable products provided by the WooCommerce Bookings plugin.

Spanish and catalan translations are available. Other translation contributions are welcome. Visit me on [my web](https://www.enriquejros.com/).

Thanks to [JuanKa Diaz](http://www.jdevelopia.com/) for the catalan translation.

== Installation ==

= Automatic installation =

Automatic installation is the easiest option as WordPress handles the file transfers itself and you don't need to leave your web browser. To do an automatic install of this plugin, log in to your WordPress dashboard, navigate to the Plugins menu and click *Add new*.

In the search field type *Add to Cart Button Custom Text* and click *Install now*.

= Manual installation =

The manual installation method involves downloading this plugin and uploading it to your webserver via your favorite FTP application or by using the *Upload plugin* option in the *Add plugin* section in your WordPress dashboard. The WordPress codex contains [instructions on how to do this here](http://codex.wordpress.org/Managing_Plugins#Manual_Plugin_Installation).

== Frequently Asked Questions ==

= Can I use HTML tags in the button text? =

No, that isn't supported

= How can I put emojis in the button text? =

Just copy them from somewhere and paste into the option

= Some texts in the settings page are displayed in my language, but some others aren't =

Most of the texts used are translated by the translations files of WooCommerce. Some of them aren't, so you'll see them in English.

= May I contribute to the plugin? =

Yes, you can translate it into your language. They're just a few sentences.

== Screenshots ==

1. Add to cart button with creative custom text (including some ASCII emojis)
2. Options page in *Settings > Add to Cart Button*

== Changelog ==

= 4.0.1 =
* Support for WordPress 6.5
* Support for WooCommerce 9.0

= 4.0.0 =
* Support for upcoming WooCommerce 8 feature HPOS (beta)
* Support for WooCommerce 7.8
* Warnings for creation of dynamic properties in PHP8.2+ are prevented

= 3.1.1 =
* Support for WordPress 6.3
* Support for WooCommerce 7.6

= 3.1.0 =
* Fix warnings for creation of dynamic properties in PHP8.2+
* Support for WooCommerce 7.5
* Bump minimum PHP required version to 7.4

= 3.0.7 =
* Support for WordPress 6.2
* Support for WooCommerce 7.3
* Bump minimum PHP required version to 7.3

= 3.0.6 =
* Support for WordPress 5.9
* Support for WooCommerce 5.9

= 3.0.5 =
* Fixed a warning

= 3.0.4 =
* Support for WordPress 5.8
* Support for WooCommerce 5.3

= 3.0.3 =
* Fixed a warning in options page
* Support for WooCommerce 5.2

= 3.0.2 =
* Fixed some warnings
* Added missing loco.xml file
* Support for WooCommerce 5.1

= 3.0.1 =
* Fixed bookable product button text issue

= 3.0.0 =
* Settings are stored as an array
* Improved performance on init
* Added PHP required version header
* Added loco.xml file for Loco Translate auto setup
* Added wpml-config.xml for admin texts auto setup in WPML
* Book Now default label was not translated properly
* Support for WordPress 5.7
* Support for WooCommerce 5.0

= 2.3.0 =
* Prevents a fatal error in WooCommerce Blocks
* Improved locale check system
* Plugin tested on WooCommerce 3.8
* Plugin tested on WordPress 5.3.1-alpha

= 2.2.0 =
* A help message is shown on the plugin activation
* Applied a singleton pattern to the main class
* All methods have now a declared scoop
* Other minor code improvements
* Plugin tested on WooCommerce 3.6
* Plugin tested on WordPress 5.2

= 2.1.1 =
* Minor code improvements

= 2.1.0 =
* Complete rebuild of the code to make it more efficient

= 2.0.1 =
* New version check support for WooCommerce 3.2
* Tanslations updated
* Minor code improvements

= 2.0.0 =
* Changed deprecated method to get the product type in WooCommerce
* Added availability to change the "Book now" text in product page for bookable products
* More effective loading system for translations
* Checked compatibility with WordPress 4.8
* Several code improvements

= 1.3.3 =
* Improved check if WooCommerce Bookings is active

= 1.3.2 =
* Code improvements

= 1.3 =
* Catalan language added

= 1.2 =
* Clean uninstall (delete options from database on uninstall)

= 1.1 =
* Added compatibility with WooCommerce <2.1
* Added support for bookable products on archive pages

= 1.0 =
* Initial release

== Upgrade Notice ==

= 2.0.1 =
* New version check support for WooCommerce 3.2
* Tanslations updated
* Minor code improvements

= 2.0.0 =
* Changed deprecated method to get the product type in WooCommerce
* Added availability to change the "Book now" text in product page for bookable products
* More effective loading system for translations
* Checked compatibility with WordPress 4.8
* Several code improvements

= 1.3.3 =
* Improved check if WooCommerce Bookings is active

= 1.3.2 =
* Code improvements

= 1.3 =
* Catalan language added

= 1.2 =
* Clean uninstall (delete options from database on uninstall)

= 1.1 =
* Added compatibility with WooCommerce <2.1
* Added support for bookable products on archive pages

= 1.0 =
* Initial release
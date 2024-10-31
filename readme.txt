=== Plugin Name ===
Contributors: donovanh
Donate link:
Tags: qr code, print version
Requires at least: 2.0.2
Tested up to: 3.2
Stable tag: trunk

QR Print adds a QR code to the print version of each page, containing the URL of the current page.

== Description ==

The plugin simply adds a [QR code](http://en.wikipedia.org/wiki/QR_code) to the footer (where you include wp_footer) of your pages.

== Installation ==

1. Upload `qrprint.php` to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. That's it! A QR code containing the current page URL will automatically be added to the footer of each page

== Frequently Asked Questions ==

N/A

== Screenshots ==

1. A QR code (this one contains the URL of the homepage for this plugin)

== Changelog ==

= 0.3 =
* Moved CSS rules to <head> of page
* Changed classname to reduce chance of conflict
* Added some extra print-only text ("Printed from: URL")
= 0.2.1 =
* Updated readme.txt to reflect compatibility with 3.2
* Screenshot comment added
= 0.2 =
* Initial version
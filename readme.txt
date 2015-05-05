=== Add Watermarks ===
Contributors: michael.zangl
Tags: watermark, media, htaccess
Requires at least: 4.0.0
Tested up to: 4.2.1
Stable tag: 1.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Adds watermarks to selected images without changing the original image.

== Description ==

This plugin allows you to add a watermark images on all images that were uploaded in your wordpress. The watermark is generated on-the-fly and cached for faster access.

To see the plugin in action, select "Add watermark to all images", chose a watermark image and and submit the settings page. You should then see the watermark appearing on your site. You might need to reload the page (F5 in most browsers) to bypass the browser cache.

The plugin does not change your source images. To disable all watermarks, simply disable the plugin, and everything is back to normal.


== Installation ==

Install and activate this plugin.

Then go to Settings->Add watermark. You can upload or chose your watermark image there. For a first test, you can leave the position settings as they are.


== Frequently Asked Questions ==

= Will this plugin need extra space =

Yes. since all images are cached with a watermark, you need twice the space for images on your server.

= Does this plugin reduce performance = 

Not much. You might experience a longer loading time on the first access to the image (normally when you upload it or on your first view of the post). But afterwards there will be no speed impact, since all logic is encoded in a htaccess-File and not in PHP.

== Screenshots ==

1. You can select an image to use as watermark and to which images watermarks should be applied.
2. The settings to adjust the position of the watermark. Those are lots of numbers, but there is a (resizeable) live preview area ;-). If you are familiar with CSS, you should have no problem with this.
3. You can add or remove watermarks from individual images in the media library.

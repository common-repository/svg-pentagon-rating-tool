=== Pentagon Rating Tool ===
Contributors: AaronKnoll
Donate Link: http://theginisin.com
Tags: ratings, SVG 
Requires at least: 3.2.1+
Test Up to: 3.3.1
Stable Tag: 0.1

Allows posts in one posts category to have an inline SVG pentagon rating at the top of that post. Adds fields on posts pages.

== Description ==

This plugin draws an SVG pentagon, based on the ratings that one assigns a given post. Users can choose the category for which the pentagon appears and assign names and colors to each of the quadrants. 

Note) Inline SVG does not work on IE versions 8 and below; therefore, the stylesheet ie8.css makes nothing appear on versions below IE 9. Will work on all other major browsers in past and current versions.

== Installation ==

1. Upload `plugin-name.php` to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Under the "Project Pentagon" menu in wordpress 
	--- choose a category name (the full human readable name for the category that you've created....)
	--- assign names and colors. Use Hex numbers.
4. Go to your "posts." Edit a post in that category and fill out:
	---- the five ratings on the upper right [mandatory]
	---- the field for textual summary [optional]

* Note, a value of "0" adds a completely blank pentagon segment with no lines. 

== Frequently Asked Questions ==

This is a proof-of-concept test I created for my blog and decided to launch as a plugin. If you are interested in where its going to go from here, this is my brief outline (which may answer some of your questions)

- make it IE8 and less compliant; add special mobile stylesheet for Ipad etc. 
- add a way to resize pentagons
- add positioning options for where to place it on the page

== Changelog ==
= 0.1 =
SVG draws and works on all non <IE9 browsers. 
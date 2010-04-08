=== Simple WP FirePHP ===
Contributors: corischlegel
Donate link: http://kinrowan.net/contact
Tags: debugging, firebug, firephp
Requires at least: 2.0
Tested up to: 2.9
Stable tag: 4.3

Extremely simple mechanism for embedding FirePHP into WordPress to use FirePHP during WP Development.

== Description ==

I like the very simple API to FirePHP and find it very useful for debugging Wordpress plugins and themes.  There are a few other plugins out there that integrate FirePHP, notable WP-FirePHP and WP-Logger, but both add complexity that I don't want to have to deal with for a quick debugging task.

It wouldn't be that hard to install the FirePHP core and add the includes to wp-config.php, and that's what I generally do on sites that I control, but having this plugin in the Wrodpress.org/extend directory means that I'll be able to install it on the fly for a blog that someone hasn't given me shell or ftp access to.

== Installation ==

1. Upload the plugin folder to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Use FIrePHP as you nromally would on a general PHP site.

== Frequently Asked Questions ==

== Changelog ==

= 0.1 =
* Alpha release - very simple includes

== Plans ==

I don't think I'll do a *whole* lot more with this, since I want to keep it pretty simple, but I plan to make sure the plugin loads first (see wp-logger) and perhaps add a simple options screen.  Might also add PHP4 support, but probably not.
=== WP Luminous ===
Contributors: daveismyname
Tags: Luminous Plugin
Requires at least: 3.0
Tested up to: 3.4.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Accurate and powerful syntax highlighting library

== Description ==

Wordpress plugin for the Luminous Accurate and powerful syntax highlighting library. The original Luminous directory is included and untouched, the plugin resides within index.php

This plugin is available on Github it can be forked from https://github.com/daveismyname/luminous

== Installation ==

1. Upload wp-luminous folder to the /wp-content/plugins/ directory.
2. Activate the plugin through the Plugins menu in WordPress.
3. Optionall select a theme from the plugin settings page in settings/WP Luminous.
4. Place code inside &lt;pre lang=''&gt; &lt;/pre&gt; blocks All languages are supported from the Luminous

== Frequently Asked Questions ==

= Sometimes I get an error for insufficent memory =

The luminous library can be memory intentive, you may need to increase the memory to your Wordpress installation you can do this by telling the system how much memory to use, in your wpconfig.php file add 

<pre>define('WP_MEMORY_LIMIT', '64M');</pre>

== Screenshots ==

1. screenshot-1.png 
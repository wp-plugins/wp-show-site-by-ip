=== Plugin Name ===
Contributors: d79
Donate link: http://www.emergency.it/form/donations/
Tags: hide website, maintenance, ip filter
Requires at least: 3.0.1
Tested up to: 4.1
Stable tag: 1.2
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Hide your Wordpress website to unknown IPs and replace it with a HTML page. Useful for developers to work online in private (e.g. maintenance).

== Description ==

Hide your Wordpress website to everyone but easily allow to whoever you want to see it.

= Why it's useful =
Sometimes you need to work directly on your online Wordpress installation, like when you are developing or refining a theme for your site, and you don't want others to see your work in progress, but at the same time you need to be able to see it from whatever place you find yourself!!!

= What it does =
This plugin allows you very easily to load a temporary HTML page for your website visitors, but it filters the IP of your connection and let you see your website and work on it.

Even better you don't have to find out your IP and then save it on some sort of whitelist, you can simply add the string `wpok` to you url to automatically obtain the permission to see your website, without even knowing your IP!!!

That makes it easier to work on your website from many different places (e.g. if you work on it with other people from different locations) or if you have an internet connection with dynamic IP (everytime it changes you can easily add the new one).

= How it works =
After installed this plugin, you'll find the submenu *Show Site by IP* on your website Dashboard, under the *Tools* menu.
That link open the plugin configuration page, where you can upload the full HTML of your temporary page and, when you are good to go, enable the IP filter.

**Once enabled the IP filter you won't be able to see your website!**

To allow the access to your website from your internet connection add the string `?wpok` to the website URL, like this:

* `http://www.your-site.com?wpok`

To remove your IP from the whitelist afterwards (and then go back to see the temporary page instead of your website) add the string `?wpko` to the website URL, like this:

* `http://www.your-site.com?wpko`

That's it. =)

== Installation ==

= Automatic installation =

Automatic installation is the easiest option as WordPress handles the file transfers itself and you don’t need to leave your web browser. To do an automatic install of this plugin, log in to your WordPress dashboard, navigate to the Plugins menu and click Add New.

In the search field type the title of this plugin and click Search Plugins. Once you’ve found it you can view details about it such as the the point release, rating and description. Most importantly of course, you can install it by simply clicking “Install Now”.

= Manual installation =

The manual installation method involves downloading the plugin and uploading it to your webserver via your favourite FTP application. The WordPress codex contains [instructions on how to do this here] (http://codex.wordpress.org/Managing_Plugins#Manual_Plugin_Installation).

= Activation =

Once it's installed, you can activate the plugin clicking “Activate Now”

== Changelog ==

= 1.2 - 03.03.2015 =
* Added HTTP 503 status for maintenance mode

= 1.1 - 17.02.2015 =
* Added link to the plugin settings
* Added warning with instructions

= 1.0 - 19.09.2014 =
* Plugin file created

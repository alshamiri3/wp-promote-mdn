=== Plugin Name ===
Contributors: mte90, groovecoder, freediver
Donate link: 
Tags: mozilla, mdn, links, html5, javascript, glossary, documentation, docs, development
Requires at least: 4.4
Tested up to: 4.5
Stable tag: 1.8.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Automatically links your WordPress blog with MDN.

== Description ==

* Automatically links [special keywords and phrases](https://raw.githubusercontent.com/mdn/wp-promote-mdn/def-list/terms.txt) to MDN.
* Provides a widget with images and links to promote MDN
* Allows you to notify Mozilla DevEngage and Communications when publishing posts

MDN is the best online resource for web developers, by web developers. Promote MDN
helps your readers discover and learn about web technologies on MDN.

To help code on this plugin, go to [Promote MDN on Github](https://github.com/mdn/wp-promote-mdn/).

Based on freediver's [SEO Smart Links](http://wordpress.org/extend/plugins/seo-automatic-links/)

== Installation ==
1. Go to "Plugins -> Add new"
2. Search for "Promote MDN"
3. Click "Install"

or manually:

1. Upload `promote-mdn/` to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Configure the plugin through the 'Settings' -> 'Promote MDN' page

== Frequently Asked Questions ==

= Why? =

MDN makes the best docs on the web, for the web.

= What are locale-specific links? =

By default, most links will go to a locale-agnostic url which will redirect
to a translated page if one is avaialble. Ideally we want to avoid redirects.
So, locale-specific links are maintained by the MDN community for some locales.

Using locale-specific links will improve your readers' experience.

== Screenshots ==

1. Settings, exceptions, limits, custom keywords
2. Automatically linking 'HTML5', 'HTML', and 'JavaScript' keywords.

== Changelog ==

= 1.8.0 = 

* Definition file it's on GitHub to improve the list of links easily

= 1.7.1 =

* Disable also for custom post types
* Updated Italian language

= 1.7 =

* New MDN banners
* New translation IT_it
* Support for comments
* Fixed notification to Mozilla DevEngage team
* Fixed bad html code in widget
* CSS class in the link
* Removed deprecated code

= 1.6 =
* Option to notify Mozilla Press and DevRel when publishing post
* Fix HTML bug in admin notices
* Update GA campaign tracking parameters
* Update logos to redesign
https://github.com/groovecoder/wp-promote-mdn/compare/596cea7...0edcb0e

= 1.5 =
* Security fixes

= 1.4 =
* Exclude links from any HTML elements
* src url param to help MDN measure effectiveness
* Color & Text options for widget
* See [GitHub Milestone](https://github.com/groovecoder/wp-promote-mdn/issues?milestone=2&page=1&state=closed)

= 1.3 =
* New Sidebar Widget
* Install/upgrade notifications in admin pages
* Use locale-specific URL for keywords/phrases links
* Add French translation
* See [GitHub Milestone](https://github.com/groovecoder/wp-promote-mdn/issues?milestone=1&page=1&state=closed)

= 1.2 =
* Internationalization and initial translations - Polish, Dutch, German, Portuguese (Brazil)

= 1.1 =
* Add "Reload now" button and send Cache-Control: no-cache, must-revalidate to MDN

= 1.0 =
* Initial version based on SEO Smart Links.

== Upgrade Notice ==
= 1.3 =
Be sure to click the "Use keywords and links specifically for ..." button if you
run a site in language besides English.

= 1.0 =
To make it work.

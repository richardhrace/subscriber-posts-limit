=== Subscriber Posts Limit ===
Contributors: richarddev
Tags: limit, post, user, role
Requires at least: 5.2
Tested up to: 5.5
Requires PHP: 7.0
Stable tag: 1.0.6
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Limit the number of posts user can create. Any post type.

== Description ==

Limit the number of posts user can create. Any post type.

[Documentation](https://en.richarddev.com/subscriber-posts-limit/)

= How To Use =
1. Plugin Settings: Select role, post type, limit, and cycle.

= How It Works =
* On post creation the number of posts from this post type belong to this user for the specified cycle will be counted and if applicable the post creation will be prevented.

= Features =
* **Hide Content**: In order to make some content hidden when posts limit exceeded wrap it with the shortcodes (replace "post" with the post type of the relevant rules): [upl_hide type="post"][/upl_hide]
* **Multisite**: Network-wide rules can be applied via the Network Admin Dashboard.
* **[Contact](https://en.richarddev.com/contact/)** to request new limiting options.

== Installation ==

= Minimum Requirements =
WordPress 5.2 or greater
PHP 7.0 or greater

= Automatic installation =
1. Go to your Dashboard => Plugins => Add new
1. In the search form write: RichardDev
1. When the search return the result, click on the Install Now button

= Manual Installation =
1. Download the plugin from this page clicking on the Download button
1. Go to your Dashboard => Plugins => Add new
1. Now select Upload Plugin button
1. Click on Select file button and select the file you just download
1. Click on Install Now button and the Activate Plugin

== Screenshots ==
1. Subscriber Posts Limit Plugin Settings
1. Post creation limit notification

== Frequently Asked Questions ==

= Why the limits do not work as expected? =

* Enable the 'Document Statistics' option to see the limits per user in the users list table
* The counts include posts in trash/draft/pending status
* The post creation date and not the post published date is taken into account
* Limits will not be applied on users with the Plugin Management Capability / create_users capability (in Multisite)

= Where users can see their limits? =

* It will be displayed in their Dashboard
* Use the [upl_limits] shortcode to display it wherever you need

= How to use the [upl_hide] shortcode with Elementor? =

You will need to add [/upl_start] right after the main shortcode [upl_hide] and remove the type attribute at all if you use on 'post'.

== Changelog ==

= 1.0.6 - October 12, 2020 =
* Feature - Rules Filters

= 1.0.5 - September 22, 2020 =
* Feature - WPMU support

= 1.0.4 - September 16, 2020 =
* Feature - Rules priority

= 1.0.3 - September 08, 2020 =
* Feature - Hide content shortcode

= 1.0.2 - August 25, 2020 =
* Feature - Users stats

= 1.0.1 - April 20, 2020 =
* Feature - Timing rule

= 1.0 - April 10, 2020 =
* Initial release

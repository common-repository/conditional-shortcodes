=== Conditional Shortcodes ===
Contributors: jrrl
Tags: shortcode, shortcodes
Requires at least: 2.5
Tested up to: 2.9.1
Stable tag: trunk
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=QLPJCSKJL4PQQ

This plugin gives content developers shortcode equivalents to the conditional tags that WordPress provides for theme developments.

== Description ==

This plugin gives content developers shortcode equivalents to the conditional tags that WordPress provides for theme developments.  Each shortcode only includes its contents if a certain condition is true.  This allows them to modify what content is shown in any given context on a post-by-post basis.

The new shortcodes and when they include contents are:

* is_single - if showing a single post.
* is_singular - if showing a single post or page.
* is_home - if showing the blog home.
* is_front_page - if showing the front page of the site.
* is_sticky - if the current post or page is 'sticky'.
* is_category - if showing a category-based archive.
* is_tag - if showing a tag-based archive.
* is_tax - if showing a tag- or category-based archive.
* is_author - if showing an author-based archive.
* is_archive - if showing any archive.
* is_year - if showing a yearly archive.
* is_month - if showing a monthly archive.
* is_day - if showing a daily archive.
* is_time - if showing an hourly or shorter archive.
* is_feed - if generating a feed.
* is_search - if showing search results.
* comments_open - if comments are open for the current post or page.

Each shortcode also allows has an "else" shortcode that can go inside it.  For example:

    [is_single]
    This is only shown if showing just this post.
    [not_single]
    This is shown everywhere else.
    [/is_single]

In general, the "else" shortcode is just replacing "is" with "not".  The one exception is "not_comments_open" as the "else" shortcode for "comments_open".

Whichever chunk of content is included is processed for shortcodes, so you can use all your other shortcodes and even nest these if you need to.


== Installation ==

Unzip it and activate it and you'll have the shortcodes.

== Further Instructions ==

Any other information I have can be found at the [Conditional Shortcodes Homepage](http://www.hostscope.com/wordpress-plugins/conditional-shortcodes-wordpress-plugin/).

== License ==

I dunno.  How about creative commons attribution?  Sound ok?  Good.


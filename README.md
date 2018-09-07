# Ultimate Facebook Comments

Ultimate Facebook Comments plugin will help you to display Facebook Comments box on your website easily. You can use Facebook Comments on your posts or pages.

[![WP compatibility](https://plugintests.com/plugins/ultimate-facebook-comments/wp-badge.svg)](https://plugintests.com/plugins/ultimate-facebook-comments/latest) [![PHP compatibility](https://plugintests.com/plugins/ultimate-facebook-comments/php-badge.svg)](https://plugintests.com/plugins/ultimate-facebook-comments/latest)

## Description

### Ultimate Facebook Comments: the Ultimate Facebook Comments plugin for WordPress.

If you’re running a blog of any kind, you’re probably looking to build an online community. You're targeting like-minded people who share the interests highlighted by the content on your site. It’s a mutually beneficial relationship: Your visitors get information that they consider valuable by visiting your site, and you build an audience.

However, it’s also a great idea to allow your visitors to interact with one another. One of the best ways to do that is with a comments section that allows them to not only leave you feedback on your content but also to interact with each other. Here are some of the benefits you can expect from a comments section.

Like the Ultimate Facebook Comments plugin? Consider leaving a [5 star review](https://wordpress.org/support/plugin/ultimate-facebook-comments/reviews/?rate=5#new-post).

#### What does this plugin do?

This plugin hooks into the WordPress native comment area or after content area and shows the facebook comments box using lazyload.

* 100% GDPR Compliant.
* Allows you to display facebook comment box in your posts and pages individually.
* Allows you to customize the facebook comment box title text.
* Allows you to disable WordPress native comments completely from WordPress dashboard.
* Allows you to set custom styles for comment box title.
* Allows you to set custom styles for comment area also.
* Allows you to set the comment area background colour.
* Allows you to open facebook comments moderation tool directly from plugin settings page.
* And you can customize all and everything.

### Themes Tested with this plugin and works perfect

* Astra/Pro
* OceanWP
* Genesis Framework
* GeneratePress
* Zephyr
* Impreza
* Newspaper by tagdiv
* Divi theme
* Twentyseventeen
* and many more.

#### Compatibility

This plugin is fully compatible with WordPress Version 3.0 and beyond and also compatible with any WordPress theme.

#### Support/Contribute

* Active development of this plugin is handled [on GitHub](https://github.com/iamsayan/ultimate-facebook-comments).
* Pull requests for documenting bugs are highly appreciated.
* If you think you’ve found a bug (e.g. You’re experiencing unexpected behaviour), please post on the [support forums](https://wordpress.org/support/plugin/ultimate-facebook-comments) first.

## Installation ##

### From within WordPress ###
1. Visit 'Plugins > Add New'.
1. Search for 'Ultimate Facebook Comments'.
1. Activate Ultimate Facebook Comments from your Plugins page.
1. Go to "after activation" below.

### Manually ###
1. Upload the `ultimate-facebook-comments` folder to the `/wp-content/plugins/` directory.
1. Activate WP Last Modified Info plugin through the 'Plugins' menu in WordPress.
1. Go to "after activation" below.

### After activation ###
1. After activation go to 'Settings > Facebook Comments'.
1. Enable/disable options and save changes.

### Frequently Asked Questions

#### Is there any admin interface for this plugin?

Yes. You can access this from 'Settings > Facebook Comments'.

#### How to use this plugin?

Go to 'Settings > Facebook Comments', enable/disable options as per your need and save your changes.

#### How to check this plugin is working?

After enabling options in 'Settings > Facebook Comments', open any page or post and you can see the facebook comment box.

#### How this plugin works?

This plugin hooks into the WordPress content area or replace WordPress native comment and displays Facebook Comment on posts and pages.

#### Will it require editing code to show Facebook Comment box?

Not at all. You can show the facebook comments by just installing this plugin. Use the Plugin Options to customize the plugin settings according to your need.

#### Is this plugin compatible with any themes?

Yes, this plugin is compatible with any theme.

#### How to show FB comment count on posts meta?

In this case, you have to edit your theme's template files i.e. single.php, page.php etc. And add/replace default published date function with this:

Returns the last modified info:

`<?php if ( function_exists( 'get_fb_comment_count' ) ) {
		get_fb_comment_count();
	}
?>`

Displays/echos the last modified info:

`<?php if ( function_exists( 'fb_comment_count' ) ) {
		fb_comment_count();
	}
?>`

#### The plugin isn't working or have a bug?

Post detailed information about the issue in the [support forum](https://wordpress.org/support/plugin/ultimate-facebook-comments) and I will work to fix it.

## Changelog ##
[View Changelog](CHANGELOG.md)

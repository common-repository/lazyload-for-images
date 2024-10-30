=== LazyLoad for Images ===
Contributors:      sahu4you
Donate link:       https://www.paypal.me/sahu4you
Tags:              Lazy Load, Loading, Image SEO, iFrames, Thumbnail, Thumbnails, Optimize, Speed, Lazy Load for Images
Requires at least: 4.0
Tested up to:      5.2
Requires PHP:      5.6
Stable tag:        1.1
License:           GPLv2 or later
License URI:       https://www.gnu.org/licenses/gpl-2.0.html

Lazy Load for WordPress images bosst your website loading speed. Load images only when required. Show images than after scrolling down and when viewport and Lazy Load Background Images loads then Improved page speed.


== Description ==
Lazyload WordPress Images without any configurations and helps the Superfast performance of your website and blogs.

Do you know? All images load only when users scroll-down and they are on the viewport. Its SEO and user-friendly, working well with all browsers.

This plugin is structured very simply and does not need any settings. Activate. Done! The plugin uses less than 1kb JavaScript. No need for jQuery.

== Exclude images ==
Yes, it can easy to exclude some images to lazy loading. This can be done by adding `data-lazy="1"` attribute to images that should not be lazy loaded.


> #### Lazy Load for Images - Features & Advantages ####
>
> - Load images only when required.<br />
> - **Improve page loading speed.**<br />
> - Reduce no. of HTTP requests.<br />
> - Lazy load also working on mobiles.<br />
> - Plugin used pure JS, no need of jQuery.<br />
> - Plugin used only 506 bytes Javascript.<br />
> - Plugin total size is less than **10kb**.<br />
> - No need configurations (Just activate, It's Done!)<br />
> - SEO friendly (search engine optimized).<br />
> - Of course, available on [GitHub](https://github.com/sahu4you/lazyload-for-images)<br />


== Installation ==


= Installing this plugin - Simple =
1. Go your WordPress admin panel, go to *Plugins > New Plugin*, search for **LazyLoad for Images** and click "*Install now*"
2. Otherwise, download the plugin and upload to your plugins directory, which usually is "/wp-content/plugins/".
3. Activate the plugin, All Done!.


= You Need Help? =
Feel free to [open a support ticket](https://wordpress.org/support/plugin/lazyload-for-images/).


= Contact with Us? =
If you would like to have an additional feature for this plugin, [let me know](https://sahu4you.com/contact-us/)


== Frequently Asked Questions ==
= Does this plugin lazyload all images on a post? =
Yes, All images that uploaded via your media library loaded with lazy load, with featured images.

= How do I lazy load other images in my theme? =
If lazy load not working, you will need to add a `add_filter` in plugin class PHP files at hooks section, i.e. like this:

`add_filter( 'post_thumbnail_html', array( __CLASS__, 'lli_images' ) );`


= How I can use custom placeholder image or GIF? =
By default, we use `"data:image/gif;base64"` for placeholder image. You can change it url with a custom URL.


= How can I deactivate Lazy Load on some images? =
Add a `data-lazy="1"` attribute tag in your specific image.


= Does this plugin work with any caching plugins? =
Yes, Lazy Load Images plugin works very well with every cache plugin.


== Changelog ==

= 1.1 =

* Fixed preview new issue for WP v5.0.3.

= 1.0 =

* First version.
# Disable Thumbnail Regeneration

Disables the default image meta and thumbnail regeneration functions that occur in WooCommerce Core to improve performance and retain better control.

* [Plugin Homepage](https://www.littlebizzy.com/plugins/disable-thumbnail-regeneration)
* [Download Latest Version (ZIP)](https://github.com/littlebizzy/disable-thumbnail-regeneration/archive/1.0.0.zip)
* [**Become A LittleBizzy.com Member Today!**](https://www.littlebizzy.com/members)

Includes these filters:    
    
    add_filter('woocommerce_resize_images', '__return_false');
    add_filter('woocommerce_background_image_regeneration', '__return_false');
    
### Defined Constants

    /* Plugin Meta */
    define('AUTOMATIC_UPDATE_PLUGINS', false); // default = false
    define('DISABLE_NAG_NOTICES', true); // default = true
    
    /* Dashboard Cleanup Functions */
    define('DISABLE_THUMBNAIL_REGENERATION', true); // default = true
    define('DISABLE_THUMBNAIL_REGENERATION_META', true); // default = true

### Compatibility

This plugin has been designed for use on [SlickStack](https://slickstack.io) web servers with PHP 7.2 and MySQL 5.7 to achieve best performance. All of our plugins are meant for single site WordPress installations only — for both performance and usability reasons, we strongly recommend avoiding WordPress Multisite for the vast majority of your projects.

Any of our WordPress plugins may also be loaded as "Must-Use" plugins (meaning that they load first, and cannot be deactivated) by using our free [Autoloader](https://github.com/littlebizzy/autoloader) script in the `mu-plugins` directory.

### Our Philosophy

> "Decisions, not options." — WordPress.org

> "Everything should be made as simple as possible, but not simpler." — Albert Einstein, et al

> "Write programs that do one thing and do it well... write programs to work together." — Doug McIlroy

> "The innovation that this industry talks about so much is bullshit. Anybody can innovate... 99% of it is 'get the work done.' The real work is in the details." — Linus Torvalds

### Support Issues

Please do not submit Pull Requests. Instead, kindly create a new Issue with relevant information if you are an experienced developer, otherwise you may become a [**LittleBizzy.com Member**](https://www.littlebizzy.com/members) if your company requires official support.

### References

* https://wordpress.org/support/topic/woocommerce-causing-huge-cpu-usage-spike/
* https://github.com/woocommerce/woocommerce/wiki/Thumbnail-Image-Regeneration-in-3.3
* https://wordpress.org/support/topic/woocommerce-conflict-25/

# Disable Thumbnail Regeneration

add_filter( 'woocommerce_resize_images', '__return_false' );
add_filter( 'woocommerce_background_image_regeneration', '__return_false' );

https://wordpress.org/support/topic/woocommerce-conflict-25/

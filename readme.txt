My Page Order
Contributors: froman118
Donate link: http://geekyweekly.com/mypageorder
Tags: page, order, sidebar, widget
Requires at least: 2.5
Tested up to: 2.5
Stable tag: 2.5

My Page Order allows you to set the order of pages through a drag and drop interface.

== Description ==

My Page Order allows you to set the order of pages through a drag and drop interface. The default method
of setting the order page by page is extremely clumsy, especially with a large number of pages.


== Installation ==

1. Move mypageorder.php to /wp-content/plugins/
2. Activate the My Page Order plugin on the Plugins menu
3. Go to the "My Page Order" tab under Manage and specify your desired order for pages

4. If you are using widgets then just make sure the "Page" widget is set to order by "Page order". That's it.

5. If you aren't using widgets, modify your sidebar template to use correct filter (additional parameter seperated by ampersands):
	wp_list_pages('sort_column=menu_order&title_li='); ?> 


== Frequently Asked Questions ==

= Why isn't this already built into WP? =

I don't know. Hopefully it will be in a future release in one form or another because the current
method is less than ideal.


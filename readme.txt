=== Multilevel Menu FX ===
Contributors: flashxml
Tags: images, photos, widget, post, plugin, posts, sidebar, free, flash, multi, level, menu, text, multilevel, xml, html, css, font, roll, over, out, effect, animation, alignment, orientation, background, action
Requires at least: 2.8.0
Tested up to: 3.0.1
Stable tag: trunk

Probably the most advanced Multilevel Menu on the web. Completely XML customizable, without any Flash knowledge. And it's free!

== Description ==

You can integrate it in any website for free without any Flash knowledge. There is the possibility to have multiple levels menu, the text is HTML/CSS formatted with different text orientation and alignment. It uses background images for main buttons and secondary buttons. There are roll over/out animation effects with different actions for each item. Also, there are more customizable properties on the Live Demo.

== Installation ==

Make sure your Wordpress version is greater than 2.8 and your hosting provider is using PHP5.

1. There are two files to download: [WordPress Plugin](http://downloads.wordpress.org/plugin/multilevel-menu-fx.zip "Multilevel Menu FX Plugin") (that you have to install and activate) & [Free package](http://www.flashxml.net/free/download/multilevel-menu.zip "Multilevel Menu FX")
2. Create a new folder inside your **wp-content** folder called **flashxml**, inside this folder create a new one called **multilevel-menu-fx** and copy the content of the **free package** there
3. If you copied the **free package** to a location different than the one above, go to **Multilevel Menu FX** from the **Settings** tab in your **WordPress Dashboard** and update the path accordingly
4. Add `[multilevel-menu-fx][/multilevel-menu-fx]` where you want the Flash to show up in your post/page
5. If you want to make the Multilevel Menu FX part of your theme, edit the template files and add `<?php multilevelmenufx_echo_embed_code(); ?>` where you want it to show up
6. Go to [FlashXML.net](http://www.flashxml.net/ "Free Flash Components") and [customize your Multilevel Menu FX](http://www.flashxml.net/multilevel-menu.html "Multilevel Menu FX") using the Live Demo. Generate the `settings.xml` text and use it to overwrite `wp-content/flashxml/multilevel-menu-fx/settings.xml`
7. To use your own text, update the `wp-content/flashxml/multilevel-menu-fx/menu.xml` file accordingly

= Additional settings file =

To embed the Multilevel Menu FX more than once, you will need another settings file. Let's assume your new file is called `settings2.xml`. Add `[multilevel-menu-fx settings="settings2.xml"][/multilevel-menu-fx]` where you want the Flash to show up in your post/page. If you made the Flash part of your theme, add the file name as **the first argument** of the `multilevelmenufx_echo_embed_code()` function call (for example `<?php multilevelmenufx_echo_embed_code("settings2.xml"); ?>`).

= No Flash support text =

To support visitors without Adobe Flash Player, you can provide alternative content by adding the text between `[multilevel-menu-fx]` and `[/multilevel-menu-fx]`. If you made the Flash part of your theme, add the text as **the second argument** of the `multilevelmenufx_echo_embed_code()` function call (for example `<?php multilevelmenufx_echo_embed_code("","Alternative content"); ?>`).

= If you have PHP4 =

To make it work with PHP4, add `[multilevel-menu-fx width="600" height="300"][/multilevel-menu-fx]` where you want the Flash to show up in your post/page. If you made the Flash part of your theme, add the width and height as **the third and fourth argument** of the `multilevelmenufx_echo_embed_code()` function call. Don't forget to provide your own width and height values, since 600 and 300 are just examples.

= Getting rid of the FlashXML.net label =

To remove the FlashXML.net label from the top-left corner you'll need to buy the [paid package](http://www.flashxml.net/multilevel-menu.html "Multilevel Menu FX"). Once you'll do that, simply use the SWF file from the paid package to overwrite the SWF file from the `wp-content/flashxml/multilevel-menu-fx/` folder.

== Screenshots ==

1. The Live Demo on [FlashXML.net](http://www.flashxml.net/multilevel-menu.html "Multilevel Menu FX") is the utility that helps easily customize your Multilevel Menu FX to fit all your needs.
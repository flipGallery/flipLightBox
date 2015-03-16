/*!
 * flipLightBox - Responsive Lightbox jQuery Plugin
 * version: 1.2.0
 * @requires jQuery v1.5 or later
 *
 * License at http://flipgallery.net/fliplightbox.html#download
 * 
 * Example at http://flipgallery.net/fliplightbox.html
 *
 * Copyright 2015 flipGallery.net
 *
 */

About flipLightBox 

flipLightBox is a free Responsive Lightbox jQuery Plugin that is extremely easy to implement and doesn't require any additional stylesheets, scripts or libraries. Its main feature is an optional flip effect as each lightbox image opens and closes. Another optional feature is a toggled slide text bar and navigation to accompany the lightbox images. Upgrades are also available.

How To Set Up

1) In your html document, before the closing </body> tag insert:

<script type="text/javascript" src="http://ajax.googleapis.com/ajax/libs/jquery/2.1.3/jquery.min.js"></script>
<script type="text/javascript" src="fliplightbox/fliplightbox.min.js"></script>
<script type="text/javascript">$('body').flipLightBox()</script>

2) Create an '<a>' tag that links to your lightbox image jpg, gif or png. Then add a class attribute named 'flipLightBox', like so: 

<a href="lightbox-image.jpg" class="flipLightBox">Link Text or Image<span>Optional Lightbox Text</span></a>

Notice there is a '<span>' tag next to the image. Within this you can add optional text to accompany the lightbox image when opened. Hyperlinks can also be added here (as shown in the demos).

3) Download 'flipLightBox.zip', unzip and place the 'fliplightbox' folder into your website directory. You are now up and running!

Adjusting The Settings

The settings can be adjusted either within 'fliplightbox.min.js' or by modifying the 'plugin call', as the example below:

$('body').flipLightBox({ 
lightbox_flip_speed: 500, 
lightbox_border_color: '#666666' 
})

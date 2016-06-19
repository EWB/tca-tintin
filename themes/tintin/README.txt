DEVELOPED BY:
--------------------------------------------------------------------
http://knackforge.com

ABOUT TINTIN THEME:
-----------------------------------------------------------------
Tintin is a Single page drupal 8 Theme with a modern flat design look. This theme is well suited for Business, Corporate site. It is very lightweight for fast loading with a modern look.

    -> Simple and clean design
    -> Drupal standards compliant
    -> Responsive layout
    -> Default Bootstrap carousel slideshow.
    -> Default Bootstrap model popup is used.

IMPORTANT DETAILS :
----------------------
Site admin credentials :

username : admin
password : admin

After installing the tintin dump, you must change email address in the following pages,
1. admin/structure/contact/manage/feedback  // Change Recipients.
2. admin/config/system/site-information     // Change email address.
3. user/1/edit                              // change email address.


FEATURES MODULE :
----------------------------
To get tintin content type and views (portfolio, testimonials, services block), you must install feature module.

1. You could see the feature folder inside your tintin/ theme folder,
2. Just extract features_portfolio.tar.gz and place the extracted content in your /modules/features/ folder.
3. Then enable the features_portfolio module through your drupal extend/module page.
4. Portfolio block would be available in the block list, you could place that in your content region.
5. Do the above steps to all the features (features_services, features_testimonials)

OPTIONAL MODULES:
---------------------------------------------------------------------
The below-listed modules can be installed if needed to enable all the functionality.

    1. FORM BLOCK
       Enables the presentation of user registration, site wide contact, or node creation forms in blocks.
       Download this module from https://www.drupal.org/project/formblock

    2. SIMPLE SUBSCRIPTION:
      Adds a form in a block for subscribing to a newsletter (or anything else).
      Download this module from https://www.drupal.org/project/simple_subscription

    3. BLOCK CLASS:
      Allows assigning CSS classes to blocks.
      Download this module from https://www.drupal.org/project/block_class



THEME SETTINGS:
----------------------------------------------------------------------
The below-listed settings can be changed in "/admin/appearance/settings"

    1. BANNER CONTENT ( with or without slideshow):
          By default, there are two options for placing banner content.

              1. To place the banner content with slider ENABLE slideshow in "/admin/appearance/settings"
                 and add the content and save it.

              2. To place the static content without slider DISABLE slideshow in "/admin/appearance/settings"
                 and Custom blocks can be placed in the banner content region.
                 This custom block content should have parent class as "intro-text".
                Ex:- <div class="intro-text">
                     <h1>We are <strong>TINTIN</strong></h1>
                     <p>sample text</p>
                     </div>

    2. SOCIAL ICON CONFIGURATION:
          To set the social icons go to "/admin/appearance/settings" and add font awesome class Ex:- "fa-gear" and respective URL of given icon.


NOTE:
-------------------------------------------------------------------------
1. To have a list with the tick as in about section add parent class "tick-list" for the list.
2. By default, all the contents in a content region will be displayed with alternative background color "white" and "grey".
3. To have the same button style as in theme use "btn-default" class.
4. To have the coloured background use "green-bg" class.
5. To have a dark background image as in testimonial section use "dark-bg-image" class.

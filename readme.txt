=== WP Coupons ===
Contributors:
Donate link: https://wpcoupons.io
Tags: wp-coupons
Requires at least: 5.5
Requires PHP: 5.6
Tested up to: 6.1.1
Stable tag: 1.8.3
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

WordPress coupon plugin for marketers.

== Description ==

[WP Coupons](https://wpcoupons.io/) was developed for affiliate marketers, bloggers, and ecommerce shops. It helps advertise your deals, coupons, and discount codes while increasing CTR and conversions. 

= Features =

* Numerous display settings you can choose from on how your coupons appear.
* Quick style options to match the branding of your site.
* Display a coupon widget on your sidebar and make it scroll as users read down your posts.
* Enable click to reveal to behave just like the popular RetailMeNot coupon site.
* Change link behaviors (direct, new tab, nofollow, etc.).
* Lightweight and scalable. The plugin doesn’t use any JavaScript on the front-end and there is no jQuery dependency. 

= Documentation =

Check out our [documentation](https://wpcoupons.io/docs/) for more information on how to use our plugin features.

== Changelog ==

= 1.8.3 - 02.20.2023 =
* Added wp-coupons-expired class to coupon panel div for any coupons that are past their expiration date.
* Fixed a rewrite rule issue that was interfering with tag navigation.
* Updated license key field to prevent it from getting auto-filled by browser extensions.
* Added notice to plugin update row if there is not an active license key.

= 1.8.2 - 10.24.2022 =
* Added a new option to set a manual Breadcrumb URL when using the single coupon template.
* Fixed an issue where the license key was not properly updating.
* Updated EDD plugin updater class to version 1.9.2.

= 1.8.1 - 05.31.2022 =
* Updated plugin settings UI.
* Added new support page with frequently asked questions and helpful links.
* Changed toggle CSS selectors to be more specific to prevent conflicts.
* Moved plugin settings header output to in_admin_header action hook for compatibility.
* Changed settings export file name date format to be easier to organize when managing multiples.
* Moved restore default functionality to a separate option in the tools section.

= 1.8.0 - 12.27.2021 =
* Added new wp_coupons_limit_meta_inputs filter to allow character count limits for certain meta options to be turned off.
* Fixed a styling issue with the force coupon dropdown in the block editor.
* Updated EDD plugin updater class to version 1.9.1.

= 1.7.9 - 11.04.2021 =
* Integrated link behavior options with click to reveal feature. Having link behavior set to split will now allow title links to pass through to the local coupon post.
* Updated EDD plugin updater class to version 1.9.0.
* Translation updates.

= 1.7.8 - 06.23.2021 =
* Added new Single Coupons option to set the Title Tag used for the banner title HTML.
* Added new wp_coupons_coupon_panel_image filter to adjust the image size that is used for the coupon panel.
* Removed character limits on discount and discount code meta options and modified front end styles to work when longer strings are present. 
* Added CodeMirror support to the Custom CSS textarea.
* Made adjustments to the WP Coupons row links on the plugins page.
* Removed license activation check and corresponding links from the plugins page to improve back-end performance.
* Added readme.txt file.
* Translation updates.

= 1.7.7 – 04.01.2021 =
* Added new Coupon Panel option to set a custom Placeholder Image.
* Added a new Configuration option to change the Heading Tag used for the related coupons heading text.

= 1.7.6 – 01.21.2021 =
* Added list layout options for single coupon shortcode.
* Fixed an issue that was causing coupon panels not to fill available space with certain image dimensions.
* Minor updates to the license management page.
* Updated outdated translation files.
* PHP 8 compatibility testing.

= 1.7.5 – 11.26.2020 =
* Added new coupon panel option to adjust the Title Tag used to display coupon panel titles for SEO purposes.
* Fixed an issue where the Direct Link meta checkbox wasn’t always working correctly for individual coupon posts.
* Added admin capability to be able to use the Move to Trash option as a bulk action when managing all coupon posts.
* Various styling fixes for better compatibility.

= 1.7.4 – 11.18.2020 =
* New coupon panel option to set Link Behavior. This replaces and expands on the previous option to Force Direct Links.
* Migrated archive styles to Flexbox in preparation for some more in-depth CSS improvements and refactoring.
* Added new configuration option to set the Related Coupons Layout.
* Migrated old Font Awesome icons to inline SVGs.
* Minified main frontend CSS file for improved performance.
* Updated EDD plugin updater class to version 1.8.0 and integrated new functionality to allow for auto-updates.
* Fixed a styling issue in the archive that would sometimes not display the coupon panels at the proper size if navigating to a certain type.
* Translation updates.

= 1.7.3 – 09.09.2020 =
* Added new extra option to Force Nofollow on any direct links.
* Added new display option to set the Coupon Type Slug to customize coupon archive pagination URLs.
* Multiple UI changes and improvements in plugin settings pages.
* Added rel=’noopener’ to attribution link for security purposes.

= 1.7.2 – 07.10.2020 =
* Updated plugin settings UI styles and made some improvements to settings framework functions.
* Improved license management functions and UI.
* Fixed an issue where pagination wasn’t working correctly on some shortcode archives if no sticky coupons were set.
* Updated plugin description.

= 1.7.1 – 05.25.2020 =
* Added meta box to Force Coupon Widget to our Coupon post type.
* Fixed undefined variable PHP warning in shortcode.php.
* Updated EDD Plugin Updater class to version 1.7.1.
* Added additional text domain information to the main plugin file’s header for translation support.

= 1.7.0 – 04.29.2020 =
* Added new options to Import and Export plugin settings in Extras → Tools.
* Added new header to plugin settings pages.
* Added additional styles for plugin settings sub-navigation.

= 1.6.9 – 03.12.2020 =
* Fixed an issue that was causing the Type and Tag taxonomies to not show up in the Block Editor.
* Added a version control function to help with future updates.

= 1.6.8 – 03.02.2020 =
* Removed ‘Show in REST API’ toggle. This is now enabled in the core coupon post type to support the new WordPress block editor by default.
* Optimized coupon archive queries for better performance.

= 1.6.7 – 01.22.2020 =
* Added new Sticky checkbox to the Coupon post meta options. This allows you to force specific coupons to display at the beginning of the coupon archive. This affects both the archive template and the shortcode.
* Added check for jQuery when certain options are enabled and enqueue it if necessary.

= 1.6.6 – 12.27.2019 =
* Reworked settings dropdowns that load a list of all coupon titles. Optimized queries for sites with a lot of coupons.
* Added some additional logic to prevent coupon lists from being requested on pages where they aren’t needed.

= 1.6.5 – 11.14.2019 =
* Fixed an issue that was causing a PHP error when updating certain options.

= 1.6.4 – 11.14.2019 =
* Added ‘sort’ parameter to both the single coupon and archive shortcode to allow for sorting override.
* Added ‘type’ parameter to the single coupon shortcode to filter the pool to a specific type.
* Added ‘tag’ parameter to the single coupon shortcode to filter the pool to a specific tag.
* Added new display option to set Expiration Behavior for expiring coupons.
* Added new display option to change the Expiration Recurrence which will change the frequency of the expiring coupon scheduled event.

= 1.6.3 – 10.10.2019 =
* Reworked all admin script enqueue functions to make sure admin scripts and styles are only being loaded on admin pages where they are necessary.
* Adding a link to the Settings page underneath the Coupons custom post type in the WordPress Admin.

= 1.6.2 – 09.02.2019 =
* Added support for excerpts to the coupon post type.
* Added additional styles to the Click to Reveal popup to clip and hide lengthy discount URLs.
* Added local site date format checks to all expiration date functions.
* Added new coupon post meta option to Exclude from Search that is specific to each coupon.

= 1.6.1 – 07.29.2019 =
* Reorganized plugin action links in the plugins table.
* Added support for custom fields to the coupon post type.
* Added new option to Enable Comment Support which will add comment support to the coupon post type.

= 1.6.0 – 06.30.2019 =
* Added additional styles to the Click to Reveal popup for better compatibility.
* Added new display options for Archive Facebook Image and Archive Twitter Image to allow for custom Open Graph image tags to be printed out on the Coupon Archive Template.
* Added new Dropdown selection to the Nav Style option to provide an alternate, more compact layout for users with a lot of navigation elements.

= 1.5.9 – 05.06.2019 =
* Increased max length of coupon discount descriptions to 500 characters.
* Added new display option to set the Coupon Description Height to allow more customization for those who want to display more text on their coupon panels.
* Added new display option to change the Archive Sort Order which will allow you to sort your archive coupons by post date (default), last modified date, post title, and random.

= 1.5.8 – 04.07.2019 =
* Added new option to Hide the Single Coupon Post Template Title which will hide the post title displayed underneath the main coupon banner and above the post content area when using the Single Coupon Template.
* Added additional parameters to the single coupon shortcode for CSS Class, Direct Links, and nofollow Tags to allow for more granular control specific to the shortcode.
* Fixed a bug that was causing the excluded posts to not work correctly after a certain limit in some cases that was interfering with the Exclude from Archive and Exclude from Rotation options in the coupon post meta.

= 1.5.7 – 03.03.2019 =
* Added new option for coupon post type to Show in REST API, available in the extras tab.
* Added new set of display options to set a custom Related Coupons Hook and Related Coupons Hook Priority for those wanting to change the location of the related coupons section using a theme hook.
* Minor styling changes to the single coupon post banner for better compatibility.

= 1.5.6 – 02.10.2019 =
* Added additional archive layouts with support for 2 Column, 4 Column, and 5 Column layouts.
* Added new display option to Hide Coupon Type Tags.

= 1.5.5 – 01.25.2019 =
* Fixed a bug that was causing the related posts to display even when not enabled on certain pages.

= 1.5.4 – 01.24.2019 =
* Fixed a bug that was causing the archive pagination elements to not display correctly on mobile.
* Made some improvements to the plugins main version control.

= 1.5.3 – 01.06.2019 =
* Added new display option to Hide Breadcrumbs on the Single Coupon Posts.
* Added support for the coupon specific Call to Action field to the custom Single Coupon Post Template.

= 1.5.2 – 12.10.2018 =
* Added new Archive Layout option along with 3 new list style layouts to select from along with the default 3 column layout.
* Added new Call to Action field in the Coupon Post meta options which will override the Call to Action for that individual coupon.
* Reworked the basic archive row + column printing function in preparation for additional future archive layouts.
* Minor optimizations to the primary archive template script.
* Fixed a bug in the archive template that was causing coupons not to display when filtering by coupon type from the nav while the Exclude From Search option was also toggled on.

= 1.5.1 – 11.14.2018 =
* Added Coupon post meta option to add your own CSS Class that will be printed out on that coupon’s panel across all views if needed for targeting with custom styles.
* Added the ability to pass multiple coupon types + tags to the wp_coupons archive shortcode (comma separated).
* Fixed some styling inconsistencies on the buttons between different templates. Link colors should now be applied correctly to all WP Coupons buttons.

= 1.5.0 – 10.07.2018 =
* Added ‘No Code Needed’ text to coupon panel function for consistency across all views when displaying discount codes.
* Added ‘wp-coupons-post-content’ class to the Single Coupon Post content container div to be able to uniquely target the Coupon Post content with custom CSS.
* Added support for custom “Call to Action” text to the Single Coupon banner when not using our Single Post Template.

= 1.4.9 – 08.27.2018 =
* Added new Display Single Template Image option for certain cases when users are not using our Custom Single Coupon Template and their default theme templates don’t automatically display featured images on Single Coupon Posts.

= 1.4.8 – 08.03.2018 =
* Added some additional logic to make sure the Coupon admin capabilities get set properly in a specific upgrade path scenario.

= 1.4.7 – 07.31.2018 =
* Fixed a bug that could cause the Coupon capabilities to not appear on the admin role by default if the Management Roles hadn’t been setup in the plugin settings. If you do not see the changes immediately, make sure to refresh WP Admin in your browser which should trigger the Coupon capabilities function.

= 1.4.6 – 07.30.2018 =
* Added a new Coupon Management Roles option to the Extras tab, allowing for selection of which WordPress roles can manage Coupon posts.
* Fixed a bug that was causing the Click to Reveal and Clipboard.js functionality to not behave properly on the Related Coupons section in certain cases.
* Added Click to Reveal logic to the coupon banner on the Single Coupon Post Template.
* Fixed various PHP warnings stemming from the Related Coupons function.

= 1.4.5 – 06.11.2018 =
* Fixed a bug that was causing the Click to Reveal links to not work properly on shortcode buttons.
* Fixed a styling issue that was allowing the coupon codes to overflow the image container in some spots.
* A few styling tweaks to the coupon panel CSS.

= 1.4.4 – 06.03.2018 =
* Added new Related Coupons toggle, along with a few customization options.
* Major Coupon Panel + CSS overhaul, refactoring, organization, less redundant styles, less code needed for generating coupon panels.
* *Note* – Due to all the styling changes in this update, we recommend clearing your site + CDN cache (/wp-content/plugins/wp-coupons/css/style.css) to make sure things are displaying properly. Custom CSS alterations may also have to be updated due to class changes and formatting updates. Please reach out if you have any questions or need some help updating custom CSS related to our plugin. Thanks!

= 1.4.3 – 05.01.2018 =
* WP Coupons is now translation ready! If you are interested in helping out with a translation, please contact us.
* Added new No Code Needed Text option to adjust the text that is displayed when no code is present.
* Added new Hide No Code Needed option to hide that section from single coupon posts.
* Added new Click to Reveal Text option to adjust the text that is displayed on the Click to Reveal buttons.
* Added new option to Exclude Coupons from Search.

= 1.4.2 – 04.01.2018 =
* Added new Clean Uninstall option in the extras tab.

= 1.4.1 – 02.28.2018 =
* Added new display option, Nav Style, to change the style + placement of the coupon archive navigation.
* Fixed a PHP undefined index warning that could happen when new options are introduced through an update.
* Removed some redundant link styles from style.css.

= 1.4.0 – 01.25.2018 =
* Added new display option to Enable Tag Subnav to add another layer of front-end organization for sites with a larger amount of coupons.
* Added new font size options for Primary Nav and Subnav elements.
* Fixed some styling issues with nav elements for sites with lots of coupon types and tags being displayed.

= 1.3.9 – 01.10.2018 =
* Fixed a bug that was causing coupons to not display properly in the admin if Exclude From Archive was checked.

= 1.3.8 – 12.21.2017 =
* Fixed the background color of the container displaying on the codeonly shortcode template.
* Removed the check for Display Discount Codes when using the codeonly shortcode template.
* Completely refactored the clipboard.js implementation to be a bit more efficient, especially when using multiple shortcodes and/or widgets on the same page.
* Fixed a styling issue with archive pagination spacing that could occur in some themes.
* Added new coupon post meta option to Exclude From Archive.
* Added functionality to copy the discount code to the clipboard before the click to reveal action occurs when both of those settings are enabled. Currently only works on the actual Click to Reveal button.

= 1.3.7 – 12.19.2017 =
* Cleaned up some code in the coupon archive template that was used for testing.

= 1.3.6 – 12.19.2017 =
* Added a new single coupon shortcode template which displays just the coupon code or ‘click to reveal’ box by itself if a coupon code is available.
* Added character masking to the license key input field.

= 1.3.5 – 10.02.2017 =
* Fixed some additional undefined index PHP notices.

= 1.3.4 – 09.27.2017 =
* Fixed various undefined index PHP notices in the coupon meta box functions.
* Fixed a bug where the Click to Reveal button corners would show up as transparent when no color was set.
* Added some logic to hide the Copy button on the Click to Reveal popup if Clipboard.js is not enabled.

= 1.3.3 – 09.24.2017 =
* Added new Click to Reveal (BETA) feature with a few corresponding customization options.

= 1.3.2 – 08.06.2017 =
* Alot of settings UI improvements, hovering tooltips, links to the web documentation, etc…
* Added version numbers to admin scripts to avoid caching on plugin update.
* Refactored a good portion of the settings initialization code.
* Upgrade licensing feature added. You can now upgrade licenses from within your account and you are automatically prorated the new amount.

= 1.3.1 – 06.21.2017 =
* Additional behind the scenes bug fixes.

= 1.3.0 – 06.19.2017 =
* Fixed a bug that caused certain shortcodes to conflict with a plugin activation function.

= 1.2.9 – 06.18.2017 =
* Fix for WordPress error that could trigger on license activation/deactivation with certain plugin configurations.
* Updated EDD Plugin Updater class to version 1.6.12.

= 1.2.8 – 06.18.2017 =
* Hotfix to enqueue jQuery UI in the admin in case it is not included for datepicker.

= 1.2.7 – 06.18.2017 =
* Added the ability to set coupon expiration dates in the WP Coupons Details post meta box. Coupon Posts will automatically go from Published to Draft status after their expiration date.
* Added option to display expiration dates on the front end.
* Increased affiliate link URL max length.
* Various styling fixes on a few different views.

= 1.2.6 – 05.25.2017 =
* Added ‘type’ parameter to the ‘wp_coupons’ shortcode so you can now filter by coupon types as well as tags.
* A few small optimizations in the ‘wp_coupons’ shortcode function.
* WordPress 4.8 support.

= 1.2.5 – 04.30.2017 =
* Added a style fix for the single coupon post template top banner position.
* Added new option in the coupon post meta options to remove from rotation on widget and single coupon shortcode.
* Added new option to prepend permalink structure for coupon custom post type and coupon type custom taxonomy. This is turned off by default.

= 1.2.4 – 04.23.2017 =
* Added additional layouts for the single coupon template coupon panel in display options. (view layouts)
* Added additional theme compatibility to single coupon post template.

= 1.2.3 – 04.16.2017 =
* Added shortcode support for the before and after content sections on the archive template.

= 1.2.2 – 04.03.2017 =
* Fixed breadcrumb on the single coupon post template to match custom label if one is set.
* Added optional support for clipboard.js. This can be enabled in the Extras tab and it will include clipboard.js and add Copy buttons to all coupon codes that will copy the code to clipboard on click.

= 1.2.1 – 02.26.2017 =
* Added support for the ‘Force Coupon’ meta box on custom post types.

= 1.2.0 – 12.29.2016 =
* Added option to add CSS classes to the custom single coupon template container div. This can help with theme compatibility in some cases.

= 1.1.9 – 11.24.16 =
* Added option to set direct links to open in the current tab instead of a new one
* Added option to force a specific coupon to display on the widget globally
* Added option to enable discount code display on coupon panels across all views
* Added tag icon to discount codes on coupon panels and single coupon posts (requires Font Awesome)
* Fixed a bug that was causing the coupon widget not to randomize properly when the ‘Post Types Order’ plugin was also being used (https://wpcoupons.io/docs/re-order-wordpress-coupons/)

= 1.1.8 – 10.15.16 =
* Added option to select default post template (post/page) for single coupon posts when the custom template is turned off

= 1.1.7 – 08.21.16 =
* Lots of under the hood fixes, cleaned up some undefined index warnings.

= 1.1.6 – 08.14.16 =
* Added nofollow attribute on single shortcode, widget, and attribution links
* Added a checkbox in the Coupon post meta box to set that coupon’s links to nofollow

= 1.1.5 – 07.13.16 =
* Fixed a bug that was causing a conflict with the WordPress tag archive pages and causing them not to display correctly
* Fixed a bug that was causing the permalinks not to refresh on first activation, causing a 404 error on the coupon post type

= 1.1.4 – 07.11.16 =
* Fixed a bug that would sometimes cause the coupons widget not to properly print the closing tags

= 1.1.3 – 07.11.16 =
* Added ‘Tags’ taxonomy to the coupon post type, allowing you to associate different coupons together with tags and then print out coupons from a single tag using |wp_coupons tag=”example”|
* Added display option to force display of a specific coupon in the widget if on home (blog) page
* Added shortcode option to hide menu navigation, |wp_coupons nav=”false”|
* Added “Fonts” section to the style tab, allowing customization of the font sizes and line heights of different coupon elements
* Style fixes
* Unified certain font styles across different views
* Added shortcode examples and documentation to the support tab
* Added option to display “Attribution Link” on the coupon widget, as well as an option to specify an affiliate ID for the generated referral link
* Increased the character limit on the coupon descriptions to 250, as font size and line height options can be changed to allow for more text to be shown

= Version 1.1.2 – 06.28.16 =
* Added “Archive Post Limit” option in display settings to set post count for archive template
* Added “limit” parameter on the main ‘wp_coupons’ shortcode to set post count
* Synchronized call to action text across all coupon panels and buttons
* Added “Call to Action” option in display settings to change call to action text across all layouts
* Added “Nav Title” option in display settings to change text of the first nav element for the archive template and ‘wp_coupons’ shortcode
* Added “Before Archive Content” and “After Archive Content” options in the extras tab to create custom content for display above and below the main coupon archive

= 1.1.1 – 06.15.16 =
* Added shortcode support for coupon description box across all views
* Added custom CSS box in the ‘Extras’ tab
* Added global force direct links checkbox in the ‘Extras’ tab

= 1.1.0 – 06.08.16 =
* Fixed a bug that was causing the “force coupon” option to not work with the widget in some themes
* Style fixes
* Added a “direct link” option to the individual coupon posts

= 1.0.9 – 06.01.16 =
* First version of the plugin launched on June 1st, 2016.

= 1.0.7 =
* Deactivate license key when plugin is uninstalled
* Style fixes
* Organizing and commenting code

= 1.0.6 =
* Styling fixes
* New license activation options to provide more info to the user about their license activation.
* Admin panel bug fix

= 1.0.2 =
* Styling fixes across the board in all views.
* Cleaned up some of the code used in the admin panel.

= 1.0.1 =
* Organized the license activation tab to make it simpler to understand.
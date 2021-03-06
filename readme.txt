=== Plugin Name ===

Contributors:      dracea
Plugin Name:       Suffusion Collapse Menu
Plugin URI:        http://drafie-design.nl
Tags:              WordPress, Suffusion, select box, select menu, navigation, responsive design, mobile devices
Author URI:        http://drafie-design.nl
Author:            Ciprian Dracea (Drake)
Donate link:       
Requires at least: 3.4
Tested up to:      4.5.3.
Stable tag:        1.0
Version:           1.0
License: GPLv2 or later. (http://www.gnu.org/licenses/gpl-2.0.html)

== Description ==
**This is the end**
This plugin is not longer maintained. Because Suffusion was removed from Repository, this plugin is not having object anymore. Farewell my friends!

The plugin was intended to improve the look of menu loaded by Suffusion on mobile devices. The Plugin just load Responsive Nav files, replacing the regular select lists used by Suffusion on mobile devices.

The menu is settled to follow the breakpoint settled at Suffusion Options -> Layouts -> Responsive Layouts -> Switches -> Navigation Menu. On higher resolutions are used the regular Suffusion Navigation Bars.

If you use both navigation bars (Above and Below Header), they are joined in only one collapse menu, that's it - you cannot have multiple menus with this plugin.(on larger screens, both menus are restored).

I choosed this solution for solving also the problem of 2 select lists which are displayed on mobile devices in Navigation Bar Above Header if both navigation bars are used. Also the plugin restore the "home" image in menu on mobile devices (as of version 0.3).

However, if you have too much menu items, in complicated structures, with many levels of dropdowns, maybe better is to remain on select lists.

**Thanks to**
This Plugin is based on Responsive Nav - Copyright (c) 2013 Viljami Salminen, http://viljamis.com/

== Installation ==

1. **Download the plugin**, unzip and load the folder "suffusion-collapse-menu" in to the "/wp-content/plugins/" directory, or install the zip file from WordPress dashboard.
2. **Activate the Plugin** from plugin menu in the WordPress dashboard
3. **CAN CHANGE STYLES**
The collapsed menu already use the background of navigation bar settled by selected skin.
If you want to change the color of icon, can do this at **Appearance -> Customize -> Colors -> Collapsing Button Color**.

== Screenshots ==
1. Suffusion Collapse Menu in action

== Changelog ==
**0.9** December 26, 2015
- Improvement - the color of menu icon can be changed now at Customizer.

**0.8** December 11, 2015
- Removed inline comments from js trigger function to prevent issues with minification.

**0.7** December 06, 2015
- Updated Responsive Nav javascript to the latest version, http://responsive-nav.com/
- Changed the default class used by script to "suf-nav-collapse" for not conflicting with other plugins which may use Viljami's script.
- Tested compatibility with WordPress 4.4.

**0.6** December 07, 2014
- Bug corrected - on devices with exactly the resolution of the trigger, the toggle button not appear yet, but also the regular menu is still hidden. By eg. if the breakpoint is settled at 480px, on smartphones with 480px width will not see any menu.

**0.5** June 23, 2014
- Improvement - the plugin follow now the breakpoints settled in Suffusion Options. So, the collapsed menu appear now at whatever resolution you have settled at Layouts -> Responsive Layouts -> Switches -> Navigation Menu.

**0.4** June 16, 2014
- Bug corrected - by adding "home-icon" in the previous version I ruined the script for sites where the icon wasn't used in Suffusion - this was addressed.
- Code improvement - all scripts are enqueued now in WP_ENQUEUE_SCRIPTS hook, following Codex recommendation;
- Changed licence to GPLv2 or later, for conforming with WordPress recommendation for getting the plugin hosted on WordPress Repository

**0.3** June 15, 2014
- Bug of Suffusion corrected - when the navigation bars become select lists the home icon is not displayed as option - instead is displayed only an empty option linked right to the homepage. The plugin restore the home icon in the "home" tab.

**0.2** June 14, 2014
- Bug corrected - the plugin does not work if you are using only Navigation Bar Above Header. Thanks to Nicolas for pointing me to this issue.

**0.1** June 1, 2014 
- Initial release

== Upgrade Notice ==
= 0.9 = The plugin use now the Customizer for changing the color of collapsed button.
= 0.8 = Removed inline comments from js trigger function to prevent issues with minification.
= 0.7 = Tested compatibility with WordPress 4.4. and upgraded the Responsive Nav script to the latest version.
= 0.6 = This version address a bug which hide all menus on screens with exactly the same resolution as the sellected trigger.
= 0.5 = From now the collapse menu is no more fixed at 480px, but will follow the settings from Suffusion Options preserving consistency with theme settings.
= 0.4 = This version corrected a bug which block the collapsing menu on sites where weren't used "home-icon" in Suffusion.
= 0.3 = If the "home" icon is used this version will show it on mobile devices
= 0.2 = If only Navigation Bar Above Header is used, this version will show the menu.

== Frequently Asked Questions ==

= This plugin will work with my theme? =
The plugin is written specifically for Suffusion, it address it's elements and even use some of Suffusion Options, so, no, it will not work with any other theme.

= You will provide updates to the plugin? =
No, I don't. At least not here. If you need support, ask for it on aquoid.com/forum or on my site directly.
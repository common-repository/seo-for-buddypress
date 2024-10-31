=== Seo for Buddypress ===
Contributors: svenl77,mahype
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=NWEYBQUNE5PVY
Tags: seo,buddypress,wpmu,wp
Requires at least: 2.9.x & buddypress 1.2.x
Tested up to: 3.0.1 & buddypress 1.2.x
Stable tag:  1.3.1

This plugin adds an option page Seo for Buddypress under your Buddypress admin.

== Description ==

The Plugin is no longer supported. The new and supported version is <a href="http://wordpress.org/extend/plugins/seopress/">SeoPress</a>.
For buddypress versions grather then 1.2.5 please use the new version from here:
http://wordpress.org/extend/plugins/seopress/

<br>
== Installation ==

1. Upload 'Seo for buddypress' to the '/wp-content/plugins/' directory<br>
2. Activate the plugin through the 'Plugins' menu in WordPress<br>
<br>
In the main blog theme header.php, must exist<br>
< title > < ?php bp_page_title() ? > < /title >
<br>
In the user blog theme header.php, must exist<br>
< title > < ?php wp_title(); ? > < /title >

<br>
These are the standard title tags. Added by buddypress and wordpress by default in the header.php.<br>
If you did not change your themes, or did any customisation, they will be there. <br>
<br><br>
That's it, have fun.<br><br>

Update:
If you update from an old version, please go to the settings page and click on "Update Database". <br><br>

== Screenshots ==

1. **Welcome**
2. **General Seo**
3. **Plugins Seo**
4. **Settings**
5. **Special Tags for WP and WPMU**
6. **Special Tags for Buddypress**


== Changelog ==
<h4>1.3.1</h4>
<ul>
<li>
Development has stopped. New version available under SeoPress!
</li>
<h4>1.3</h4>
<ul>
<li>
This Version is a jump back and rewrite of 1.2.5, with many bug fixes. Because there have bean to many bugs after I did change the core logic of the plugin. This version should be stable now. The next version will come with a new logic, which needs much more testing. This new system will be important for buddypress 1.3, and I will make it stable with a small testing crew. For your productive site this Version 1.3 should be the right version. 
</li>
</ul>
<h4>1.2.9</h4>
<ul>
<li>Fixed a bug: There was an undefind function in wpmu without buddypress for the post title</li>
</ul>
<h4>1.2.7</h4>
<ul>
<li>Fixed a bug reported by guigoz</li>
<li>Add Italien translation</li>
</ul>
<h4>1.2.6</h4>
<ul>
<li>FIxed a bug according to this ticket: http://trac.buddypress.org/ticket/2645</li>
<li>cleaned up the code.</li>
</ul>
<h4>1.2.5</h4>
<ul>
<li>Added title length settings</li>
<li>Added noindex</li>
<li>Fixed a bug with the static home page </li>
<li>Add an option to disable seo meta boxes in post and pages</li>
<li>Fixed the Plugin seo section, it was broken in 3.0</li>
</ul>
<h4>1.2.4 beta</h4>
<ul>
<li>I killed the menue with the last update... should be fixed now<br>
</li>
</ul>
<h4>1.2.3 beta</h4>
<ul>
<li>Fixed a conflict reported by Terence (forum-attachments-for-buddypress use the same function named curPageURL</li>
<li>Changed the Plugin menue behaviour, so if bp is instaled, the menue will be under Buddypress</li>
</ul>
<h4>1.2.2 beta</h4>
<ul>
<li>Fixed many bugs reported by the buddypress community. Thanks for all the feadback.</li>
</ul>
<h4>1.2.1 beta</h4>
<ul>
<li>Plugin is now ready for Wordpress and Wordpress MU without Buddypress</li>
<li>Added new Meta fields for post and pages</li>
<li>Compatible with wpSEO and AllInOne Seo Page Meta data</li>
</ul>
<h4>1.1</h4>
<ul>
<li>Stable version</li>
</ul>
<h4>1.0.10 beta</h4>
<ul>
<li>Fixed some Bugs reported by stwc</li>
</ul>
<h4>1.0.9 beta</h4>
<ul>
<li>There was a problem with version 1.8...it prevents blog creation.</li>
</ul>
<h4>1.0.8 beta</h4>
<ul>
<li>Fixed a lot of bugs, reported in the forum</li>
</ul>
<h4>1.0.7 beta</h4>
<ul>
<li>Fixed a bbPress forums bug if forums component is disabled Fatal error: Class 'BP_Forums_Template_Forum'</li>
</ul>
<h4>1.0.5 beta</h4>
<ul>
<li>Fixed the %%forumtopictitle%% bug </li>
</ul>
<h4>1.0.4 beta</h4>
<ul>
<li>Add special tags for forum</li>
</ul>
<h4>1.0.3 beta</h4>
<ul>
<li>Missed to close a </strong> tag</li>
</ul>
<h4>1.0.2 beta </h4>
<ul>
<li>Fixed some Bugs</li>
</ul>
<h4>1.0.1 beta</h4>
<ul>
<li>add_action( 'bp_init', 'bp_seo_init' )</li>
</ul>
<h4>1.0 beta</h4>
<ul>
<li>This version is a complete rewrite of the old plugin. It has a new logic, and much more functionality.</li>
</ul>
<h4>0.6.9</h4>
<ul>
<li>Fixed some bugs, to make it work with bp 1.2</li>
</ul>
<h4>0.6.8</h4>
<ul>
<li>Fixed some bugs</li>
</ul>
<h4>0.6.7</h4>
<ul>
<li>Add Seo Options:</li>
<li>PROFILE BLOGS RECENT POSTS</li>
<li>PROFILE BLOGS RECENT COMMENTS</li>
<li><br>
PROFILE ACTIVITY FRIENDS</li>
<li>GROUPS FORUM TOPIC</li>
<li>YOUR OWN PROFILE PAGE & YOUR OWN DIRECTORY</li>
<li>Changed some functions and file names like common in buddypress. That's why "Seo for Buddypress" is renamed in "bp-seo".</li>
</ul>
<h4>0.6.6</h4>
<ul>
<li>Fixed the nav bug.</li>
</ul>
<h4>0.6.5</h4>
<ul>
<li>I have problems with the svn. I lost some js and css again. Tray again to fix nav bug...</li>
</ul>
<h4>0.6.4</h4>
<ul>
<li>Changed the way Seo for Buddyp0ress is added to the Buddypress admin panel.There has bean some conflicts out there. I hope it will work now for everyone.<br></li>
</ul>
<h4>0.6.3</h4>
<ul>
<li>update to work with wpmu 2.8.5.2</li>
<li>Fixed some Bugs in the Main Blogs</li>
<li>Fixed a Bugs in the Events Dirctory Blogs</li>
</ul>
<h4>0.6.2.a</h4>
<ul>
<li>I lost some js in 0.6.2. In this version added again</li>
</ul>
<h4>0.6.2</h4>
<ul>
<li>added bp-events plugin 1.1 support for all event pages. Added user blogs info help text</li>
</ul>
<h4>0.6</h4>
<ul>
<li>update to work with buddypress 1.1.2</li>
<li>added main blog and user blogs support</li>
</ul>
<h4>0.5</h4>
<ul>
<li>integrate the directories view groups, members, blogs and events<br></li>
<li>fix a bug reported by Mark Leonard</li>
</ul>

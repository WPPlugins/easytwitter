=== EasyTwitter ===
Contributors: jimburnettva,jimmyburnett
Donate link: http://www.jimburnettva.com/
Tags: twitter,development,programming,php,twitter followers
Requires at least: 3.0
Tested up to: 3.5.1
Stable tag: 1.9.2

EasyTwitter provides an easy way to add twitter followers count and other twitter info to your wordpress template.

== Description ==


EasyTwitter provides an easy way to add your twitter information to your wordpress blog. 

<b>Here are some features:</b>
* Show Profile timezone.<br />
* Show Twitter Follower Count.<br />
* Show Twitter Friends Count.<br />
* Show Twitter profile picture.<br />
* Show Twitter location.<br />
* Show Twitter description.<br />
* Show you recent twitter status message.<br />
* Show Twitter name and profile name.<br />
* Show Twitter profile url.<br />
* Show retweet count!. <br />

Developed by: The <a href="http://www.jimburnettva.com/" title="Jim Burnett">Jim Burnett</a>.


== Installation ==

1. Upload `easytwitter.php` to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Use the follow example code to add your twitter information to yourtemplate:


<b>Step 1:</b><br />
$et = new EasyTwitter("twitterusername");//place this at the top of your template.<br />
<br /><br />

<b>Step 2:</b><br />
echo $et->followers_count(); // Your twitter followers.<br />
echo $et->profile_image_url();//This returns your profile image URL with no html markup. <br />
echo $et->location(); //This will show your location field. e.g. "Virginia".<br />
echo $et->status_text(); //Your most recent twitter status text.<br />
echo $et->profile_image_url();//URL to your twitter profile picture.<br />


Note: No methods will return any data with html markup. <br />


== Upgrade Notice == 
N/A

== Frequently Asked Questions ==

= Is there caching availible? =

Any wordpress cache plugin will cache this information. This is not javascript based so it will be cached like any other PHP plugin or script.



== Screenshots ==

None.

== Changelog ==

= 1.0 =
* Initial release.

= 1.1 =

= 1.2 =

= 1.3 =
Fixed a typo.
Add retweet_count.

= 1.4 =
Fixed glitch.

= 1.5 =
Added timezone

= 1.6 =
Tested with 3.4.2 wordpress.

= 1.7 =
Tested with 3.5.x wordpress.
Fix documentation.
Updated documentation.

= 1.8 =
Tested with 3.5.1 wordpress.
Fix minor code.

= 1.9 =
Miner change.

= 1.9.1 =
Documentation change.

== A brief Markdown Example ==

N/A

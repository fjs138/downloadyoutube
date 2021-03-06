Download YouTube Videos as MP4
===============

<h3>
===============
<a href="https://github.com/gantt/downloadyoutube/raw/master/script/yt.user.js">
    Install the script
</a> 
===============
</h3>

<br>

<div id="full_description"><b>Important</b>: If you find compatibility issues, check <a href="Debug.md">the bug reporting page</a>.
The script is also available <a href="https://greasyfork.org/scripts/1317-download-youtube-videos-as-mp4">at greasyfork.org</a>. 
<br><br><b>What's new</b>: Tampermonkey bug fix. <a href="Changelog.md">More in the changelog</a>.


<br><br><img alt="" src="http://i.imgur.com/xhdYmVg.png"><br><br>

The script works in:

<ul><li><b>Firefox</b> (install <a href="https://addons.mozilla.org/firefox/addon/greasemonkey/">Greasemonkey</a> first. Alternatively, you can install <a href="https://addons.mozilla.org/firefox/addon/download-youtube/">an extension that uses this script</a>)</li><li><b>Chrome</b> (install <a href="https://chrome.google.com/webstore/detail/dhdgffkkebhmkfjojejmpbldmpobfkfo">the Tampermonkey extension</a> first)</li><li><b>Opera</b> (install <a href="https://addons.opera.com/en/extensions/details/violent-monkey/">Violent Monkey</a> or <a href="http://addons.opera.com/extensions/details/tampermonkey-beta/">Tampermonkey</a> first. Alternatively, you can install <a href="https://addons.opera.com/addons/extensions/details/download-youtube-videos-as-mp4/">an extension which uses the script</a>)</li><li><b>Safari</b> (install the <a href="http://ss-o.net/safari/extension/NinjaKit.safariextz">NinjaKit</a> extension first. Make sure that extensions are enabled in the settings, download the file and double click it. Then you can install the script. More information <a href="http://wiki.greasespot.net/Cross-browser_userscripting#NinjaKit">here</a>.)</li></ul>


Here are the formats you can download using this script (Wikipedia has <a href="http://en.wikipedia.org/wiki/YouTube#Quality_and_codecs">the full list</a>):

<ul><li><b>MP4 360p</b> (384x288, 480x360, 640x360) - all videos are available in this format. Use it if you want to play videos on a mobile phone (iPhone, Android) or to save space.</li><li><b>MP4 720p</b> (1280x720) - HD format, available for an increasing number of videos. Use this format if you want to play videos on a tablet (iPad, Motorola Xoom, Samsung Galaxy Tab) or a laptop.</li><li><del><b>MP4 1080p</b> (1920x1080) - Full HD format, available for fewer videos than MP4 720p. Use this format to watch videos on a HD TV or a high resolution monitor.</del></li><li><del><b>MP4 4K</b> (<a href="http://youtube-global.blogspot.com/2010/07/whats-bigger-than-1080p-4k-video-comes.html">up to 4096p</a>) - HD format, available for a few videos.</del></li><li>the highest-quality FLV version available: <b>FLV 240p</b> (426x240), <del><b>FLV 360p</b> (480x360, 640x360) or <b>FLV 480p</b> (640x480, 854x480)</del>. Even if they have a different extension, .flv videos use the H.264 codec, just like .mp4 videos.</li><li>480p and 1080p are no longer available as standalone videos downloaded from youtube.com. YouTube switched to adaptive streams and uses separate files for video and audio, which need to be merged to get a video file. This is more complicated and requires more advanced tools (ffmpeg), so I haven't added them yet. </li></ul>

After downloading videos, you can play them using free applications like:
<ul><li><a href="http://www.videolan.org/vlc/">VLC</a> (Windows, Mac, Linux / plays both MP4 and FLV videos) - recommended video player</li><li><a href="http://windows.microsoft.com/en-US/windows7/products/features/windows-media-player-12">Windows Media Player 12</a> for Windows 7 (plays only MP4 videos)</li><li><a href="http://www.apple.com/itunes/download/">iTunes</a> and <a href="http://www.apple.com/quicktime/download/">QuickTime Player</a> (Windows, Mac / play only MP4 videos)</li><li>video players for mobile devices (for example, MP4 360p videos are better suited for older smartphones like iPhone 3GS, HTC Desire, Galaxy S/S2; MP4 720p videos are great for more recent smartphones (iPhone 4/4S/5, Galaxy S3), 7-inch tablets and older 10-inch tablets (iPad 1/2), while 1080p videos work better on the latest iPad, Nexus 10 and other high-resolution tablets and smartphones.)</li></ul><b>Automatic updates</b>: Scriptish and Greasemonkey for Firefox and Tampermonkey for Chrome support automatic updating.

<br><br><b>Related extensions</b>: If you use Firefox, you can also install <a href="https://addons.mozilla.org/firefox/addon/download-youtube/">an extension based on this script</a>. There's also <a href="https://addons.opera.com/addons/extensions/details/download-youtube-videos-as-mp4/">an extension for Opera</a>.</div>

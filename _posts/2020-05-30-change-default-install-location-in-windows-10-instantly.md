---
ID: 221
post_title: 'Change Default Install Location in Windows 10! [Instantly]'
author: Helena
post_excerpt: ""
layout: post
permalink: >
  https://windowsdot.com/change-default-install-location-in-windows-10-instantly/
published: true
post_date: 2020-05-30 14:24:03
---
Here, we come up with a useful article on how to <strong>Change Default Install Location in Windows 10</strong>.
<ul class="toc">
 	 
 	<li><a href="#1">Reasons to Change the Default Install Location</a></li>
 	<li><a href="#2">Switch the Default Install Location - Using Settings</a></li>
 	<li><a href="#3">Switch the Default Install Location via Registry Editor</a></li>
 	<li><a href="#4">Closure</a></li>

</ul>
<h2 id="1">Reasons to Change the Default Install Location:</h2>
In general, when you download any app or game from Microsoft Store it will install it in your C: drive or main system drive automatically. That's fine in most instances, but if you want to install any game that occupies more storage and <strong>you have a drive with limited storage</strong>, in such cases, you will end up with an error message 'free up your disk space'.

Fortunately, there is a solution to this issue. It is possible to switch the default location to save new apps from the Microsoft Store. You are not limited to install apps only in your C: drive or any particular drive. Even, you can use external storage for apps and games.

Further, you can also move already installed apps to a preferred location, and you can even choose a different location during download. Just follow any one of the two ways that are given below so you can <strong>change your default install location to any drive</strong> as per your own preference.

Changing the default install location in Windows 10 for apps will not move any of your currently installed apps. When apps receive updates they will remain in the location where they were originally installed.
<h2 id="2">Switch the Default Install Location - Using Settings:</h2>
<ol>
 	<li>Using this shortcut <strong>Windows key + I</strong>, you can open the <strong>Settings</strong>.</li>
 	<li>Then, you have to click on <strong>System</strong>.

[caption id="attachment_231" align="alignnone" width="861"]<img class="size-full wp-image-231" src="https://windowsdot.com/wp-content/uploads/2020/05/di1.png" alt="Choose System" width="861" height="543" /> Choose System[/caption]</li>
 	<li>Next, in the left pane, you have to click on <strong>Storage</strong>.

[caption id="attachment_232" align="alignnone" width="861"]<img class="size-full wp-image-232" src="https://windowsdot.com/wp-content/uploads/2020/05/di2.png" alt="Choose Storage" width="861" height="543" /> Choose Storage[/caption]</li>
 	<li>Click on the <strong>'Change where new content is saved'</strong> link, under <strong>More storage settings</strong> section.

[caption id="attachment_233" align="alignnone" width="861"]<img class="size-full wp-image-233" src="https://windowsdot.com/wp-content/uploads/2020/05/di3.png" alt="Change where new content is saved" width="861" height="543" /> Change where new content is saved[/caption]</li>
 	<li>Now, choose the new default location for apps using the drop-down menu of <strong>'New apps will save to'</strong> section. (Before choosing, make sure that the drive has the essential storage to install new apps.)

[caption id="attachment_234" align="alignnone" width="861"]<img class="size-full wp-image-234" src="https://windowsdot.com/wp-content/uploads/2020/05/di4.png" alt="Choose the drive" width="861" height="543" /> Choose the drive[/caption]</li>
 	<li>Click on the <strong>Apply</strong> button to save your changes and now you can install new apps or games on your desired location.</li>
</ol>
<p id="note"><strong>Tip: </strong>To move existing Windows 10 apps and games on an individual basis, you will need to head to <strong>Settings &gt; System &gt; Apps &amp; Features</strong>. Choose any installed app and click the <strong>Move</strong> button to switch the location.</p>

<h2 id="3">Switch the Default Install Location via Registry Editor:</h2>
<ol>
 	<li>Open the <strong>Run command</strong> via a shortcut <strong>Windows key + R</strong>.</li>
 	<li>You have to type 'regedit' and click <strong>OK</strong>. (If you get any pop-up from User Account Control, you have to press <strong>'Yes'</strong>) <code>regedit</code>

[caption id="attachment_235" align="alignnone" width="432"]<img class="size-full wp-image-235" src="https://windowsdot.com/wp-content/uploads/2020/05/di5.png" alt="Open Registry Editor" width="432" height="234" /> Open Registry Editor[/caption]</li>
 	<li>It will open the <strong>Registry Editor</strong>. In the left pane, you have to navigate to the following path. <code>HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion</code></li>
 	<li>Now, you have to double-click on <strong>CurrentVersion</strong>. In the right pane, double-click on <strong>ProgramFilesDir</strong> from the list. (If your OS is 64 bit, then you will find two entries ProgramFilesDir and ProgramFilesDir(x86). You can choose any one of them.)

[caption id="attachment_236" align="alignnone" width="964"]<img class="size-full wp-image-236" src="https://windowsdot.com/wp-content/uploads/2020/05/di6.png" alt="ProgramFilesDir" width="964" height="559" /> ProgramFilesDir[/caption]</li>
 	<li>You will see an <strong>Edit String</strong> dialog box. In the <strong>Value data</strong> field, you can edit the drive. By default, it will be in C: drive. Then, you have to press <strong>OK</strong>.

[caption id="attachment_237" align="alignnone" width="964"]<img class="size-full wp-image-237" src="https://windowsdot.com/wp-content/uploads/2020/05/di7.png" alt="Change the drive" width="964" height="559" /> Change the drive[/caption]</li>
 	<li>Restart your computer to apply the changes.</li>
</ol>
<h2 id="4">Closure:</h2>
That's it. Now, we have changed the default installation location. It's easy, right? We hope that this article on how to <strong>Change Default Install Location in Windows 10</strong> helped you a lot. Kindly, share your valuable comments to enhance our write-up. Thanks for visiting <a href="https://windowsdot.com/"><strong>Windows Dot</strong></a>.
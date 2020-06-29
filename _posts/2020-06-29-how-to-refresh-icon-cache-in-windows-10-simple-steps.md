---
ID: 1690
post_title: 'How to Refresh Icon Cache in Windows 10? [Simple Steps]'
author: Helena
post_excerpt: ""
layout: post
permalink: >
  https://windowsdot.com/how-to-refresh-icon-cache-in-windows-10-simple-steps/
published: true
post_date: 2020-06-29 09:54:17
---
Here, we come up with an interesting article on how to <strong>Refresh Icon Cache in Windows 10</strong>.
<ul class="toc">
 	<li><a href="#1">Refresh Icon Cache in Windows 10</a></li>
 	<li><a href="#2">Steps to Refresh Icon Cache</a></li>
 	<li><a href="#3">A Short Synopsis</a></li>
</ul>
<h2 id="1">Refresh Icon Cache in Windows 10:</h2>
Icon cache is a database (db) file that has a copy of each and every icon for quicker access. For each and every icon on Windows 10, the device stores updated information about them in a file called <span class="skimlinks-unlinked">IconCache.db</span> which remains hidden somewhere. Whenever Windows needs icons, it gets from the cache rather than retrieving the icon image from the original app.

The details about new icons are first stored in the main memory, and then the cache file is updated periodically. If any of your icons are not showing, then it states that you want to refresh your icon cache. This is mainly due to the issues with the icon cache file. In such cases, we have to refresh the icon cache. So, you just follow the below steps to do it without restarting your system.

<strong>Tip:</strong> Learn how to <a href="https://windowsdot.com/clear-all-types-of-windows-10-cache-quickly/#2"><strong>clear all types of Windows 10 cache</strong></a>.
<h2 id="2">Steps to Refresh Icon Cache:</h2>
<ol>
 	<li>Go to the <strong>Start</strong> menu and type ‘<strong>file explorer options</strong>‘ in the search box and hit <strong>Enter</strong>.

[caption id="attachment_1695" align="alignnone" width="1314"]<img class="size-full wp-image-1695" src="https://windowsdot.com/wp-content/uploads/2020/06/File-Explorer-Options-1.png" alt="File Explorer Options" width="1314" height="884" /> File Explorer Options[/caption]</li>
 	<li>Now, you have to click the <strong>View</strong> tab.</li>
 	<li>Select the check-box of ‘<strong>Show hidden files, folders, and drives</strong>‘.</li>
 	<li>Then, you have to click the <strong>Apply</strong> and <strong>OK</strong> button.

[caption id="attachment_1696" align="alignnone" width="621"]<img class="size-full wp-image-1696" src="https://windowsdot.com/wp-content/uploads/2020/06/Show-hidden-files.png" alt="Show hidden files" width="621" height="764" /> Show hidden files[/caption]</li>
 	<li>Go to <code>C:\Users\username\AppData\Local\iconCache.db</code> Replace username with your system's username.</li>
 	<li>You have to delete the '<strong>iconCache.db</strong>' file to refresh the icon cache. So, Windows will automatically begin rebuilding the new cache.</li>
 	<li>Further, you have to navigate to the below folder. <code>C:\Users\username\AppData\Local\Microsoft\Windows\Explorer</code>Replace username with your system's username.</li>
 	<li>Right-click on the <strong>Explorer</strong> folder and choose the <strong>Open command window here</strong>.</li>
 	<li>It will open the command prompt window. You have to type '<strong>dir</strong>' and hit <strong>Enter </strong>to make sure that you are in the correct folder.</li>
 	<li>Now, you can see the icon cache file.</li>
 	<li>You have to press <strong>Ctrl + Shift + Esc</strong> to open the <strong>Task Manager</strong>.</li>
 	<li>In the <strong>Processes</strong> tab, you have to right-click on <strong>Windows Explorer</strong> and choose <strong>End task</strong>.

[caption id="attachment_1697" align="alignnone" width="1054"]<img class="size-full wp-image-1697" src="https://windowsdot.com/wp-content/uploads/2020/06/Windows-Explorer-End-task.png" alt="Windows Explorer - End task" width="1054" height="938" /> Windows Explorer - End task[/caption]</li>
 	<li>Now, you have to type '<strong>del iconcache*</strong>' and hit <strong>Enter</strong> so it will delete the cache files.</li>
 	<li>All icon cache files will be repaired and rebuilt.</li>
</ol>
<h2 id="3">A Short Synopsis:</h2>
This tutorial guided you on how to <strong>Refresh Icon Cache in Windows 10</strong> in clear-cut steps. You just follow the above simple steps to rebuild the icon cache quickly on your PC. Don't forget to share your <strong>comments</strong> in the below box. Check out more interesting articles in <a href="https://windowsdot.com/"><strong>Windows Dot</strong></a>.
<h2>Keep Reading:</h2>
<ul>
 	<li><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsdot.com/disable-windows-defender-in-windows-10-5-simple-ways/" target="_blank" rel="noopener noreferrer">Disable Windows Defender in Windows 10!! (*5 Simple Ways*)</a></li>
 	<li><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsdot.com/simple-guide-create-an-invisible-folder-on-windows-10/" target="_blank" rel="noopener noreferrer">{Simple Guide} Create an Invisible Folder on Windows 10!!</a></li>
 	<li><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsdot.com/use-audio-router-for-windows-10-4-simple-applications/" target="_blank" rel="noopener noreferrer">Use Audio Router for Windows 10!! (4 Simple Applications)</a></li>
 	<li><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsdot.com/view-show-folder-size-in-windows-explorer-easily/" target="_blank" rel="noopener noreferrer">View/Show Folder Size in Windows Explorer!! [Easily]</a></li>
</ul>
---
ID: 2042
post_title: >
  Enable Metered Connection in Windows
  8/8.1/10!! (Quick Guide)
author: Helena
post_excerpt: ""
layout: post
permalink: >
  https://windowsdot.com/enable-metered-connection-in-windows-8-8-1-10-quick-guide/
published: true
post_date: 2020-07-11 22:56:36
---
In this article, we are going to show you three simple ways to <strong>Enable Metered Connection in Windows 8/8.1/10</strong>.
<ul class="toc">
 	<li><a href="#1">Metered Connection in Windows 8/8.1/10</a></li>
 	<li><a href="#2">2 Simple Ways to Enable Metered Connection</a></li>
 	<li><a href="#3">How to Set Data Limit?</a></li>
 	<li><a href="#4">Track App Usage History in Metered Connection</a></li>
 	<li><a href="#5">Wind-up</a></li>
</ul>
<h2 id="1">Metered Connection in Windows 8/8.1/10:</h2>
Metered Connection is a useful feature that limits the data usage in Windows 8/8.1/10. This kind of feature is not present in Windows 7 and its earlier versions. Setting your network connection (ethernet or wifi) to metered can assist you to reduce the data usage you send and receive.

Once you enable the metered connection, then it will restrict the apps from consuming extra internet bandwidth. The metered connection will do the following:
<ul>
 	<li>Priority updates will only be downloaded by Windows Update.</li>
 	<li>Offline files will not synchronize automatically.</li>
 	<li>Prevents unnecessary data transfers.</li>
 	<li>Apps that are downloading from Windows Store will be stopped and Start Screen tiles will prevent updating live data.</li>
</ul>
<h2 id="2">2 Simple Ways to Enable Metered Connection:</h2>
Setting a network connection as metered is almost the same in Windows 8, Windows 8.1, and Windows 10. The steps and screenshots in this post are taken on Windows 10 PC.
<h3>Via Settings:</h3>
<ol>
 	<li>To open the <strong>Settings</strong>, you have to press the <strong>Windows key + I</strong> keyboard shortcut.</li>
 	<li>In the<strong> Windows Settings</strong> screen, you have to click on <strong>Network &amp; Internet</strong>.

[caption id="attachment_2053" align="alignnone" width="1311"]<img class="size-full wp-image-2053" src="https://windowsdot.com/wp-content/uploads/2020/07/Network-Internet.png" alt="Network &amp; Internet" width="1311" height="762" /> Network &amp; Internet[/caption]</li>
 	<li>In the left pane, you have to click either <strong>Ethernet or Wifi</strong> as per your current network.

[caption id="attachment_2049" align="alignnone" width="1320"]<img class="size-full wp-image-2049" src="https://windowsdot.com/wp-content/uploads/2020/07/Choose-the-current-network.png" alt="Choose the current network" width="1320" height="764" /> Choose the current network[/caption]</li>
 	<li>After that, <strong>turn on</strong> the toggle switch of ‘<strong>Set as metered connection</strong>‘ so that it restricts the data usage.

[caption id="attachment_2057" align="alignnone" width="1315"]<img class="size-full wp-image-2057" src="https://windowsdot.com/wp-content/uploads/2020/07/Turn-on-metered-connection.png" alt="Turn on a metered connection" width="1315" height="764" /> Turn on a metered connection[/caption]</li>
</ol>
<h3>Via Registry Editor:</h3>
<ol>
 	<li>Open the <strong>Run box </strong>with the use of this shortcut <strong>Windows key + R</strong>.</li>
 	<li>After that, you have to type ‘<strong>regedit</strong>‘ and click the <strong>OK </strong>button.

[caption id="attachment_2054" align="alignnone" width="491"]<img class="size-full wp-image-2054" src="https://windowsdot.com/wp-content/uploads/2020/07/regedit.png" alt="regedit" width="491" height="300" /> regedit[/caption]</li>
 	<li>You have to navigate to the following path.<code>HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\NetworkList\DefaultMediaCost </code></li>
 	<li>In the right pane, you will see five DWORD values.</li>
 	<li>You have to double-click on <strong>Ethernet or Wifi </strong>as per your current network and set it value as <strong>2 </strong>and click<strong> OK</strong>.

[caption id="attachment_2056" align="alignnone" width="1097"]<img class="size-full wp-image-2056" src="https://windowsdot.com/wp-content/uploads/2020/07/Set-value-as-2.png" alt="Set value as 2" width="1097" height="706" /> Set value as 2[/caption]</li>
</ol>
<h2 id="3">How to Set Data Limit?</h2>
<ol>
 	<li>To open the <strong>Settings</strong>, you have to press the <strong>Windows key + I</strong> keyboard shortcut.</li>
 	<li>In the<strong> Windows Settings</strong> screen, you have to click on <strong>Network &amp; Internet</strong>.

[caption id="attachment_2053" align="alignnone" width="1311"]<img class="size-full wp-image-2053" src="https://windowsdot.com/wp-content/uploads/2020/07/Network-Internet.png" alt="Network &amp; Internet" width="1311" height="762" /> Network &amp; Internet[/caption]</li>
 	<li>It will open the <strong>Status</strong> settings by default.</li>
 	<li>You have to click the <strong>Data usage</strong> button that appears below your current network connection.

[caption id="attachment_2051" align="alignnone" width="1312"]<img class="size-full wp-image-2051" src="https://windowsdot.com/wp-content/uploads/2020/07/Data-usage.png" alt="Data usage" width="1312" height="767" /> Data usage[/caption]</li>
 	<li>Click the <strong>Enter limit</strong> button so you can set the <strong>data limit type, monthly reset date, data limit, and unit</strong>.</li>
 	<li>Once you set the values, you have to click the <strong>Save</strong> button.

[caption id="attachment_2055" align="alignnone" width="1323"]<img class="size-full wp-image-2055" src="https://windowsdot.com/wp-content/uploads/2020/07/Set-data-limit.png" alt="Set data limit" width="1323" height="764" /> Set data limit[/caption]</li>
</ol>
<h2 id="4">Track App Usage History in Metered Connection:</h2>
<ol>
 	<li>You have to press <strong>Ctrl + Shift + Esc</strong> shortcut to open the <strong>Task Manager</strong>.</li>
 	<li>Click the <strong>App history</strong> tab.</li>
 	<li>Now, you can see the data usage history of each app in a metered connection.

[caption id="attachment_2048" align="alignnone" width="923"]<img class="size-full wp-image-2048" src="https://windowsdot.com/wp-content/uploads/2020/07/App-history.png" alt="App history" width="923" height="619" /> App history[/caption]</li>
</ol>
<h2 id="5">Wind-up:</h2>
The three ways explained in this article to <strong>Enable Metered Connection in Windows 8/8.1/10 </strong>are simple and easy. You can follow any one of the ways to set a metered connection for Ethernet or Wifi so that you can save the internet bandwidth. <strong>Leave a reply</strong> below so it enhances our write-up. Check out more interesting articles in <a href="https://windowsdot.com/"><strong>Windows Dot</strong></a>.
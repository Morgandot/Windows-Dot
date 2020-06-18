---
ID: 276
post_title: 'Change Network Type in Windows 10!! (*3 Easy Methods*)'
author: Helena
post_excerpt: ""
layout: post
permalink: >
  https://windowsdot.com/change-network-type-in-windows-10-3-easy-methods/
published: true
post_date: 2020-05-29 09:08:41
---
In this guide, we will explain different methods with clear-cut steps to <strong>Change Network Type in Windows 10</strong>.
<ul class="toc">
 	<li><a href="#1">Network Type in Windows 10</a></li>
 	<li><a href="#2">Find the Current Network Type of your Connection</a></li>
 	<li><a href="#3">Change Network Type - Using Settings</a></li>
 	<li><a href="#4">Modify Network Type via Powershell</a></li>
 	<li><a href="#5">Change Network Type - Using Local Security Policy</a></li>
 	<li><a href="#6">Summary</a></li>
</ul>
<h2 id="1">Network Type in Windows 10:</h2>
When you connect to a wired or wireless network for the first time in your system, the network location is automatically set to 'Public' in Windows 10. This is considered to be the safest option as your device will not discoverable on the network and you cannot share printers and folders with that network.

Your Windows PC will get the highest protection from other devices on the same network because it treats that network as untrusted. If you want to change your network type from<strong> Public to Private or Private to Public</strong>, you can do it easily in less effort.
<ul>
 	<li><strong>Private network:</strong> For trustable networks like the network at home or work, you can use this type. Once you set your network as Private, your system is discoverable to other devices on the network. You can use your PC to share files and printers.</li>
 	<li><strong>Public network:</strong> When you connect to a Wi-Fi network available in public locations like a coffee shop, bus terminus, etc, you have to use this network type. Once you set your network as Public, your PC will be hidden from other devices on the network so you can't share files and printers.</li>
</ul>
<h2 id="2">Find the Current Network Type of your Connection:</h2>
<h3>Way 1 - Via Settings:</h3>
<ol>
 	<li>In order to open the <strong>Settings</strong>, you can make use of this keyboard combination <strong>Windows key + I</strong>.</li>
 	<li>You have to click on the <strong>Network &amp; Internet</strong>.

[caption id="attachment_295" align="alignnone" width="862"]<img class="size-full wp-image-295" src="https://windowsdot.com/wp-content/uploads/2020/05/nt1.png" alt="Network &amp; Internet" width="862" height="546" /> Network &amp; Internet[/caption]</li>
 	<li>Under <strong>Network status</strong>, you can check your current network type.

[caption id="attachment_296" align="alignnone" width="862"]<img class="size-full wp-image-296" src="https://windowsdot.com/wp-content/uploads/2020/05/nt2.png" alt="Network type" width="862" height="546" /> Network type[/caption]</li>
</ol>
<h3>Way 2 - Via Control Panel:</h3>
<ol>
 	<li>Go to the <strong>Start</strong> menu and search for <strong>'control panel'</strong> and hit Enter to open it.

[caption id="attachment_297" align="alignnone" width="880"]<img class="size-full wp-image-297" src="https://windowsdot.com/wp-content/uploads/2020/05/nt3.png" alt="Control Panel" width="880" height="680" /> Control Panel[/caption]</li>
 	<li>Now, click on <strong>'View network status and tasks'</strong> under <strong>Network and Internet</strong> option.

[caption id="attachment_298" align="alignnone" width="815"]<img class="size-full wp-image-298" src="https://windowsdot.com/wp-content/uploads/2020/05/nt4.png" alt="View network status and tasks" width="815" height="511" /> View network status and tasks[/caption]</li>
 	<li>You can view the network type of your current connection.

[caption id="attachment_299" align="alignnone" width="815"]<img class="size-full wp-image-299" src="https://windowsdot.com/wp-content/uploads/2020/05/nt5.png" alt="Network type" width="815" height="511" /> Network type[/caption]</li>
</ol>
<h2 id="3">1) Change Network Type - Using Settings:</h2>
<ol>
 	<li>Open the <strong>Settings</strong> via this keyboard shortcut <strong>Windows key + I</strong>.</li>
 	<li>Next, you have to click on the <strong>Network &amp; Internet</strong>.

[caption id="attachment_295" align="alignnone" width="862"]<img class="size-full wp-image-295" src="https://windowsdot.com/wp-content/uploads/2020/05/nt1.png" alt="Network &amp; Internet" width="862" height="546" /> Network &amp; Internet[/caption]</li>
 	<li>If you are using a wireless connection, you have to click on <strong>Wi-Fi </strong>in the left pane. Those who are using a wired connection, you have to go with the <strong>Ethernet</strong> option.

[caption id="attachment_300" align="alignnone" width="855"]<img class="size-full wp-image-300" src="https://windowsdot.com/wp-content/uploads/2020/05/nt6.png" alt="Wi-Fi" width="855" height="541" /> Wi-Fi[/caption]</li>
 	<li>Now, you have to click on your current network connection.

[caption id="attachment_301" align="alignnone" width="855"]<img class="size-full wp-image-301" src="https://windowsdot.com/wp-content/uploads/2020/05/nt7.png" alt="Choose current network" width="855" height="541" /> Choose current network[/caption]</li>
 	<li>Under <strong>Network profile</strong>, you can change your network type either <strong>Public or Private</strong>.

[caption id="attachment_302" align="alignnone" width="855"]<img class="size-full wp-image-302" src="https://windowsdot.com/wp-content/uploads/2020/05/nt8.png" alt="Change network type" width="855" height="541" /> Change network type[/caption]</li>
 	<li>Go back to the network status so you can see the change in network type.

[caption id="attachment_303" align="alignnone" width="855"]<img class="size-full wp-image-303" src="https://windowsdot.com/wp-content/uploads/2020/05/nt9.png" alt="Network type changed" width="855" height="541" /> Network type changed[/caption]</li>
</ol>
<h2 id="4">2) Modify Network Type via Powershell:</h2>
<ol>
 	<li>Go to the <strong>Start</strong> menu, search for <strong>'powershell' </strong>in the search box, right-click on the top result, and choose <strong>Run as administrator</strong> to open the Powershell. (If prompted, you have to press <strong>Yes</strong> to confirm the User Account Control window.)

[caption id="attachment_256" align="alignnone" width="879"]<img class="size-full wp-image-256" src="https://windowsdot.com/wp-content/uploads/2020/05/wu2.png" alt="Powershell" width="879" height="678" /> Powershell[/caption]</li>
 	<li>To view the list of current networks: <code>Get-NetConnectionProfile</code>

[caption id="attachment_304" align="alignnone" width="776"]<img class="size-full wp-image-304" src="https://windowsdot.com/wp-content/uploads/2020/05/nt10.png" alt="View networks" width="776" height="456" /> View networks[/caption]</li>
 	<li>You have to note down the <strong>Name and NetworkCategory</strong> of the network.</li>
 	<li>Switch your network type: <code>Set-NetConnectionProfile -Name "YourNetworkName" -NetworkCategory Public</code></li>
 	<li><strong>Note: </strong>Enter your network name for "YourNetworkName" and you can change the NetworkCategory either as Public or Private.

[caption id="attachment_305" align="alignnone" width="751"]<img class="size-full wp-image-305" src="https://windowsdot.com/wp-content/uploads/2020/05/nt11.png" alt="Change network type" width="751" height="387" /> Change network type[/caption]</li>
 	<li>That's it. Your network type will change immediately.</li>
</ol>
<h2 id="5">3) Change Network Type - Using Local Security Policy:</h2>
<ol>
 	<li>Using this shortcut <strong>Windows key + R, </strong>you can open the <strong>Run command</strong>.</li>
 	<li>Type <strong>'secpol.msc'</strong> and click <strong>OK</strong>. <code>secpol.msc</code>

[caption id="attachment_306" align="alignnone" width="428"]<img class="size-full wp-image-306" src="https://windowsdot.com/wp-content/uploads/2020/05/nt12.png" alt="Run command - secpol.msc" width="428" height="233" /> Run command - secpol.msc[/caption]</li>
 	<li>You have to select<strong> Network List Manager Policies</strong>.</li>
 	<li>Now, you can see the list of all the networks in the right pane.</li>
 	<li>You have to double-click on the network for which you want to change the network type.

[caption id="attachment_307" align="alignnone" width="825"]<img class="size-full wp-image-307" src="https://windowsdot.com/wp-content/uploads/2020/05/nt13.png" alt="Choose current network" width="825" height="489" /> Choose current network[/caption]</li>
 	<li>Click on the <strong>Network Location</strong> tab.</li>
 	<li>Under the <strong>Location type</strong>, you can choose the desired type and click <strong>Apply</strong> and then <strong>OK</strong>.

[caption id="attachment_308" align="alignnone" width="828"]<img class="size-full wp-image-308" src="https://windowsdot.com/wp-content/uploads/2020/05/nt14.png" alt="Change network type" width="828" height="502" /> Change network type[/caption]</li>
</ol>
<h2 id="6">Summary:</h2>
If you follow the steps described above, you can <strong>Change Network Type in Windows 10</strong> quickly. It is recommended to keep your network type as Public if you don't share anything on your network. Convey us your <strong>feedback</strong> about this article in the below section. Thanks for visiting <a href="https://windowsdot.com" class="ilgen">Windows Dot</a>.
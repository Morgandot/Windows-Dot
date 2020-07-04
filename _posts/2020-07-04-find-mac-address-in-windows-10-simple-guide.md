---
ID: 1853
post_title: 'Find Mac Address In Windows 10? {Simple Guide}'
author: Olivia
post_excerpt: ""
layout: post
permalink: >
  https://windowsdot.com/find-mac-address-in-windows-10-simple-guide/
published: true
post_date: 2020-07-04 05:17:22
---
In this article, we describe <strong>How to Find Mac Address In Windows 10</strong> using simple steps.
<ul class="toc">
 	<li><a href="#1">Media Access Control (MAC)</a></li>
 	<li><a href="#2">Locate MAC address using Command Prompt</a></li>
 	<li><a href="#3">Locate the MAC address of a specific network adapter</a></li>
 	<li><a href="#4">Address Resolution Protocol</a></li>
 	<li><a href="#5">Wireless Network Watcher</a></li>
 	<li><a href="#6">Summary</a></li>
</ul>
<h2 id="1">Media Access Control (MAC):</h2>
<ul>
 	<li>To identify the network uniquely, each network device has its <strong>unique ID.</strong></li>
 	<li><strong>MAC</strong> has identified a network component by their<strong> 12 digit hexadecimal number.</strong></li>
 	<li>In <strong>MAC</strong> each and every network has a unique number, it is not able to connect the two devices on the mac address.</li>
 	<li>It is also known as<strong> hardware address</strong> and easily be changed or spoofed with some temporary hacks.</li>
</ul>
<h2 id="2">Locate MAC address using Command Prompt:</h2>
To find the MAC address of all the network devices on your computer, just follow the below steps.
<ol>
 	<li>Make use of the<strong> Windows +X</strong> to open the <strong>Power Menu.</strong></li>
 	<li>Select the <strong>Command Prompt</strong> option.

[caption id="attachment_1854" align="aligncenter" width="297"]<img class="size-full wp-image-1854" src="https://windowsdot.com/wp-content/uploads/2020/07/E5CiHELiJY.png" alt="Command Prompt" width="297" height="529" /> Command Prompt[/caption]</li>
 	<li>Then in the command prompt window, <strong>type</strong> the following command.</li>
 	<li>Press <strong>Enter</strong>.
<pre><code>getmac</code></pre>
[caption id="attachment_1855" align="aligncenter" width="775"]<img class="size-full wp-image-1855" src="https://windowsdot.com/wp-content/uploads/2020/07/cmd_0cDsegJmcs.png" alt="Command " width="775" height="235" /> Command[/caption]</li>
 	<li>The above command gives you the<strong> list of all the network devices</strong> on your computer and their respective MAC addresses.</li>
 	<li>The below command shows you <strong>detail about each network</strong> device including their MAC addresses.</li>
 	<li><strong>Copy and Paste</strong> the following command in the command prompt window and press <strong>Enter</strong>.
<pre><code>ipconfig /all</code></pre>
[caption id="attachment_1857" align="aligncenter" width="737"]<img class="size-full wp-image-1857" src="https://windowsdot.com/wp-content/uploads/2020/07/cmd_JDDcogAYkR.png" alt="Command" width="737" height="640" /> Command[/caption]</li>
 	<li>That's all.</li>
</ol>
<h2 id="3">Locate the MAC address of a specific network adapter:</h2>
<ol>
 	<li>Make use of the shortcut <strong>Windows + R</strong> to open the<strong> Run command dialog box.</strong></li>
 	<li>Type<strong> control /name Microsoft.NetworkAndSharingCenter</strong> in the given space box of <strong>Open</strong> and click <strong>OK</strong>.

[caption id="attachment_1856" align="aligncenter" width="446"]<img class="size-full wp-image-1856" src="https://windowsdot.com/wp-content/uploads/2020/07/explorer_jGBsUnmPIp.png" alt="Run command " width="446" height="261" /> Run command[/caption]</li>
 	<li>In the left pane, click the<strong> Change adapter settings</strong> link.

[caption id="attachment_1860" align="aligncenter" width="1093"]<img class="size-full wp-image-1860" src="https://windowsdot.com/wp-content/uploads/2020/07/explorer_OccNqaxmJt.png" alt="Change Settings" width="1093" height="498" /> Change Settings[/caption]</li>
 	<li>Press <strong>Alt</strong> key the <strong>menu</strong> will open, in that click the <strong>View</strong> and select <strong>Details</strong>.

[caption id="attachment_1861" align="aligncenter" width="1092"]<img class="size-full wp-image-1861" src="https://windowsdot.com/wp-content/uploads/2020/07/explorer_drqYUbgUdP.png" alt="Menu" width="1092" height="552" /> Menu[/caption]</li>
 	<li><strong>Double-click</strong> on the <strong>active</strong> <strong>network</strong> <strong>adapter</strong> for which you want to know the <strong>MAC</strong> address.</li>
 	<li>Now, the <strong>Wi-Fi status window</strong> gets open, in that click the <strong>Details</strong> tab.

[caption id="attachment_1858" align="aligncenter" width="973"]<img class="size-full wp-image-1858" src="https://windowsdot.com/wp-content/uploads/2020/07/explorer_54UiRGOjRq.png" alt="Wi-Fi status" width="973" height="604" /> Wi-Fi status[/caption]</li>
 	<li>Now, you can find the <strong>MAC</strong> <strong>address</strong> with all other network details.</li>
</ol>
<h2 id="4">Address Resolution Protocol (ARP):</h2>
To locate the MAC address of a remote computer, <strong>ARP</strong> is the tool that resolves the IP and hardware addresses of the devices which are communicating with your computer.
<ol>
 	<li>Make use of the<strong> Windows +X</strong> to open the <strong>Power Menu.</strong></li>
 	<li>Select the<strong> Command Prompt</strong> option.

[caption id="attachment_1854" align="aligncenter" width="297"]<img class="size-full wp-image-1854" src="https://windowsdot.com/wp-content/uploads/2020/07/E5CiHELiJY.png" alt="Command Prompt" width="297" height="529" /> Command Prompt[/caption]</li>
 	<li>To <strong>replace</strong> the<strong> IP address with the IP address</strong> of the <strong>remote</strong> computer.</li>
 	<li>In the command prompt window, <strong>type</strong> the following command.</li>
 	<li>Press <strong>Enter</strong>.
<pre><code>ping 192.168.1.1</code></pre>
</li>
 	<li><strong>To list all devices</strong> communicating with your computer and to know the remote computer IP and its mac address.</li>
 	<li><strong>Copy and Paste</strong> the following command in the command prompt window and press <strong>Enter</strong>.
<pre><code>ARP -A</code></pre>
</li>
 	<li>That's all.</li>
</ol>
<h2 id="5">Wireless Network Watcher:</h2>
To<strong> get a list of all MAC addresses on your network</strong> then use this Wireless Network Watcher tool.
<ul>
 	<li><strong>Wireless Network Watcher</strong> gives a wealth of information about each network device including the<strong> IP address, device name, MAC address, and network adapter company.</strong></li>
 	<li>It is mainly for<strong> wireless networks</strong> but it displays<strong> all the devices over the network</strong> whether they are <strong>wired or wireless.</strong></li>
 	<li><strong>Refer to this page</strong> to know more details about<a href="https://www.nirsoft.net/utils/wireless_network_watcher.html"><strong> Wireless Network Watcher.</strong></a>

[caption id="attachment_1862" align="aligncenter" width="708"]<img class="size-full wp-image-1862" src="https://windowsdot.com/wp-content/uploads/2020/07/chrome_gJbSchoXM6.png" alt="Wireless Network Watcher" width="708" height="267" /> Wireless Network Watcher[/caption]</li>
</ul>
<h2 id="6">Summary:</h2>
This article gives you clarity on <strong>How to Find Mac Address In Windows 10.</strong> Share if any case of <strong>queries/suggestions</strong> in the below comment box and drop your<strong> worthwhile feedback.</strong>
<h2>Related Articles:</h2>
<ul>
 	<li><a href="https://windowsdot.com/how-to-view-command-prompt-history-in-windows/" rel="nofollow"><strong>View Command Prompt history in Windows 10</strong></a></li>
 	<li><a href="https://windowsdot.com/5-ways-to-check-who-is-on-my-wifi-how/" rel="nofollow"><strong>How to check who is on my Wi-Fi?</strong></a></li>
 	<li><a href="https://windowsdot.com/laptop-battery-drains-after-sleep-mode-simple-guide/" rel="nofollow"><strong>Laptop battery drains after sleep mode</strong></a></li>
</ul>
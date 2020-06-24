---
ID: 1474
post_title: >
  How to Check Public IP Address in
  Windows 10?
author: Olivia
post_excerpt: ""
layout: post
permalink: >
  https://windowsdot.com/how-to-check-public-ip-address-in-windows-10/
published: true
post_date: 2020-06-23 06:57:23
---
In this article, we describe <strong>How to check public IP Address using Command Line in Windows 10.</strong>
<ul class="toc">
 	<li><a href="#1">IP address</a></li>
 	<li><a href="#2">How to find my IP Address?</a></li>
 	<li><a href="#3">How to get my external IP address?</a></li>
 	<li><a href="#4">Using third-party services Get my public IP address</a></li>
 	<li><a href="#5">Summary</a></li>
</ul>
<h2 id="1">IP address:</h2>
It is used to identify a computer in a network. There are mainly two types of IP addresses,
<ol>
 	<li>Local Network (LAN) IP address or Local IP address or Private IP address or Internal IP address.</li>
 	<li>The Public IP address or External IP address.</li>
</ol>
<strong>Private IP address:</strong>
<ul>
 	<li>It is the one that is used within a <strong>local area network.</strong></li>
 	<li>This <strong>IP</strong> is used to identify the computer within the LAN.</li>
 	<li>This<strong> private IP</strong> can’t be accessed directly from the Internet.</li>
</ul>
<strong>Public IP address:</strong>
<ul>
 	<li>It is the one which is provided by your <strong>Internet Service Provider (ISP).</strong></li>
 	<li><strong>Multiple computers</strong> can have a single public IP if a network is set up using the technique called NAT (Network Address Translation).</li>
 	<li>It is normally not provided free of cost, people use a mixture of<strong> private IP addresses.</strong></li>
 	<li>That connects to a single <strong>public IP address</strong> to run the Internet on every network computer in a private network.</li>
</ul>
<h2 id="2">How to find my (LAN) IP Address?</h2>
When you want to know about the network information of your computer, you can get it from multiple locations. Here, some locations are listed down.
<ol>
 	<li>Using <strong>Windows Settings</strong>, then click the <strong>Network &amp; Internet</strong> option.</li>
 	<li>Then using the <strong>Control Panel</strong>, click on the <strong>Network and Sharing Center</strong> option.</li>
 	<li>While using the <strong>Task Manager</strong>, select the <strong>Performance</strong> tab.</li>
</ol>
Follow the below steps to get all the network-related information using Command Prompt:
<ul>
 	<li>Make use of the shortcut <strong>Windows + R</strong> to open the Run command dialog box.</li>
 	<li>Then, type <strong>cmd</strong> in the given space box of <strong>Open</strong> and click <strong>OK</strong>.

[caption id="attachment_1482" align="aligncenter" width="445"]<img class="size-full wp-image-1482" src="https://windowsdot.com/wp-content/uploads/2020/06/explorer_Fvxu3N3teq.png" alt="The run command dialog box" width="445" height="255" /> The run command dialog box[/caption]</li>
 	<li>Now, in the Command Prompt window, type the following command for IP address lookup.
<pre><code>ipconfig</code></pre>
</li>
 	<li>Press <strong>Enter</strong>.

[caption id="attachment_1480" align="aligncenter" width="776"]<img class="size-full wp-image-1480" src="https://windowsdot.com/wp-content/uploads/2020/06/chrome_1FF92Tovst.png" alt="Command Prompt" width="776" height="600" /> Command Prompt[/caption]

<strong>Image Source:</strong> <em>itechtics.com</em></li>
 	<li>The summary of all the connected network interfaces including their assigned <strong>IP addresses</strong> is shown when using the above command.</li>
 	<li>When you want <strong>complete information of all the network</strong> interfaces on your computer.</li>
 	<li><strong>Copy and Paste</strong> the below command and press Enter.
<pre><code>ipconfig /all</code></pre>
</li>
 	<li>That's all.</li>
</ul>
<h2 id="3">How to get my external IP address?</h2>
<strong>Note:</strong> You need to be connected to the Internet for using the below-mentioned commands and services.
<h3>Command Prompt:</h3>
<ul>
 	<li>Get the external IP information using the <strong>command nslookup</strong> and the <strong>OpenDNS service.</strong></li>
 	<li>Make use of the shortcut <strong>Windows + R</strong> to open the Run command dialog box.</li>
 	<li>Then, type <strong>cmd</strong> in the given space box of <strong>Open</strong> and click <strong>OK</strong>.

[caption id="attachment_1482" align="aligncenter" width="445"]<img class="size-full wp-image-1482" src="https://windowsdot.com/wp-content/uploads/2020/06/explorer_Fvxu3N3teq.png" alt="The run command dialog box" width="445" height="255" /> The run command dialog box[/caption]</li>
 	<li>To get your external IP address, <strong>copy and paste</strong> the below command in your <strong>Command Prompt</strong> window and press <strong>enter</strong>.
<pre><code>nslookup myip.opendns.com resolver1.opendns.com</code></pre>
[caption id="attachment_1481" align="aligncenter" width="645"]<img class="size-full wp-image-1481" src="https://windowsdot.com/wp-content/uploads/2020/06/cmd_Y1a4n5dqJK.png" alt="Command Prompt" width="645" height="337" /> Command Prompt[/caption]</li>
</ul>
<h3>PowerShell:</h3>
<ul>
 	<li>To get the external IP, you can also use the <strong>PowerShell</strong> command.</li>
 	<li>Make use of the shortcut <strong>Windows + R</strong> to open the Run command dialog box.</li>
 	<li>Then, type <strong>powershell</strong> in the given space box of <strong>Open</strong> and click <strong>OK</strong>.

[caption id="attachment_1478" align="aligncenter" width="450"]<img class="size-full wp-image-1478" src="https://windowsdot.com/wp-content/uploads/2020/06/explorer_ddBQxkVZ4n.png" alt="The run command dialog box" width="450" height="262" /> The run command dialog box[/caption]</li>
 	<li>Now, in the <strong>PowerShell</strong> window, type the following command.</li>
 	<li>Press <strong>Enter</strong>.
<pre><code>(Invoke-WebRequest ifconfig.me/ip).Content.Trim()</code></pre>
[caption id="attachment_1479" align="aligncenter" width="1063"]<img class="size-full wp-image-1479" src="https://windowsdot.com/wp-content/uploads/2020/06/chrome_evJ1CiQ7NZ.png" alt="PowerShell" width="1063" height="297" /> PowerShell[/caption]</li>
</ul>
<h2 id="4">Using third-party services Get my public IP address:</h2>
Here, a list of third-party services to get my public IP address.

<strong>1) Google.com:</strong>
<ul>
 	<li>It is used to search for my IP.</li>
 	<li>Google will show you the<strong> public IP</strong> of your device.</li>
 	<li>Use this link to download <a href="https://www.google.com/search?q=my+ip"><strong>Google.com</strong></a>.</li>
</ul>
<strong>2) Whatismyip.com:</strong>
<ul>
 	<li>It shows a wealth of information about the network including the <strong>external IP.</strong></li>
 	<li>What is my IP command line is also available through their <strong>API service.</strong></li>
 	<li>Use this link to download<a href="https://www.whatismyip.com/"><strong> Whatismyip.com</strong></a>.</li>
</ul>
<strong>3) Myexternalip.com:</strong>
<ul>
 	<li>It simply outputs the<strong> public IP</strong> in plain text.</li>
 	<li>Use this link to download <a href="https://myexternalip.com/"><strong>Myexternalip.com</strong></a>.</li>
</ul>
<strong>4) Icanhazip.com:</strong>
<ul>
 	<li>It outputs <strong>public IP</strong> in text format.</li>
 	<li>Use this link to download <a href="https://icanhazip.com/"><strong>Icanhazip.com</strong></a>.</li>
</ul>
<strong>5) ifconfig.me:</strong>
<ul>
 	<li>It displays a wealth of information including<strong> public IP,</strong> user agent, port used, language, etc.</li>
 	<li>Use this link to download <a href="https://ifconfig.me/"><strong>ifconfig.me</strong></a>.</li>
</ul>
<h2 id="5">Summary:</h2>
That’s it. Now, we have learned <strong>How to check public IP Address using Command Line in Windows 10.</strong> Kindly, share your valuable comments to enhance our write-up.
---
ID: 1326
post_title: 'Check if a Remote Network Port is Open!! {Quick Guide}'
author: Olivia
post_excerpt: ""
layout: post
permalink: >
  https://windowsdot.com/check-if-a-remote-network-port-is-open-quick-guide/
published: true
post_date: 2020-06-21 07:43:15
---
In this article, we describe <strong>How to check if a Remote Network Port is open</strong> in simple steps.
<ul class="toc">
 	<li><a href="#1">Install Telnet in Windows 10</a></li>
 	<li><a href="#2">Check whether the port is open or not using Command Prompt</a></li>
 	<li><a href="#3">Check open port using PowerShell</a></li>
 	<li><a href="#4">Verdict</a></li>
</ul>
<h2 id="1">Install Telnet in Windows 10:</h2>
Follow the below steps to install.
<ul>
 	<li>Go to the <strong>start menu.</strong></li>
 	<li>In the search column type as <strong>Command Prompt.</strong></li>
 	<li>Then<strong> right-click</strong> on the Command Prompt and select <strong>Run as Administrator.</strong>

[caption id="attachment_647" align="aligncenter" width="485"]<img class="size-full wp-image-647" src="https://windowsdot.com/wp-content/uploads/2020/06/Screenshot_5-1.png" alt="Start Menu" width="485" height="772" /> Start Menu[/caption]</li>
 	<li><strong>Copy and paste</strong> the below command in the command prompt window.
<pre><code>pkgmgr /iu:”TelnetClient”</code></pre>
[caption id="attachment_1331" align="aligncenter" width="1100"]<img class="size-full wp-image-1331" src="https://windowsdot.com/wp-content/uploads/2020/06/cmd_o7AxIcm9Rn.png" alt="Command" width="1100" height="639" /> Command[/caption]</li>
 	<li>Then, Go running the <strong>telnet</strong>.</li>
 	<li>That's all.</li>
</ul>
<h2 id="2">Check whether the port is open or not using Command Prompt:</h2>
Follow the below steps to check the network port.
<ul>
 	<li>First, <strong>open the telnet</strong> by using the above steps.</li>
 	<li>If any <strong>issues</strong> occur then type the following command.
<pre><code>open google.com 80
</code></pre>
</li>
 	<li>The<strong> google.com</strong> is the host you want to test.</li>
 	<li>There, you can also put an<strong> IP address</strong> instead of the name.</li>
 	<li>Then,<strong> 80 is the port number</strong> that you want to probe.</li>
 	<li><strong>Replace</strong> <strong>80</strong> with your desired port number.</li>
 	<li>If you receive<strong> Press any key to continue</strong> prompt, this means that the port is open and responding to telnet.</li>
 	<li>If you receive<strong> Could not open connection or a blank screen</strong> with the blinking cursor, this means the port is closed.</li>
 	<li>If you receive<strong> Connection to host lost,</strong> this means that the port is open but the host is not accepting new connections.</li>
 	<li>That's all.</li>
</ul>
<h2 id="3">Check open port using PowerShell:</h2>
Follow the below steps to check open port using PowerShell.
<ul>
 	<li>Go to the<strong> start menu.</strong></li>
 	<li>In the search column type as <strong>PowerShell.</strong></li>
 	<li>Then <strong>right-click</strong> on the PowerShell and select <strong>Run as Administrator.</strong>

[caption id="attachment_1333" align="aligncenter" width="481"]<img class="size-full wp-image-1333" src="https://windowsdot.com/wp-content/uploads/2020/06/Screenshot_8-9.png" alt="Start Menu" width="481" height="768" /> Start Menu[/caption]</li>
 	<li>Then, <strong>run</strong> the following command.
<pre><code>tnc google.com -port 80</code></pre>
[caption id="attachment_1330" align="aligncenter" width="558"]<img class="size-full wp-image-1330" src="https://windowsdot.com/wp-content/uploads/2020/06/chrome_YTSWPIVjAe.png" alt="Command" width="558" height="290" /> Command[/caption]</li>
 	<li>Here, the <strong>tns</strong> is abbreviated as <strong>Test-NetworkConnection</strong> command.</li>
 	<li>The <strong>google.com</strong> is the hostname.</li>
 	<li>Then, you can also put an <strong>IP address</strong> instead of the hostname.</li>
 	<li>Now, you can specify the<strong> port number</strong> using the <strong>-port switch</strong> at the end of the tnc command.</li>
 	<li>The<strong> TNC command</strong> will give you basic information about the network connection like computer name, IP address, Interface through which you are connecting, source IP, whether the ping is successful or not, Ping reply time, and finally TcpTestSucceeded.</li>
 	<li><strong>TcpTestSucceeded</strong> will give you True if the port is open and false if the port is closed.</li>
 	<li>These <strong>commands and techniques</strong> are very useful when you are troubleshooting a network.</li>
 	<li>That's all.</li>
</ul>
<strong>Image Source:</strong> <em>itechtics.com</em>
<h2 id="4">Verdict:</h2>
This tutorial guided you on <strong>How to check if a Remote Network Port is open</strong>. Kindly, Don’t forget to share your <strong>comments</strong> in the below box and drop your worthwhile feedback.
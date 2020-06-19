---
ID: 1282
post_title: 'How to Check Windows 10 Uptime? {4 Quick Ways}'
author: Helena
post_excerpt: ""
layout: post
permalink: >
  https://windowsdot.com/how-to-check-windows-10-uptime-4-quick-ways/
published: true
post_date: 2020-06-19 07:29:03
---
If you are curious to know your system uptime in Windows 10? In this tutorial, you will learn four diverse ways on how to check <strong>Windows 10 Uptime</strong>.
<ul class="toc">
 	<li><a href="#1">System Uptime in Windows 10</a></li>
 	<li><a href="#2">Check Uptime via Task Manager</a></li>
 	<li><a href="#3">Find Uptime - Using Network Adapter</a></li>
 	<li><a href="#4">Check Uptime via Command Prompt</a></li>
 	<li><a href="#5">See Uptime - Using PowerShell</a></li>
 	<li><a href="#6">Closure</a></li>
</ul>
<h2 id="1">System Uptime in Windows 10:</h2>
Uptime is used as a measure of computer OS stability or reliability. The system uptime will let you know how long your device has been up and running since the last time shutdown or restart. It will show useful information and it assists you to troubleshoot your system properly.

This is mostly used by network admins for troubleshooting several issues on a computer. For example, if they want to see if a reboot has been applied to the device recently, then they will check this system or Windows uptime.
<h2 id="2">Way 1 - Check Uptime via Task Manager:</h2>
<ol>
 	<li>Use this shortcut <strong>Ctrl + Shift + Esc</strong> to open the <strong>Task Manager</strong>.</li>
 	<li>In the Task Manager window, you have to click the <strong>Performance</strong> tab.</li>
 	<li>Now, you can see the <strong>Uptime</strong> in <strong>days: hours: minutes: seconds</strong> in real-time in the <strong>CPU</strong> section.

[caption id="attachment_1291" align="alignnone" width="704"]<img class="size-full wp-image-1291" src="https://windowsdot.com/wp-content/uploads/2020/06/up1.png" alt="Task Manager" width="704" height="633" /> Task Manager[/caption]</li>
</ol>
<h2 id="3">Way 2 - Find Uptime - Using Network Adapter:</h2>
<ol>
 	<li>In the Taskbar, you have to right-click on the network icon and choose <strong>Open Network &amp; Internet settings</strong>.

[caption id="attachment_1292" align="alignnone" width="605"]<img class="size-full wp-image-1292" src="https://windowsdot.com/wp-content/uploads/2020/06/up2.png" alt="Open Network &amp; Internet settings" width="605" height="291" /> Open Network &amp; Internet settings[/caption]</li>
 	<li>It will open the Status settings and in that, you have to click on the <strong>Network and Sharing Center</strong> link.

[caption id="attachment_1293" align="alignnone" width="843"]<img class="size-full wp-image-1293" src="https://windowsdot.com/wp-content/uploads/2020/06/up3.png" alt="Network and sharing center" width="843" height="515" /> Network and sharing center[/caption]</li>
 	<li>You have to click on the current network's link so it will show the network uptime next to the <strong>Duration</strong> field.

[caption id="attachment_1294" align="alignnone" width="745"]<img class="size-full wp-image-1294" src="https://windowsdot.com/wp-content/uploads/2020/06/up4.png" alt="Click Current Network" width="745" height="458" /> Click Current Network[/caption]

[caption id="attachment_1295" align="alignnone" width="404"]<img class="size-full wp-image-1295" src="https://windowsdot.com/wp-content/uploads/2020/06/up5.png" alt="Network Uptime" width="404" height="493" /> Network Uptime[/caption]</li>
 	<li>If your device goes to hibernate or sleep mode, this network uptime will reset. This only works if your network is always connected.</li>
</ol>
<h2 id="4">Way 3 - Check Uptime via Command Prompt:</h2>
<strong>Command 1: Systeminfo</strong>
<ol>
 	<li>Open the <strong>Run command</strong> with the help of this keyboard shortcut <strong>Windows key + R</strong>. Then, you have to type 'cmd' and click <strong>OK</strong> to launch the <strong>Command Prompt</strong>.</li>
 	<li>Type the below command and hit <strong>Enter</strong>. <code>systeminfo | find “System Boot Time”</code>

[caption id="attachment_1296" align="alignnone" width="705"]<img class="size-full wp-image-1296" src="https://windowsdot.com/wp-content/uploads/2020/06/up6.png" alt="Command 1" width="705" height="381" /> Command 1[/caption]</li>
</ol>
<strong>Command 2: WMIC</strong>
<ol>
 	<li>Open the <strong>Run command</strong> with the help of this keyboard shortcut <strong>Windows key + R</strong>. Then, you have to type 'cmd' and click <strong>OK</strong> to launch the <strong>Command Prompt</strong>.</li>
 	<li>Type the below command and hit <strong>Enter</strong>. <code>wmic path Win32_OperatingSystem get LastBootUpTime</code>

[caption id="attachment_1297" align="alignnone" width="703"]<img class="size-full wp-image-1297" src="https://windowsdot.com/wp-content/uploads/2020/06/up7.png" alt="Command 2" width="703" height="369" /> Command 2[/caption]</li>
</ol>
<strong>Command 3: Net Statistics</strong>
<ol>
 	<li>Open the <strong>Run command</strong> with the help of this keyboard shortcut <strong>Windows key + R</strong>. Then, you have to type 'cmd' and click <strong>OK</strong> to launch the <strong>Command Prompt</strong>.</li>
 	<li>Type the below command and hit <strong>Enter</strong>. <code>net statistics workstation</code>

[caption id="attachment_1298" align="alignnone" width="737"]<img class="size-full wp-image-1298" src="https://windowsdot.com/wp-content/uploads/2020/06/up8.png" alt="Command 3" width="737" height="415" /> Command 3[/caption]</li>
</ol>
<h2 id="5">Way 4 - See Uptime - Using Powershell:</h2>
<ol>
 	<li>Go to the <strong>Start</strong> menu and type '<strong>powershell</strong>' in the search box and hit <strong>Enter</strong>.</li>
 	<li>Now, you have to type the below command and hit <strong>Enter</strong>. <code>(get-date) – (gcim Win32_OperatingSystem).LastBootUpTime</code>

[caption id="attachment_1299" align="alignnone" width="822"]<img class="size-full wp-image-1299" src="https://windowsdot.com/wp-content/uploads/2020/06/up9.png" alt="PowerShell" width="822" height="419" /> PowerShell[/caption]</li>
</ol>
<blockquote>If you are using PowerShell 6, you can run this command. <code>Get-Uptime -Since</code></blockquote>
<h2 id="6">Closure:</h2>
That's it. Now, we have learned how to check system uptime in four different ways. It's easy, right? We hope that this article on how to check<b> Windows 10 Uptime </b>helped you a lot. Kindly, share your valuable comments to enhance our write-up. Thanks for visiting Windows Dot.
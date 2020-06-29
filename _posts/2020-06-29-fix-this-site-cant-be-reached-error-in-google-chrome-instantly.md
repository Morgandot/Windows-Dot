---
ID: 1674
post_title: 'Fix &#8216;This Site Can&#8217;t Be Reached&#8217; Error in Google Chrome!! [Instantly]'
author: Helena
post_excerpt: ""
layout: post
permalink: >
  https://windowsdot.com/fix-this-site-cant-be-reached-error-in-google-chrome-instantly/
published: true
post_date: 2020-06-29 07:57:14
---
This guide lets you fix<strong> This Site Can't Be Reached </strong>error in Google Chrome<strong> </strong>easily.
<ul class="toc">
 	<li><a href="#1">This Site Can't Be Reached Error in Chrome</a></li>
 	<li><a href="#2">Clear your Browser Cache</a></li>
 	<li><a href="#3">Reset Google Chrome</a></li>
 	<li><a href="#4">Disable Experimental QUIC Protocol</a></li>
 	<li><a href="#5">Reset TCP/IP</a></li>
 	<li><a href="#6">Restart DNS Client</a></li>
 	<li><a href="#7">Bottom Line</a></li>
</ul>
<h2 id="1">This Site Can't Be Reached Error in Chrome:</h2>
'This Site Can't Be Reached' is a common error that Chrome users face when trying to open any required webpage. This error comes with different error codes such as DNS_PROBE_FINISHED_NXDOMAIN, Server DNS address could not be found, etc.

The causes of this error may be Chrome isn't updated one, DNS server isn't responding, TLS version isn't appropriate or any other issue. We come with 5 effective solutions that let you fix the error easily.
<h2 id="2">1) Clear your Browser Cache:</h2>
<ol>
 	<li>To do this, you have to open your Google Chrome browser and click the <strong>three dots</strong> in the top right-hand corner.</li>
 	<li>Navigate to <strong>More tools</strong> -&gt; <strong>Clear browsing data</strong>. Alternatively, you can click the <strong>Ctrl + Shift + Delete</strong> shortcut.

[caption id="attachment_1680" align="alignnone" width="1920"]<img class="size-full wp-image-1680" src="https://windowsdot.com/wp-content/uploads/2020/06/Clear-browsing-data.png" alt="Clear browsing data" width="1920" height="1020" /> Clear browsing data[/caption]</li>
 	<li>Click <strong>Advanced</strong> and choose '<strong>All time</strong>' in the<strong> Time range. </strong>You have to select all check-boxes and click the <strong>Clear data</strong> button so it will delete your browsing history, cookies, saved passwords, etc.

[caption id="attachment_1681" align="alignnone" width="1920"]<img class="size-full wp-image-1681" src="https://windowsdot.com/wp-content/uploads/2020/06/Clear-data.png" alt="Clear data" width="1920" height="1020" /> Clear data[/caption]</li>
 	<li>Try to reload the webpage that shows the error and see if the problem has cleared up.</li>
</ol>
<h2 id="3">2) Reset Google Chrome:</h2>
<ol>
 	<li>You have to open your Google Chrome browser and click the <strong>three dots</strong> in the top right-hand corner.</li>
 	<li>Choose the <strong>Settings</strong> option.

[caption id="attachment_1687" align="alignnone" width="1920"]<img class="size-full wp-image-1687" src="https://windowsdot.com/wp-content/uploads/2020/06/Settings.png" alt="Settings" width="1920" height="1020" /> Settings[/caption]</li>
 	<li>In the left pane, you can see the <strong>Advanced</strong> option.</li>
 	<li>Click the drop-down arrow and choose <strong>Reset and clean up</strong> option.

[caption id="attachment_1685" align="alignnone" width="1920"]<img class="size-full wp-image-1685" src="https://windowsdot.com/wp-content/uploads/2020/06/Reset-and-clean-up.png" alt="Reset and clean up" width="1920" height="1020" /> Reset and clean up[/caption]</li>
 	<li>After that, try to reload the webpage that shows the error and see if the problem has cleared up.</li>
</ol>
<h2 id="4">3) Disable Experimental QUIC Protocol:</h2>
QUIC (Quick UDP Internet Connection) is the protocol that is designed to offer security protection like TLS/SSL with transport latency and reduced connection. If you disable this protocol, you can open the required webpages without getting any error.
<ol>
 	<li>Open the Google Chrome browser, type '<strong>chrome://flags</strong>' in the address bar.</li>
 	<li>In the search box, you can type 'QUIC' so it will filter the results.</li>
 	<li>You can find the '<strong>Experimental QUIC Protocol</strong>' option.</li>
 	<li>Choose the option <strong>Disabled</strong> from the drop-down menu.

[caption id="attachment_1683" align="alignnone" width="1920"]<img class="size-full wp-image-1683" src="https://windowsdot.com/wp-content/uploads/2020/06/Disabled-QUIC-Protocol.png" alt="Disabled QUIC Protocol" width="1920" height="1020" /> Disabled QUIC Protocol[/caption]</li>
 	<li>Then, you have to close the browser and open it again.</li>
 	<li>Now, you can see that the error gets fixed and it will redirect you to the required webpage.</li>
</ol>
<h2 id="5">4) Reset TCP/IP:</h2>
<ol>
 	<li>Go to the <strong>Start</strong> menu.</li>
 	<li>In the search box, you have to type <strong>'cmd'</strong>. Then, you have to right-click on the top result and choose <strong>Run as administrator</strong>. (If prompted, you have to press <strong>'Yes'</strong> in the User Account Control window.)

[caption id="attachment_1682" align="alignnone" width="1318"]<img class="size-full wp-image-1682" src="https://windowsdot.com/wp-content/uploads/2020/06/Command-Prompt-2.png" alt="Command Prompt" width="1318" height="882" /> Command Prompt[/caption]</li>
 	<li>Now, you have to run the following commands one by one and hit <strong>Enter</strong> after each command: <code>Ipconfig /release</code> <code>Ipconfig /all</code> <code>Ipconfig /flushdns</code> <code>Ipconfig /renew</code> <code>Netsh int ip set dns</code> <code>Netsh winsock reset</code></li>
 	<li>Close the command prompt window and restart your system to apply the changes.</li>
</ol>
<h2 id="6">5) Restart DNS Client:</h2>
<ol>
 	<li>You have to press <strong>Windows key + R</strong> to open the <strong>Run Command</strong>.</li>
 	<li>Enter the below command and click <strong>OK</strong>.<code>services.msc</code>

[caption id="attachment_1686" align="alignnone" width="599"]<img class="size-full wp-image-1686" src="https://windowsdot.com/wp-content/uploads/2020/06/services.msc_.png" alt="services.msc" width="599" height="363" /> services.msc[/caption]</li>
 	<li>In the <strong>Services</strong> window, you have to scroll down and locate the <strong>DNS Client </strong>service.

[caption id="attachment_1684" align="alignnone" width="1256"]<img class="size-full wp-image-1684" src="https://windowsdot.com/wp-content/uploads/2020/06/DNS-Client.png" alt="DNS Client" width="1256" height="866" /> DNS Client[/caption]</li>
 	<li>You have to right-click on it and navigate to <strong>Restart</strong> option.</li>
 	<li>Close all the applications and restart your PC.</li>
</ol>
<h2 id="7">Bottom Line:</h2>
We hope that this guide assisted you to fix<strong> This Site Can't Be Reached </strong>error in Google Chrome. The steps explained in this article let you understand the solutions simpler. Kindly share your valuable <strong>comments/feedback</strong> in the below section. Check out more interesting articles in <a href="https://windowsdot.com/"><strong>Windows Dot</strong></a>.
<h2>Keep Reading:</h2>
<ul>
 	<li><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsdot.com/how-to-save-google-chrome-history-2-ways/" target="_blank" rel="noopener noreferrer">How to Save Google Chrome History?- {2 Ways}</a></li>
 	<li><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsdot.com/simple-guide-create-an-invisible-folder-on-windows-10/" target="_blank" rel="noopener noreferrer">{Simple Guide} Create an Invisible Folder on Windows 10!!</a></li>
 	<li><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsdot.com/how-to-use-chrome-remote-desktop-as-teamviewer-quickly/" target="_blank" rel="noopener noreferrer">How to Use Chrome Remote Desktop as TeamViewer? [Quickly]</a></li>
 	<li><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsdot.com/fix-keyboard-not-working-after-update-on-windows-10/" target="_blank" rel="noopener noreferrer">Fix Keyboard Not Working After Update on Windows 10!!</a></li>
</ul>
---
ID: 1530
post_title: 'Disable Windows Defender in Windows 10!! (*5 Simple Ways*)'
author: Helena
post_excerpt: ""
layout: post
permalink: >
  https://windowsdot.com/disable-windows-defender-in-windows-10-5-simple-ways/
published: true
post_date: 2020-06-24 06:46:08
---
Here, we come up with an interesting article on how to <strong>Disable Windows Defender in Windows 10</strong>.
<ul class="toc">
 	<li><a href="#1">Disable Windows Defender</a></li>
 	<li><a href="#2">Using PowerShell to Disable Windows Defender</a></li>
 	<li><a href="#3">How to Disable Windows Defender via Command Prompt?</a></li>
 	<li><a href="#4">Disable it Using Settings</a></li>
 	<li><a href="#5">Use Group Policy Editor to Disable it</a></li>
 	<li><a href="#6">Disable via Registry Editor</a></li>
 	<li><a href="#7">A Short Synopsis</a></li>
</ul>
<h2 id="1">Disable Windows Defender:</h2>
Windows Defender is easy to use and pre-installed security software in Windows 10. It does not need any manual configuration and enabled by default. There comes a situation when you want to disable it for installing any other applications in your system.

This security software will not disable itself when you want to install other antivirus programs for securing your server or system. You can choose any one of the methods illustrated below to disable this software.
<h2 id="2">1) Using PowerShell to Disable Windows Defender:</h2>
<ol>
 	<li>Go to the <strong>Start</strong> menu and type '<strong>powershell</strong>' in the search box. Right-click on the top result and choose <strong>Run as administrator</strong>.

[caption id="attachment_1552" align="alignnone" width="1321"]<img class="size-full wp-image-1552" src="https://windowsdot.com/wp-content/uploads/2020/06/wdd1.png" alt="PowerShell" width="1321" height="884" /> PowerShell[/caption]</li>
 	<li>Now, you have to type the below command and hit <strong>Enter </strong>to disable real-time monitoring. <code>Set-MpPreference -DisableRealtimeMonitoring $true</code>

[caption id="attachment_1539" align="alignnone" width="1164"]<img class="size-full wp-image-1539" src="https://windowsdot.com/wp-content/uploads/2020/06/wd1.png" alt="PowerShell - Command" width="1164" height="588" /> PowerShell - Command[/caption]</li>
 	<li>If you want to remove it completely, you have to run this command and hit <strong>Enter</strong>. <code>Uninstall-WindowsFeature -Name Windows-Defender</code>

[caption id="attachment_1540" align="alignnone" width="1157"]<img class="size-full wp-image-1540" src="https://windowsdot.com/wp-content/uploads/2020/06/wd2.png" alt="PowerShell - Command" width="1157" height="584" /> PowerShell - Command[/caption]</li>
</ol>
<h2 id="3">2) How to Disable Windows Defender via Command Prompt?</h2>
<ol>
 	<li>Click on the <strong>Windows key</strong> to open the <strong>Start</strong> menu.</li>
 	<li>In the search box, you have to type <strong>‘cmd’</strong>. Right-click on the result and choose <strong>Run as administrator</strong>. (If prompted, you have to press <strong>‘Yes’</strong> in the User Account Control window.)

[caption id="attachment_1393" align="alignnone" width="1319"]<img class="size-full wp-image-1393" src="https://windowsdot.com/wp-content/uploads/2020/06/wi1.png" alt="Command Prompt" width="1319" height="881" /> Command Prompt[/caption]</li>
 	<li>To disable the software: <code>sc stop WinDefend</code>

[caption id="attachment_1541" align="alignnone" width="1139"]<img class="size-full wp-image-1541" src="https://windowsdot.com/wp-content/uploads/2020/06/wd3.png" alt="Command Prompt - Command" width="1139" height="609" /> Command Prompt - Command[/caption]</li>
 	<li>To disable it permanently: <code>sc config WinDefend start= disabled</code> <code>sc stop WinDefend</code></li>
 	<li>Check the current state: <code>sc query WinDefend</code>

[caption id="attachment_1542" align="alignnone" width="1146"]<img class="size-full wp-image-1542" src="https://windowsdot.com/wp-content/uploads/2020/06/wd4.png" alt="Command Prompt - Command" width="1146" height="614" /> Command Prompt - Command[/caption]</li>
</ol>
<p id="note"><strong>Note: </strong>Don't forget to hit <strong>Enter</strong> at the end of every command.</p>

<h2 id="4">3) Disable it Using Settings:</h2>
<ol>
 	<li>Use this shortcut <strong>Windows key + I</strong> to open the <strong>Settings</strong>.</li>
 	<li>You have to click the <strong>Update &amp; Security</strong> option.

[caption id="attachment_1543" align="alignnone" width="1298"]<img class="size-full wp-image-1543" src="https://windowsdot.com/wp-content/uploads/2020/06/wd5.png" alt="Update &amp; Security" width="1298" height="799" /> Update &amp; Security[/caption]</li>
 	<li>In the left pane, you have to tap on <strong>Windows Security</strong>.

[caption id="attachment_1544" align="alignnone" width="1318"]<img class="size-full wp-image-1544" src="https://windowsdot.com/wp-content/uploads/2020/06/wd6.png" alt="Windows Security" width="1318" height="818" /> Windows Security[/caption]</li>
 	<li>Under <strong>Protections areas</strong>, you have to click on the <strong>Virus &amp; threat protection</strong>.

[caption id="attachment_1545" align="alignnone" width="1319"]<img class="size-full wp-image-1545" src="https://windowsdot.com/wp-content/uploads/2020/06/wd7.png" alt="Virus &amp; threat protection" width="1319" height="827" /> Virus &amp; threat protection[/caption]</li>
 	<li>Now, you have to click on <strong>Manage settings</strong> link under <strong>Virus &amp; threat protection settings</strong>.

[caption id="attachment_1546" align="alignnone" width="1029"]<img class="size-full wp-image-1546" src="https://windowsdot.com/wp-content/uploads/2020/06/wd8.png" alt="Manage settings" width="1029" height="816" /> Manage settings[/caption]</li>
 	<li><strong>Turn off</strong> the toggle switch of <strong>Real-time protection</strong>.

[caption id="attachment_1547" align="alignnone" width="1037"]<img class="size-full wp-image-1547" src="https://windowsdot.com/wp-content/uploads/2020/06/wd9.png" alt="Turn off" width="1037" height="821" /> Turn off[/caption]</li>
</ol>
<h2 id="5">4) Use Group Policy Editor to Disable it:</h2>
<ol>
 	<li>First, you have to open the <strong>Run box </strong>by using this shortcut <strong>Windows key + R</strong>.</li>
 	<li>Type the below command and click <strong>OK</strong>. <code>gpedit.msc</code>

[caption id="attachment_1411" align="alignnone" width="570"]<img class="size-full wp-image-1411" src="https://windowsdot.com/wp-content/uploads/2020/06/re2.png" alt="gpedit.msc" width="570" height="337" /> gpedit.msc[/caption]</li>
 	<li>It will open the <strong>Local Group Policy Editor</strong>.</li>
 	<li>You just navigate to this path: <code>Computer Configuration\Administrative Templates\Windows Components\Windows Defender Antivirus</code></li>
 	<li>On the RHS, you have to double-click on "<strong>Turn off Windows Defender Antivirus</strong>".

[caption id="attachment_1548" align="alignnone" width="1181"]<img class="size-full wp-image-1548" src="https://windowsdot.com/wp-content/uploads/2020/06/wd10.png" alt="Turn off Windows Defender Antivirus" width="1181" height="836" /> Turn off Windows Defender Antivirus[/caption]</li>
 	<li>Select the <strong>Enabled</strong> option and tap on the <strong>Apply</strong> and then <strong>OK</strong> button.

[caption id="attachment_1549" align="alignnone" width="1028"]<img class="size-full wp-image-1549" src="https://windowsdot.com/wp-content/uploads/2020/06/wd11.png" alt="Enabled" width="1028" height="954" /> Enabled[/caption]</li>
</ol>
<h2 id="6">5) Disable via Registry Editor:</h2>
<ol>
 	<li>Hit this keyboard combination <strong>Windows key + R</strong> to open the <strong>Run command.</strong></li>
 	<li>You have to type the below command and click <strong>OK</strong>. (If you get any pop-up from User Account Control, you have to press Yes) <code>regedit</code>

[caption id="attachment_1375" align="alignnone" width="570"]<img class="size-full wp-image-1375" src="https://windowsdot.com/wp-content/uploads/2020/06/iis4.png" alt="regedit" width="570" height="337" /> regedit[/caption]</li>
 	<li>It will open the <strong>Registry Editor</strong>.</li>
 	<li>In the left pane, you have to navigate to the following path. <code>HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows Defender</code></li>
 	<li>Right-click on the white space of RHS and choose the option <strong>DWORD (32-bit) value</strong> and name it as '<strong>DisableDefender</strong>'.

[caption id="attachment_1550" align="alignnone" width="1191"]<img class="size-full wp-image-1550" src="https://windowsdot.com/wp-content/uploads/2020/06/wd12.png" alt="DWORD (32-bit) value" width="1191" height="725" /> DWORD (32-bit) value[/caption]</li>
 	<li>Next, you have to double-click on that value and set the <strong>Value data</strong> to '<strong>1' </strong>and click<strong> OK</strong>.

[caption id="attachment_1551" align="alignnone" width="1190"]<img class="size-full wp-image-1551" src="https://windowsdot.com/wp-content/uploads/2020/06/wd13.png" alt="Value 1" width="1190" height="729" /> Value 1[/caption]</li>
 	<li>Restart your PC to apply the changes.</li>
</ol>
<h2 id="7">A Short Synopsis:</h2>
This tutorial guided you on how to <strong>Disable Windows Defender in Windows 10</strong> in clear-cut steps. You can follow any one of the above methods to disable or turn off this software on your PC. Don't forget to share your <strong>comments</strong> in the below box. Thanks for visiting <b>Windows Dot.</b>
<h2>Keep Reading:</h2>
<ul>
 	<li><strong><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsdot.com/how-to-check-windows-10-uptime-4-quick-ways/" target="_blank" rel="noopener noreferrer">How to Check Windows 10 Uptime? {4 Quick Ways}</a></strong></li>
 	<li><strong><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsdot.com/fix-encrypt-contents-to-secure-data-greyed-out-in-windows-10/" target="_blank" rel="noopener noreferrer">Fix "Encrypt Contents to Secure Data" Greyed Out in Windows 10!!</a></strong></li>
 	<li><strong><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsdot.com/quickly-restart-shutdown-without-updating-in-windows-10/" target="_blank" rel="noopener noreferrer">Quickly Restart/Shutdown Without Updating in Windows 10!!</a></strong></li>
</ul>
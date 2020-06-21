---
ID: 1358
post_title: 'How to Check What Version of IIS Do I Have? (*5 Quick Methods*)'
author: Helena
post_excerpt: ""
layout: post
permalink: >
  https://windowsdot.com/how-to-check-what-version-of-iis-do-i-have-5-quick-methods/
published: true
post_date: 2020-06-21 09:06:44
---
We will show you five diverse ways to <strong>Check What Version of IIS Do I Have</strong> quickly.
<ul>
 	<li><a href="#1">Internet Information Services (IIS)</a></li>
 	<li><a href="#2">Check IIS Version - Using Control Panel</a></li>
 	<li><a href="#3">Registry Editor to View IIS Version</a></li>
 	<li><a href="#4">How to Check IIS Version using Run Command?</a></li>
 	<li><a href="#5">Check IIS Version via Command Prompt</a></li>
 	<li><a href="#6">Find the IIS Version - Using PowerShell</a></li>
 	<li><a href="#7">Closure</a></li>
</ul>
<h2 id="1">Internet Information Services (IIS):</h2>
IIS stands for Internet Information Services that is a web server software package exclusively designed for Windows Server. IIS is created by Microsoft and used for hosting sites and other content on the web.

You can manage websites and associated users with the help of a graphical user interface provided by this service. Click the Windows icon and type Turn Windows features on or off and hit Enter. After that, you can enable this feature and restart your system. If you want to know the version of IIS installed in your system, you have to follow the below ways.
<h2 id="2">1) Check IIS Version - Using Control Panel:</h2>
<ol>
 	<li>Click the <strong>Start</strong> button and type '<strong>control panel</strong>' in the search box and hit <strong>Enter</strong>.

[caption id="attachment_1342" align="alignnone" width="1323"]<img class="size-full wp-image-1342" src="https://windowsdot.com/wp-content/uploads/2020/06/kn1.png" alt="Control Panel" width="1323" height="878" /> Control Panel[/caption]</li>
 	<li>Choose <strong>Large icons</strong> in the <strong>View by</strong> drop-down menu.

[caption id="attachment_1604" align="alignnone" width="806"]<img class="size-full wp-image-1604" src="https://s3.amazonaws.com/windows-crazy/wp-content/uploads/2020/06/19044117/wh7.png" alt="Large icons" width="806" height="337" /> Large icons[/caption]</li>
 	<li>After that, you have to click on <b><b>Administrative Tools.</b></b>

[caption id="attachment_1374" align="alignnone" width="1206"]<img class="size-full wp-image-1374" src="https://windowsdot.com/wp-content/uploads/2020/06/iis3.png" alt="Administrative Tools" width="1206" height="668" /> Administrative Tools[/caption]</li>
 	<li>Double-click on the <strong>Internet Information Services (IIS) Manager</strong>.

[caption id="attachment_1373" align="alignnone" width="1201"]<img class="size-full wp-image-1373" src="https://windowsdot.com/wp-content/uploads/2020/06/iis2.png" alt="IIS Manager" width="1201" height="664" /> IIS Manager[/caption]</li>
 	<li>Then, you have to click the <strong>Help</strong> option and then navigate to <strong>About Internet Information Services</strong>.

[caption id="attachment_1378" align="alignnone" width="1007"]<img class="size-full wp-image-1378" src="https://windowsdot.com/wp-content/uploads/2020/06/iis7.png" alt="Help" width="1007" height="709" /> Help[/caption]</li>
 	<li>Now, you can view the version of IIS.

[caption id="attachment_1377" align="alignnone" width="1007"]<img class="size-full wp-image-1377" src="https://windowsdot.com/wp-content/uploads/2020/06/iis6.png" alt="IIS Version" width="1007" height="709" /> IIS Version[/caption]</li>
</ol>
<h2 id="3">2) Registry Editor to View IIS Version:</h2>
<ol>
 	<li>Press <strong>Windows key + R</strong> to open the Run box.</li>
 	<li>Now, you have to type <strong>'regedit' </strong>and click <strong>OK</strong>. (If you get any pop-up from User Account Control, you have to press Yes) <code>regedit</code>

[caption id="attachment_1375" align="alignnone" width="570"]<img class="size-full wp-image-1375" src="https://windowsdot.com/wp-content/uploads/2020/06/iis4.png" alt="regedit" width="570" height="337" /> regedit[/caption]</li>
 	<li>It will open the <strong>Registry Editor</strong>.</li>
 	<li>In the left pane, you have to navigate to the following path. <code>HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\InetStp</code></li>
 	<li>Now, you can check the version number installed in your system that is next to <strong>VersionString</strong>.

[caption id="attachment_1380" align="alignnone" width="1145"]<img class="size-full wp-image-1380" src="https://windowsdot.com/wp-content/uploads/2020/06/iis9.png" alt="Registry Editor - IIS Version" width="1145" height="685" /> Registry Editor - IIS Version[/caption]</li>
</ol>
<h2 id="4">3) How to Check IIS Version using Run Command?</h2>
<ol>
 	<li>You have to press this shortcut <strong>Windows key + R</strong> to launch the Run box.</li>
 	<li>After that, you have to type <code>inetmgr</code> (or) <code>%SystemRoot%\system32\inetsrv\InetMgr.exe</code> and click <strong>OK</strong>.

[caption id="attachment_1376" align="alignnone" width="570"]<img class="size-full wp-image-1376" src="https://windowsdot.com/wp-content/uploads/2020/06/iis5.png" alt="inetmgt" width="570" height="337" /> inetmgt[/caption]</li>
 	<li>It will open the <strong>Internet Information Services</strong> window.</li>
 	<li>Then, you have to click the <strong>Help</strong> option and then navigate to <strong>About Internet Information Services</strong>.</li>
 	<li>Then, you can see the version of IIS.</li>
</ol>
<h2 id="5">4) Check IIS Version via Command Prompt:</h2>
<ol>
 	<li>Open the <strong>Command Prompt</strong>.</li>
 	<li>After that, you have to copy and paste this command <code>%SystemRoot%\system32\inetsrv\InetMgr.exe</code> and hit <strong>Enter</strong>.

[caption id="attachment_1372" align="alignnone" width="1067"]<img class="size-full wp-image-1372" src="https://windowsdot.com/wp-content/uploads/2020/06/iis1.png" alt="Command Prompt - IIS Version" width="1067" height="554" /> Command Prompt - IIS Version[/caption]</li>
 	<li>Then, you have to repeat the above steps from 3 to 5.</li>
</ol>
<h2 id="6">5) Find the IIS Version - Using PowerShell:</h2>
<ol>
 	<li>You have to open the PowerShell.</li>
 	<li>Next, you have to copy and paste this command <code>[System.Diagnostics.FileVersionInfo]::GetVersionInfo(“C:\Windows\system32\notepad.exe”).FileVersion</code> (or) <code>Get-ItemProperty -Path registry::HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\InetStp\ | Select-Object</code> and hit <strong>Enter</strong>.</li>
 	<li>Now, you can check the version of your IIS installed in your system.

[caption id="attachment_1379" align="alignnone" width="1157"]<img class="size-full wp-image-1379" src="https://windowsdot.com/wp-content/uploads/2020/06/iis8.png" alt="IIS Version - PowerShell" width="1157" height="616" /> IIS Version - PowerShell[/caption]</li>
</ol>
<h2 id="7">Closure:</h2>
This post helped you to <strong>Check What Version of IIS Do I Have</strong>. We hope that the above methods let you know the version of IIS installed in your system in a few efforts. Share your <strong>comments</strong> in the below section. Thanks for visiting <a href="https://windowsdot.com/"><strong>Windows Dot</strong></a>.
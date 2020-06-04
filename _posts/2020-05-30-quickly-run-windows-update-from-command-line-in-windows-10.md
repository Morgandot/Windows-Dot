---
ID: 239
post_title: '{Quickly} Run Windows Update from Command Line in Windows 10!!'
author: Helena
post_excerpt: ""
layout: post
permalink: >
  https://windowsdot.com/quickly-run-windows-update-from-command-line-in-windows-10/
published: true
post_date: 2020-05-30 14:03:16
---
This guide shows you two diverse ways to <strong>Run Windows Update from Command Line in Windows 10</strong>.
<ul class="toc">
 	<li><a href="#1">Importance of Updating Windows</a></li>
 	<li><a href="#2">Run Windows Update - Using Powershell</a></li>
 	<li><a href="#3">Run Windows Update via Command Prompt</a></li>
 	<li><a href="#4">Conclusion</a></li>
</ul>
<h2 id="1">Importance of Updating Windows:</h2>
<strong>Windows Update</strong> is one of the most highlighted features of Windows 10. Because it helps the users to <strong>stay secured against all sorts of threats or malware</strong> and offers the latest from Microsoft. Every year, there will be several updates from Microsoft to Windows.

It is vital that you should not ignore the updates as it may increase the risk of your computer. To improve Windows security, Microsoft will add new features to Windows or upgrade the existed programs.

But sometimes there may be some issues with your device, causing your Windows 10 not to update automatically. So, you can run Windows Update from Command-Line.
<h2 id="2">Way 1 - Run Windows Update - Using Powershell:</h2>
You have to run the below commands one-by-one in order to install and run the Powershell module to check for new updates.
<p id="note"><strong>Note: </strong>Don't forget to hit <strong>Enter</strong> at the end of every command.</p>
<p id="note"><strong>Note: </strong>If prompted, you have to <strong>press 'y'</strong> to continue the process.</p>

<ol>
 	<li>Go to the <strong>Start</strong> menu, search for <strong>'powershell' </strong>in the search box, right-click on the top result, and choose <strong>Run as administrator</strong> to open the Powershell. (If prompted, you have to press <strong>Yes</strong> to confirm the User Account Control window.)

[caption id="attachment_256" align="alignnone" width="879"]<img class="size-full wp-image-256" src="https://windowsdot.com/wp-content/uploads/2020/05/wu2.png" alt="Powershell" width="879" height="678" /> Powershell[/caption]</li>
 	<li>To install the Windows Update module: <code>Install-Module PSWindowsUpdate</code>

[caption id="attachment_257" align="alignnone" width="777"]<img class="size-full wp-image-257" src="https://windowsdot.com/wp-content/uploads/2020/05/wu3.png" alt="Powershell - Run Commands" width="777" height="349" /> Powershell - Run Commands[/caption]</li>
 	<li>To connect to the Windows Update servers and download the updates if available: <code>Get-WindowsUpdate</code></li>
 	<li>To install the downloaded updates on your computer: <code>Install-WindowsUpdate</code></li>
</ol>
<h2 id="3">Way 2 - Run Windows Update via Command Prompt:</h2>
<ul>
 	<li>Click on the <strong>Windows key</strong> to open the <strong>Start</strong> menu.</li>
 	<li>In the search box, you have to type <strong>'cmd'</strong>. Right-click on the result and choose <strong>Run as administrator</strong>. (If prompted, you have to press <strong>'Yes'</strong> in the User Account Control window.)

[caption id="attachment_255" align="alignnone" width="885"]<img class="size-full wp-image-255" src="https://windowsdot.com/wp-content/uploads/2020/05/wu1.png" alt="Command Prompt" width="885" height="678" /> Command Prompt[/caption]</li>
</ul>
<p id="note"><strong>Note: </strong>Don't forget to hit <strong>Enter</strong> at the end of every command.</p>

<h3>Commands for Windows 10:</h3>
<ol>
 	<li>To start checking for updates: <code>UsoClient StartScan</code></li>
 	<li>Start downloading updates: <code>UsoClient StartDownload</code></li>
 	<li>To start installing the downloaded updates: <code>UsoClient StartInstall</code></li>
 	<li>Restart your computer after installing the updates: <code>UsoClient RestartDevice</code></li>
 	<li>To check, download, and install updates: <code>UsoClient ScanInstallWait</code>

[caption id="attachment_258" align="alignnone" width="791"]<img class="size-full wp-image-258" src="https://windowsdot.com/wp-content/uploads/2020/05/wu4.png" alt="Command Prompt - Run Commands" width="791" height="435" /> Command Prompt - Run Commands[/caption]</li>
</ol>
<h3>Commands for Older Versions:</h3>
<ol>
 	<li>To check for updates: <code>wuauclt /detectnow</code></li>
 	<li>Install available updates: <code>wuauclt /updatenow</code></li>
 	<li>To check, download, and install updates: <code>wuauclt /detectnow /updatenow</code></li>
</ol>
<h2 id="4">Conclusion:</h2>
We hope that this guide is useful as it lets you <strong>Run Windows Update from Command Line in Windows 10</strong>. You can try to run commands from any one of the ways to update and secure your Windows. <strong>Leave a Reply</strong> about this article in the below section. Thanks for visiting <a href="https://windowsdot.com/"><strong>Windows Dot</strong></a>.
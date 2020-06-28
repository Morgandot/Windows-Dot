---
ID: 1647
post_title: 'How to View/Hide File Extensions In Windows 10? {5 Ways}'
author: Olivia
post_excerpt: ""
layout: post
permalink: >
  https://windowsdot.com/how-to-view-hide-file-extensions-in-windows-10-5-ways/
published: true
post_date: 2020-06-28 16:02:07
---
In this article, we discuss <strong>How to View/Hide File Extensions in Windows 10</strong> in five different ways.
<ul class="toc">
 	<li><a href="#5">Way-1 By using Folder Options</a></li>
 	<li><a href="#6">Way-2 By using File Explorer</a></li>
 	<li><a href="#1">Way-3 By using Registry Editor</a></li>
 	<li><a href="#2">Way-4 By using Command Line</a></li>
 	<li><a href="#3">Way-5 By using Group Policy Editor</a></li>
 	<li><a href="#4">Synopsis</a></li>
</ul>
<h2>Way-1 By using Folder Options:</h2>
<ol>
 	<li>Make use of the shortcut <strong>Windows + R</strong> to open the Run command dialog box.</li>
 	<li>Type <strong>control folders</strong> in the given space box of Open and click OK.

[caption id="attachment_1653" align="aligncenter" width="446"]<img class="size-full wp-image-1653" src="https://windowsdot.com/wp-content/uploads/2020/06/explorer_iE2rsybRl6.png" alt="Run command" width="446" height="262" /> Run command[/caption]</li>
 	<li>Select the <strong>View</strong> tab.</li>
 	<li>Under the <strong>Advanced</strong> settings, <strong>uncheck</strong> the Hide extensions of known file types option.

[caption id="attachment_1654" align="aligncenter" width="497"]<img class="size-full wp-image-1654" src="https://windowsdot.com/wp-content/uploads/2020/06/ShareX_TT8yy6h51N.png" alt="Advanced" width="497" height="572" /> Advanced[/caption]</li>
 	<li>That's all.</li>
</ol>
<h2>Way-2 By using File Explorer:</h2>
<ol>
 	<li>Press <strong>Windows + E </strong>to open the File Explorer.</li>
 	<li>Click the <strong>View</strong> option.</li>
 	<li><strong>Check in</strong> the File Name Extensions.

[caption id="attachment_1652" align="aligncenter" width="955"]<img class="size-full wp-image-1652" src="https://windowsdot.com/wp-content/uploads/2020/06/explorer_e2UJqvnO1h.png" alt="File Explorer" width="955" height="560" /> File Explorer[/caption]</li>
 	<li>That's all.</li>
</ol>
<h2>Way-3 By using Registry Editor:</h2>
<ol>
 	<li>Make use of the shortcut <strong>Windows + R</strong> to open the Run command dialog box.</li>
 	<li>Type <strong>regedit</strong> in the given space box of <strong>Open</strong> and click <strong>OK</strong>.</li>
 	<li>Go to the <strong>following</strong> path.
<pre><code>HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced</code></pre>
</li>
 	<li>In the right pane, double-click the <strong>HideFileExt</strong> option.</li>
 	<li>Now, <strong>show</strong> File extensions set the value as <strong>0</strong>.</li>
 	<li>To <strong>hide</strong> set the value as <strong>1</strong>.

[caption id="attachment_1649" align="aligncenter" width="992"]<img class="size-full wp-image-1649" src="https://windowsdot.com/wp-content/uploads/2020/06/regedit_YsgUGJ2qab.png" alt="Registry" width="992" height="736" /> Registry[/caption]</li>
 	<li>If the changes are not occurring then restart File Explorer from the task manager or restart the computer altogether.</li>
</ol>
<h2>Way-4 By using Command Line:</h2>
<ol>
 	<li>Go to the <strong>start</strong> menu.</li>
 	<li>In the search column, type as <strong>Command Prompt.</strong></li>
 	<li><strong>Tap</strong> it which appears at the top of the start menu.

[caption id="attachment_1640" align="aligncenter" width="477"]<img class="size-full wp-image-1640" src="https://windowsdot.com/wp-content/uploads/2020/06/explorer_HIUFrc7npv.png" alt="Start Menu" width="477" height="767" /> Start Menu[/caption]</li>
 	<li>To <strong>Hide</strong> file extensions, type the following command and press <strong>Enter</strong>.
<pre><code>reg add HKCU\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced /v 
HideFileExt /t REG_DWORD /d 1 /f</code></pre>
</li>
 	<li>To <strong>show</strong> file extensions then copy and paste the below command and press <strong>Enter</strong>.
<pre><code>reg add HKCU\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced /v 
HideFileExt /t REG_DWORD /d 0 /f</code></pre>
</li>
</ol>
<h2>Way-5 By using Group Policy Editor:</h2>
<ol>
 	<li>Open<strong> Domain Group Policy Management Editor.</strong></li>
 	<li>Go to the <strong>following</strong> path.
<pre><code> User Configuration –&gt; Preferences –&gt; Control Panel items –&gt; Folder Options</code></pre>
</li>
 	<li>In the left pane,<strong> right-click</strong> on the <strong>Folder</strong> <strong>Options</strong>.</li>
 	<li>Now, select <strong>New</strong> and click the<strong> Folder Options.</strong></li>
 	<li>In the <strong>regular Folder Options</strong> window, you can make changes to this window and the changes and that will be applied.

[caption id="attachment_1648" align="aligncenter" width="1096"]<img class="size-full wp-image-1648" src="https://windowsdot.com/wp-content/uploads/2020/06/chrome_PsiRTAsuga.png" alt="Editor" width="1096" height="772" /> Editor[/caption]</li>
</ol>
<strong>Image Source:</strong><em> itechtics.com</em>
<h2>Synopsis:</h2>
This tutorial guided you on <strong>how to View/Hide File Extensions in Windows 10</strong> in clear-cut steps. Don’t forget to share your <strong>comments</strong> in the below box.
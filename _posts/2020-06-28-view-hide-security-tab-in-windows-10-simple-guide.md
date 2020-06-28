---
ID: 1639
post_title: 'View/Hide Security Tab in Windows 10!! {Simple Guide}'
author: Olivia
post_excerpt: ""
layout: post
permalink: >
  https://windowsdot.com/view-hide-security-tab-in-windows-10-simple-guide/
published: true
post_date: 2020-06-28 16:00:35
---
In this article, we guide you <strong>How to View/Hide Security Tab in Windows 10</strong> in simple steps.
<ul class="toc">
 	<li><a href="#1">View/Hide Security Tab using Windows Registry</a></li>
 	<li><a href="#2">View/Hide Security Tab using Group Policy Editor</a></li>
 	<li><a href="#3">View/Hide Security Tab using the command line</a></li>
 	<li><a href="#4">Summary</a></li>
</ul>
<h2 id="1">View/Hide Security Tab using Windows Registry:</h2>
<ol>
 	<li>Make use of the shortcut <strong>Windows + R</strong> to open the Run command dialog box.</li>
 	<li>Type<strong> regedit.exe</strong> in the given space box of Open and click OK.

[caption id="attachment_1642" align="aligncenter" width="448"]<img class="size-full wp-image-1642" src="https://windowsdot.com/wp-content/uploads/2020/06/explorer_73GxpFckJT.png" alt="Run command" width="448" height="255" /> Run command[/caption]</li>
 	<li>Now, go to the following path in the <strong>Windows Registry.</strong>
<pre><code>HKEY_CURRENT_USER\Software\Microsoft\Windows\Currentversion\Policies\Explorer</code></pre>
</li>
 	<li>In the right pane, double-click the <strong>NoSecurityTab</strong> and change its value to<strong> 1</strong> by modifying it.</li>
 	<li>Now <strong>refresh</strong> your window and the security tabs from each folder will hide.

[caption id="attachment_1645" align="aligncenter" width="819"]<img class="size-full wp-image-1645" src="https://windowsdot.com/wp-content/uploads/2020/06/chrome_lQfXeRBHh9.png" alt="Windows Registry" width="819" height="618" /> Windows Registry[/caption]</li>
 	<li>When you want to <strong>view</strong>, then Go to the <strong>same</strong> registry path and set its value to<strong> 0.</strong></li>
 	<li>Now, the <strong>security</strong> tab will be <strong>visible</strong>.</li>
</ol>
<h2 id="2">View/Hide Security Tab using Group Policy Editor:</h2>
<ol>
 	<li>Go to the <strong>start</strong> menu.</li>
 	<li>In the search column, type as<strong> Local Group Policy editor.</strong></li>
 	<li><strong>Tap</strong> it which appears at the top of the start menu.

[caption id="attachment_1641" align="aligncenter" width="470"]<img class="size-full wp-image-1641" src="https://windowsdot.com/wp-content/uploads/2020/06/explorer_dqTK3x55x4.png" alt="Start Menu" width="470" height="766" /> Start Menu[/caption]</li>
 	<li>Go to the following path.
<pre><code> User Configuration\Administrative Tools\Windows Components\File Explorer</code></pre>
</li>
 	<li>In the right pane, open <strong>Remove</strong> <strong>Security</strong> <strong>Tab</strong>.

[caption id="attachment_1644" align="aligncenter" width="922"]<img class="size-full wp-image-1644" src="https://windowsdot.com/wp-content/uploads/2020/06/chrome_o6uVeE6TcQ.png" alt="Group policy editor" width="922" height="648" /> Group policy editor[/caption]</li>
 	<li>Then, a list of options will occur.</li>
 	<li>Select <strong>enable</strong> to remove Security Tab.</li>
 	<li>Select <strong>disable</strong> if you don't want to remove it.</li>
 	<li>Now, press <strong>OK</strong>.

[caption id="attachment_1643" align="aligncenter" width="851"]<img class="size-full wp-image-1643" src="https://windowsdot.com/wp-content/uploads/2020/06/chrome_xmTYfcvZlY.png" alt="Group policy editor" width="851" height="784" /> Group policy editor[/caption]</li>
</ol>
<h2 id="3">View/Hide Security Tab using the command line:</h2>
<ol>
 	<li style="list-style-type: none;">
<ol>
 	<li>Go to the <strong>start</strong> menu.</li>
 	<li>In the search column, type as <strong>Command Prompt.</strong></li>
 	<li><strong>Tap</strong> it which appears at the top of the start menu.

[caption id="attachment_1640" align="aligncenter" width="477"]<img class="size-full wp-image-1640" src="https://windowsdot.com/wp-content/uploads/2020/06/explorer_HIUFrc7npv.png" alt="Start Menu" width="477" height="767" /> Start Menu[/caption]</li>
 	<li>To <strong>enable</strong> type the following command and press <strong>Enter</strong>.
<pre><code>REG add HKCU\Software\Microsoft\Windows\CurrentVersion\Policies\Explorer /v 
Nosecuritytab /t REG_DWORD /d 0 /f</code></pre>
</li>
 	<li>To <strong>disable</strong> the security tab, copy and paste the following command.</li>
 	<li>Press <strong>Enter</strong>.
<pre><code>REG add HKCU\Software\Microsoft\Windows\CurrentVersion\Policies\Explorer /v 
Nosecuritytab /t REG_DWORD /d 1 /f</code></pre>
</li>
</ol>
</li>
</ol>
<strong>Image Source:</strong><em> itechtics.com</em>
<h2 id="4">Summary:</h2>
We hope that this guide assisted you in <strong>How to View/Hide Security Tab in Windows 10.</strong> The steps explained in this article let you understand the process simpler. Kindly share your valuable<strong> comments/feedback</strong> in the below section.
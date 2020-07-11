---
ID: 1953
post_title: >
  How to Delete/Disable Search History In
  File Explorer in Windows 10?
author: Olivia
post_excerpt: ""
layout: post
permalink: >
  https://windowsdot.com/how-to-delete-disable-search-history-in-file-explorer-in-windows-10/
published: true
post_date: 2020-07-11 15:15:47
---
In this article, we illustrate an outline of <strong>How to Delete/Disable Search History In File Explorer in Windows 10</strong> in simple steps.
<ul class="toc">
 	<li><a href="#1">Delete search history using File Explorer</a></li>
 	<li><a href="#2">Delete search history using Registry</a></li>
 	<li><a href="#3">Disable File Explorer search history using Group Policy</a></li>
 	<li><a href="#4">Disable File Explorer search history using Registry</a></li>
 	<li><a href="#5">Summary</a></li>
</ul>
<h2 id="1">Delete search history using File Explorer:</h2>
<ol>
 	<li>Make use of the shortcut <strong>Windows + E</strong> to open <strong>File Explorer.</strong></li>
 	<li>Then, <strong>search</strong> for anything to make available the <strong>Search</strong> tab.</li>
 	<li>Now, click the <strong>Recent</strong> <strong>Searches</strong> option from the <strong>Search</strong> tab.</li>
 	<li>Click the <strong>Clear</strong> <strong>search</strong> <strong>history</strong> option.

[caption id="attachment_1999" align="aligncenter" width="954"]<img class="size-full wp-image-1999" src="https://windowsdot.com/wp-content/uploads/2020/07/explorer_tGyUJVLy3b.png" alt="Search" width="954" height="568" /> Search[/caption]</li>
 	<li>That's all.</li>
</ol>
<h2 id="2">Delete search history using Registry:</h2>
<ol>
 	<li>Make use of the shortcut <strong>Windows + R</strong> to open the<strong> Run command dialog box.</strong></li>
 	<li>Type <strong>regedit.exe</strong> in the given space box of <strong>Open</strong> and click <strong>OK</strong>.

[caption id="attachment_1998" align="aligncenter" width="442"]<img class="size-full wp-image-1998" src="https://windowsdot.com/wp-content/uploads/2020/07/explorer_rWN09XPym6.png" alt="Run command " width="442" height="253" /> Run command[/caption]</li>
 	<li>In the <strong>Registry</strong> window, Go to the <strong>following</strong> path.
<pre><code>HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\WordWheelQuery</code></pre>
</li>
 	<li><strong>Select</strong> the DWORD keys storing the search history value.</li>
 	<li><strong>Right-click</strong> the selection and <strong>choose</strong> the Delete option.

[caption id="attachment_1993" align="aligncenter" width="1290"]<img class="size-full wp-image-1993" src="https://windowsdot.com/wp-content/uploads/2020/07/ShareX_ZBNowBrwko.png" alt="Registry" width="1290" height="479" /> Registry[/caption]</li>
 	<li>Finally, click <strong>OK</strong>.</li>
</ol>
<h2 id="3">Disable File Explorer search history using Group Policy:</h2>
<ol>
 	<li>Make use of the shortcut<strong> Windows + R</strong> to open the <strong>Run command dialog box.</strong></li>
 	<li>Type <strong>gpedit.msc</strong> in the given space box of Open and click <strong>OK</strong>.

[caption id="attachment_1997" align="aligncenter" width="440"]<img class="size-full wp-image-1997" src="https://windowsdot.com/wp-content/uploads/2020/07/explorer_1bjCV1w4dI.png" alt="Run command " width="440" height="259" /> Run command[/caption]</li>
 	<li>In the<strong> Group Policy Editor</strong> window, Go to the <strong>following</strong> path.
<pre><code>User Configuration\Administrative Templates\Windows Components\File Explorer</code></pre>
</li>
 	<li><strong>Double-click</strong> on the File Explorer and in the right pane, <strong>locate</strong> Turn off the display of recent search entries in File Explorer … option.

[caption id="attachment_1996" align="aligncenter" width="930"]<img class="size-full wp-image-1996" src="https://windowsdot.com/wp-content/uploads/2020/07/mmc_VQ6Z4nZW2Z.png" alt="Group Policy" width="930" height="640" /> Group Policy[/caption]</li>
 	<li>Now, double click to open its <strong>Properties</strong> window.</li>
 	<li><strong>Select</strong> the Enabled option to enable this feature.

[caption id="attachment_2000" align="aligncenter" width="848"]<img class="size-full wp-image-2000" src="https://windowsdot.com/wp-content/uploads/2020/07/mmc_YiuMxjUXq4.png" alt="Enabled" width="848" height="774" /> Enabled[/caption]</li>
 	<li>Click <strong>Apply</strong> then <strong>OK</strong>.</li>
 	<li>That's all.</li>
</ol>
<h2 id="4">Disable File Explorer search history using Registry:</h2>
<ol>
 	<li>Make use of the shortcut <strong>Windows + R</strong> to open the <strong>Run command dialog box.</strong></li>
 	<li>Type <strong>regedit.exe</strong> in the given space box of <strong>Open</strong> and click <strong>OK</strong>.

[caption id="attachment_1998" align="aligncenter" width="442"]<img class="size-full wp-image-1998" src="https://windowsdot.com/wp-content/uploads/2020/07/explorer_rWN09XPym6.png" alt="Run command " width="442" height="253" /> Run command[/caption]</li>
 	<li>In the <strong>Registry</strong> window, Go to the <strong>following</strong> path.
<pre><code>HKEY_CURRENT_USER\Software\Policies\Microsoft\Windows\Explorer</code></pre>
</li>
 	<li>Right-click the <strong>Explorer</strong> key, select <strong>New</strong> and click on<strong> DWORD (32-bit)</strong> Value.

[caption id="attachment_1994" align="aligncenter" width="985"]<img class="size-full wp-image-1994" src="https://windowsdot.com/wp-content/uploads/2020/07/ShareX_kSi16qZ0Dv.png" alt="New" width="985" height="650" /> New[/caption]</li>
 	<li>Rename it as <strong>DisableSearchBoxSuggestions</strong> and press <strong>Enter</strong>.</li>
 	<li><strong>Double-click</strong> the newly created and set the value<strong><strong> 1.</strong></strong>

[caption id="attachment_1995" align="aligncenter" width="427"]<img class="size-full wp-image-1995" src="https://windowsdot.com/wp-content/uploads/2020/07/regedit_7MBR73lZXk.png" alt="Value " width="427" height="229" /> Value[/caption]</li>
 	<li>Click the <strong>OK</strong> button.</li>
</ol>
<h2 id="5">Summary:</h2>
In this article, we discussed<strong> How to Delete/Disable Search History In File Explorer in Windows 10</strong> in simple and easy steps. In addition, the clear cut screenshots let you understand clearly. Share the <strong>comments</strong> in the below section and drop your <strong>valuable</strong> <strong>feedback</strong>.
<h2>Related Articles:</h2>
<ul>
 	<li><a href="https://windowsdot.com/turn-off-wi-fi-when-connecting-ethernet-in-windows-10/" rel="nofollow"><strong>Turn Off Wi-Fi When Connecting Ethernet in Windows 10</strong></a></li>
 	<li><a href="https://windowsdot.com/how-to-view-hide-file-extensions-in-windows-10-5-ways/" rel="nofollow"><strong>How to View/Hide File Extensions in Windows 10?</strong></a></li>
 	<li><a href="https://windowsdot.com/how-to-check-public-ip-address-in-windows-10/" rel="nofollow"><strong>Check Public IP Address in Windows 10</strong></a></li>
 	<li><a href="https://windowsdot.com/laptop-battery-drains-after-sleep-mode-simple-guide/" rel="nofollow"><strong>Laptop battery drains after sleep mode</strong></a></li>
</ul>
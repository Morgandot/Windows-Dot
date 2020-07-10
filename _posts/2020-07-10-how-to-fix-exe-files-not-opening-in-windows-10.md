---
ID: 1901
post_title: >
  How to Fix Exe Files Not Opening In
  Windows 10?
author: Olivia
post_excerpt: ""
layout: post
permalink: >
  https://windowsdot.com/how-to-fix-exe-files-not-opening-in-windows-10/
published: true
post_date: 2020-07-10 14:08:57
---
In this article, we discuss <strong>How to Fix Exe Files Not Opening In Windows 10</strong> in simple steps.
<ul class="toc">
 	<li><a href="#1">How to Fix unable to download any exe files?</a></li>
 	<li><a href="#2">How to Fix Exe Files Not Opening In Windows 10?</a></li>
 	<li><a href="#3">Adding a Registry for EXE file extension</a></li>
 	<li><a href="#4">Synopsis</a></li>
</ul>
<h2 id="1">How to Fix unable to download any exe files?</h2>
Follow the below steps to fix unable to download any exe files by using Internet Options.
<ol>
 	<li>Go to the<strong> start menu.</strong></li>
 	<li>In the search column, type as<strong> Internet Options.</strong></li>
 	<li><strong>Tap</strong> it which appears on the top of the start menu.</li>
 	<li>In the <strong>Internet Options</strong> window, select the<strong> Security option.</strong></li>
 	<li>Then click on the <strong>Internet</strong> and click the<strong> Custom Level</strong> option.</li>
 	<li>Then in the <strong>Security Settings</strong> window, under the <strong>Downloads section,</strong> <strong>enable File Download and Font Download</strong> options.</li>
 	<li>Again in the <strong>same window,</strong> locate<strong> Launching application</strong>s <strong>and unsafe files, </strong>select the <strong>Prompt option.</strong></li>
 	<li>Click <strong>Apply</strong> and <strong>OK</strong>.</li>
</ol>
<h2 id="2">How to Fix Exe Files Not Opening In Windows 10?</h2>
<ul>
 	<li><a href="#5"><strong>Change your registry</strong></a></li>
 	<li><a href="#6"><strong>Turn off Windows Firewall</strong></a></li>
 	<li><a href="#7"><strong>Change your sound scheme and turn off User Account Control</strong></a></li>
</ul>
<h2 id="5">Change your registry:</h2>
<ol>
 	<li>Make use of the shortcut <strong>Windows + R</strong> to open the <strong>Run command dialog box.</strong></li>
 	<li>Type <strong>regedit.exe</strong> in the given space box of <strong>Open</strong> and click <strong>OK</strong>.

[caption id="attachment_1915" align="aligncenter" width="448"]<img class="size-full wp-image-1915" src="https://windowsdot.com/wp-content/uploads/2020/07/explorer_FovdcmXvkd.png" alt="Run command " width="448" height="256" /> Run command[/caption]</li>
 	<li>In the<strong> Windows Registry</strong> window, Go to the following path.
<pre><code>HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Policies\Attachments</code></pre>
</li>
 	<li>Then, <strong>right-click</strong> on the right pane and select <strong>New</strong>.</li>
 	<li>Now, select the<strong> 32-bit DWORD</strong> value and rename it with <strong><strong>ScanWithAntivirus.</strong></strong>

[caption id="attachment_1914" align="aligncenter" width="450"]<img class="size-full wp-image-1914" src="https://windowsdot.com/wp-content/uploads/2020/07/regedit_d6ooei5m07.png" alt="New" width="450" height="229" /> New[/caption]

[caption id="attachment_1913" align="aligncenter" width="507"]<img class="size-full wp-image-1913" src="https://windowsdot.com/wp-content/uploads/2020/07/regedit_5eenkOmL3b.png" alt="Rename" width="507" height="149" /> Rename[/caption]</li>
 	<li><strong>Double-click</strong> on the newly created value and in the <strong>Value</strong> <strong>data</strong> box set the<strong><strong> value as 1.</strong></strong>

[caption id="attachment_1912" align="aligncenter" width="421"]<img class="size-full wp-image-1912" src="https://windowsdot.com/wp-content/uploads/2020/07/regedit_sjj2CwxajM.png" alt="Value set" width="421" height="227" /> Value set[/caption]</li>
 	<li>This value<strong> will off or disable</strong> the scan.</li>
 	<li>That's all, now any file you will <strong>download</strong>, antivirus software will not scan it.</li>
</ol>
<h2 id="6">Turn off Windows Firewall:</h2>
<ol>
 	<li>Go to the <strong>start</strong> <strong>menu</strong>.</li>
 	<li>In the search column, type as <strong>Windows Firewall.</strong></li>
 	<li><strong>Tap</strong> it which appears on the top of the start menu.

[caption id="attachment_1911" align="aligncenter" width="462"]<img class="size-full wp-image-1911" src="https://windowsdot.com/wp-content/uploads/2020/07/explorer_fymIs7sB28.png" alt="Start Menu" width="462" height="765" /> Start Menu[/caption]</li>
 	<li>In the left pane, click on the link <strong><strong>Turn Windows Firewall on or off.</strong></strong>

[caption id="attachment_1910" align="aligncenter" width="1091"]<img class="size-full wp-image-1910" src="https://windowsdot.com/wp-content/uploads/2020/07/explorer_aHTs3l6Ptw.png" alt="Control Panel" width="1091" height="685" /> Control Panel[/caption]</li>
 	<li>Now, select <strong>Turn off Windows Firewall (not recommended)</strong> option for both <strong>Private</strong> and <strong>Public</strong> network settings.

[caption id="attachment_1919" align="aligncenter" width="1091"]<img class="size-full wp-image-1919" src="https://windowsdot.com/wp-content/uploads/2020/07/explorer_6vukd2sPEF.png" alt="Control Panel" width="1091" height="528" /> Control Panel[/caption]</li>
 	<li>Click <strong>OK</strong> to save changes.</li>
 	<li>That's all.</li>
</ol>
<h2 id="7">Change your sound scheme and turn off User Account Control:</h2>
Follow the steps to Change your sound scheme.
<ol>
 	<li>Go to the <strong>start menu.</strong></li>
 	<li>In the search column, type as <strong>Sound</strong>.</li>
 	<li><strong>Tap</strong> it which appears on the top of the start menu.

[caption id="attachment_1909" align="aligncenter" width="467"]<img class="size-full wp-image-1909" src="https://windowsdot.com/wp-content/uploads/2020/07/explorer_vW0Zs4Z9J9.png" alt="Start Menu" width="467" height="757" /> Start Menu[/caption]</li>
 	<li>In the Sound window, select the <strong>Sound</strong> <strong>tab</strong>.</li>
 	<li>Under the <strong>Sound</strong> <strong>Scheme</strong> option, click the <strong>drop-down arrow</strong> and select <strong>No Sounds</strong> option.

[caption id="attachment_1908" align="aligncenter" width="451"]<img class="size-full wp-image-1908" src="https://windowsdot.com/wp-content/uploads/2020/07/rundll32_yh9pi09m71.png" alt="Sound" width="451" height="574" /> Sound[/caption]</li>
 	<li>Click <strong>Apply</strong> and <strong>OK</strong> to save changes.</li>
</ol>
Follow the steps to turn off User Account Control.
<ol>
 	<li>Go to the <strong>start menu.</strong></li>
 	<li>In the search column, type as<strong> User Accounts.</strong></li>
 	<li><strong>Tap</strong> it which appears on the top of the start menu.

[caption id="attachment_1906" align="aligncenter" width="466"]<img class="size-full wp-image-1906" src="https://windowsdot.com/wp-content/uploads/2020/07/explorer_q125C5Riqa.png" alt="Start Menu" width="466" height="765" /> Start Menu[/caption]</li>
 	<li>In the right pane, click the link <strong><strong>Change User Account Control settings.</strong></strong>

[caption id="attachment_1905" align="aligncenter" width="647"]<img class="size-full wp-image-1905" src="https://windowsdot.com/wp-content/uploads/2020/07/explorer_A973n9xrpV.png" alt="Change Settings" width="647" height="418" /> Change Settings[/caption]</li>
 	<li><strong>Lower</strong> the slider all the way down to the<strong><strong> Never notify.</strong></strong>

[caption id="attachment_1904" align="aligncenter" width="918"]<img class="size-full wp-image-1904" src="https://windowsdot.com/wp-content/uploads/2020/07/dllhost_Ah6fT1kJrw.png" alt="Never Notify" width="918" height="678" /> Never Notify[/caption]</li>
 	<li>Click <strong>OK</strong> to save changes.</li>
 	<li>Now, again Go to the <strong>Sound window</strong> and select the <strong>Sound tab.</strong></li>
 	<li>Under the <strong>Sound Scheme</strong> option, click the <strong>drop-down arrow</strong> and select the<strong> Windows Default</strong> option.

[caption id="attachment_1907" align="aligncenter" width="458"]<img class="size-full wp-image-1907" src="https://windowsdot.com/wp-content/uploads/2020/07/rundll32_N1HQ37DoCv.png" alt="Sound" width="458" height="579" /> Sound[/caption]</li>
 	<li>Click <strong>Apply</strong> and <strong>OK</strong> to save changes.</li>
 	<li>After <strong>saving</strong> changes <strong>check</strong> if the issue is resolved or not.</li>
</ol>
<h2 id="3">Adding a Registry for EXE file extension:</h2>
<ol>
 	<li>First, Download the<a href="https://www.winhelponline.com/fileasso/exe_fix_w10.zip"><strong> Registry key</strong></a>.</li>
 	<li>Then, Go to the <strong>File Explorer</strong> and locate where you <strong>save</strong> the file.</li>
 	<li><strong>Double-click</strong> on it to <strong>add</strong> this registry to the <strong>Windows Registry.</strong></li>
 	<li>Then, a <strong>confirmatory</strong> window will open and Press <strong>Yes</strong>.</li>
 	<li>That's all.</li>
</ol>
<h2 id="4">Synopsis:</h2>
In this article, we illustrated <strong>How to Fix Exe Files Not Opening In Windows 10</strong> in simple steps. In addition, the clear cut screenshots let you understand clearly. Share the <strong>comments</strong> in the below section and drop your <strong>valuable feedback.</strong>
<h2>Related Articles:</h2>
<ul>
 	<li><a href="https://windowsdot.com/view-hide-security-tab-in-windows-10-simple-guide/" rel="nofollow"><strong>View/Hide Security tab in Windows 10</strong></a></li>
 	<li><a href="https://windowsdot.com/how-to-download-install-windows-media-center-on-windows-10/" rel="nofollow"><strong>Download &amp; Install Windows Media Center on Windows 10</strong></a></li>
 	<li><a href="https://windowsdot.com/quick-way-to-reset-network-adapter-in-windows-10/" rel="nofollow"><strong>To Reset Network Adaptor in Windows 10</strong></a></li>
 	<li><a href="https://windowsdot.com/quick-guide-cant-open-downloads-in-windows-10/" rel="nofollow"><strong>Fix - Can't Open Downloads in Windows 10</strong></a></li>
</ul>
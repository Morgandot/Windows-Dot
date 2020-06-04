---
ID: 345
post_title: 'Disable Software Reporter Tool!! {Different Ways}'
author: Olivia
post_excerpt: ""
layout: post
permalink: >
  https://windowsdot.com/disable-software-reporter-tool-different-ways/
published: true
post_date: 2020-05-30 13:35:06
---
Read this article to get points <strong>to disable the Software Reporter Tool</strong> in different ways.
<ul class="toc">
 	<li><a href="#1">Software Reporter Tool</a></li>
 	<li><a href="#2">Disable Software Reporter Tool using on Windows networks</a></li>
 	<li><a href="#3">Disable Software Reporter Tool by deleting its contents</a></li>
 	<li><a href="#4">Disable Software Reporter Tool using Chrome Policies</a></li>
 	<li><a href="#5">Disable Software Reporter Tool using file permissions</a></li>
 	<li><a href="#6">Verdict</a></li>
</ul>
<h2 id="1">Software Reporter Tool:</h2>
The <strong>Software Reporter Tool </strong>is scheduled to run once a week (most probably with Google Update) and sends its results to Google. This tool will come with a pre-installed with Google Chrome browser. It consists of all the processes and programs which are interfering with Chrome’s browsing experience.
<h2 id="2">Disable Software Reporter Tool using on Windows networks (Recommended):</h2>
This was the <strong>first way </strong>to disable Software Reporter Tool using on Windows networks. Follow the below steps.
<ol>
 	<li>Firstly, you have to<a href="https://dl.google.com/dl/edgedl/chrome/policy/policy_templates.zip"><strong> Download Google Policy Templates.</strong></a></li>
 	<li>Then <strong>tap</strong> the downloaded zip file.</li>
 	<li>After it gets open in the <strong>downloads</strong> folder, then select the <strong>windows</strong> and select <strong>admx</strong> folder and search for <strong>Google.admx and Chrome.admx</strong></li>
 	<li>Once you find it then<strong> copy and paste</strong> to C:\Windows\PolicyDefinitions\ folder.</li>
 	<li><strong>Refer to the below screenshots</strong> for clear understanding.

[caption id="attachment_367" align="aligncenter" width="1159"]<img class="wp-image-367 size-full" src="https://windowsdot.com/wp-content/uploads/2020/05/Screenshot_1-1.png" alt="Windows" width="1159" height="734" /> Windows[/caption]

[caption id="attachment_368" align="aligncenter" width="1157"]<img class="wp-image-368 size-full" src="https://windowsdot.com/wp-content/uploads/2020/05/Screenshot_2-1.png" alt="admx" width="1157" height="731" /> admx[/caption]

[caption id="attachment_369" align="aligncenter" width="1157"]<img class="wp-image-369 size-full" src="https://windowsdot.com/wp-content/uploads/2020/05/Screenshot_3-1.png" alt="admx" width="1157" height="736" /> admx[/caption]

[caption id="attachment_370" align="aligncenter" width="1153"]<img class="wp-image-370 size-full" src="https://windowsdot.com/wp-content/uploads/2020/05/Screenshot_4-1.png" alt="Local disk" width="1153" height="736" /> Local disk[/caption]</li>
 	<li>Then again go the <strong>W</strong><strong>indows</strong> folder and select the <strong>admx</strong> folder.</li>
 	<li>Select<strong> en-us</strong> and <strong>copy</strong> the<strong> Google.adml and Chrome.adml</strong></li>
 	<li><strong>Paste</strong> it to the C:\Windows\PolicyDefinitions\en-us\

[caption id="attachment_371" align="aligncenter" width="1160"]<img class="wp-image-371 size-full" src="https://windowsdot.com/wp-content/uploads/2020/05/Screenshot_5-1.png" alt="Windows " width="1160" height="738" /> Windows[/caption]

[caption id="attachment_372" align="aligncenter" width="1154"]<img class="wp-image-372 size-full" src="https://windowsdot.com/wp-content/uploads/2020/05/Screenshot_6-1.png" alt="en-US" width="1154" height="733" /> en-US[/caption]

[caption id="attachment_373" align="aligncenter" width="1157"]<img class="wp-image-373 size-full" src="https://windowsdot.com/wp-content/uploads/2020/05/Screenshot_7-1.png" alt="Local disk" width="1157" height="739" /> Local disk[/caption]</li>
 	<li>The open the<strong> Run command dialog box</strong> using the shortcut <strong>Windows +R.</strong></li>
 	<li>Then type <strong>gpedit.msc</strong> in the given space of open and click <strong><strong>OK.</strong></strong>

[caption id="attachment_374" align="aligncenter" width="449"]<img class="wp-image-374 size-full" src="https://windowsdot.com/wp-content/uploads/2020/05/Screenshot_8-1.png" alt="Run command " width="449" height="267" /> Run command[/caption]</li>
 	<li><strong>Local Group Policy Editor</strong> window gets open in that select the <strong>Computer Configuration.</strong></li>
 	<li>Click the dropdown arrow of the Computer Configuration and select <strong>Administrative Templates.</strong></li>
 	<li>In the left pane select <strong>Google</strong> and then <strong><strong>Google Chrome.</strong></strong>

[caption id="attachment_375" align="aligncenter" width="940"]<img class="wp-image-375 size-full" src="https://windowsdot.com/wp-content/uploads/2020/05/Screenshot_9-1.png" alt="Group policy editor" width="940" height="658" /> Group policy editor[/caption]</li>
 	<li>Scroll down and find the option <strong>Enable Chrome cleanup on Windows</strong> and then disable it.

[caption id="attachment_376" align="aligncenter" width="937"]<img class="wp-image-376 size-full" src="https://windowsdot.com/wp-content/uploads/2020/05/Screenshot_10-1.png" alt="Group policy editor" width="937" height="660" /> Group policy editor[/caption]</li>
</ol>
<h2 id="3">Disable Software Reporter Tool by deleting its contents:</h2>
This was the <strong>second way</strong> to disable the Software Reporter Tool by deleting its contents. Follow the below steps.
<ol>
 	<li>Go to the <strong>start menu</strong> and in the search column type as <strong>Notepad</strong>.</li>
 	<li>The icon will get appear then <strong>tap</strong> to get open.</li>
 	<li>In the Notepad window, select the <strong>File</strong> option and click the <strong>open</strong>.</li>
 	<li>Navigate to the following path:
%localappdata%\google\chrome\User Data\SwReporter\81.234.200\</li>
 	<li>In the bottom, select all files from the <strong>open</strong> menu.</li>
 	<li>Then select <strong>software_reporter_tool.exe</strong> from the list and press <strong>Open</strong>.</li>
 	<li>After that, select all the files using shortcut <strong>Ctrl + A</strong> and delete the contents of the file.</li>
 	<li>Finally, <strong>save</strong> the file.</li>
 	<li>It ensures the software reporter does not run again on your computer.</li>
 	<li>But it is a temporary method as the folders related to Chrome are automatically updated when a new version of Chrome is installed.</li>
</ol>
<h2 id="4">Disable Software Reporter Tool using Chrome Policies:</h2>
This was the <strong>third way</strong> to disable Software Reporter Tool using Chrome Policies. Follow the below steps.
<ol>
 	<li>Open the<strong> Run command dialog box</strong> using the shortcut key <strong>Windows +R.</strong></li>
 	<li>Then type <strong>regedit </strong>in the given space of open and click <strong>OK</strong>.</li>
 	<li>The <strong>Registry Editor</strong> window will get open.</li>
 	<li>In the left pane, select the <strong>Computer option.</strong></li>
 	<li>Click the dropdown arrow of the Computer and select <strong>HKEY_LOCAL_MACHINE.</strong></li>
 	<li>Again click the dropdown arrow of HKEY_LOCAL_MACHINE and select<strong> SOFTWARE.</strong></li>
 	<li>Once more click the dropdown arrow of SOFTWARE and select<strong> Policies.</strong></li>
 	<li>Under Policies, click <strong>Google\Chrome.</strong></li>
 	<li>If these folders don’t exist on your system, you will need to <strong>create</strong> them.</li>
 	<li>When you are in the chrome folder, in the right pane, right-click, and select <strong>New</strong>.</li>
 	<li>Then create the following DWORD (32-bit) value:
<strong>ChromeCleanupEnabled</strong></li>
 	<li>Enter 0 for disabling the tool. Enter 1 to enable the tool.</li>
 	<li>Create another DWORD (32-bit) value with the following name:
<strong>ChromeCleanupReportingEnabled</strong></li>
 	<li>Enter 0 for disabling the reporting functionality. Enter 1 to enable the reporting functionality.</li>
 	<li>That's all.</li>
</ol>
<h2 id="5">Disable Software Reporter Tool using file permissions:</h2>
This was the <strong>fourth way</strong> to disable the Software Reporter Tool using file permissions. Follow the below steps.
<ol>
 	<li>Open<strong> file explorer.</strong></li>
 	<li>Then Go to %localappdata%\google\chrome\User Data\SwReporter\81.234.200\</li>
 	<li>After that, right-click <strong>software_reporter_tool.exe</strong> and select <strong>Properties</strong>.</li>
 	<li>In the <strong>Security</strong> tab, click the <strong>Edit</strong> button and remove all groups and users from the list.</li>
 	<li>Then, we need to check inheritance permissions of the file and remove all permissions from the object in the <strong>Advanced</strong> menu. To do this, go to the same <strong>security</strong> tab and then click on the <strong>Advanced</strong> button.</li>
 	<li>Click the <strong>Disable inheritance</strong> button and then remove all inherited permissions from this object one by one.</li>
 	<li>If you can’t remove the permissions, just select <strong>Deny</strong> from the permissions list for all users.</li>
 	<li>Then easy to<strong> disable the Google Chrome software reporter tool.</strong></li>
</ol>
<h2 id="6"><strong>Verdict:</strong></h2>
In the above article, we explained the clear cut steps to<strong> disable the Software Reporter Tool. </strong>Kindly leave if any queries and suggestions in the below comment section.
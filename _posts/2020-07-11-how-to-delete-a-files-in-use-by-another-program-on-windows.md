---
ID: 2002
post_title: >
  How to Delete a Files in Use by Another
  Program on Windows?
author: Olivia
post_excerpt: ""
layout: post
permalink: >
  https://windowsdot.com/how-to-delete-a-files-in-use-by-another-program-on-windows/
published: true
post_date: 2020-07-11 15:14:18
---
In this article, we silhouette<strong> How to Delete a File in Use by Another Program on Windows.</strong>
<ul class="toc">
 	<li><a href="#1">Simple ways to Overcome the File in Use Error</a></li>
 	<li><a href="#2">Unlock the File in Use with Third-party Tools</a></li>
 	<li><a href="#3">Synopsis</a></li>
</ul>
<h2 id="1">Simple ways to Overcome the File in Use Error:</h2>
Here the simple ways are listed below to Overcome the File in Use Error.
<ul>
 	<li>Close the program</li>
 	<li>Change File Explorer Process Settings</li>
 	<li>End the Application via the Task Manager</li>
 	<li>Use Windows Shadowcopy</li>
 	<li>Reboot your computer</li>
</ul>
<h3>Close the program:</h3>
<ol>
 	<li>First, we have started with the <strong>obvious</strong> way.</li>
 	<li>When you <strong>open</strong> the file and not <strong>close</strong> it.</li>
 	<li>After <strong>closing</strong> the file but the <strong>program</strong> is still running.</li>
 	<li>No problem just <strong>close</strong> it too, then <strong>try again.</strong></li>
</ol>
<h3>Change File Explorer Process Settings:</h3>
To restart the Explorer process in Windows 10, follow the below steps.
<ol>
 	<li>Press <strong>Ctrl + Shift + Esc</strong> to open <strong>Task Manager.</strong></li>
 	<li>Then in the <strong>Processes</strong> tab, <strong>locate</strong> Windows Explorer.</li>
 	<li>Now right click on the <strong>Windows Explorer</strong> and select <strong>Restart</strong>.

[caption id="attachment_2023" align="aligncenter" width="801"]<img class="size-full wp-image-2023" src="https://windowsdot.com/wp-content/uploads/2020/07/Taskmgr_VgjmSYa0Fa.png" alt="Task Manager" width="801" height="640" /> Task Manager[/caption]</li>
</ol>
If you are using Windows 8.1, Windows 7 or earlier, then follow the below steps to restart the Explorer process.
<ol>
 	<li>Press<strong> Ctrl + Shift + Esc</strong> to open Task Manager.</li>
 	<li>Then in the <strong>Processes</strong> tab, <strong>locate</strong> Windows Explorer.</li>
 	<li>Now<strong> right click</strong> on the Windows Explorer and select <strong><strong>End Task.</strong></strong>

[caption id="attachment_2022" align="aligncenter" width="797"]<img class="size-full wp-image-2022" src="https://windowsdot.com/wp-content/uploads/2020/07/Taskmgr_Vp6F78I9G5.png" alt="Task Manager" width="797" height="725" /> Task Manager[/caption]</li>
 	<li>Then, click the <strong>File</strong> and select <strong>Run new task.</strong></li>
 	<li>In the Create new task window, type<strong> explorer.exe</strong> in the given space box of <strong>Open</strong> and click <strong>OK</strong>.

[caption id="attachment_2020" align="aligncenter" width="457"]<img class="size-full wp-image-2020" src="https://windowsdot.com/wp-content/uploads/2020/07/Taskmgr_tY7y6QX14c.png" alt="New task" width="457" height="286" /> New task[/caption]</li>
 	<li>This will help you to start <strong>Windows Explorer</strong> again.</li>
</ol>
Follow the below steps to open each file explorer process is a separate window.
<ol>
 	<li>Make use of the shortcut <strong>Windows + E</strong> to open File Explorer.</li>
 	<li>In the <strong>File Explorer</strong> window, click on the <strong>View</strong> option.</li>
 	<li>Now, select the <strong>Options</strong>, then the<strong> Folder options</strong> window gets appear.

[caption id="attachment_2018" align="aligncenter" width="954"]<img class="size-full wp-image-2018" src="https://windowsdot.com/wp-content/uploads/2020/07/explorer_trbugYyo2y.png" alt="Options" width="954" height="337" /> Options[/caption]</li>
 	<li>Click on the <strong>View</strong> tab and <strong>check in</strong> the option Launch folder windows in a separate process.

[caption id="attachment_2017" align="aligncenter" width="496"]<img class="size-full wp-image-2017" src="https://windowsdot.com/wp-content/uploads/2020/07/explorer_HotUCbwEbX.png" alt="View" width="496" height="570" /> View[/caption]</li>
</ol>
<h3>End the Application via the Task Manager:</h3>
<ol>
 	<li>Press <strong>Ctrl + Shift + Esc</strong> to open <strong>Task Manager.</strong></li>
 	<li>Then in the <strong>Processes</strong> tab, <strong>browse</strong> for the application that you used to open the file in use.</li>
 	<li>Now <strong>right-click</strong> on it and select <strong>End</strong> <strong>Task</strong>.

[caption id="attachment_2019" align="aligncenter" width="805"]<img class="size-full wp-image-2019" src="https://windowsdot.com/wp-content/uploads/2020/07/Taskmgr_nTBsT66GA8.png" alt="Task Manager" width="805" height="733" /> Task Manager[/caption]</li>
</ol>
<h3>Use Windows Shadowcopy:</h3>
Windows Shadowcopy can be used to extract a copy of the file being used by the system itself. Just follow the below steps.
<ol>
 	<li>Go to the <strong>start menu.</strong></li>
 	<li>In the search column, type as <strong>Command Prompt.</strong></li>
 	<li>Right-click on it and select <strong>Run as Administrator</strong> option.

[caption id="attachment_2016" align="aligncenter" width="470"]<img class="size-full wp-image-2016" src="https://windowsdot.com/wp-content/uploads/2020/07/WVgDiYJ5u6.png" alt="Start Menu" width="470" height="768" /> Start Menu[/caption]</li>
 	<li>Now run the <strong>following</strong> command.
<pre><code>esentutl /y &lt;SOURCE&gt; /vss /d &lt;DEST&gt; </code></pre>
</li>
</ol>
<strong>Note</strong>: Replace &lt;SOURCE&gt; and &lt;DEST&gt; with the source and destination paths.

Here the <strong>example</strong> for you to easily understand,
<pre><code>esentutl /y C:\Windows\regedit.exe /VSS /d E:\regedit.exe</code></pre>
<h3>Reboot your computer:</h3>
When the above methods do not fix the problem simply try to <strong>restart</strong> your computer. A clean boot is preferable because it will not cache anything in the memory.
<h2 id="2">Unlock the File in Use with Third-party Tools:</h2>
When you can't delete the file after trying the above steps, then your file gets locked up to unlock you will need third-party tools.
<ul>
 	<li>Microsoft Process Explorer</li>
 	<li>IObit Unlocker</li>
 	<li>LockHunter</li>
</ul>
<h3>Microsoft Process Explorer:</h3>
<ol>
 	<li>First, you have to download the <a href="https://docs.microsoft.com/en-us/sysinternals/downloads/process-explorer"><strong>Microsoft Process Explorer</strong></a>.</li>
 	<li>Extract the downloaded <strong>zip</strong> file and <strong>run</strong> the <strong>setup</strong> process.</li>
 	<li>Now, in the Microsoft Process Explorer window <strong>click</strong> on the <strong>Find</strong> and <strong>select</strong> Find handle or DLL.</li>
 	<li>The <strong>window</strong> gets open in that, enter the<strong> file name</strong> which you want to delete/rename/move and press the Search.</li>
 	<li>Then it takes a few minutes and <strong>listed</strong> down the locked files.</li>
</ol>
<h3>IObit Unlocker:</h3>
<ol>
 	<li>Download the <a href="https://www.iobit.com/en/iobit-unlocker.php"><strong>IObit Unlocker</strong></a> here.</li>
 	<li>Click the <strong>Add</strong> button to open the <strong>Unlocker</strong> <strong>window</strong> and <strong>add</strong> multiple files to Unlock.</li>
 	<li>Else simply <strong>right-click</strong> the stubborn file and <strong>select</strong> IObit Unlocker.</li>
 	<li>Then, it <strong>listed</strong> the locked files and you can <strong>press</strong> the <strong>Unlock</strong> button to free the file.</li>
</ol>
<h3>LockHunter:</h3>
<ol>
 	<li>Download the <a href="https://lockhunter.com/download.htm"><strong>LockHunter</strong> </a>here.</li>
 	<li>In the <strong>LockHunter</strong> window, adds a context menu by the name What is locking this file?.</li>
 	<li><strong>Right-click</strong> the file and simply select What is locking this file?.</li>
 	<li><strong>LockHunter</strong> will come up with multiple options.</li>
</ol>
<h2 id="3">Synopsis:</h2>
Hoping that the above article will give clear information on <strong>How to Delete a File in Use by Another Program on Windows.</strong> Share the <strong>comments</strong> in the below section and drop your <strong>valuable feedback.</strong>
<h2>Related Articles:</h2>
<ul>
 	<li><a href="https://windowsdot.com/view-hide-security-tab-in-windows-10-simple-guide/" rel="nofollow"><strong>View/Hide Security tab in Windows 10</strong></a></li>
 	<li><a href="https://windowsdot.com/how-to-download-install-windows-media-center-on-windows-10/" rel="nofollow"><strong>Download &amp; Install Windows Media Center on Windows 10</strong></a></li>
 	<li><a href="https://windowsdot.com/quick-way-to-reset-network-adapter-in-windows-10/" rel="nofollow"><strong>To Reset Network Adaptor in Windows 10</strong></a></li>
 	<li><a href="https://windowsdot.com/quick-guide-cant-open-downloads-in-windows-10/" rel="nofollow"><strong>Fix - Can't Open Downloads in Windows 10</strong></a></li>
</ul>
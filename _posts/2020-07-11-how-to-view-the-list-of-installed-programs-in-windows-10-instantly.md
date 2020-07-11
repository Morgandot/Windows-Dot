---
ID: 2013
post_title: 'How to View the List of Installed Programs in Windows 10? {Instantly}'
author: Helena
post_excerpt: ""
layout: post
permalink: >
  https://windowsdot.com/how-to-view-the-list-of-installed-programs-in-windows-10-instantly/
published: true
post_date: 2020-07-11 15:42:27
---
This guide lets you <strong>View the List of Installed Programs in Windows 10 </strong>in different ways.
<ul class="toc">
 	<li><a href="#1">List of Installed Programs in Windows 10</a></li>
 	<li><a href="#2">View the List of Installed Programs via Command Prompt</a></li>
 	<li><a href="#3">Use PowerShell to Get the List of Installed Programs</a></li>
 	<li><a href="#4">View the List of Installed Programs through Control Panel</a></li>
 	<li><a href="#5">Generate the List of Installed Programs - Using CCleaner</a></li>
 	<li><a href="#6">Sum-up</a></li>
</ul>
<h2 id="1">List of Installed Programs in Windows 10:</h2>
If you own a Windows PC, you will probably have a list of many installed programs and might not remember all of them. That forgotten software takes up more disk space and it can be a security risk. It is highly recommended to uninstall any unused programs properly on Windows 10.

If you don't know what you have installed if you are managing several PCs at once, then there are four different ways to generate or view a list of installed programs.
<h2 id="2">Way 1: View the List of Installed Programs via Command Prompt</h2>
<ol>
 	<li>Click on the <strong>Windows key</strong> to open the <strong>Start</strong> menu.</li>
 	<li>In the search box, you have to type <strong>‘cmd’</strong>. Right-click on the result and choose <strong>Run as administrator</strong>. (If prompted, you have to press <strong>‘Yes’</strong> in the User Account Control window.)

[caption id="attachment_1682" align="alignnone" width="1318"]<img class="size-full wp-image-1682" src="https://windowsdot.com/wp-content/uploads/2020/06/Command-Prompt-2.png" alt="Command Prompt" width="1318" height="882" /> Command Prompt[/caption]</li>
 	<li>You have to copy and paste the below command and hit <strong>Enter</strong>. <code>Wmic product get name,version</code>

[caption id="attachment_2035" align="alignnone" width="874"]<img class="size-full wp-image-2035" src="https://windowsdot.com/wp-content/uploads/2020/07/Command-Prompt-Command.png" alt="Command Prompt - Command" width="874" height="571" /> Command Prompt - Command[/caption]</li>
 	<li>Now, you can see the list of all installed programs shortly and its version.</li>
</ol>
<h2 id="3">Way 2: Use PowerShell to Get the List of Installed Programs</h2>
<ol>
 	<li>Go to the <strong>Start</strong> menu, search for <strong>'powershell' </strong>and hit <strong>Enter</strong>.

[caption id="attachment_2038" align="alignnone" width="1116"]<img class="size-full wp-image-2038" src="https://windowsdot.com/wp-content/uploads/2020/07/PowerShell-1.png" alt="PowerShell" width="1116" height="853" /> PowerShell[/caption]</li>
 	<li>Run the following command and hit <strong>Enter</strong>. <code>Get-ItemProperty HKLM:\Software\Wow6432Node\Microsoft\Windows\CurrentVersion\Uninstall\* | Select-Object DisplayName, DisplayVersion, Publisher, InstallDate |Format-Table -AutoSize</code></li>
 	<li>You can view the list of all installed programs with the name, version, publisher, and installed date.

[caption id="attachment_2037" align="alignnone" width="1215"]<img class="size-full wp-image-2037" src="https://windowsdot.com/wp-content/uploads/2020/07/PowerShell-Command.png" alt="PowerShell - Command" width="1215" height="564" /> PowerShell - Command[/caption]</li>
 	<li>If you want to export the list, you have to run this command and hit Enter.  <code>Get-ItemProperty HKLM:\Software\Wow6432Node\Microsoft\Windows\CurrentVersion\Uninstall\* | Select-Object DisplayName, DisplayVersion, Publisher, InstallDate |Format-Table –AutoSize &gt; C:\Users\Documents\InstalledPrograms-PS.txt.</code></li>
 	<li>In the above command, you can change the required folder path as per your needs.</li>
</ol>
<h2 id="4">Way 3: View the List of Installed Programs through Control Panel</h2>
<ol>
 	<li>Go to the <strong>Start</strong> menu and type ‘<strong>control panel</strong>‘ in the search box and hit <strong>Enter</strong>.

[caption id="attachment_1977" align="alignnone" width="1091"]<img class="size-full wp-image-1977" src="https://windowsdot.com/wp-content/uploads/2020/07/Control-Panel.png" alt="Control Panel" width="1091" height="854" /> Control Panel[/caption]</li>
 	<li>You have to click <strong>Uninstall a program</strong> under <strong>Programs</strong>.

[caption id="attachment_2039" align="alignnone" width="1104"]<img class="size-full wp-image-2039" src="https://windowsdot.com/wp-content/uploads/2020/07/Uninstall-a-program.png" alt="Uninstall a program" width="1104" height="689" /> Uninstall a program[/caption]</li>
 	<li>Now, you can view the list of installed programs on your computer. You can change the view to <strong>Details</strong> so you can see the Name, Publisher, Size, Version, and Installed date.

[caption id="attachment_2036" align="alignnone" width="1248"]<img class="size-full wp-image-2036" src="https://windowsdot.com/wp-content/uploads/2020/07/Details.png" alt="Details" width="1248" height="719" /> Details[/caption]</li>
 	<li>You can take screenshots and save it on your PC so you can refer whenever you need it.</li>
</ol>
<h2 id="5">Way 4: Generate the List of Installed Programs - Using CCleaner</h2>
CCleaner is a useful tool to enhance the performance of your computer by deleting temporary and unwanted files. In addition, you can view the list of installed programs with the help of this utility.
<ol>
 	<li>You just go to <strong>Tools -&gt; Uninstall</strong> to view the list of all installed programs in your system.</li>
 	<li>After that, you have to click the '<strong>Save as txt file</strong>' button so you can save this text file in your preferred location.</li>
 	<li>If you don't have this tool, you can <a href="https://www.ccleaner.com/ccleaner/download" target="_blank" rel="noopener noreferrer"><strong>Download CCleaner</strong></a> from the official site.</li>
</ol>
<h2 id="6">Sum-up:</h2>
We hope that this guide assisted you to <strong>View the List of Installed Programs in Windows 10</strong>. The steps explained in this article let you understand the ways simpler. Kindly share your valuable <strong>comments/feedback</strong> in the below section. Check out more interesting articles in <a href="https://windowsdot.com/"><strong>Windows Dot</strong></a>.
<h2>Keep Reading:</h2>
<ul>
 	<li><strong><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsdot.com/fix-this-site-cant-be-reached-error-in-google-chrome-instantly/" target="_blank" rel="noopener noreferrer">Fix 'This Site Can't Be Reached' Error in Google Chrome!! [Instantly]</a></strong></li>
 	<li><strong><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsdot.com/how-to-save-google-chrome-history-2-ways/" target="_blank" rel="noopener noreferrer">How to Save Google Chrome History?- {2 Ways}</a></strong></li>
 	<li><strong><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsdot.com/3-easy-ways-enable-disable-focus-assist-in-windows-10/" target="_blank" rel="noopener noreferrer">[3 Easy Ways] Enable/Disable Focus Assist in Windows 10!!</a></strong></li>
 	<li><strong><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsdot.com/easily-rotate-screen-on-windows-10-and-fix-keyboard-shortcut-not-working/" target="_blank" rel="noopener noreferrer">{Easily} Rotate Screen on Windows 10 and Fix Keyboard Shortcut Not Working!!</a></strong></li>
</ul>
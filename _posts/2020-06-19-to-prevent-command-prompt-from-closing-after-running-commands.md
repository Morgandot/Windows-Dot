---
ID: 1249
post_title: >
  To prevent Command Prompt from closing
  after running commands!!
author: Olivia
post_excerpt: ""
layout: post
permalink: >
  https://windowsdot.com/to-prevent-command-prompt-from-closing-after-running-commands/
published: true
post_date: 2020-06-19 04:13:42
---
In this article, we illustrate an outline of <strong>how to prevent Command Prompt from closing after running commands</strong> (Batch File Pause) in three different ways.
<ul class="toc">
 	<li><a href="#1">First Way - Adding cmd /k</a></li>
 	<li><a href="#2">Second Way - Adding PAUSE</a></li>
 	<li><a href="#3">Third Way - Adding a Registry Key</a></li>
 	<li><a href="#4">Closure</a></li>
</ul>
<h2 id="1">First Way - Adding cmd /k:</h2>
<ul>
 	<li>This is the <strong>very easy and handy way</strong> to prevent the Command Prompt window from closing after running commands.</li>
</ul>
Follow the below steps to prevent Command Prompt from closing after running commands.
<ul>
 	<li>Go to the<strong> start menu.</strong></li>
 	<li>In the search column, type as <strong>File Explorer.</strong></li>
 	<li><strong>Tap</strong> it which appears at the top of the start menu.</li>
</ul>
[caption id="attachment_1261" align="aligncenter" width="830"]<img class="size-full wp-image-1261" src="https://windowsdot.com/wp-content/uploads/2020/06/Screenshot_8-8.png" alt="File Explorer" width="830" height="660" /> File Explorer[/caption]
<ul>
 	<li>Then locate the <strong>Batch</strong> file.</li>
 	<li><strong>Right-click</strong> on it and select the <strong>Edit</strong> option to open the <strong>batch file in Notepad.</strong></li>
</ul>
[caption id="attachment_1251" align="aligncenter" width="1122"]<img class="size-full wp-image-1251" src="https://windowsdot.com/wp-content/uploads/2020/06/Screenshot_1-27.png" alt="Edit" width="1122" height="464" /> Edit[/caption]
<ul>
 	<li>Simply, <strong>copy and paste</strong> the <strong>following command</strong> at the <strong>end of your batch file.</strong>
<pre><code>cmd /k</code></pre>
</li>
</ul>
[caption id="attachment_1252" align="aligncenter" width="1005"]<img class="size-full wp-image-1252" src="https://windowsdot.com/wp-content/uploads/2020/06/Screenshot_2-27.png" alt="cmd /k" width="1005" height="466" /> cmd /k[/caption]
<ul>
 	<li>Then save your Notepad File by pressing<strong> Ctrl + S</strong> and <strong>close</strong> the Notepad Window.</li>
 	<li>Now<strong>, double-click</strong> on your .bat file.</li>
 	<li>You will see that <strong>Command Prompt (CMD)</strong> will remain open as long as you want it to stay open.</li>
</ul>
[caption id="attachment_1253" align="aligncenter" width="772"]<img class="size-full wp-image-1253" src="https://windowsdot.com/wp-content/uploads/2020/06/Screenshot_3-27.png" alt="Command Prompt" width="772" height="546" /> Command Prompt[/caption]
<ul>
 	<li>That's all.</li>
</ul>
<h2 id="2">Second Way - Adding PAUSE:</h2>
<ul>
 	<li>First, open the <strong>File Explorer.</strong></li>
 	<li>Then locate the <strong>Batch</strong> file.</li>
 	<li><strong>Right-click</strong> on it and select the <strong>Edit</strong> option to open the <strong>batch</strong> file in <strong>Notepad</strong>.</li>
</ul>
[caption id="attachment_1251" align="aligncenter" width="1122"]<img class="size-full wp-image-1251" src="https://windowsdot.com/wp-content/uploads/2020/06/Screenshot_1-27.png" alt="Edit" width="1122" height="464" /> Edit[/caption]
<ul>
 	<li>Now, add the <strong>PAUSE</strong> word at the<strong> end of your batch file.</strong></li>
</ul>
[caption id="attachment_1254" align="aligncenter" width="1006"]<img class="size-full wp-image-1254" src="https://windowsdot.com/wp-content/uploads/2020/06/Screenshot_4-21.png" alt="PAUSE" width="1006" height="517" /> PAUSE[/caption]
<ul>
 	<li>Then save your Notepad File by pressing<strong> Ctrl + S</strong> and <strong>close</strong> the Notepad Window.</li>
 	<li>Now,<strong> double-click</strong> on your .bat file.</li>
 	<li>This will keep the <strong>Command Prompt</strong> window open until you do not press any key.</li>
</ul>
[caption id="attachment_1255" align="aligncenter" width="777"]<img class="size-full wp-image-1255" src="https://windowsdot.com/wp-content/uploads/2020/06/Screenshot_5-20.png" alt="Command Prompt" width="777" height="553" /> Command Prompt[/caption]
<ul>
 	<li>Then, you can easily see each command which had run on the result of bat file in<strong> CMD</strong> as long as you do not press any key.</li>
 	<li>That's all.</li>
</ul>
<h2 id="3">Third Way - Adding a Registry Key:</h2>
<ul>
 	<li>Go to the <strong>start menu.</strong></li>
 	<li>In the search column, type as <strong>Notepad</strong>.</li>
 	<li><strong>Tap</strong> it which appears at the top of the start menu.</li>
</ul>
[caption id="attachment_1260" align="aligncenter" width="826"]<img class="size-full wp-image-1260" src="https://windowsdot.com/wp-content/uploads/2020/06/Screenshot_7-13.png" alt="Notepad" width="826" height="664" /> Notepad[/caption]
<ul>
 	<li>Now, in the Notepad Window <strong>copy and paste</strong> the following commands.</li>
 	<li>Then <strong>save the file</strong> with the <strong> .reg extension.</strong></li>
</ul>
<pre><code>Windows Registry Editor Version 5.00

[HKEY_CLASSES_ROOT\Applications\powershell.exe\shell\open\command]
@=”\ ”C:\\Windows\\System32\\WindowsPowerShell\\v1.0\\powershell.exe\” –noExit \ “&amp; \\\ “%1\\\ ”\””

[HKEY_CLASSES_ROOT\Microsoft.PowerShellScript.1\Shell\0\Command]
@=”\ “C:\\Windows\\System32\\WindowsPowerShell\\v1.0\\powershell.exe\ “ –NoExit \ “-Command\” \”if ( ( Get-ExecutionPolicy ) –ne ‘AllSigned’) { Set-ExecutionPolicy –Scope Process Bypass }; &amp; \\\ ”%1” \\\ “\””</code></pre>
[caption id="attachment_1257" align="aligncenter" width="923"]<img class="size-full wp-image-1257" src="https://windowsdot.com/wp-content/uploads/2020/06/Screenshot_10-3.png" alt="Notepad" width="923" height="596" /> Notepad[/caption]
<ul>
 	<li>After saving the file, <strong>double-click</strong> on it.</li>
 	<li>This registry will save to your<strong> Registry Editor of Windows.</strong></li>
</ul>
[caption id="attachment_1258" align="aligncenter" width="1122"]<img class="size-full wp-image-1258" src="https://windowsdot.com/wp-content/uploads/2020/06/Screenshot_11-3.png" alt="Saved File" width="1122" height="432" /> Saved File[/caption]
<ul>
 	<li>Now run any command, the <strong>Command Prompt window</strong> will stay open as long as you will keep it open.</li>
</ul>
<h2 id="4">Closure:</h2>
In the above article, you can get a piece of brief information on <strong>how to prevent Command Prompt from closing after running commands (Batch File Pause) in three different ways.</strong> Kindly share the <strong>suggestions/queries</strong> in the below comment box and drop your worthwhile <strong>feedback.</strong>

&nbsp;
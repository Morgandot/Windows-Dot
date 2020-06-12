---
ID: 975
post_title: 'Renaming Computer in Windows 10!! [3 Ways]'
author: Olivia
post_excerpt: ""
layout: post
permalink: >
  https://windowsdot.com/renaming-computer-in-windows-10-3-ways/
published: true
post_date: 2020-06-12 14:18:08
---
In this article, we give an outline of <strong>How to renaming the computer in Windows 10</strong> in different ways.
<ul class="toc">
 	<li><a href="#1">Rename the computer using command prompt</a></li>
 	<li><a href="#2">Rename the computer using the control panel</a></li>
 	<li><a href="#3">Rename the computer using Windows Settings</a></li>
 	<li><a href="#4">Closure</a></li>
</ul>
<h2 id="1">Rename the computer using command prompt:</h2>
Follow the below to Rename the computer using command prompt in simple steps.
<ol>
 	<li>Go to the<strong> start menu.</strong></li>
 	<li>Type as <strong>Command Prompt</strong> in the search column.</li>
 	<li>Then, right-click the command prompt and select as<strong> Run as administrator.</strong>

[caption id="attachment_647" align="aligncenter" width="485"]<img class="wp-image-647 size-full" src="https://windowsdot.com/wp-content/uploads/2020/06/Screenshot_5-1.png" alt="Start Menu" width="485" height="772" /> Start Menu[/caption]</li>
 	<li>Now, <strong>run</strong> the following command in Command Prompt.
<pre><code>WMIC computersystem where caption=“CurrentPCName” rename “NewPCName”</code></pre>
</li>
 	<li>If you want to <strong>find</strong> the current system name. Then <strong>run</strong> the following command.
<pre><code>hostname</code></pre>
</li>
 	<li>Then, If you want to <strong>change</strong> the system name of a remote computer.</li>
 	<li><strong>Copy and paste</strong> the below command in your command prompt.
<pre><code>WMIC /node:“CurrentSystemName” /user:Admin /password:AdminPassword 
computersystem call rename “NewSystemName”</code></pre>
</li>
 	<li>That's all.</li>
</ol>
<h2 id="2">Rename the computer using Control Panel:</h2>
Follow the below to Rename the computer using Control Panel in simple steps.
<ol>
 	<li>Make use of the shortcut <strong>Windows + R</strong> to open the Run command dialog box.</li>
 	<li>Type as <strong>systempropertiescomputername</strong> in the given space box of Open.</li>
 	<li>Click OK.

[caption id="attachment_979" align="aligncenter" width="448"]<img class="wp-image-979 size-full" src="https://windowsdot.com/wp-content/uploads/2020/06/Screenshot_3-17.png" alt="Run command " width="448" height="269" /> Run command[/caption]</li>
 	<li>It will open the System Properties window with the <strong>Computer Name</strong> tab.</li>
 	<li>In that, click the <strong>Change</strong> button.

[caption id="attachment_977" align="aligncenter" width="542"]<img class="wp-image-977 size-full" src="https://windowsdot.com/wp-content/uploads/2020/06/Screenshot_1-17.png" alt="Change" width="542" height="570" /> Change[/caption]</li>
 	<li>The next windows get open, in that you can change the computer name, domain, and workgroup.</li>
 	<li>In the <strong>Computer name</strong> section, delete the old name and input the new computer name.

[caption id="attachment_978" align="aligncenter" width="537"]<img class="wp-image-978 size-full" src="https://windowsdot.com/wp-content/uploads/2020/06/Screenshot_2-17.png" alt="New name" width="537" height="564" /> New name[/caption]</li>
 	<li>The dialog box opens and asks you must <strong>restart</strong> your computer to apply these changes.</li>
 	<li>So, you want to click <strong>OK</strong>.</li>
 	<li>The<strong> new system</strong> name will be applied after restarting.</li>
 	<li>That's all.</li>
</ol>
<h2 id="3">Rename the computer using Settings:</h2>
Follow the below to Rename the computer using Settings in simple steps.
<ol>
 	<li style="list-style-type: none;">
<ol>
 	<li>Make use of the shortcut <strong>Windows + I</strong> to open Windows Settings.</li>
 	<li>Select the <strong>System</strong> option in the Settings window.

[caption id="attachment_980" align="aligncenter" width="1102"]<img class="wp-image-980 size-full" src="https://windowsdot.com/wp-content/uploads/2020/06/Screenshot_4-12.png" alt="Settings" width="1102" height="669" /> Settings[/caption]</li>
 	<li>In the left pane of the system, click the <strong>About</strong> option.</li>
 	<li>Then, in the right pane, click on the <strong>Rename</strong> <strong>PC</strong> option.

[caption id="attachment_981" align="aligncenter" width="1100"]<img class="wp-image-981 size-full" src="https://windowsdot.com/wp-content/uploads/2020/06/Screenshot_5-11.png" alt="About" width="1100" height="762" /> About[/caption]</li>
 	<li>In the next window, type your <strong>new</strong> <strong>system</strong> name.</li>
 	<li>Click Next.

[caption id="attachment_982" align="aligncenter" width="848"]<img class="wp-image-982 size-full" src="https://windowsdot.com/wp-content/uploads/2020/06/Screenshot_6-9.png" alt="New name" width="848" height="369" /> New name[/caption]</li>
 	<li>Then, click the <strong>restart</strong> in the next dialog box.</li>
 	<li>In that, you can choose either restart the system immediately or restart later.</li>
</ol>
</li>
</ol>
<ol>
 	<li>After the restart, the system will display the <strong>new name.</strong></li>
 	<li>That's all.</li>
</ol>
<h2 id="4">Closure:</h2>
In the above article, you can get a piece of brief information on <strong>How to renaming the computer in Windows 10</strong> by using different methods with clear cut<strong> screenshots.</strong> Kindly share the <strong>suggestions/queries</strong> in the below comment box and drop your worthwhile <strong>feedback.</strong>
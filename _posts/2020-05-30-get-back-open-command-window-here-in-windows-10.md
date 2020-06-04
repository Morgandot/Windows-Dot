---
ID: 457
post_title: >
  Get back Open Command Window Here in
  Windows 10!!
author: Helena
post_excerpt: ""
layout: post
permalink: >
  https://windowsdot.com/get-back-open-command-window-here-in-windows-10/
published: true
post_date: 2020-05-30 15:45:54
---
In this tutorial, we will show you the ways to get back the <strong>Open Command Window Here</strong> to the context menu in Windows 10.
<ul class="toc">
 	<li><a href="#1">Open Command Window Here</a></li>
 	<li><a href="#2">Add 'Open Command Window Here' to Folder Context Menu</a></li>
 	<li><a href="#3">Adding 'Open Command Window Here' to Background Context Menu</a></li>
 	<li><a href="#4">Closure</a></li>
</ul>
<h2 id="1">Open Command Window Here:</h2>
Microsoft continues to remove the support of Command Prompt in favor of PowerShell in Windows 10. You will note that you cannot find the option of Command Prompt on the Power User menu (Windows key + X) and in the extended context menu (Shift + Right-click).

However, it is still possible to get back the option in Windows 10 even you can't find the option <strong>"Open command window here"</strong> in the context menu.
<h2 id="2">1) Add 'Open Command Windows Here' to Folder Context Menu:</h2>
<ol>
 	<li>Press <strong>Windows key + R</strong> to open the Run box.</li>
 	<li>Now, you have to type <strong>'regedit' </strong>and click <strong>OK</strong>. (If you get any pop-up from User Account Control, you have to press Yes) <code>regedit</code>

[caption id="attachment_489" align="alignnone" width="424"]<img class="size-full wp-image-489" src="https://windowsdot.com/wp-content/uploads/2020/05/cw1.png" alt="Regedit" width="424" height="228" /> Regedit[/caption]</li>
 	<li>It will open the <strong>Registry Editor</strong>.</li>
 	<li>In the left pane, you have to navigate to the following path. <code>HKEY_CLASSES_ROOT\Directory\shell\cmd</code></li>
 	<li>Now, you have to right-click on the <strong>cmd</strong> folder and choose <strong>Permissions</strong>.

[caption id="attachment_498" align="alignnone" width="962"]<img class="size-full wp-image-498" src="https://windowsdot.com/wp-content/uploads/2020/05/cw9.png" alt="Choose Permissions" width="962" height="548" /> Choose Permissions[/caption]</li>
 	<li>Then, tap on the <strong>Advanced</strong> button.

[caption id="attachment_499" align="alignnone" width="944"]<img class="size-full wp-image-499" src="https://windowsdot.com/wp-content/uploads/2020/05/cw10.png" alt="Advanced" width="944" height="552" /> Advanced[/caption]</li>
 	<li>Click on the <strong>Change</strong> link next to the <strong>Owner</strong>.

[caption id="attachment_492" align="alignnone" width="944"]<img class="size-full wp-image-492" src="https://windowsdot.com/wp-content/uploads/2020/05/cw4.png" alt="Change" width="944" height="544" /> Change[/caption]</li>
 	<li>Next, you have to type your account name in the given field and click <strong>Check Names</strong> to make sure you are typing the exact account name and click <strong>OK</strong>.

[caption id="attachment_493" align="alignnone" width="944"]<img class="size-full wp-image-493" src="https://windowsdot.com/wp-content/uploads/2020/05/cw5.png" alt="Check Names" width="944" height="552" /> Check Names[/caption]</li>
 	<li>Select the <strong>'Replace owner on subcontainers and objects'</strong> option.</li>
 	<li>Then, click <strong>Apply</strong> and <strong>OK</strong>.

[caption id="attachment_494" align="alignnone" width="944"]<img class="size-full wp-image-494" src="https://windowsdot.com/wp-content/uploads/2020/05/cw6.png" alt="Apply and OK" width="944" height="552" /> Apply and OK[/caption]</li>
 	<li>Choose the <strong>Administrators</strong> group on <strong>Permissions</strong>.</li>
 	<li>Under <strong>'Permissions for Administrators'</strong>, you have to select <strong>Allow</strong> for the <strong>Full Control</strong> option.</li>
 	<li>Click <strong>Apply</strong> and <strong>OK</strong>.

[caption id="attachment_500" align="alignnone" width="944"]<img class="size-full wp-image-500" src="https://windowsdot.com/wp-content/uploads/2020/05/cw11.png" alt="Click Apply and OK" width="944" height="552" /> Click Apply and OK[/caption]</li>
 	<li>Now, inside the <strong>cmd</strong> folder, you have to right-click on <strong>HideBasedOnVelocityId </strong>and choose <strong>Rename</strong>.

[caption id="attachment_501" align="alignnone" width="944"]<img class="size-full wp-image-501" src="https://windowsdot.com/wp-content/uploads/2020/05/cw12.png" alt="Rename" width="944" height="552" /> Rename[/caption]</li>
 	<li>Change the name from <strong>HideBasedOnVelocityId</strong> to <strong>ShowBasedOnVelocityId</strong>, and hit <strong>Enter</strong>.</li>
 	<li>Once you complete the above steps, place the cursor on the folder, press <strong>Shift + Right-click</strong> so it will display the context menu with the <strong>'Open command window here' </strong>option.</li>
</ol>
<h2 id="3">2) Add 'Open Command Windows Here' to Background Context Menu:</h2>
<ol>
 	<li>Press <strong>Windows key + R</strong> to open the Run box.</li>
 	<li>Now, you have to type <strong>'regedit' </strong>and click <strong>OK</strong>. (If you get any pop-up from User Account Control, you have to press Yes) <code>regedit</code>

[caption id="attachment_489" align="alignnone" width="424"]<img class="size-full wp-image-489" src="https://windowsdot.com/wp-content/uploads/2020/05/cw1.png" alt="Regedit" width="424" height="228" /> Regedit[/caption]</li>
 	<li>It will open the <strong>Registry Editor</strong>.</li>
 	<li>In the left pane, you have to navigate to the following path. <code>HKEY_CLASSES_ROOT\Directory\Background\shell\cmd</code></li>
 	<li>Now, you have to right-click on the <strong>cmd</strong> folder and choose <strong>Permissions</strong>.

[caption id="attachment_490" align="alignnone" width="944"]<img class="size-full wp-image-490" src="https://windowsdot.com/wp-content/uploads/2020/05/cw2.png" alt="Permissions" width="944" height="546" /> Permissions[/caption]</li>
 	<li>Then, tap on the <strong>Advanced</strong> button.

[caption id="attachment_491" align="alignnone" width="944"]<img class="size-full wp-image-491" src="https://windowsdot.com/wp-content/uploads/2020/05/cw3.png" alt="Advanced" width="944" height="544" /> Advanced[/caption]</li>
 	<li>Click on the <strong>Change</strong> link next to the <strong>Owner</strong>.

[caption id="attachment_492" align="alignnone" width="944"]<img class="size-full wp-image-492" src="https://windowsdot.com/wp-content/uploads/2020/05/cw4.png" alt="Change" width="944" height="544" /> Change[/caption]</li>
 	<li>Next, you have to type your account name in the given field and click <strong>Check Names</strong> to make sure you are typing the exact account name and click <strong>OK</strong>.

[caption id="attachment_493" align="alignnone" width="944"]<img class="size-full wp-image-493" src="https://windowsdot.com/wp-content/uploads/2020/05/cw5.png" alt="Check Names" width="944" height="552" /> Check Names[/caption]</li>
 	<li>Select the <strong>'Replace owner on subcontainers and objects'</strong> option.</li>
 	<li>Then, click <strong>Apply</strong> and <strong>OK</strong>.

[caption id="attachment_494" align="alignnone" width="944"]<img class="size-full wp-image-494" src="https://windowsdot.com/wp-content/uploads/2020/05/cw6.png" alt="Apply and OK" width="944" height="552" /> Apply and OK[/caption]</li>
 	<li>Choose the <strong>Administrators</strong> group on <strong>Permissions</strong>.</li>
 	<li>Under <strong>'Permissions for Administrators'</strong>, you have to select <strong>Allow</strong> for the <strong>Full Control</strong> option.</li>
 	<li>Click <strong>Apply</strong> and <strong>OK</strong>.

[caption id="attachment_495" align="alignnone" width="944"]<img class="size-full wp-image-495" src="https://windowsdot.com/wp-content/uploads/2020/05/cw7.png" alt="Administrator" width="944" height="552" /> Administrator[/caption]</li>
 	<li>Now, inside the <strong>cmd</strong> folder, you have to right-click on <strong>HideBasedOnVelocityId </strong>and choose <strong>Rename</strong>.

[caption id="attachment_496" align="alignnone" width="944"]<img class="size-full wp-image-496" src="https://windowsdot.com/wp-content/uploads/2020/05/cw8.png" alt="Rename" width="944" height="552" /> Rename[/caption]</li>
 	<li>Change the name from <strong>HideBasedOnVelocityId</strong> to <strong>ShowBasedOnVelocityId</strong>, and hit <strong>Enter</strong>.</li>
 	<li>Once you complete the above steps, place the cursor on the folder, press <strong>Shift + Right-click</strong> so it will display the context menu with the <strong>'Open command window here' </strong>option.</li>
</ol>
<h2 id="4">Closure:</h2>
Many users prefer Command Prompt to run commands. These articles helped you to get back the <strong>Open Command Window Here</strong> to the context menu in Windows. So, you can get a quick access to the utility in a particular location. Share your <strong>comments</strong> in the below section. Thanks for visiting <a href="https://windowsdot.com/"><strong>Windows Dot</strong></a>.
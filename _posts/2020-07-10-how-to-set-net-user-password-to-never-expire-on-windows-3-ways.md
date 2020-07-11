---
ID: 1898
post_title: >
  How to Set Net User Password to Never
  Expire on Windows? (3 Ways)
author: Helena
post_excerpt: ""
layout: post
permalink: >
  https://windowsdot.com/how-to-set-net-user-password-to-never-expire-on-windows-3-ways/
published: true
post_date: 2020-07-10 23:06:49
---
In this tutorial, we will show you three diverse ways to <strong>Set Net User Password to Never Expire on Windows</strong>.
<ul class="toc">
 	<li><a href="#1">Net User Password to Never Expire</a></li>
 	<li><a href="#2">Set Windows Password to Never Expire - Using User Management</a></li>
 	<li><a href="#3">Set Windows Password to Never Expire via Command Prompt</a></li>
 	<li><a href="#4">Use PowerShell to Configure Password Expiration</a></li>
 	<li><a href="#5">Verdict</a></li>
</ul>
<h2 id="1">Net User Password to Never Expire:</h2>
When you log into your Windows PC, you might receive a message that says 'Your password has expired and must be changed'. If the password expires, you will not be able to reset it remotely.

If you wish to disable the password expiration, it is possible to do it in different ways. We will show you three ways so you can set your password to never expire for a specific user or all users through user management, command prompt, and PowerShell.
<h2 id="2">1) Set Windows Password to Never Expire - Using User Management:</h2>
<strong>For a Specific User:</strong>
<ol>
 	<li>On your keyboard, you have to hit the <strong>Windows Key + R</strong> button combination to open the <strong>Run box</strong>.</li>
 	<li>Then, you have to type <strong>lusrmgr.msc </strong>and click <strong>OK</strong>.

[caption id="attachment_1932" align="alignnone" width="489"]<img class="size-full wp-image-1932" src="https://windowsdot.com/wp-content/uploads/2020/07/lusrmgr.msc_.png" alt="lusrmgr.msc" width="489" height="301" /> lusrmgr.msc[/caption]</li>
 	<li>In the left pane, you have to select the <strong>Users</strong>.</li>
 	<li>Now, you have to right-click on the user (which you want to configure) and navigate to <strong>Properties. </strong></li>
 	<li>In the <strong>General</strong> tab, you have to select the check-box of <strong>Password never expires</strong>. Alternatively, you can press the <strong>Alt + P</strong> shortcut.</li>
 	<li>After that, you have to click the <strong>Apply</strong> and <strong>OK</strong> button.</li>
</ol>
<strong>For All Users:</strong>
<ol>
 	<li>Open the <strong>Run command</strong> by using this shortcut <strong>Windows key + R</strong>.</li>
 	<li>Then, you have to type the below command and click <strong>OK</strong>. <code>gpedit.msc</code>

[caption id="attachment_1931" align="alignnone" width="484"]<img class="size-full wp-image-1931" src="https://windowsdot.com/wp-content/uploads/2020/07/gpedit.msc_.png" alt="gpedit.msc" width="484" height="300" /> gpedit.msc[/caption]</li>
 	<li>After that, you have to navigate to the following path.<code>Computer configuration –&gt; Windows Settings –&gt; Security Settings –&gt; Account Policies –&gt; Password Policy</code></li>
 	<li>Now, in the right pane, you have to double-click on the <strong>Maximum password age</strong> and set it value as <strong>0</strong>.</li>
 	<li>Once you set the value as 0, it will disable the password expiration feature.</li>
</ol>
<h2 id="3">2) Set Windows Password to Never Expire via Command Prompt:</h2>
<strong>For a Specific User:</strong>
<ol>
 	<li>Click on the <strong>Windows key</strong> to open the <strong>Start</strong> menu.</li>
 	<li>In the search box, you have to type <strong>‘cmd’</strong>. Right-click on the result and choose <strong>Run as administrator</strong>. (If prompted, you have to press <strong>‘Yes’</strong> in the User Account Control window.

[caption id="attachment_1682" align="alignnone" width="1318"]<img class="size-full wp-image-1682" src="https://windowsdot.com/wp-content/uploads/2020/06/Command-Prompt-2.png" alt="Command Prompt" width="1318" height="882" /> Command Prompt[/caption]</li>
 	<li>To view the current user names, you have to execute the following command and hit <strong>Enter</strong>.<code>net accounts</code></li>
 	<li>Run the below command and hit <strong>Enter</strong>.<code>wmic useraccount where “Name=’username'” set PasswordExpires=false</code></li>
 	<li>You have to replace username with your desired name of a user.</li>
</ol>
<strong>For All Users:</strong>
<ol>
 	<li>Click on the <strong>Windows key</strong> to open the <strong>Start</strong> menu.</li>
 	<li>In the search box, you have to type <strong>‘cmd’</strong>. Right-click on the result and choose <strong>Run as administrator</strong>. (If prompted, you have to press <strong>‘Yes’</strong> in the User Account Control window.

[caption id="attachment_1682" align="alignnone" width="1318"]<img class="size-full wp-image-1682" src="https://windowsdot.com/wp-content/uploads/2020/06/Command-Prompt-2.png" alt="Command Prompt" width="1318" height="882" /> Command Prompt[/caption]</li>
 	<li>Execute the following command and hit <strong>Enter</strong>.<code>net accounts /maxpwage:unlimited</code></li>
</ol>
<h2 id="4">3) Use PowerShell to Configure Password Expiration:</h2>
<strong>For a Specific User:</strong>
<ol>
 	<li>Go to the <strong>Start</strong> menu, search for <strong>‘powershell’ </strong>in the search box, right-click on the top result, and choose <strong>Run as administrator</strong> to open the PowerShell. (If prompted, you have to press <strong>Yes</strong> to confirm the User Account Control window.)

[caption id="attachment_1933" align="alignnone" width="1102"]<img class="size-full wp-image-1933" src="https://windowsdot.com/wp-content/uploads/2020/07/PowerShell.png" alt="PowerShell" width="1102" height="854" /> PowerShell[/caption]</li>
 	<li>Run the below command and hit <strong>Enter</strong>.<code>Set-LocalUser -Name “username” -PasswordNeverExpires 1</code></li>
 	<li>You have to replace username with your desired name of a user.</li>
</ol>
<h2 id="5">Verdict:</h2>
We hope that the above information assisted you to understand how to <strong>Set Net User Password to Never Expire on Windows</strong>. You just follow any one of the ways set the password to never expire for your local user accounts. If you found this article useful, kindly share your <strong>comments/feedback</strong> in the below section. Check out more interesting articles in <strong>Windows Dot</strong>.
<h2>Keep Reading:</h2>
<ul>
 	<li><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsdot.com/3-easy-ways-how-to-run-programs-as-administrator-in-windows-10/" target="_blank" rel="noopener noreferrer">(3 Easy Ways) How to Run Programs as Administrator in Windows 10?</a></li>
 	<li><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsdot.com/how-to-fix-exe-files-not-opening-in-windows-10/" target="_blank" rel="noopener noreferrer">How to Fix Exe Files Not Opening In Windows 10?</a></li>
 	<li><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsdot.com/quickly-run-windows-update-from-command-line-in-windows-10/" target="_blank" rel="noopener noreferrer">{Quickly} Run Windows Update from Command Line in Windows 10!!</a></li>
 	<li><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsdot.com/how-to-check-windows-10-uptime-4-quick-ways/" target="_blank" rel="noopener noreferrer">How to Check Windows 10 Uptime? {4 Quick Ways}</a></li>
</ul>
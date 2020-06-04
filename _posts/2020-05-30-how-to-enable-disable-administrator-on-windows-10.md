---
ID: 321
post_title: 'How to enable &#038; disable Administrator on Windows 10?'
author: Olivia
post_excerpt: ""
layout: post
permalink: >
  https://windowsdot.com/how-to-enable-disable-administrator-on-windows-10/
published: true
post_date: 2020-05-30 13:22:44
---
In this article, we have illustrated the silhouette of<strong> how to enable &amp; disable the Administrator account on Windows 10</strong> using three different methods. Follow the below article and use any one of the methods to enable &amp; disable it.
<ul class="toc">
 	<li><a href="#1">Administrator on Windows 10</a></li>
 	<li><a href="#2">Enable &amp; Disable Administrator using PowerShell</a></li>
 	<li><a href="#3">Enable &amp; Disable Administrator using Computer Management</a></li>
 	<li><a href="#4">Enable &amp; Disable Administrator using Command Prompt</a></li>
 	<li><a href="#5">Verdict</a></li>
</ul>
<h2 id="1"><strong><strong>Administrator on Windows 10:</strong></strong></h2>
The <strong>Administrator account</strong> is used for troubleshooting and management purposes. It is a built-in Administrator local account, but it’s <strong>disabled by default.</strong>
<h2 id="2">Enable &amp; Disable Administrator using PowerShell:</h2>
<h4><strong>To enable the administrator account using PowerShell use the below steps,</strong></h4>
<ol>
 	<li>Go to the<strong> Start Menu.</strong></li>
 	<li>In the search column, type as <strong>PowerShell.</strong></li>
 	<li>The icon will appear on the top of the start menu.</li>
 	<li><strong>Right-click</strong> the icon and select the option Run as administrator.

[caption id="attachment_327" align="aligncenter" width="485"]<img class="wp-image-327 size-full" src="https://windowsdot.com/wp-content/uploads/2020/05/Screenshot_4.png" alt="PowerShell" width="485" height="775" /> PowerShell[/caption]</li>
 	<li>Now, the<strong> PowerShell</strong> gets open, in that<strong> copy and paste</strong> the following command.
<pre><code>Get-LocalUser -Name "Administrator" | Enable-LocalUser</code></pre>
[caption id="attachment_329" align="aligncenter" width="1337"]<img class="wp-image-329 size-full" src="https://windowsdot.com/wp-content/uploads/2020/05/Screenshot_6.png" alt="Enable command " width="1337" height="477" /> Enable command[/caption]</li>
 	<li>That's all, Now the<strong> default Administrator account</strong> will be <strong>enabled</strong>, and available from the Sign-in screen.</li>
</ol>
<h4><strong>Just follow the below steps to disable the administrator account using PowerShell,</strong></h4>
<ol>
 	<li>Simply, follow the above<strong> enabling steps.</strong></li>
 	<li>The only change is don't copy the enabling command instead of just <strong>type the following command.</strong>
<pre><code>Get-LocalUser -Name "Administrator" | Disable-LocalUser</code></pre>
[caption id="attachment_330" align="aligncenter" width="1335"]<img class="wp-image-330 size-full" src="https://windowsdot.com/wp-content/uploads/2020/05/Screenshot_7.png" alt="Disable command " width="1335" height="470" /> Disable command[/caption]</li>
 	<li>That's all, Now the<strong> default Administrator account</strong> will be <strong>disabled.</strong></li>
</ol>
<h2 id="3">Enable &amp; Disable Administrator using Computer Management:</h2>
<h4><strong>Simply, </strong>use the below steps t<strong>o enable the administrator account using Computer Management</strong>,</h4>
<ol>
 	<li>Go to the<strong> Start Menu.</strong></li>
 	<li>In the search column, type as <strong>Computer Management.</strong></li>
 	<li>The icon will appear on the top of the start menu, simply <strong><strong>tap it.</strong></strong>

[caption id="attachment_328" align="aligncenter" width="481"]<img class="wp-image-328 size-full" src="https://windowsdot.com/wp-content/uploads/2020/05/Screenshot_5.png" alt="Computer Management" width="481" height="772" /> Computer Management[/caption]</li>
 	<li>Now it gets<strong> open.</strong></li>
 	<li>In the left pane, click the dropdown arrow of  <strong><strong>Local Users and Groups</strong></strong>

[caption id="attachment_331" align="aligncenter" width="1040"]<img class="wp-image-331 size-full" src="https://windowsdot.com/wp-content/uploads/2020/05/Screenshot_8.png" alt="Local Users and Groups " width="1040" height="574" /> Local Users and Groups[/caption]</li>
 	<li>Click the <strong>User option.</strong></li>
 	<li>Then, in the right pane, <strong>right-click</strong> on the <strong>Administrator account</strong> and select <strong><strong>Properties.</strong></strong>

[caption id="attachment_332" align="aligncenter" width="1014"]<img class="wp-image-332 size-full" src="https://windowsdot.com/wp-content/uploads/2020/05/Screenshot_9.png" alt="User" width="1014" height="566" /> User[/caption]</li>
 	<li>In the Administrator Properties window, check out the <strong>Account is disabled</strong> option.</li>
 	<li>Then click <strong>Apply</strong> and after that click <strong><strong>OK.</strong></strong>

[caption id="attachment_333" align="aligncenter" width="578"]<img class="wp-image-333 size-full" src="https://windowsdot.com/wp-content/uploads/2020/05/Screenshot_10.png" alt="Enable" width="578" height="636" /> Enable[/caption]</li>
 	<li>That's all, Now the <strong>default Administrator account</strong> will be <strong>enabled</strong>, and available from the Sign-in screen.</li>
</ol>
<h4><strong>To disable the administrator account using Computer Management</strong> use the below steps,</h4>
<ol>
 	<li><strong>Repeat the same steps</strong> which are explained in the above enabling method.</li>
 	<li>At last, you have to check-in the <strong>Account is disabled</strong> option in the Administrator Properties window.

[caption id="attachment_334" align="aligncenter" width="621"]<img class="wp-image-334 size-full" src="https://windowsdot.com/wp-content/uploads/2020/05/Screenshot_11.png" alt="Disable" width="621" height="645" /> Disable[/caption]</li>
 	<li>Then<strong> the default Administrator account</strong> will be <strong>disabled</strong></li>
</ol>
<h2 id="4">Enable &amp; Disable Administrator using Command Prompt:</h2>
<h4><strong>To enable the administrator account using Command Prompt</strong> use the below steps,</h4>
<ol>
 	<li>Go to the <strong>Start Menu.</strong></li>
 	<li>In the search column, type as <strong>Command Prompt.</strong></li>
 	<li>The icon will appear on the top of the start menu.</li>
 	<li><strong>Right-click</strong> the icon and select the option <strong><strong>Run as administrator.</strong></strong>

[caption id="attachment_324" align="aligncenter" width="489"]<img class="wp-image-324 size-full" src="https://windowsdot.com/wp-content/uploads/2020/05/Screenshot_1.png" alt="Command Prompt" width="489" height="779" /> Command Prompt[/caption]</li>
 	<li><strong>Copy &amp; Paste</strong> the following command to enable the built-in Administrator account and press <strong><strong>Enter.</strong></strong>
<pre><code>net user "Administrator" /active:yes</code></pre>
[caption id="attachment_325" align="aligncenter" width="1032"]<img class="wp-image-325 size-full" src="https://windowsdot.com/wp-content/uploads/2020/05/Screenshot_2.png" alt="Enable command " width="1032" height="490" /> Enable command[/caption]</li>
 	<li>That's all, Now you can sign out of the account and sign in with the <strong>Administrator account.</strong></li>
</ol>
<h4><strong>To disable the administrator account using Command Prompt</strong> use the below steps,</h4>
<ol>
 	<li>Follow the<strong> above steps</strong> which are explained in the enabling method using Command Prompt.</li>
 	<li><strong>Copy and paste</strong> the following command instead of copying the enabling command.
<pre><code>net user "Administrator" /active:no</code></pre>
[caption id="attachment_326" align="aligncenter" width="1028"]<img class="wp-image-326 size-full" src="https://windowsdot.com/wp-content/uploads/2020/05/Screenshot_3.png" alt="Disable command " width="1028" height="499" /> Disable command[/caption]</li>
 	<li>Now, the <strong>Administrator account gets disabled.</strong></li>
</ol>
<h2 id="5">Verdict:</h2>
Hoping that the above article will help you <strong>how to enable &amp; disable the Administrator account on Windows 10 </strong>by using simple steps with clear cut<strong> screenshots.</strong> Kindly share the <strong>suggestions/queries</strong> in the below comment box and drop your worthwhile <strong>feedback.</strong>
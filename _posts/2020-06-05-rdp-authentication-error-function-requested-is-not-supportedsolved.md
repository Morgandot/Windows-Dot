---
ID: 642
post_title: 'RDP Authentication Error Function Requested Is Not Supported!{SOLVED}'
author: Olivia
post_excerpt: ""
layout: post
permalink: >
  https://windowsdot.com/rdp-authentication-error-function-requested-is-not-supportedsolved/
published: true
post_date: 2020-06-05 06:28:26
---
Here, we give you the guidelines of <strong>how to solve if an Authentication Error has occurred the Function Requested Is Not Supported</strong> in different ways.
<ul class="toc">
 	<li><a href="#1">By using Group Policy Editor</a></li>
 	<li><a href="#2">By using Registry Editor</a></li>
 	<li><a href="#3">By installing and uninstalling updates from your computer</a></li>
 	<li><a href="#4">Verdict</a></li>
</ul>
Let’s go through some resolutions to this problem. Follow the below article!!
<h2 id="1">Way 1: By using Group Policy Editor</h2>
<ol>
 	<li>Make use of the shortcut <strong>Windows + R</strong> key to open the Run command dialog box.</li>
 	<li>Then type as <strong>gpedit.msc</strong> in the given space of open and click <strong><strong>OK.</strong></strong>

[caption id="attachment_644" align="aligncenter" width="475"]<img class="wp-image-644 size-full" src="https://windowsdot.com/wp-content/uploads/2020/06/Screenshot_2-2.png" alt="Run command dialog box" width="475" height="328" /> A run command dialog box[/caption]</li>
 	<li>The<strong> Group Policy Editor</strong> window gets open.</li>
 	<li>Select the <strong>Computer Configuration</strong> and click the dropdown arrow of<strong> Administrative templates</strong> and select <strong>System</strong>.

[caption id="attachment_645" align="aligncenter" width="937"]<img class="wp-image-645 size-full" src="https://windowsdot.com/wp-content/uploads/2020/06/Screenshot_3-2.png" alt="Group Policy Editor " width="937" height="662" /> Group Policy Editor[/caption]</li>
 	<li>Again click the dropdown arrow of System, select the option <strong><strong>Credentials Delegation.</strong></strong>

[caption id="attachment_646" align="aligncenter" width="935"]<img class="wp-image-646 size-full" src="https://windowsdot.com/wp-content/uploads/2020/06/Screenshot_4-1.png" alt="System" width="935" height="659" /> System[/caption]</li>
 	<li>Double-click the Credentials Delegation and select the option <strong>Encryption Oracle Remediation.</strong></li>
 	<li>Then the window gets open and select the <strong>Enabled</strong> and in the Protection level select the <strong>Vulnerable</strong>.

[caption id="attachment_643" align="aligncenter" width="657"]<img class="wp-image-643 size-full" src="https://windowsdot.com/wp-content/uploads/2020/06/Screenshot_1-2.png" alt="Encryption Oracle Remediation" width="657" height="613" /> Encryption Oracle Remediation[/caption]</li>
 	<li>After that go to start menu and in the search column type as <strong><strong>Command Prompt.</strong></strong>

[caption id="attachment_647" align="aligncenter" width="485"]<img class="wp-image-647 size-full" src="https://windowsdot.com/wp-content/uploads/2020/06/Screenshot_5-1.png" alt="Start Menu" width="485" height="772" /> Start Menu[/caption]</li>
 	<li><strong>Tap</strong> the option which it appears at the top of the start menu.</li>
 	<li>In the command prompt window, simply <strong>copy and paste</strong> the below command and press <strong>enter</strong> to proceed.
<pre><code>gpupdate /force</code></pre>
[caption id="attachment_648" align="aligncenter" width="755"]<img class="wp-image-648 size-full" src="https://windowsdot.com/wp-content/uploads/2020/06/Screenshot_6-1.png" alt="Command Prompt" width="755" height="472" /> Command Prompt[/caption]</li>
 	<li>That's all.</li>
</ol>
<h2 id="2">Way 2: By using Registry Editor</h2>
<ol>
 	<li>Use the shortcut <strong>Windows + R</strong> key to open the Run command dialog box.</li>
 	<li>Then type as <strong>regedit</strong> in the given space of open and click<strong> OK.</strong></li>
 	<li>The<strong> Registry Editor</strong> window gets open.</li>
 	<li>In that, select<strong> HKLM → Software → Microsoft → Windows → CurrentVersion → Policies → System → CredSSP → Parameters.</strong></li>
 	<li>After that, in the right pane edit the DWORD value of AllowEncrptionOracle key to 2.</li>
 	<li>Then if you can't find the key, you need to create it.</li>
</ol>
<h2 id="3">Way 3: By installing and uninstalling updates from your computer</h2>
<strong>Follow the steps to install updates:</strong>
<ul>
 	<li>Firstly, Go to Windows Update and check for updates.</li>
 	<li>Then install all the updates especially related to <strong>CVE-2018-0886.</strong></li>
 	<li>If you are using<strong> Windows Server 2016,</strong> you should install<strong> KB4103723</strong>  or if you are using <strong>Windows Server 2012 R2,</strong> then you should install<strong> KB4103725.</strong></li>
 	<li>Finally, a server reboot will be required after installing these updates.</li>
</ul>
<strong>Follow the steps to uninstall updates:</strong>
<ul>
 	<li>This is another workaround is to uninstall the updates from your computer.</li>
 	<li>If you are using<strong> Windows 10 Version 1709</strong>, you should uninstall the update <strong>KB4103727</strong> and <strong>KB4103718</strong> if you’re running <strong>Windows 7.</strong></li>
 	<li>Ultimately, uninstalling these updates requires the computer to be restarted.</li>
</ul>
<h2 id="4">Verdict:</h2>
In this article, we will help you to<strong> solve if an Authentication Error has occurred the Function Requested Is Not Supported</strong> using simple steps. Kindly share if any <strong>queries/suggestions</strong> in the below comment section and Don't forget to drop your worthwhile <strong>feedback.</strong>
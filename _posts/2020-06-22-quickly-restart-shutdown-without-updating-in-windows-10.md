---
ID: 1398
post_title: >
  Quickly Restart/Shutdown Without
  Updating in Windows 10!!
author: Helena
post_excerpt: ""
layout: post
permalink: >
  https://windowsdot.com/quickly-restart-shutdown-without-updating-in-windows-10/
published: true
post_date: 2020-06-22 06:19:47
---
In this guide, we will explain diverse methods with clear-cut steps on how to <strong>Restart/Shutdown Without Updating in Windows 10</strong>.
<ul class="toc">
 	<li><a href="#1">Restart/Shutdown Without Updating</a></li>
 	<li><a href="#2">Disable 'Install Updates and Shut Down' option</a></li>
 	<li><a href="#3">How to Disable Automatic Updates?</a></li>
 	<li><a href="#4">Evade Windows Updates Using Command Line</a></li>
 	<li><a href="#5">Summary</a></li>
</ul>
<h2 id="1">Restart/Shutdown Without Updating:</h2>
Windows has always offered updates in order to provide better features to its users. If you update your system, you can get rid of security risks and bugs. But, there are times when you have to wait for a long time for your PC to update during important works or office hours.

Further, these sorts of updates may slow down your system while you are in urge to restart or shutdown your system. In some cases, you will be forced to reboot your PC to complete the update process or the system will be restarted without your awareness.

It is not possible to disable Windows updates because it is mandatory to install updates. You just follow the below solutions so you can restart or shutdown your device without installing updates.
<h2 id="2">1) Disable 'Install Updates and Shut Down' option:</h2>
If you want to avoid installing updates while you are going to restart or shut down your system, you have to make use of the <a href="https://windowsdot.com/how-to-download-enable-gpedit-msc-on-windows-10-home-edition/"><strong>gpedit.msc</strong></a> command to open the <strong>Local Group Policy Editor</strong>.
<ol>
 	<li>You have to open the <strong>Run command</strong> by using this shortcut <strong>Windows key + R</strong>.</li>
 	<li>Type the below command and click OK. <code>gpedit.msc</code>

[caption id="attachment_1411" align="alignnone" width="570"]<img class="size-full wp-image-1411" src="https://windowsdot.com/wp-content/uploads/2020/06/re2.png" alt="gpedit.msc" width="570" height="337" /> gpedit.msc[/caption]</li>
 	<li>It will open the <strong>Local Group Policy Editor</strong>.

[caption id="attachment_269" align="alignnone" width="763"]<img class="size-full wp-image-269" src="https://windowsdot.com/wp-content/uploads/2020/05/gp3.png" alt="Group Policy Editor" width="763" height="495" /> Group Policy Editor[/caption]</li>
 	<li>Navigate to this path: <code>Computer Configuration\Administrative Templates\Windows Components\Windows Update</code></li>
 	<li>You have to double-click on "<strong>Do not display ‘Install Updates and Shut Down’ option in Shut Down Windows dialog box</strong>".

[caption id="attachment_1420" align="alignnone" width="1400"]<img class="size-full wp-image-1420" src="https://windowsdot.com/wp-content/uploads/2020/06/re9.png" alt="Do not display ‘Install Updates and Shut Down’ option in Shut Down Windows dialog box" width="1400" height="795" /> Do not display ‘Install Updates and Shut Down’ option in Shut Down Windows dialog box[/caption]</li>
 	<li>Choose <strong>Enabled</strong> option and click <strong>Apply</strong> and <strong>OK</strong> button.

[caption id="attachment_1421" align="alignnone" width="1028"]<img class="size-full wp-image-1421" src="https://windowsdot.com/wp-content/uploads/2020/06/re10.png" alt="Disabled" width="1028" height="949" /> Disabled[/caption]</li>
 	<li>After that, you cannot find the 'Install Updates and Shut Down' option in the Shutdown dialog box. You can find a normal Shut down option only.</li>
 	<li>If you want to install the updates, you have to go to Settings -&gt; Update &amp; Security -&gt; Windows Update.</li>
</ol>
<h2 id="3">2) How to Disable Automatic Updates?</h2>
<ol>
 	<li>You have to press <strong>Windows key + R</strong> to open the <strong>Run Command</strong>.</li>
 	<li>Enter the below command and click <strong>OK</strong>. <code>services.msc</code>

[caption id="attachment_1410" align="alignnone" width="570"]<img class="size-full wp-image-1410" src="https://windowsdot.com/wp-content/uploads/2020/06/re1.png" alt="services.msc" width="570" height="337" /> services.msc[/caption]</li>
 	<li>In the <strong>Services</strong> window, you have to scroll down and locate the <strong>Windows Update </strong>service.

[caption id="attachment_1417" align="alignnone" width="1208"]<img class="size-full wp-image-1417" src="https://windowsdot.com/wp-content/uploads/2020/06/re8.png" alt="Windows Update" width="1208" height="889" /> Windows Update[/caption]</li>
 	<li>Double-click on the Windows Update service so it will open the <strong>Windows Update Properties</strong> window.</li>
 	<li>In the <strong>Startup type</strong>, you have to change the option to <strong><strong>Disabled.</strong></strong></li>
 	<li>You have to click the <strong>Apply </strong>button and then <strong>OK</strong>.

[caption id="attachment_1416" align="alignnone" width="608"]<img class="size-full wp-image-1416" src="https://windowsdot.com/wp-content/uploads/2020/06/re7.png" alt="Disabled" width="608" height="702" /> Disabled[/caption]</li>
</ol>
<h2 id="4">3) Evade Windows Updates Using Command Line:</h2>
<ol>
 	<li>Open the <strong>Run command</strong> by using this keyboard shortcut <strong>Windows key + R</strong>.</li>
 	<li>At first, we have to stop the update service. To do so, type <code>net stop wuauserv</code> and click <strong>OK</strong>.

[caption id="attachment_1413" align="alignnone" width="570"]<img class="size-full wp-image-1413" src="https://windowsdot.com/wp-content/uploads/2020/06/re4.png" alt="net stop wuauserv" width="570" height="337" /> net stop wuauserv[/caption]</li>
 	<li>To restart your PC, type <code>shutdown -r -t 0</code> , and hit <strong>Enter</strong>.

[caption id="attachment_1415" align="alignnone" width="570"]<img class="size-full wp-image-1415" src="https://windowsdot.com/wp-content/uploads/2020/06/re6.png" alt="shutdown -r -t 0" width="570" height="337" /> shutdown -r -t 0[/caption]</li>
 	<li>If you want to shut down your system, you have to run this command and hit <strong>Enter</strong>.<code>shutdown -s -t 0</code>

[caption id="attachment_1412" align="alignnone" width="570"]<img class="size-full wp-image-1412" src="https://windowsdot.com/wp-content/uploads/2020/06/re3.png" alt="shutdown -s -t 0" width="570" height="337" /> shutdown -s -t 0[/caption]</li>
 	<li>You can also execute both commands at the same time. Run this command to restart your system without installing updates and hit <strong>Enter</strong>. <code>net stop wuauserv &amp;&amp; shutdown -r -t 0</code>

[caption id="attachment_1414" align="alignnone" width="570"]<img class="size-full wp-image-1414" src="https://windowsdot.com/wp-content/uploads/2020/06/re5.png" alt="net stop wuauserv &amp;&amp; shutdown -r -t 0" width="570" height="337" /> net stop wuauserv &amp;&amp; shutdown -r -t 0[/caption]</li>
</ol>
<h2 id="5">Summary:</h2>
If you follow the methods described above, you can <strong>Restart/Shutdown Without Updating in Windows 10 </strong>quickly. Let us know which method worked well for you. Convey us your <strong>feedback</strong> about this article in the below section. Thanks for visiting <strong>Windows Dot</strong>.
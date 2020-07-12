---
ID: 2105
post_title: '[3 Easy Methods] How to Hide Programs on Windows 10?'
author: Helena
post_excerpt: ""
layout: post
permalink: >
  https://windowsdot.com/3-easy-methods-how-to-hide-programs-on-windows-10/
published: true
post_date: 2020-07-12 07:31:27
---
In this Windows 10 guide, we will discuss <strong>how to Hide Programs on Windows 10 </strong>in three dissimilar methods.
<ul class="toc">
 	<li><a href="#1">Hide Programs on Windows 10</a></li>
 	<li><a href="#2">Hide Programs via Registry Editor</a></li>
 	<li><a href="#3">Use Group Policy Editor to Hide Programs</a></li>
 	<li><a href="#4">Third-Party Tool to Hide Programs</a></li>
 	<li><a href="#5">Closure</a></li>
</ul>
<h2 id="1"><strong>Hide Programs On Windows 10</strong></h2>
Do you have programs installed on your PC that you don't want any person to know about for security or privacy purpose? If this is the case, it is possible to hide programs from the Control Panel and Settings so that no one will know that the programs are installed. Further, it helps you to secure any important programs from removing or uninstalling by others.

We have covered three methods that allow you to hide programs from the Control Panel and Settings app either manually or using the third-party tool. Once you hide the programs, it cannot be uninstalled or no one will be able to find out if you ever installed it.
<h2 id="2">Method 1: Hide Programs via Registry Editor</h2>
<ol>
 	<li>Here, we are going to hide the VLC media player from installed programs.

[caption id="attachment_2118" align="alignnone" width="1104"]<img class="size-full wp-image-2118" src="https://windowsdot.com/wp-content/uploads/2020/07/VLC-showing-in-installed-programs.png" alt="VLC showing in installed programs" width="1104" height="692" /> VLC showing in installed programs[/caption]</li>
 	<li>Hit this keyboard combination <strong>Windows key + R</strong> to open the <strong>Run command.</strong></li>
 	<li>You have to type the below command and click <strong>OK</strong>. <code>regedit</code>

[caption id="attachment_2054" align="alignnone" width="491"]<img class="size-full wp-image-2054" src="https://windowsdot.com/wp-content/uploads/2020/07/regedit.png" alt="regedit" width="491" height="300" /> regedit[/caption]</li>
 	<li>For a <strong>32-bit program</strong>, you have to navigate to the following path.<code>HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Uninstall</code></li>
 	<li>If an application is <strong>32-bit and your OS is 64-bit</strong>, you have to navigate to the following path.<code>HKEY_LOCAL_MACHINE\SOFTWARE\Wow6432Node\Microsoft\Windows\CurrentVersion\Uninstall</code></li>
 	<li>If you want to hide VLC Media Player, you have to right-click on that folder and navigate to <strong>New -&gt; DWORD (32-bit) Value</strong>.

[caption id="attachment_2119" align="alignnone" width="1348"]<img class="size-full wp-image-2119" src="https://windowsdot.com/wp-content/uploads/2020/07/New-DWORD-Value.png" alt="New DWORD Value" width="1348" height="861" /> New DWORD Value[/caption]</li>
 	<li>You have to name the new value as <strong>SystemComponent</strong> and set its value as <strong>1 </strong>and click<strong><strong> OK.</strong></strong>

[caption id="attachment_2116" align="alignnone" width="1335"]<img class="size-full wp-image-2116" src="https://windowsdot.com/wp-content/uploads/2020/07/Set-value-as-1.png" alt="Set value as 1" width="1335" height="862" /> Set value as 1[/caption]

&nbsp;</li>
 	<li>Refresh the Control Panel or Settings and now, the VLC media player is not showing in the list.

[caption id="attachment_2117" align="alignnone" width="1105"]<img class="size-full wp-image-2117" src="https://windowsdot.com/wp-content/uploads/2020/07/VLC-not-showing.png" alt="VLC not showing" width="1105" height="692" /> VLC not showing[/caption]</li>
 	<li>If you delete that new value, you can see the application again in the list of installed programs.</li>
</ol>
<h2 id="3">Method 2: Use Group Policy Editor to Hide Programs</h2>
<ol>
 	<li>Open the <strong>Run command</strong> by using this shortcut <strong>Windows key + R</strong>.</li>
 	<li>Then, you have to type the below command and click <strong>OK</strong>. <code>gpedit.msc</code>

[caption id="attachment_1931" align="alignnone" width="484"]<img class="size-full wp-image-1931" src="https://windowsdot.com/wp-content/uploads/2020/07/gpedit.msc_.png" alt="gpedit.msc" width="484" height="300" /> gpedit.msc[/caption]</li>
 	<li>After that, you have to navigate to the following path.<code>User Configuration -&gt; Administrative Templates -&gt; Control Panel -&gt; Programs</code></li>
 	<li>Now, on the right side, you have to double-click on the <strong>Hide Programs and Features page. </strong></li>
 	<li>You have to select the <strong>Enabled</strong> option and click <strong>Apply</strong> and <strong>OK</strong> button.</li>
</ol>
<h2 id="4">Method 3: Third-Party Tool to Hide Programs</h2>
Those who don't wish to hide programs manually can make use of '<strong>Hide Programs</strong>' which is a tool to hide any program in your system.
<ol>
 	<li>First, you have to download <a href="https://download.cnet.com/Hide-Programs/3000-2094_4-10727390.html" target="_blank" rel="noopener noreferrer"><strong>Hide Programs</strong></a>.</li>
 	<li>After that, install it in your device.</li>
 	<li>Open the tool so you can see the programs installed on your system.</li>
 	<li>You just need to select the check-box near to the application so that the application will disappear if you choose the <strong>Hide checked</strong> button.</li>
 	<li>You can make use of <strong>Show checked</strong> or <strong>Hide checked</strong> button as per your preference.

[caption id="attachment_2115" align="alignnone" width="750"]<img class="size-full wp-image-2115" src="https://windowsdot.com/wp-content/uploads/2020/07/Hide-Programs-Tool.png" alt="Hide Programs Tool" width="750" height="663" /> Hide Programs Tool[/caption]</li>
</ol>
<h2 id="5">Closure:</h2>
That's it. We have well informed regarding <strong>how to Hide Programs on Windows 10</strong>. We hope that this article with three methods lets you hide programs so no one can find the installed programs in your system. Kindly, share your valuable <strong>comments</strong> to enhance our write-up. Check out more interesting articles in <strong>Windows Dot</strong>.
<h2>Keep Reading:</h2>
<ul>
 	<li><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsdot.com/3-simple-methods-to-turn-off-inprivate-browsing-instantly/" target="_blank" rel="noopener noreferrer"><strong>3 Simple Methods to Turn Off InPrivate Browsing Instantly!!</strong></a></li>
 	<li><strong><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsdot.com/disable-windows-defender-in-windows-10-5-simple-ways/" target="_blank" rel="noopener noreferrer">Disable Windows Defender in Windows 10!! (*5 Simple Ways*)</a></strong></li>
 	<li><strong><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsdot.com/how-to-view-the-list-of-installed-programs-in-windows-10-instantly/" target="_blank" rel="noopener noreferrer">How to View the List of Installed Programs in Windows 10? {Instantly}</a></strong></li>
</ul>
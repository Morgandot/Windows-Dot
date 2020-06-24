---
ID: 1517
post_title: >
  3 Simple Methods to Turn Off InPrivate
  Browsing Instantly!!
author: Helena
post_excerpt: ""
layout: post
permalink: >
  https://windowsdot.com/3-simple-methods-to-turn-off-inprivate-browsing-instantly/
published: true
post_date: 2020-06-24 12:57:05
---
In this article, you will learn three different methods of <strong>Turning Off InPrivate Browing</strong> in all browsers.
<ul class="toc">
 	<li><a href="#1">Disable InPrivate Browsing</a></li>
 	<li><a href="#2">Turn off InPrivate Browing via Group Policy Editor</a></li>
 	<li><a href="#3">Use Registry Editor to Turn off In-Private Browsing</a></li>
 	<li><a href="#4">Disable Incognito Mode - Using Third-Party Tool</a></li>
 	<li><a href="#5">Wrap-up</a></li>
</ul>
<h2 id="1">Disable InPrivate Browsing:</h2>
Private browsing lets you surf the web without saving browsing history. It is referred to as InPrivate Browsing in Internet Explorer, Private Browsing in Mozilla Firefox, and Incognito Mode in Google Chrome.

If you want to prevent users from private browsing in all browsers like IE, Chrome, Edge, and Firefox, you can attain it by following three simple methods that will be described in this post. Those who want to track the activity of their users properly will find this article useful.
<h2 id="2">1) Turn off InPrivate Browing via Group Policy Editor:</h2>
If you want to turn off in-private browsing in IE, you have to follow the below steps.
<ol>
 	<li>Open the <strong>Run command</strong> by using this shortcut <strong>Windows key + R</strong>.</li>
 	<li>Then, you have to type the below command and click <strong>OK</strong>. <code>gpedit.msc</code>

[caption id="attachment_1411" align="alignnone" width="570"]<img class="size-full wp-image-1411" src="https://windowsdot.com/wp-content/uploads/2020/06/re2.png" alt="gpedit.msc" width="570" height="337" /> gpedit.msc[/caption]</li>
 	<li>It will open the <strong>Local Group Policy Editor</strong>.</li>
 	<li>Navigate to this path for IE: <code>Computer Configuration\Administrative Templates\Windows Components\Internet Explorer\Privacy</code></li>
 	<li>You have to double-click on "<strong>Turn off InPrivate Browsing</strong>" on the right-hand side.

[caption id="attachment_1522" align="alignnone" width="1158"]<img class="size-full wp-image-1522" src="https://windowsdot.com/wp-content/uploads/2020/06/in1.png" alt="Turn off InPrivate Browsing" width="1158" height="778" /> Turn off InPrivate Browsing[/caption]</li>
 	<li>Then, you have to choose the <strong>Enabled</strong> option and then click the <strong>Apply</strong> and <strong>OK</strong> button.

[caption id="attachment_1523" align="alignnone" width="1028"]<img class="size-full wp-image-1523" src="https://windowsdot.com/wp-content/uploads/2020/06/in2.png" alt="Enabled" width="1028" height="954" /> Enabled[/caption]</li>
</ol>
<blockquote><strong>Tip:</strong> Navigate to this path for Microsoft Edge: <code>Computer Configuration\Administrative Templates\Windows Components\Microsoft Edge</code>. Enable '<strong>Allow InPrivate browsing</strong>' feature.</blockquote>
<h2 id="3">2) Use Registry Editor to Turn off InPrivate Browsing:</h2>
<ol>
 	<li>Press <strong>Windows key + R</strong> to open the <strong>Run box</strong>.</li>
 	<li>Now, you have to type the below command and click <strong>OK</strong>. (If you get any pop-up from User Account Control, you have to press Yes) <code>regedit</code>

[caption id="attachment_1375" align="alignnone" width="570"]<img class="size-full wp-image-1375" src="https://windowsdot.com/wp-content/uploads/2020/06/iis4.png" alt="regedit" width="570" height="337" /> regedit[/caption]</li>
 	<li>It will open the <strong>Registry Editor</strong>.</li>
 	<li>In the left pane, you have to navigate to the following path. <code>HKEY_CURRENT_USER\Software\Policies\Microsoft</code></li>
 	<li>You have to right-click on the <strong>Microsoft</strong> folder -&gt; <strong>New</strong> -&gt; <strong>Key</strong> and create a new key with the name <strong>Internet Explorer</strong>.

[caption id="attachment_1524" align="alignnone" width="1207"]<img class="size-full wp-image-1524" src="https://windowsdot.com/wp-content/uploads/2020/06/in3.png" alt="New and Key" width="1207" height="808" /> New and Key[/caption]</li>
 	<li>After that, right-click on the <strong>Internet Explorer</strong> folder -&gt; <strong>New</strong> -&gt; <strong>Key</strong> and create a new key with the name <strong>Privacy</strong>.</li>
 	<li> Select the Privacy folder and then right-click on the white space of RHS and choose the option <strong>DWORD (32-bit) value</strong> and name it as '<strong>EnableInPrivate</strong>'.

[caption id="attachment_1525" align="alignnone" width="1211"]<img class="size-full wp-image-1525" src="https://windowsdot.com/wp-content/uploads/2020/06/in4.png" alt="DWORD (32-bit) value" width="1211" height="741" /> DWORD (32-bit) value[/caption]</li>
 	<li>Now, you have to double-click on that value and set the <strong>Value data</strong> to '<strong>0</strong>' and click <strong>OK</strong>.

[caption id="attachment_1526" align="alignnone" width="1198"]<img class="size-full wp-image-1526" src="https://windowsdot.com/wp-content/uploads/2020/06/in5.png" alt="Enter 0" width="1198" height="740" /> Enter 0[/caption]</li>
 	<li>Once you complete the above steps, you just close the registry editor. So, the users will not be able to browse in the InPrivate Browsing mode in the IE browser.</li>
</ol>
<h2 id="4">3) Disable Incognito Mode - Using Third-Party Tool:</h2>
It is possible to disable incognito mode with the help of a third-party application. <a href="http://incognitogone.com/" target="_blank" rel="noopener noreferrer">Incognito Gone</a> is a small tool that is available at free of cost. Using this tool, you can disable incognito mode or private browsing in the browsers.
<h2 id="5">Wrap-up:</h2>
The simple methods illustrated in this article let you understand about <strong>Turning Off InPrivate Browing </strong>in all browsers. We hope that the above three methods helped you in the right way. Your <strong>comments</strong> are highly welcomed as it enhances our write-up. Thanks for visiting <b>Windows Dot.</b>
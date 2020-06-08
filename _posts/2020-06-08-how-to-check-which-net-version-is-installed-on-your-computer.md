---
ID: 740
post_title: >
  How to check which .Net Version is
  installed on your computer?
author: Olivia
post_excerpt: ""
layout: post
permalink: >
  https://windowsdot.com/how-to-check-which-net-version-is-installed-on-your-computer/
published: true
post_date: 2020-06-08 09:58:18
---
In this article, we will give some tips <strong>to check which .Net Version is installed on your computer</strong> using two different methods.
<ul class="toc">
 	<li><a href="#1">Check which .Net Version is installed on your computer</a></li>
 	<li><a href="#2">Conclusion</a></li>
</ul>
<h2 id="1">Check which .Net Version is installed on your computer:</h2>
<h3>Method 1: By using the Windows directory</h3>
Follow the below steps to check which .Net Version is installed on your computer using the Windows directory.
<ul>
 	<li>Go to the <strong>Start Menu.</strong></li>
 	<li>Then in the search column, type as <strong>Command Prompt.</strong></li>
 	<li><strong>Tap</strong> the icon in which it appears at the top of the start menu.

[caption id="attachment_647" align="aligncenter" width="485"]<img class="wp-image-647 size-full" src="https://windowsdot.com/wp-content/uploads/2020/06/Screenshot_5-1.png" alt="Start Menu" width="485" height="772" /> Start Menu[/caption]</li>
 	<li>Then, <strong>copy</strong> the following command and <strong>paste</strong> it in the Command Prompt window.</li>
 	<li>Press <strong>Enter</strong> to proceed.</li>
</ul>
<pre><code>dir %windir%\Microsoft.NET\Framework /AD</code></pre>
[caption id="attachment_744" align="aligncenter" width="948"]<img class="wp-image-744 size-full" src="https://windowsdot.com/wp-content/uploads/2020/06/Screenshot_1-6.png" alt="Commands" width="948" height="559" /> Commands[/caption]
<ul>
 	<li>The<strong> above command</strong> shows the list of all the directories with all the versions installed along with the latest ones.</li>
 	<li>When you are in the directory than to check which the latest version is installed.</li>
 	<li>Then <strong>copy</strong> and <strong>paste</strong> the following command.</li>
</ul>
<pre><code>.\MSBuild.exe -version</code></pre>
<ul>
 	<li><strong>For instance,</strong> if I want to check the exact version for .NET Framework 4, then run the following commands in sequence.</li>
</ul>
<pre><code>dir %windir%\Microsoft.NET\Framework /AD
cd %windir%\Microsoft.NET\Framework\v4.0.30319
.\MSBuild.exe -version</code></pre>
<h3>Method 2: By using the WMIC</h3>
Follow the below steps to check which .Net Version is installed on your computer using WMIC command.
<ul>
 	<li>List down the default .NET Framework being used by the system by using the <strong>WMIC command,</strong> which is given below.</li>
</ul>
<pre><code>wmic product get description | findstr /C:.NET</code></pre>
<ul>
 	<li>Then, you want a<strong> list of all versions</strong> installed on your computer.</li>
 	<li>Then use the following command.</li>
</ul>
<pre><code>dir /b %windir%\Microsoft.NET\Framework\v*</code></pre>
[caption id="attachment_745" align="aligncenter" width="913"]<img class="wp-image-745 size-full" src="https://windowsdot.com/wp-content/uploads/2020/06/Screenshot_2-5.png" alt="Commands" width="913" height="457" /> Commands[/caption]
<ul>
 	<li>The above command is basically a rip-off of the first method.</li>
 	<li>This will not give you the<strong> exact version number</strong> as you still have to use the MSBuild command as listed above to get the exact version number.</li>
 	<li>That's all.</li>
</ul>
<h2 id="2">Conclusion:</h2>
In the above article, you can get a piece of brief information on <strong>How to check which .Net Version is installed on your computer using two different methods.</strong> Kindly share the <strong>suggestions/queries</strong> in the below comment box and drop your worthwhile <strong>feedback.</strong>
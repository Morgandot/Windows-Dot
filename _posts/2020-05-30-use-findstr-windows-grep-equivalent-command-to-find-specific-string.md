---
ID: 358
post_title: 'Use Findstr &#8211; Windows Grep Equivalent Command to Find Specific String!!'
author: Helena
post_excerpt: ""
layout: post
permalink: >
  https://windowsdot.com/use-findstr-windows-grep-equivalent-command-to-find-specific-string/
published: true
post_date: 2020-05-30 08:13:51
---
In this tutorial, we will illustrate how to use <strong>Findstr - Windows Grep Equivalent </strong>command to search and filter strings easily.
<ul class="toc">
 	<li><a href="#1">Findstr - Windows Grep Equivalent</a></li>
 	<li><a href="#2">Search &amp; Filter a String</a></li>
 	<li><a href="#3">Print only the Filename</a></li>
 	<li><a href="#4">Findstr - Help Command</a></li>
 	<li><a href="#5">A Brief Summary</a></li>
</ul>
<h2 id="1">Findstr - Windows Grep Equivalent:</h2>
<strong>Grep command </strong>in Linux is used to <strong>search and filter strings</strong> easily. You may wonder that there is an equivalent tool to grep command on Windows. <strong>'Findstr'</strong> is the command in Windows will do the same function as grep command.

It is a quite powerful search command like grep and we can use regular expression with it. Many users of Windows may not know how to find a specific string in files from the command-line.
<h2 id="2">Search &amp; Filter a String:</h2>
If you use '<strong>/M</strong>' with 'findstr' command it only <strong>prints the filename if a file contains a match</strong>.
<ul>
 	<li>Using this shortcut <strong>Windows key + R</strong>, you can open the Run command.</li>
 	<li>Type <strong>'cmd'</strong> and hit <strong>Enter</strong> to open the <strong>Command Prompt</strong>.

[caption id="attachment_382" align="alignnone" width="430"]<img class="size-full wp-image-382" src="https://windowsdot.com/wp-content/uploads/2020/05/wg4.png" alt="Command Prompt" width="430" height="229" /> Command Prompt[/caption]</li>
</ul>
<code>findstr "browser" "file2.txt"</code>
<ul>
 	<li>Replace your string in the place of the 'browser'.</li>
 	<li>Enter your file name in the place of 'file2.txt'.

[caption id="attachment_381" align="alignnone" width="764"]<img class="size-full wp-image-381" src="https://windowsdot.com/wp-content/uploads/2020/05/wg3.png" alt="Search a string" width="764" height="453" /> Search a string[/caption]</li>
</ul>
<h2 id="3">Print only the Filename:</h2>
If you use '<strong>/M</strong>' with 'findstr' command it only <strong>prints the filename if a file contains a match</strong>.

<code>findstr /M tutorial C:\Users\ZZZ\Folder*</code>
<ul>
 	<li>Replace your string in the place of 'tutorial'.</li>
 	<li>Enter your file location path in the place of 'C:\Users\ZZZ\Folder*'.

[caption id="attachment_380" align="alignnone" width="699"]<img class="size-full wp-image-380" src="https://windowsdot.com/wp-content/uploads/2020/05/wg2.png" alt="Print filename" width="699" height="430" /> Print filename[/caption]</li>
</ul>
<h2 id="4">Findstr - Help Command:</h2>
If you want to know more about 'findstr' command, you can get help from this command.

Execute the below command on the command prompt:

<code>findstr -?</code>

[caption id="attachment_379" align="alignnone" width="740"]<img class="size-full wp-image-379" src="https://windowsdot.com/wp-content/uploads/2020/05/wg1.png" alt="Findstr - Help" width="740" height="475" /> Findstr - Help[/caption]
<h2 id="5">A Brief Summary:</h2>
We hope that this tutorial helped you to understand how to use <strong>Findstr - Windows Grep Equivalent </strong>command to search and filter a string. Try different options for this command in your command-line so you will learn more about it. If you found this article useful, share your <strong>comments</strong> below. Thanks for visiting <a href="https://windowsdot.com/"><strong>Windows Dot</strong></a>.
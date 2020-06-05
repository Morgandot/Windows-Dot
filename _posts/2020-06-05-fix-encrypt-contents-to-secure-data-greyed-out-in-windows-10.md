---
ID: 659
post_title: 'Fix &#8220;Encrypt Contents to Secure Data&#8221; Greyed Out in Windows 10!!'
author: Helena
post_excerpt: ""
layout: post
permalink: >
  https://windowsdot.com/fix-encrypt-contents-to-secure-data-greyed-out-in-windows-10/
published: true
post_date: 2020-06-05 07:21:40
---
In this tutorial, you will learn how to fix <strong>"Encrypt Contents to Secure Data" Greyed Out</strong> in Windows 10.
<ul class="toc">
 	<li><a href="#1">Encrypt Contents to Secure Data Greyed Out</a></li>
 	<li><a href="#2">Enable EFS via Registry Editor</a></li>
 	<li><a href="#3">How to Enable EFS from Command Line</a></li>
 	<li><a href="#4">Enable EFS via Group Policy Editor</a></li>
 	<li><a href="#5">Closure</a></li>
</ul>
<h2 id="1">Encrypt Contents to Secure Data Greyed Out:</h2>
Many users like to encrypt the files and data in order to make sure about the privacy and security of data and files. In Windows 10, Encrypted File System (EFS) allows users to secure their information in a specific folder or drive. If you want to keep your data in private, this EFS will be useful so you can access the data from your Windows account only.

EFS is available in all editions of Windows 10 except Home edition. Sometimes, you may meet encrypt contents to secure data greyed out in Windows 10. In this scenario, you cannot encrypt your data and files. Let's look out the solutions to resolve this issue.
<h2 id="2">Solution 1: Enable EFS via Registry Editor</h2>
<ol>
 	<li>Press <strong>Windows key + R</strong> to open the Run box.</li>
 	<li>Now, you have to type <strong>'regedit' </strong>and click <strong>OK</strong>. (If you get any pop-up from User Account Control, you have to press Yes) <code>regedit</code>

[caption id="attachment_489" align="alignnone" width="424"]<img class="size-full wp-image-489" src="https://windowsdot.com/wp-content/uploads/2020/05/cw1.png" alt="Regedit" width="424" height="228" /> Regedit[/caption]</li>
 	<li>It will open the <strong>Registry Editor</strong>.</li>
 	<li>In the left pane, you have to navigate to the following path. <code>HKEY_LOCAL_MACHINE\System\CurrentControlSet\Control\FileSystem</code>

[caption id="attachment_671" align="alignnone" width="818"]<img class="size-full wp-image-671" src="https://windowsdot.com/wp-content/uploads/2020/06/en1.png" alt="File System" width="818" height="449" /> File System[/caption]</li>
 	<li>In the right-hand window, you have to look for the key named <strong><strong>NtfsDisableEncryption.</strong></strong>

[caption id="attachment_672" align="alignnone" width="826"]<img class="size-full wp-image-672" src="https://windowsdot.com/wp-content/uploads/2020/06/en2.png" alt="NtfsDisableEncryption" width="826" height="464" /> NtfsDisableEncryption[/caption]</li>
 	<li>Double-click on it and then set its value to<strong> 0 </strong>and click<strong> OK </strong>button.

[caption id="attachment_673" align="alignnone" width="817"]<img class="size-full wp-image-673" src="https://windowsdot.com/wp-content/uploads/2020/06/en3.png" alt="Set Value" width="817" height="450" /> Set Value[/caption]</li>
 	<li>Now, you just go back to the folder which you wish to encrypt. Then, navigate to <strong>Properties -&gt; Advanced -&gt; Advance Attributes</strong> option so you can see the encryption option is not greyed out.</li>
</ol>
<h2 id="3">Solution 2: How to Enable EFS from the Command Line?</h2>
<ol>
 	<li>Click on the <strong>Windows key</strong> to open the <strong>Start</strong> menu.</li>
 	<li>In the search box, you have to type <strong>'cmd'</strong>. Right-click on the result and choose <strong>Run as administrator</strong>. (If prompted, you have to press <strong>'Yes'</strong> in the User Account Control window.)

[caption id="attachment_255" align="alignnone" width="885"]<img class="size-full wp-image-255" src="https://windowsdot.com/wp-content/uploads/2020/05/wu1.png" alt="Command Prompt" width="885" height="678" /> Command Prompt[/caption]</li>
 	<li>Then, you have to copy and paste this command.<code>fsutil behavior set disableencryption 0</code>

[caption id="attachment_676" align="alignnone" width="689"]<img class="size-full wp-image-676" src="https://windowsdot.com/wp-content/uploads/2020/06/en4.png" alt="Command Prompt" width="689" height="424" /> Command Prompt[/caption]</li>
 	<li>It will ask you to reboot your computer if the command runs successfully.</li>
 	<li>Reboot your system and check the encryption option will now be available.</li>
</ol>
<p id="note"><strong>Note: </strong>Don't forget to hit <strong>Enter</strong> at the end of every command.</p>

<h2 id="4">Solution 3: Enable EFS via Group Policy Editor</h2>
<ol>
 	<li>You have to open the <strong>Run command</strong> by using this shortcut <strong>Windows key + R</strong>.</li>
 	<li>Type <strong>'gpedit.msc'</strong> and click <strong>OK</strong>.

[caption id="attachment_268" align="alignnone" width="428"]<img class="size-full wp-image-268" src="https://windowsdot.com/wp-content/uploads/2020/05/gp2.png" alt="Run gpedit.msc" width="428" height="234" /> Run gpedit.msc[/caption]</li>
 	<li>It will open the Group Policy Editor.

[caption id="attachment_269" align="alignnone" width="763"]<img class="size-full wp-image-269" src="https://windowsdot.com/wp-content/uploads/2020/05/gp3.png" alt="Group Policy Editor" width="763" height="495" /> Group Policy Editor[/caption]</li>
 	<li>Navigate to this path: <code>Computer Configuration\Administrative Templates\System\Filesystem\NTFS</code>

[caption id="attachment_677" align="alignnone" width="801"]<img class="size-full wp-image-677" src="https://windowsdot.com/wp-content/uploads/2020/06/en5.png" alt="Do not allow encryption on all NTFS volumes" width="801" height="573" /> Do not allow encryption on all NTFS volumes[/caption]</li>
 	<li>In the right pane, you have to double-click on the <strong>'Do not allow encryption on all NTFS volumes' </strong>policy to edit it.</li>
 	<li>Choose the <strong>Disabled</strong> option and click <strong>Apply</strong> and then <strong>OK</strong>.

[caption id="attachment_678" align="alignnone" width="822"]<img class="size-full wp-image-678" src="https://windowsdot.com/wp-content/uploads/2020/06/en6.png" alt="Disabled" width="822" height="691" /> Disabled[/caption]</li>
 	<li>Restart your system to apply the changes and then check the encryption option will not be greyed out.</li>
</ol>
<h2 id="5">Closure:</h2>
That's it. Now, we have fixed the issue. It's easy, right? We hope that this article on how to fix <strong>"Encrypt Contents to Secure Data" Greyed Out</strong> in Windows 10 helped you a lot. Kindly, share your valuable comments to enhance our write-up. Thanks for visiting <a href="https://windowsdot.com/"><strong>Windows Dot</strong></a>.
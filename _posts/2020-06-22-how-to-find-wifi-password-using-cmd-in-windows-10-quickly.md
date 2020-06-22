---
ID: 1383
post_title: 'How to Find Wifi Password Using CMD in Windows 10? {Quickly}'
author: Helena
post_excerpt: ""
layout: post
permalink: >
  https://windowsdot.com/how-to-find-wifi-password-using-cmd-in-windows-10-quickly/
published: true
post_date: 2020-06-22 00:42:25
---
In this post, you will learn how to <strong>Find Wifi Password Using CMD </strong>in Windows 10.
<ul class="toc">
 	<li><a href="#1">Know Wifi Password Using CMD</a></li>
 	<li><a href="#2">View the List of All Saved Wifi Profiles</a></li>
 	<li><a href="#3">Find Specific Wifi Network's Password</a></li>
 	<li><a href="#4">Conclusion</a></li>
</ul>
<h2 id="1">Know Wifi Password Using CMD:</h2>
Did you forget one of your wifi passwords? Do you want to find it right away? Using the Command Prompt (CMD), you can view a list of saved passwords of wireless networks that your computer has ever connected.

WLAN profiles are created whenever you enter wifi credentials and start a new connection. The profile of that wifi network includes necessary details like the network name, settings, and password. It is really very easy to know the wifi password from the command line as it can be achievable with few commands.

These commands will work even when you are offline or connected to some other wifi network. We will show you an easy way on how to know the wifi password from the command line in Windows 10. You just run the simple commands to view the password of any particular network. You can also refer to this article to <a href="https://windowsdot.com/how-to-find-saved-wi-fi-passwords-in-windows-10-3-easy-ways/">know the wifi password in three ways</a>.
<h2 id="2">View the List of All Saved Wifi Profiles:</h2>
<ol>
 	<li>Go to the <strong>Start</strong> menu.</li>
 	<li>In the search box, you have to type <strong>'cmd'</strong>. Then, you have to right-click on the top result and choose <strong>Run as administrator</strong>. (If prompted, you have to press <strong>'Yes'</strong> in the User Account Control window.)

[caption id="attachment_1393" align="alignnone" width="1319"]<img class="size-full wp-image-1393" src="https://windowsdot.com/wp-content/uploads/2020/06/wi1.png" alt="Command Prompt" width="1319" height="881" /> Command Prompt[/caption]</li>
 	<li>Now, you have to run this command and hit <strong>Enter</strong> to view the list of all saved wireless profiles: <code>netsh wlan show profile</code>

[caption id="attachment_1391" align="alignnone" width="1132"]<img class="size-full wp-image-1391" src="https://windowsdot.com/wp-content/uploads/2020/06/wi3.png" alt="View WLAN Profiles" width="1132" height="672" /> View WLAN Profiles[/caption]</li>
 	<li>After that, you have to note down the name of the wifi network for which you need to know the password.</li>
</ol>
<h2 id="3">Find Specific Wifi Network's Password:</h2>
<ol>
 	<li>You can execute the below command in the same Command Prompt window.</li>
 	<li>Run this command and hit Enter to view the Password: <code>netsh wlan show profile WiFiName key=clear</code>(Replace WiFiName with your wifi network name that you have noted down at step 4 above)</li>
 	<li>That's it. You can see the password of your given wifi network that will appear next to the <strong>Key Content</strong> section.

[caption id="attachment_1394" align="alignnone" width="1310"]<img class="size-full wp-image-1394" src="https://windowsdot.com/wp-content/uploads/2020/06/wi2.png" alt="Find Wifi Password" width="1310" height="852" /> Find Wifi Password[/caption]</li>
</ol>
<h2 id="4">Conclusion:</h2>
The simple steps described in this article helped you to <strong>Find Wifi Password Using CMD </strong>in Windows 10. We assure you that the steps given above are really easy for you to know the wifi password of a specific network. Kindly share your <strong>queries or comments</strong> in the below section. Thanks for visiting <b>Windows Dot.</b>
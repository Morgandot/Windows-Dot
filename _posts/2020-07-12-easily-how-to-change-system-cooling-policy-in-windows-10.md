---
ID: 2069
post_title: '[Easily] How to Change System Cooling Policy in Windows 10?'
author: Helena
post_excerpt: ""
layout: post
permalink: >
  https://windowsdot.com/easily-how-to-change-system-cooling-policy-in-windows-10/
published: true
post_date: 2020-07-12 02:28:07
---
In this tutorial, we will illustrate <strong>how to Change System Cooling Policy in Windows 10</strong> easily.
<ul class="toc">
 	<li><a href="#1">Description of System Cooling Policy</a></li>
 	<li><a href="#2">Two Types of Cooling Policy</a></li>
 	<li><a href="#3">Change Cooling Policy using Settings</a></li>
 	<li><a href="#4">Change Cooling Policy via Command Prompt</a></li>
 	<li><a href="#5">A Brief Summary</a></li>
</ul>
<h2 id="1">Description of System Cooling Policy:</h2>
System Cooling Policy lets you specify the cooling type that you wish to use for your Windows 10 PC. Starting with Windows 8, OS can automatically observe the changes in PC usage and environmental conditions. Devices that have thermal management capabilities can only expose these abilities to the OS with a special driver.

Windows can apply a particular cooling policy to the hardware as per the temperature changes. The hardware will make the necessary changes to the computer to decrease the temperature to the normal range. If the temperature of your processor goes beyond the optimal range, then the Windows will activate its cooling policy automatically.
<h2 id="2">Two Types of Cooling Policy:</h2>
There are two cooling policies in Windows 10. They are:

<strong>1) Active Cooling:</strong>
<ul>
 	<li>Once this policy is turned on, it decreases the temperature of the system by increasing the fan speed. This increases power consumption and it won't affect the system performance.</li>
 	<li>In general, desktop devices need to be connected to a power source all the time as it doesn't come with a built-in battery. So, you can prefer the active cooling mode for all Desktop PCs.</li>
</ul>
<strong>2) Passive Cooling:</strong>
<ul>
 	<li>This kind of cooling mode slows the processor and reduces system performance. If your fan is always running and you would like to make it quieter, you can choose this passive mode.</li>
 	<li>For laptops, you can opt for passive cooling mode when the laptop is on battery and active cooling mode while the laptops are connected to a power source.</li>
</ul>
<h2 id="3">Change Cooling Policy using Settings:</h2>
<ol>
 	<li>You have to open the <strong>Settings</strong> with the use of this keyboard shortcut <strong>Windows key + I</strong>.</li>
 	<li>After that, you have to click the <strong>System</strong> option.

[caption id="attachment_1944" align="alignnone" width="1308"]<img class="size-full wp-image-1944" src="https://windowsdot.com/wp-content/uploads/2020/07/System.png" alt="System" width="1308" height="760" /> System[/caption]</li>
 	<li>Then, in the left pane, you have to tap on the <strong>Power &amp; sleep</strong> option.

[caption id="attachment_2077" align="alignnone" width="1308"]<img class="size-full wp-image-2077" src="https://windowsdot.com/wp-content/uploads/2020/07/Power-sleep.png" alt="Power &amp; sleep" width="1308" height="761" /> Power &amp; sleep[/caption]</li>
 	<li>Now, you have to click on <strong>Additional power settings</strong> below the <strong>Related settings</strong> section.

[caption id="attachment_2074" align="alignnone" width="1315"]<img class="size-full wp-image-2074" src="https://windowsdot.com/wp-content/uploads/2020/07/Additional-power-settings.png" alt="Additional power settings" width="1315" height="761" /> Additional power settings[/caption]</li>
 	<li>Tap on the <strong>Change plan settings</strong> link.

[caption id="attachment_2076" align="alignnone" width="1094"]<img class="size-full wp-image-2076" src="https://windowsdot.com/wp-content/uploads/2020/07/Change-plan-settings.png" alt="Change plan settings" width="1094" height="681" /> Change plan settings[/caption]</li>
 	<li>Continue to click on <strong>Change advanced power settings</strong>.

[caption id="attachment_2075" align="alignnone" width="1094"]<img class="size-full wp-image-2075" src="https://windowsdot.com/wp-content/uploads/2020/07/Change-advanced-power-settings.png" alt="Change advanced power settings" width="1094" height="681" /> Change advanced power settings[/caption]</li>
 	<li>You have to expand <strong>Processor power management</strong> and then expand the <strong>System cooling policy</strong>.</li>
 	<li>Now, you can change the cooling policy as either Active or Passive by selecting the options <strong>On battery</strong> and <strong>Plugged in</strong>.

[caption id="attachment_2078" align="alignnone" width="501"]<img class="size-full wp-image-2078" src="https://windowsdot.com/wp-content/uploads/2020/07/System-cooling-policy.png" alt="System cooling policy" width="501" height="611" /> System cooling policy[/caption]</li>
 	<li>Then, you have to click <strong>Apply</strong> and <strong>OK</strong> button.</li>
</ol>
<h2 id="4">Change Cooling Policy via Command Prompt:</h2>
You can follow the below steps if you can't able to find the cooling policy option in Windows 10.
<ol>
 	<li>Click on the <strong>Windows key</strong> to open the <strong>Start</strong> menu.</li>
 	<li>In the search box, you have to type <strong>‘cmd’</strong>. Right-click on the result and choose <strong>Run as administrator</strong>. (If prompted, you have to press <strong>‘Yes’</strong> in the User Account Control window.)

[caption id="attachment_1682" align="alignnone" width="1318"]<img class="size-full wp-image-1682" src="https://windowsdot.com/wp-content/uploads/2020/06/Command-Prompt-2.png" alt="Command Prompt" width="1318" height="882" /> Command Prompt[/caption]</li>
 	<li>Run the below command and hit <strong>Enter </strong>to add the option. <code>powercfg -attributes SUB_PROCESSOR 94D3A615-A899-4AC5-AE2B-E4D8F634367F -ATTRIB_HIDE</code></li>
 	<li>You can remove the option by running the below command and hit <strong>Enter</strong>. <code>powercfg -attributes SUB_PROCESSOR 94D3A615-A899-4AC5-AE2B-E4D8F634367F +ATTRIB_HIDE</code></li>
</ol>
<h2 id="5">A Brief Summary:</h2>
We hope that this tutorial helped you to understand <strong>how to Change System Cooling Policy in Windows 10</strong>. You can choose the cooling policy mode as per your system requirements so that you can make sure that your PC part is not overheated. If you found this article useful, share your <strong>comments</strong> below. Check out more interesting articles in <strong>Windows Dot</strong>.
<h2>Keep Reading:</h2>
<ul>
 	<li><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsdot.com/3-easy-ways-enable-disable-focus-assist-in-windows-10/" target="_blank" rel="noopener noreferrer">[3 Easy Ways] Enable/Disable Focus Assist in Windows 10!!</a></li>
 	<li><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsdot.com/how-to-prevent-a-windows-10-update-from-installing-simple-steps/" target="_blank" rel="noopener noreferrer">How to Prevent a Windows 10 Update from Installing? (*Simple Steps*)</a></li>
</ul>
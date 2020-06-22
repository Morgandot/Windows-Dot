---
ID: 1400
post_title: >
  Fix MsMpEng.exe Causing High CPU and
  Disk Usage!!
author: Olivia
post_excerpt: ""
layout: post
permalink: >
  https://windowsdot.com/fix-msmpeng-exe-causing-high-cpu-and-disk-usage/
published: true
post_date: 2020-06-22 13:30:57
---
In this article, we explain <strong>How to Fix MsMpEng.exe Causing High CPU and Disk Usage</strong> in simple steps.
<ul class="toc">
 	<li><a href="#1">MsMpEng.exe</a></li>
 	<li><a href="#2">Disable Windows Defender</a></li>
 	<li><a href="#3">Prevent scanning</a></li>
 	<li><a href="#4">Give MsMpEng.exe the least affinity</a></li>
 	<li><a href="#5">Verdict</a></li>
</ul>
<h2 id="1">MsMpEng.exe:</h2>
<ul>
 	<li>It is the core process of <strong>Windows Defender.</strong></li>
 	<li>Windows Defender comes <strong>pre-installed</strong> on Windows 10.</li>
 	<li>It issues of taking<strong> 100% disk and CPU usage</strong> normally occurs when Windows Defender is scanning the system for malware.</li>
 	<li>While this is happening, the system becomes <strong>slow or even stops</strong> responding.</li>
 	<li><strong>Windows Defender</strong> is stuck on a few files for checking malware.</li>
</ul>
<h2 id="2">Disable Windows Defender:</h2>
Follow the below steps to Disable Windows Defender using Group Policy in simple steps.
<ol>
 	<li>Make use of the shortcut <strong>Windows + R</strong> to open the Run command dialog box.</li>
 	<li>In the given space box of Open type as<strong> gpedit.msc</strong> and click <strong>OK.</strong>

[caption id="attachment_1433" align="aligncenter" width="445"]<img class="size-full wp-image-1433" src="https://windowsdot.com/wp-content/uploads/2020/06/Screenshot_1-28.png" alt="The run command dialog box" width="445" height="261" /> The run command dialog box[/caption]</li>
 	<li>In the <strong>Group Policy Editor</strong> window, Go to the following path.</li>
 	<li>Computer Configuration\Administrative Templates\Windows Components\Windows Defender.

[caption id="attachment_1432" align="aligncenter" width="1405"]<img class="size-full wp-image-1432" src="https://windowsdot.com/wp-content/uploads/2020/06/mmc_YnlS08EUCV-1.png" alt="Group policy" width="1405" height="682" /> Group policy[/caption]

[caption id="attachment_1435" align="aligncenter" width="1342"]<img class="size-full wp-image-1435" src="https://windowsdot.com/wp-content/uploads/2020/06/mmc_fMxoW5I34m.png" alt="Windows Defender" width="1342" height="682" /> Windows Defender[/caption]</li>
 	<li>Then, double-click on <strong>Windows Defender</strong>, its window will expand further on the right-hand side.</li>
 	<li>Now, locate the option of  <strong>Turn Off Windows Defender.</strong>

[caption id="attachment_1431" align="aligncenter" width="1517"]<img class="size-full wp-image-1431" src="https://windowsdot.com/wp-content/uploads/2020/06/mmc_yIDYBWShJn.png" alt="Turn Off Windows Defender" width="1517" height="696" /> Turn Off Windows Defender[/caption]</li>
 	<li>Double-click on it to open its Properties window gets open and choose <strong>Enabled</strong> option to enable this feature.

[caption id="attachment_1430" align="aligncenter" width="850"]<img class="size-full wp-image-1430" src="https://windowsdot.com/wp-content/uploads/2020/06/mmc_Do8VHvtVLd.png" alt="Enabled" width="850" height="789" /> Enabled[/caption]</li>
 	<li>Finally, press <strong>OK</strong> and close all windows.</li>
 	<li>After disabling it, install another good <a href="https://www.bitdefender.com/Downloads/"><strong>Antivirus software</strong></a> so your system’s protection will not suffer.</li>
 	<li>That's all.</li>
</ol>
<h2 id="3">Prevent scanning:</h2>
Follow the below steps to prevent the scanning of a specific folder in simple steps.
<ul>
 	<li>Click on the shortcut <strong>Windows + I</strong> to open Windows Settings.</li>
 	<li>Select the<strong> Update &amp; Security</strong> option in the settings window.

[caption id="attachment_1429" align="aligncenter" width="1903"]<img class="size-full wp-image-1429" src="https://windowsdot.com/wp-content/uploads/2020/06/ApplicationFrameHost_lGFuwgZPRB.png" alt="Settings" width="1903" height="754" /> Settings[/caption]</li>
 	<li>Then, in the left pane select the <strong>Windows Defender</strong> option.</li>
 	<li>In the right pane, an option is available which says<strong> Excluded Files</strong> and Location and click on it.

[caption id="attachment_1428" align="aligncenter" width="1370"]<img class="size-full wp-image-1428" src="https://windowsdot.com/wp-content/uploads/2020/06/ApplicationFrameHost_S0EaPgUjn0.png" alt="Windows Defender" width="1370" height="991" /> Windows Defender[/caption]</li>
 	<li>Now press the <strong>Browse</strong> button for your required folder.</li>
 	<li>Go to the <strong>directory</strong> of the defender in the system’s drive.</li>
 	<li>Now, enter the location of <strong>MsMpEng.exe</strong> file.</li>
 	<li>The file will be browsed in File Location.</li>
 	<li>Click on the <strong>Add</strong> button to add this file in the excluded file and folder option.</li>
 	<li>Now, your required file will be added.</li>
 	<li><strong>CPU usage</strong> for MsMpEng.exe file will not be high now, as it only takes little extra resources on time of Defender’s scan.</li>
 	<li>Otherwise, you will have the usual load for every process.</li>
 	<li>That's all.</li>
</ul>
<h2 id="4">Give MsMpEng.exe the least affinity:</h2>
First, set MsMpEng.exe file to use the specific processor of the system to avoid high CPU usage by this file. It will cut the scan speed of the Windows defender than usual but slow scan speed is better than having high CPU usage.

Follow the below steps to set the affinity in limited mode.
<ul>
 	<li>Make use of the shortcut key <strong>Ctrl+Shift+Esc</strong> to open the Task Manager window.</li>
 	<li>Go to the <strong>Details</strong> tab and locate<strong> MsMpEng.exe</strong> process then right-click on it.</li>
 	<li>Select<strong> Set Affinity.</strong>

[caption id="attachment_1427" align="aligncenter" width="804"]<img class="size-full wp-image-1427" src="https://windowsdot.com/wp-content/uploads/2020/06/mspaint_rqeLmB7M77.png" alt="Details" width="804" height="735" /> Details[/caption]</li>
 	<li>A new window will open, to select the processors for <strong>MsMpEng.exe file.</strong></li>
 	<li>Select<strong> 2 processors</strong> for normal CPU usage, if your system is quad-core, and set one processor if your system is dual-core.

[caption id="attachment_1426" align="aligncenter" width="1279"]<img class="size-full wp-image-1426" src="https://windowsdot.com/wp-content/uploads/2020/06/chrome_8x24WgCpZe.png" alt="processors for MsMpEng.exe file" width="1279" height="531" /> Processors for MsMpEng.exe file[/caption]</li>
 	<li>Close all windows and now <strong>CPU will automatically</strong> spend less of its resources on the MsMpEng.exe process.</li>
</ul>
<h2 id="5">Verdict:</h2>
We hope that this article helped you know<strong> How to Fix MsMpEng.exe Causing High CPU and Disk Usage.</strong> Convey us your feedback about this article in the below section.
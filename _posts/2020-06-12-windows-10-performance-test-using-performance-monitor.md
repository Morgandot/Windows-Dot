---
ID: 942
post_title: >
  Windows 10 Performance Test Using
  Performance Monitor!!
author: Olivia
post_excerpt: ""
layout: post
permalink: >
  https://windowsdot.com/windows-10-performance-test-using-performance-monitor/
published: true
post_date: 2020-06-12 14:15:05
---
In this article, we describe <strong>how to run Windows 10 Performance Test Using Performance Monitor</strong> in simple steps.
<ul class="toc">
 	<li><a href="#1">To create a system performance report in Windows 10</a></li>
 	<li><a href="#2">To create a custom performance report in Windows 10</a></li>
 	<li><a href="#3">Verdict</a></li>
</ul>
<h2 id="1">To create a system performance report in Windows 10:</h2>
Follow the below steps to create a system performance report in Windows 10.
<ul>
 	<li>There are<strong> two built-in data sets</strong> in Windows 10, such as <strong>System Diagnostics</strong> and <strong>System Performance.</strong></li>
 	<li>It can be used to run to create a general report of different system metrics.</li>
 	<li>Now, Let’s generate a <strong>system performance report.</strong></li>
 	<li>First, Open the Run command dialog box using the shortcut <strong>Windows + R.</strong></li>
 	<li>Type as <strong>perfmon</strong> in the given space of <strong>Open</strong> and click <strong>OK</strong>.</li>
 	<li>In the left pane click the <strong>Data Collector Sets.</strong></li>
 	<li>Click the dropdown arrow of the Data Collector Sets and select <strong>System</strong>.</li>
 	<li>Again, click the dropdown arrow System and select <strong>System Performance.</strong></li>
 	<li>Then, right-click the System Performance and select <strong>Start</strong>.

[caption id="attachment_956" align="aligncenter" width="857"]<img class="wp-image-956 size-full" src="https://windowsdot.com/wp-content/uploads/2020/06/Screenshot_1-15.png" alt="System Performance" width="857" height="674" /> System Performance[/caption]</li>
 	<li>The <strong>data set</strong> will run for 60 seconds.</li>
 	<li>Then, a new report will be published under <strong>Reports</strong> and click the dropdown arrow of the <strong>System</strong> and select <strong>System Performance.</strong>

[caption id="attachment_957" align="aligncenter" width="854"]<img class="wp-image-957 size-full" src="https://windowsdot.com/wp-content/uploads/2020/06/Screenshot_2-14.png" alt="Windows 10 Performance Test Report" width="854" height="668" /> Windows 10 Performance Test Report[/caption]</li>
 	<li>This will give you an overview of how the system is running.</li>
</ul>
<h2 id="2">To create a custom performance report in Windows 10:</h2>
To create a custom report, you will need to create a custom data collector set.
<ul>
 	<li>First, Open the Run command dialog box using the shortcut <strong>Windows + R.</strong></li>
 	<li>Type as <strong>perfmon</strong> in the given space of <strong>Open</strong> and click <strong>OK</strong>.</li>
 	<li>In the left pane click the <strong>Data Collector Sets.</strong></li>
 	<li>Click the dropdown arrow of the Data Collector Sets and select <strong>User Defined.</strong></li>
 	<li>Then, right-click User Defined and select <strong>New</strong> and then select<strong> Data Collector Set.</strong>

[caption id="attachment_958" align="aligncenter" width="855"]<img class="wp-image-958 size-full" src="https://windowsdot.com/wp-content/uploads/2020/06/Screenshot_3-15.png" alt="New custom data collector set" width="855" height="762" /> New custom data collector set[/caption]</li>
 	<li>Now, <strong>give</strong> <strong>a name</strong> to your data collector set.</li>
 	<li>Select <strong>Create manually</strong> option or else select create from a template and click <strong>Next.</strong>

[caption id="attachment_959" align="aligncenter" width="850"]<img class="wp-image-959 size-full" src="https://windowsdot.com/wp-content/uploads/2020/06/Screenshot_4-11.png" alt="Name your data collector set" width="850" height="511" /> Name your data collector set[/caption]</li>
 	<li>Now, <strong>select the type of data</strong> and click <strong>Next</strong>.

[caption id="attachment_960" align="aligncenter" width="850"]<img class="wp-image-960 size-full" src="https://windowsdot.com/wp-content/uploads/2020/06/Screenshot_5-10.png" alt="Type of data to include in data set" width="850" height="511" /> Type of data to include in the data set[/caption]</li>
 	<li>Then,<strong> add performance counters</strong> specific to your requirements.

[caption id="attachment_961" align="aligncenter" width="879"]<img class="wp-image-961 size-full" src="https://windowsdot.com/wp-content/uploads/2020/06/Screenshot_7-7.png" alt="Add performance counters of your choice" width="879" height="659" /> Add performance counters of your choice[/caption]</li>
 	<li>Select<strong> event trace providers</strong> you want to enable.</li>
 	<li>Or else leave black if you don’t know about this.

[caption id="attachment_962" align="aligncenter" width="651"]<img class="wp-image-962 size-full" src="https://windowsdot.com/wp-content/uploads/2020/06/Screenshot_8-5.png" alt="Event trace providers" width="651" height="412" /> Event trace providers[/caption]</li>
 	<li>Add <strong>registry</strong> <strong>keys</strong> to monitor in the performance report.

[caption id="attachment_963" align="aligncenter" width="648"]<img class="wp-image-963 size-full" src="https://windowsdot.com/wp-content/uploads/2020/06/Screenshot_9-2.png" alt="Monitoring registry in performance test" width="648" height="422" /> Monitoring registry in the performance test[/caption]</li>
 	<li>Then, add your report <strong>save</strong> <strong>location</strong>.

[caption id="attachment_964" align="aligncenter" width="642"]<img class="wp-image-964 size-full" src="https://windowsdot.com/wp-content/uploads/2020/06/Screenshot_10-1.png" alt="Save your performance report data 1" width="642" height="435" /> Save your performance report data 1[/caption]</li>
 	<li>Select the <strong>user</strong> under which this performance counter should run.</li>
 	<li>Finally, click the <strong>Save</strong> and <strong>Finish</strong> button.</li>
 	<li>The <strong>new user-defined data collector set</strong> will be created.</li>
 	<li>Then, right-click and select <strong>Run</strong> to run this data set.</li>
 	<li>When you want to stop the<strong> data collector set</strong> then right-click it, and select <strong>Stop</strong>.</li>
 	<li>This will create a new report under <strong>Reports</strong>.</li>
 	<li> Click the dropdown arrow of <strong>Reports</strong> and select User <strong>Defined</strong> it will view the new report.

[caption id="attachment_965" align="aligncenter" width="737"]<img class="wp-image-965 size-full" src="https://windowsdot.com/wp-content/uploads/2020/06/Screenshot_11-1.png" alt="Custom Performance Report" width="737" height="753" /> Custom Performance Report[/caption]</li>
 	<li>That's all.</li>
</ul>
<h2 id="3">Verdict:</h2>
In this tutorial, we have explained <strong>how to Run Windows 10 Performance Test Using Performance Monitor.</strong> Besides, the screenshots let you understand even simpler. Kindly share your queries/feedback in the below comment section.
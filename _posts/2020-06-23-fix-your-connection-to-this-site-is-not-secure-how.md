---
ID: 1454
post_title: 'Fix your connection to this site is not secure &#8211; How?'
author: Olivia
post_excerpt: ""
layout: post
permalink: >
  https://windowsdot.com/fix-your-connection-to-this-site-is-not-secure-how/
published: true
post_date: 2020-06-23 06:57:29
---
In this article, we illustrate an outline of <strong>How to fix your connection to this site is not secure</strong> in simple ways.
<ul class="toc">
 	<li><a href="#1">SSL error</a></li>
 	<li><a href="#2">Fixing the issue on WordPress</a></li>
 	<li><a href="#3">Finding the problematic resources and fixing the error</a></li>
 	<li><a href="#4">A Brief Synopsis</a></li>
</ul>
<h2 id="1">SSL error:</h2>
<ul>
 	<li>It means that some components of your website are not loading securely with <strong>HTTPS</strong>.</li>
 	<li><strong>HTTPS</strong> is a secure way to send and receive web traffic in your browser.</li>
 	<li>In order to increase data security, all <strong>HTTPS</strong> traffic is encrypted.</li>
 	<li>When a website is transmitting sensitive data like login and credit card information, then this becomes more important.</li>
 	<li>If you send data through the normal <strong>HTTP</strong> protocol, it will not be encrypted and can be read using network packet analyzers like Wireshark.

[caption id="attachment_1455" align="aligncenter" width="658"]<img class="size-full wp-image-1455" src="https://windowsdot.com/wp-content/uploads/2020/06/chrome_qcCIwRYkZw.png" alt="Error" width="658" height="387" /> Error[/caption]</li>
 	<li>Then, this error usually comes in both <strong>Google Chrome</strong> and <strong>Firefox</strong>.</li>
 	<li>The <strong>errors</strong> will be shown in their <strong>address bars</strong> and the <strong>SSL</strong> lock sign will not turn green.</li>
 	<li>The <strong>green padlock</strong> in the address bar before the URL means the site is fully secure.

[caption id="attachment_1458" align="aligncenter" width="571"]<img class="size-full wp-image-1458" src="https://windowsdot.com/wp-content/uploads/2020/06/chrome_bq4y4R4wx1.png" alt="Secure" width="571" height="391" /> Secure[/caption]</li>
 	<li>Before moving forward, make sure that your<strong> SSL certificate</strong> is valid and properly installed.</li>
 	<li>To check the <strong>SSL Certificate,</strong> you can go to the <a href="https://www.sslshopper.com/ssl-checker.html"><strong>SSLShopper SSL Checker page</strong></a>.</li>
 	<li>Then, enter your <strong>domain name</strong> and press the<strong> Check SSL</strong> button.</li>
 	<li>It will automatically<strong> detect and diagnose</strong> if a valid SSL certificate is installed.</li>
</ul>
<h2 id="2">Fixing the issue on WordPress:</h2>
Follow the below steps to fix the issue on WordPress.
<ol>
 	<li>First, Go to the<strong> wp-admin</strong> site area.</li>
 	<li>Then, Go to <strong>Plugins</strong> and click on the <strong>Add New</strong> option.</li>
 	<li>In the window, <strong>search</strong> for <strong>Really Simple SSL.</strong></li>
 	<li>After locating, now <strong>install</strong> and <strong>activate</strong> Really Simple SSL plugin.</li>
 	<li>Then, Go to <strong>Settings</strong> and click on the <strong>SSL</strong>.

[caption id="attachment_1459" align="aligncenter" width="494"]<img class="size-full wp-image-1459" src="https://windowsdot.com/wp-content/uploads/2020/06/chrome_Ulelqy7GWm.png" alt="SSL" width="494" height="366" /> SSL[/caption]</li>
 	<li>Select the <strong>settings</strong> tab and <strong>check in</strong> the option<strong><strong> Mixed content fixer.</strong></strong>

[caption id="attachment_1456" align="aligncenter" width="754"]<img class="size-full wp-image-1456" src="https://windowsdot.com/wp-content/uploads/2020/06/chrome_MbtpcOl8Yx-e1592897530830.png" alt="Settings" width="754" height="625" /> Settings[/caption]</li>
 	<li>Now, this should fix all <strong>HTTP</strong> references in your site automatically.</li>
 	<li>That's all.</li>
</ol>
<h2 id="3">Finding the problematic resources and fixing the error:</h2>
Note: The above method will only <strong>fix internal HTTP</strong> references to your site. If you have external images or other resources that open using HTTP, then you should follow this method for fixing this issue.

If you are not using <strong>WordPress</strong> or the above-mentioned method doesn’t work, then you should use this method.
<ol>
 	<li>To quickly check the <strong>HTTP references</strong> on the web page is to view its source and search for <strong>https://</strong> is one of the best way.</li>
 	<li>But sometimes there are images which load from the <strong>CSS</strong> or other resources which don’t get mentioned in the main source code and these are hard to detect.</li>
 	<li>To get rid of this error, there is a wonderful service called <strong>Why No Padlock. </strong></li>
 	<li>Go to the official page of <a href="https://www.whynopadlock.com/"><strong>https://whynopadlock.com</strong></a>, and then enter your <strong>problematic URL</strong> and wait for it to process.</li>
 	<li>Then, it will list down all the resources which are loading with <strong>HTTP protocol</strong> instead of HTTPS.</li>
 	<li>That's all, Now you will no longer get the error <strong>your connection to this site is not secure. </strong></li>
</ol>
<strong>Image Source:</strong> <em>itechtics.com</em>
<h2 id="4">A Brief Synopsis:</h2>
This tutorial guided you on <strong>How to fix your connection to this site is not secure</strong> in simple ways. Don’t forget to share your comments in the below box.
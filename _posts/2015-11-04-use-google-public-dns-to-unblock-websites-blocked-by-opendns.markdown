---
published: true
title: Use Google Public DNS to Unblock Websites Blocked by OpenDNS
layout: post
tags: [Google, Linux, Mac, OSX, Windows, DNS, Public]
categories: [Web]
---
Use the following instructions to improve your browser speed and circumvent blocks by OpenDNS. Enjoy!<br />
<br />
<h4>
Microsoft Windows</h4>
DNS settings are specified in the&nbsp;<b>TCP/IP Properties</b> window for the selected network connection.<br />
<br />
<b>Example: Changing DNS server settings on Microsoft Windows 7</b><br />
<ol><br />
<li>Go the <b>Control Panel</b>.</li>
<br />
<li>Click <b>Network and Internet</b>, then <b>Network and Sharing Center</b>, and click <b>Change adapter settings</b>.</li>
<br />
<li>Select the connection for which you want to configure Google Public DNS. For example:<br /><ul><br />
<li>To change the settings for an Ethernet connection, right-click <b>Local Area Connection</b>, and click <b>Properties</b>.</li>
<br />
<li>To change the settings for a wireless connection, right-click<b> Wireless Network Connection</b>, and click <b>Properties</b>.</li>
</ul>
<br />If you are prompted for an administrator password or confirmation, type the password or provide confirmation.</li>
<br />
<li>Select the <b>Networking</b> tab. Under <b>This connection uses the following items</b>, select <b>Internet Protocol Version 4 (TCP/IPv4)</b> or<b>Internet Protocol Version 6 (TCP/IPv6)</b> and then click <b>Properties</b>.</li>
<br />
<li>Click <b>Advanced</b> and select the <b>DNS</b> tab. If there are any DNS server IP addresses listed there, write them down for future reference, and remove them from this window.</li>
<br />
<li>Click <b>OK</b>.</li>
<br />
<li>Select <b>Use the following DNS server addresses</b>. If there are any IP addresses listed in the <b>Preferred DNS server</b> or <b>Alternate DNS server</b>, write them down for future reference.</li>
<br />
<li>Replace those addresses with the IP addresses of the Google DNS servers:<br /><ul><br />
<li>For IPv4: 8.8.8.8 and/or 8.8.4.4.</li>
<br />
<li>For IPv6: 2001:4860:4860::8888 and/or 2001:4860:4860::8844</li>
</ul>
</li>
<br />
<li>Restart the connection you selected in step 3.</li>
<br />
<li>Test that your setup is working correctly; see <a href="https://developers.google.com/speed/public-dns/docs/using#testing">Testing your new settings</a> below.</li>
<br />
<li>Repeat the procedure for additional network connections you want to change.</li>
</ol>
<h4>
Mac OS X</h4>
DNS settings are specified in the&nbsp;<b>Network</b> window.<br />
<br />
<b>Example: Changing DNS server settings on Mac OS 10.5</b><br />
<ol><br />
<li>From the <b>Apple</b> menu, click <b>System Preferences</b>, then click <b>Network</b>.</li>
<br />
<li>If the lock icon in the lower left-hand corner of the window is locked, click the icon to make changes, and when prompted to authenticate, enter your password.</li>
<br />
<li>Select the connection for which you want to configure Google Public DNS. For example:<br /><ul><br />
<li>To change the settings for an Ethernet connection, select <b>Built-In Ethernet</b>, and click <b>Advanced</b>.</li>
<br />
<li>To change the settings for a wireless connection, select <b>Airport</b>, and click <b>Advanced</b>.</li>
</ul>
</li>
<br />
<li>Select the <b>DNS</b> tab.</li>
<br />
<li>Click + to replace any listed addresses with, or add, the Google IP addresses at the top of the list:<br /><ul><br />
<li>For IPv4: 8.8.8.8 and/or 8.8.4.4.</li>
<br />
<li>For IPv6: 2001:4860:4860::8888 and/or 2001:4860:4860::8844</li>
</ul>
</li>
<br />
<li>Click <b>Apply</b> and <b>OK</b>.</li>
<br />
<li>Test that your setup is working correctly; see <a href="https://developers.google.com/speed/public-dns/docs/using#testing">Testing your new settings</a> below.</li>
<br />
<li>Repeat the procedure for additional network connections you want to change.</li>
</ol>
<h4>
Linux</h4>
In most modern Linux distributions, DNS settings are configured through Network Manager.<br />
<br />
<b>Example: Changing DNS server settings on Ubuntu</b><br />
<ol><br />
<li>In the <b>System</b> menu, click <b>Preferences</b>, then click <b>Network Connections</b>.</li>
<br />
<li>Select the connection for which you want to configure Google Public DNS. For example:<br /><ul><br />
<li>To change the settings for an Ethernet connection, select the <b>Wired</b> tab, then select your network interface in the list. It is usually called <b>eth0</b>.</li>
<br />
<li>To change the settings for a wireless connection, select the <b>Wireless</b> tab, then select the appropriate wireless network.</li>
</ul>
</li>
<br />
<li>Click <b>Edit</b>, and in the window that appears, select the <b>IPv4 Settings</b> or <b>IPv6 Settings</b> tab.</li>
<br />
<li>If the selected method is <b>Automatic (DHCP)</b>, open the dropdown and select <b>Automatic (DHCP) addresses only</b> instead. If the method is set to something else, do not change it.</li>
<br />
<li>In the <b>DNS servers</b> field, enter the Google Public DNS IP addresses, separated by a space:<br /><ul><br />
<li>For IPv4: 8.8.8.8 and/or 8.8.4.4.</li>
<br />
<li>For IPv6: 2001:4860:4860::8888 and/or 2001:4860:4860::8844</li>
</ul>
</li>
<br />
<li>Click <b>Apply</b> to save the change. If you are prompted for a password or confirmation, type the password or provide confirmation.</li>
<br />
<li>Test that your setup is working correctly; see <a href="https://developers.google.com/speed/public-dns/docs/using#testing">Testing your new settings</a> below.</li>
<br />
<li>Repeat the procedure for additional network connections you want to change.</li>
</ol>

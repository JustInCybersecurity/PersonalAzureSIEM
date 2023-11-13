<h1>Failed RDP to IP Geolocation Information</h1>



<h2>Description</h2>
<p>The Powershell script in this repository is responsible for parsing out Windows Event Log information for failed RDP attacks and using a third party API to collect geographic information about the attackers location.</p>

<p>The script is used where I setup Azure Sentinel (SIEM) and connect it to a live virtual machine acting as a honey pot. I observe live attacks (RDP Brute Force) from around the world. I  use a custom PowerShell script to look up the attackers Geolocation information and plot it on an Azure Sentinel Map! 
<br />

<p align="center">
<a href="https://imgur.com/rGswmu1"><img src="https://i.imgur.com/rGswmu1.png" title="source: imgur.com" /></a>
</p>

<h2>Languages and Utilities Used</h2>

- <b>PowerShell: Extract RDP failed logon logs from Windows Event Viewer</b> 
- <b>ipgeolocation.io: IP Address to Geolocation API</b>

<h2>Attacks from Indonesia coming in; Custom logs being output with geodata</h2>

<a href="https://imgur.com/LdJfXl1"><img src="https://i.imgur.com/LdJfXl1.png" title="source: imgur.com" /></a>

<h2>World map of incoming attacks after 12 hours</h2>

<a href="https://imgur.com/vU82O6I"><img src="https://i.imgur.com/vU82O6I.png" title="source: imgur.com" /></a>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>

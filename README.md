<h1>Implementing VLAN and Trunking</h1>

<h2>Description</h2>
This project involves the configuration and testing of VLANs and trunks on switches. 
<br />


<h2>Languages and Utilities Used</h2>

- <b>CLI</b> 


<h2>Environments Used </h2>

- <b>CISCO Packet Tracer</b> 

<h2>Program walk-through:</h2>

- <b>Topology: <b/> 
<br/>
<img src="https://imgur.com/2eVn2GF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>

- <b> Configured eighteen VLANs on three switches and assigned ports to each VLAN

<br/>
<img src="https://imgur.com/9k1HCTt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

- <b> Configured virtual management interfaces on all three switches.
- Configured the link between SWA and SWB as a static trunk: A trunk link allows multiple VLANs' traffic to traverse between switches, maintaining network segmentation while enabling communication between VLANs.
- Configured the trunk with the native VLAN (100) and eliminate native VLAN conflicts: <br/>
<img src="https://imgur.com/RREJ8BA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

- <b> Configure G0/2 on SWA so that it successfully negotiates trunking with SWC.
- Configure the trunk with the native VLAN and eliminate native VLAN conflicts: <br/>
<img src="https://imgur.com/t8yKBMS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br/>
<img src="https://imgur.com/qX1P3SC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>

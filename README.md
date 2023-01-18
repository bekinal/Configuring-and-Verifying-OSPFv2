<h1>Configuring and Verifying OSPFv2</h1>

<h2>Description</h2>
Project consists of configuring routers to use OSPF with the best practices in mind
<br />


<h2>Utilities Used</h2>

- <b>VirtualBox</b> 
- <b>Cisco Packet Tracer</b>

<h2>Environments Used </h2>

- <b>Windows 10</b>

<h2>Set OSPF Router ID:</h2>
Network Topology: <br/>
<img src="https://imagizer.imageshack.com/img923/9003/qNEzAh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
The OSPF process is started with an ID of 1. The router ID is set, and the networks are added to OSPF broadcasting. The gigabitethernet interface is set to passive: <br/>
<img src="https://imagizer.imageshack.com/img922/876/hzxOq6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
The steps are repeated for router 2: <br/>
<img src="https://imagizer.imageshack.com/img923/5417/IRDUIX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
The steps are repeated for router 3: <br/>
<img src="https://imagizer.imageshack.com/img924/9883/POJ056.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<h2>Default Route with OSPF:</h2>
The default route for R2 is set towards the internet. OSPF default route broadcasting is enabled: <br/>
<img src="https://imagizer.imageshack.com/img922/1222/2dSnZF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
The router information is verified. This is repeated for routers 1 and 2: <br/>
<img src="https://imagizer.imageshack.com/img922/9285/V9nacn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>

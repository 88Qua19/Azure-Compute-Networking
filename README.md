# Azure-Compute-Networking
Create some compute and networking resources in Azure and perform some network activities. 
![Created VM's](https://github.com/88Qua19/Azure-Compute-Networking/assets/169956201/fe48970c-2a0f-4f82-8d6c-8e590b01f5be)
<ul>
<li>Using remote desktop I will connect to the virtual machines. Wireshark will be installed to the virtual machine that is running Window 10 operating system. The other virtual machine will have Ubuntu (Linux) operating system.</li> 
<li>ICMP traffic will be observed between the two Virtual machines.</li> 
</ul>

![ICMP_traffic](https://github.com/88Qua19/Azure-Compute-Networking/assets/169956201/49f905a6-ba66-43ab-b3a9-c5a30458f143)

<ul>
<li>Within Azure I will disable incoming ICMP traffic form the network security group in the Ubuntu (linux) virtual machine. </li>
<li>From the Windows 10 virtual machine I will ssh into the Ubuntu (linux) virtual machine.</li>
</ul>

![Deny_ICMP_2](https://github.com/88Qua19/Azure-Compute-Networking/assets/169956201/ee7ced4f-048e-4bd4-a93a-d7591d835ec1)

![SSH_Traffic](https://github.com/88Qua19/Azure-Compute-Networking/assets/169956201/99410c6b-d02a-40e7-b33a-688f2dda3c0f)

<ul>
<li>From the Windows 10 virtual machine we will observe DHCP traffic. In window 10 command line I will  ipconfig /renew to be issued a new IP address for the windows 10 virtual machine</li>
<li>From the Windows 10 Virtual machine I will filter for RDP traffic only to observe non- stop spam traffic from one Virtual machine to the other. </li>
</ul>

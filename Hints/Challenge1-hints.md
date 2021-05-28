## Challenge 1 Hints
- Every Virtual Machine needs to be attached to a Virtual Network (vnet). Therefore, do not forget to have a vnet. You can deploy the vnet during or before the deployment of the Virtual Machine.
- To filter traffic to and from a Virtual Machine, you need to use Network Security Groups (NSG).
- NSGs can be attached to Virtual Machines and/or Subnets.
- Here in [the link](https://azure.microsoft.com/en-us/support/legal/sla/virtual-machines/v1_9/) you will find more information about Virtual Machine SLAs. Make sure you make use of Availability Zones in your design.
- For load balancing traffic to your VMs, Azure provides different options. i.e. Azure Load Balancer, Application Gateway, Traffic Manager. Make sure you use the best and simplest option. 
- If you have a Windows Virtual Machine, use Remote Desktop Connection to connect to it. See [this link](https://support.microsoft.com/en-us/windows/how-to-use-remote-desktop-5fe128d5-8fb1-7a23-3b8a-41e636865e8c) -> follow step 2 in the guide.
- If you have a Linux Virtual Machine, use Putty to connect to it. Download it from [this link](https://www.putty.org/). Using it is pretty simple. Just type in the IP address of the Linux VM and click Open.
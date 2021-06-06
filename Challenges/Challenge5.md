## Challenge 5
In this challenge you are asked to improve your website's availability by being present in another region. You will need to expand your highly-available VMs setup to another region. This means you will need to set up Virtual Machines in a completely new region, set up a website on them, and in the end make sure traffic is load balanced across both regions.

Make sure you start with drawing a diagram of your architecture.

### Success Requirements
- You need to make your website available in two regions. It is an HA (active-active) setup, which means the website in both regions must be active and responsive.
- Make sure you pick a region in North America and another one in Europe. Ensure traffic from end users in each geographical region is routed to the website in the respective Azure region.
- There is a number of different Azure services to make load balancing across regions possible. You can use any one of them. A simple Bing/Google search can give you ideas.

#### Essential Readings
[Understand Azure Load Balancing](https://docs.microsoft.com/en-us/azure/architecture/guide/technology-choices/load-balancing-overview)
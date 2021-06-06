## Challenge 5 Hints
- Implement the same setup of your web servers which you created in Challenge 1 in a new region. For this to work, you will also need another Virtual Network in the new region.
- Once step above is taken, you should have a total of 4 Virtual Machines (running your website) and 2 public-facing Azure Load Balancers.
- Create another layer of load balancing in front of the 2 Load Balancers to route traffic between the two. You are not limited to using only Azure Load Balancer. Feel free to be creative. 
- Look into other services such as Azure Traffic Manager and Front Door.
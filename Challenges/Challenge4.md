## Challenge 4
You need to implement disaster revovery for your entire infrastructure. Your disaster recovery plan must give you the ability to recover your infrastructure partially or entirely to a different region. At the end of this challenge you must execute a DR drill in which your VMs are shut down (for any reason) and your Azure Files share becomes unavailable, and you must be able to recover all of them in another region.

### Success Requirements
- Recovering Virtual Machines and Azure Files share should be enough. You don't need to recover an Azure Load Balancer, private endpoints, or any other infrastructure components. Doing so however helps you gain bonus points.
- Use Azure Site Recovery for Virtual Machines recovery.
- Recover Azure Files share using its built-in recovery mechanism.
- Make sure all your infrastructure components are recovered to the same region.
- You are not limited by any specific SLA, RTP, RPO for this exercise. 

#### Essential Readings
- [About Azure Site Recovery](https://docs.microsoft.com/en-us/azure/site-recovery/site-recovery-overview)
- [Azure Paired Regions](https://docs.microsoft.com/en-us/azure/best-practices-availability-paired-regions)
- [Disaster Recovery and Storage Account Failover](https://docs.microsoft.com/en-us/azure/storage/common/storage-disaster-recovery-guidance)
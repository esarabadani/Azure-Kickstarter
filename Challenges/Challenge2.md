## Challenge 2
In this challenge you are asked to configure Azure Files to provide file storage and sharing, and set up a VM acting as an application server to connect to your Azure Files share.

### Success Requirements
- Feel free to use any tiers on Azure Files. 
- Make sure your Azure Files shares are geo-replicated. 
- Upload any sample data to your file share.
- Perform a manual snapshot on your file share to ensure you have a backup after you copy your data. (You don't need to perform regular backups at this stage).
- Set up a Virtual Machine (as an application server) and connect your Azure Files share to it over a private network. You can choose any Operating System for your VM, but Windows will probably make your life easier.
- Using the Virtual Machine, make sure you can copy files to and from the file share.

#### Essential Readings
- [What is Azure Files?](https://docs.microsoft.com/en-us/azure/storage/files/storage-files-introduction)
- [What is Azure Private Link?](https://docs.microsoft.com/en-us/azure/private-link/private-link-overview)
- [Private Endpoint for Azure Storage](https://docs.microsoft.com/en-us/azure/storage/common/storage-private-endpoints)
- [Geo Redundancy in Azure Files](https://docs.microsoft.com/en-us/azure/storage/files/storage-files-planning#redundancy)
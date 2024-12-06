
# Cloud Developement
- Team 5
- Project: Wekan
---
### Overview of setup on Azure
By installing the Wekan-snap package on Virtual Machine in Azure, we can easily build and run the Wekan on VM because Wekan Snap is a self-contained package that includes all necessary components (e.g., MongoDB, Node.js, Wekan) in a single installation.
- How to install Wekan on Asure?
  1. Find Virtual Machine services on Asure
  2. Create a virtual machine
  3. Run $ sudo snap install wekan on VM
  4. Access Wekan through the DNS/Hostname
      
### Instructions for running the load tests
- Look into autocannon 
###  Issues encountered during testing
When we first tried to run test on cloud, the windows system couldn't run or access it. The server running on VM is Ubuntu which supports Linux, it has to use the Linux or macOS to be able to test it.  

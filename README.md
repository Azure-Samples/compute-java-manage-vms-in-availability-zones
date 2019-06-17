---
services: Compute
platforms: java
author: yaohaizh
---

## Getting Started with Compute - Manage Zonal Virtual Machine - in Java ##


  Azure Compute sample for managing virtual machines -
   - Create a zonal virtual machine with implicitly zoned related resources (PublicIP, Disk)
   - Creates a zonal PublicIP address
   - Creates a zonal managed data disk
   - Create a zonal virtual machine and associate explicitly created zonal PublicIP and data disk.
 

## Running this Sample ##

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-libraries-for-java/blob/master/AUTH.md).

    git clone https://github.com/Azure-Samples/compute-java-manage-vms-in-availability-zones.git

    cd compute-java-manage-vms-in-availability-zones

    mvn clean compile exec:java

## More information ##

[http://azure.com/java](http://azure.com/java)

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
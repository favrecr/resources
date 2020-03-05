---

copyright:

  years: 2020

lastupdated: "2020-03-04"

keywords: migrate, migrating data center

subcollection: resources

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}
{:gif: data-image-type='gif'}
{:tip: .tip}

# Migrating resources to a different data center
{: #migrate-data-center}

{{site.data.keyword.IBM_notm}} continually updates and modernizes data centers to give you higher levels of performance. Some data centers aren't able to be upgraded, so they must be closed and your resources must be migrated to a different data center. For information about which data centers are closing, see [Withdrawal of support for some data centers](/docs/get-support?topic=get-support-dc-migrate).
{:shortdesc}

Throughout the data center migration process, help is available. To identify your impacted servers, take advantage of special offers, or learn about recommended configurations, contact the {{site.data.keyword.IBM_notm}} 24x7 Client Success team: 
  * [Live chat](https://www.ibm.com/cloud/data-centers/?focusArea=WCP%20-%20Pooled%20CSM&contactmodule){: external}
  * Phone: (US) 866-597-9687; (EMEA) +31 20 308 0540; (APAC) +65 6622 2231


## Migrating your resources
{: #migrating-your-resources}
 
If you have services that run on the closing data centers, plan to migrate to a new data center. You must complete the following steps before 31 August 2020: 

1. Identify any virtual server instances or bare metal servers that are currently running on the data centers that are set to close. For more information, contact the Client Success team [Live chat](https://www.ibm.com/cloud/data-centers/?focusArea=WCP%20-%20Pooled%20CSM&contactmodule){: external} and view [Determining your current hardware configuration](link). 
1. Order replacement servers in new data centers and choose from different. For more information, contact the Client Success team [Live chat](https://www.ibm.com/cloud/data-centers/?focusArea=WCP%20-%20Pooled%20CSM&contactmodule){: external} or visit the following documentation:
  * [Planning for VPC instances](/docs/vpc?topic=vpc-vsi_best_practices)
  * [Getting started with virtual servers](/docs/vsi?topic=virtual-servers-getting-started-tutorial)
  * [Getting started with bare metal servers](/docs/bare-metal?topic=bare-metal-getting-started) 
  * [Comparing {{site.data.keyword.cloud_notm}} Classic and VPC infrastructure environments](/docs/overview?topic=overview-compare-infrastructure)
1. Migrate your workloads to a new {{site.data.keyword.cloud_notm}} data center before 31 August 2020 to avoid service interruptions. See [Copying data from my old server](/docs/resources?topic=resources-migrate-data-center#copying-data-to-new-server) or contact the Client Success team [Live chat](https://www.ibm.com/cloud/data-centers/?focusArea=WCP%20-%20Pooled%20CSM&contactmodule){: external} for more information.
1. Cancel your servers after you complete the migration to a new data center. The old servers continue to be invoiced until they're canceled. For more information, see [Device types and actions](/docs/vsi?topic=virtual-servers-managing-virtual-servers#device-types-and-actions) and [Cancel](/docs/vsi?topic=virtual-servers-managing-virtual-servers#cancel). 

For more information about data centers that are available for you to migrate your current services, see [Locations, regions, and data centers](/docs/overview?topic=overview-locations). For a current list of multizone regions (MZRs) that feature multiple availability zones for increased fault tolerance, see [Multizone regions](/docs/overview?topic=overview-locations#mzr-table). 

For more information about the benefits of MZRs, see [Why Deploy Applications on {{site.data.keyword.cloud_notm}} Availability Zones?](https://www.ibm.com/cloud/blog/why-deploy-applications-on-ibm-cloud-availability-zones){: external}.
{: tip}

### Special offers for migration
{: #special-offers-migration}

Transferring data centers can be complex and costly. View the following offers and contact the Client Success team [Live chat](https://www.ibm.com/cloud/data-centers/?focusArea=WCP%20-%20Pooled%20CSM&contactmodule){: external} for more information.

* Two months free on replacement servers or services in new data centers.  
* The same or a lower price with a same or better configuration.
  * **Bare metal to virtual server**: Migrate to a new {{site.data.keyword.IBM_notm}} virtual server and pay a lower price with the same configuration or next available upgrade. This includes a free architectural consultation with guidance on recommended configurations to help you with the transition and maximize solution performance.
  * **Bare metal to bare metal server**: Migrate to a new bare metal server and pay the same price with the same configuration or next available upgrade.  
  * **Virtual server to virtual server**: For existing virtual servers, pay the same price with the same configuration or next available upgrade.  


## Determining your current hardware configuration
{: #current-hardware-config}

From your Resource list, you can find system configuration details. Location indicates the data center where the resource is configured. You can view the processor type, for example, Single Intel Xeon E3-1270 (4 Cores, 3.50 GHz). You can also view the amount of memory (RAM), storage, and other data.

To view your current hardware configuration, use the following steps:

1. From the {{site.data.keyword.cloud_notm}} console, click the Menu icon ![Menu icon](../icons/icon_hamburger.svg) > **Resource list** to view your list of resources.
2. Expand **Devices**. 
3. Select the device from the list to see details.  


## Copying data from my old server to the new one
{: #copying-data-to-new-server}

You must establish connectivity between the old and new servers and have sufficient storage in the new server. Use one of the following methods to copy your data.

* [scp](https://www.ibm.com/support/knowledgecenter/ST5Q4U_1.5.2/com.ibm.storwize.v7000.unified.152.doc/usgr_usng_scp.html){: external} is a good choice to securely copy a file from source to destination. 
* If you need to copy multiple files, [rsync](https://download.samba.org/pub/rsync/rsync.html){: external} over ssh is much faster than scp. rsync also copies directory structures and preserves file permissions. 

Copy only applications and application data between systems. Copying older versions of operating system files to a newer version can cause problems. Shut down databases before you copy them between the systems to ensure that the data is consistent. When migrating database data, ensure that data is migrated in a way that doesn’t limit your options to import it into the new system. Rather than copy database data from system to system, consider exporting it to a format so you can import it to a newer database. Flat text files, CSV files, and other files, provide more options than using proprietary or closed file formats when it comes to moving data between systems. Always test your data migration approaches on a small set of test data before officially copying.
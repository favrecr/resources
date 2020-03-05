---

copyright:

  years: 2020

lastupdated: "2020-03-04"

keywords: migration FAQs, data centers

subcollection: resources

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:tip: .tip}
{:new_window: target="_blank"}
{:faq: data-hd-content-type='faq'}

#  FAQs for data center closures and migration
{: #faqs-dc-closure}


##  Why am I required to move to another data center?
{: #dc-required-move}
{: faq}

To continue bringing you the best service, hardware, and connectivity, data centers are continually evaluated to ensure that they meet networking, electrical, and other infrastructure standards. The [closing data centers](/docs/get-support?topic=get-support-dc-migrate) no longer meet the ongoing standards.


## Do I need to be fully migrated on the date my data center is closed?
{: #dc-fully-migrated}
{: faq}

Yes. To ensure that you have no interruption in service, we try to allow as much lead time as possible to make the transition easier. 


## Will I need to move to another data center ever again?
{: #dc-move-again}
{: faq}

We constantly evaluate the quality of our sites to bring you the best and most dependable service. It's possible that we might have other moves as we continue to evaluate some of the older sites.


## How do I select which data center to deploy to?
{: #dc-select-deploy}
{: faq}

{{site.data.keyword.IBM_notm}} has more than 60 data centers in locations around the world. View the data center map on our [global data centers page](https://www.ibm.com/cloud/data-centers/){: external} to see the data centers in which you can deploy. 

The following factors might influence which data center you select:
* Proximity to the users of the systems
* Proximity to any other systems that this server needs to communicate with
* Any data policies or regulations that require data to be stored in a specific location


## What data centers can I use during the transition period?
{: #dc-transition-sites}
{: faq}

You can use any worldwide {{site.data.keyword.cloud_notm}} data centers during your transition period, which lasts up to 60 days. See [global data centers page](https://www.ibm.com/cloud/data-centers/){: external} to view the data center map.


## Are the two free months of transition period resources in addition to my existing server time?
{: #dc-free-months}
{: faq}

Yes. You can [contact an appropriate support representative](https://www.ibm.com/cloud/data-centers/?focusArea=WCP%20-%20Pooled%20CSM&contactmodule){: external} to help you through the process of acquiring your transition period servers.


## How do I determine my current hardware configuration?
{: #dc-determine-config}
{: faq}

You can find your system configuration details by selecting you device from your Resource list. For more information, see [Determining your current hardware configuration](/docs/resources?topic=resources-migrate-data-center#current-hardware-config). 


## How do I determine the utilization of my current hardware?
{: #dc-determine-utilization} 
{: faq}

In general, you need to understand which specific resources within the system are required regarding things like the processor, memory, disk, and network. Having this information can help you better size your new system. For example, a system where memory capacity is frequently overcommitted is likely to benefit from larger memory sizes in the target system that you migrate to.

Most operating systems provide tools that you can use to understand the utilization of your system, for example, vmstat and iostat on Linux or Windows System Performance Monitor. Performance monitoring and tuning is something that you might invest significant time and effort in. 

For more information, contact the Client Success team [Live chat](https://www.ibm.com/cloud/data-centers/?focusArea=WCP%20-%20Pooled%20CSM&contactmodule){: external}.


## How do I compare old and new processors?
{: #dc-compare-processor}
{: faq}

To compare the specifications of old and new Intel processors, go to [Intel processors product specifications page](https://ark.intel.com/content/www/us/en/ark.html#@Processors){: external}. Newer processors tend to have more processor cores and typically run at slower clock speeds than older variants. 

If you have a workload that is processor-bound, meaning that the performance is limited by the speed of the processor, choose a processor that has fewer cores and a higher clock speed. If you run many workloads that aren't constrained by processor speed, choose a processor with more cores and a similar, or slower, clock speed.


## How do I choose my new operating system?
{: #dc-choose-os}
{: faq}

Compatibility and functionality are two of the main influencers when you choose a new operating system. Older versions of operating systems can present challenges with migration. Installation media might not be compatible and the server hardware might not be supported by the older operating system. The best course of action is to compare specs and ensure that the operating system is compatible. Functionality is important because if you have the source code for the application, ensure the necessary development tools and supporting operating system or middleware functions are available on the new platform. In general, Linux type systems are better at supporting older applications on newer versions of the operating system than Windows.

For more information, contact the Client Success team [Live chat](https://www.ibm.com/cloud/data-centers/?focusArea=WCP%20-%20Pooled%20CSM&contactmodule){: external}.


## What bandwidth do I get with my new configuration and is it at the same rate I currently have?
{: #dc-bandwidth-rate}
{: faq}

You receive a current bandwidth package that is most closely related to the package you currently have. The rate for that package is whatever your current rate or package includes.


## How do I copy data from my old server to the new one?
{: #dc-copy-data}
{: faq}

You can copy applications and application data from your old server to your new one. For more information, see [Copying data from my old server to the new one](/docs/resources?topic=resources-migrate-data-center#copying-data-to-new-server).


## Do I need to set up my networking again at the new site?
{: #dc-setup-networking}
{: faq}

Most likely, your networking needs to change to work with the new servers and site. If you need help with this process, contact the [{{site.data.keyword.cloud_notm}} support team](/docs/get-support?topic=get-support-dc-migrate#dc-migration-help). For more information about setting up your network, see [Setting up a virtual machine network](/docs/infrastructure/virtualization?topic=Virtualization-setting-up-a-virtual-machine-network).


## Can I keep my existing IP addresses?
{: #dc-ip-addresses}

Your new servers come with new primary IP subnets. Your current IP addresses cannot be transferred. If you need additional IP addresses, you can request those directly through the IBM Cloud console. 

For more information about VPC subnets, see [Bring your own subnet](/docs/vpc?topic=vpc-configuring-address-prefixes). For more information about Classic infrastructure subnets, see [Getting started with subnets and IPs](/docs/subnets?topic=subnets-getting-started). In your new IP address request, you are migrating from a [data center that is closing](/docs/get-support?topic=get-support-dc-migrate).
---

copyright:
  years: 2018, 2020
lastupdated: "2020-05-28"

keywords: set up private endpoints, private endpoint,private network endpoint,connect service over private network

subcollection: resources

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}
{:codeblock: .codeblock}
{:pre: .pre}
{:screen: .screen}
{:tip: .tip}
{:download: .download}

# Setting up service endpoints
{: #private-network-endpoints}

To connect to {{site.data.keyword.cloud}} services over a private network, you must have access to classic infrastructure and enable virtual routing and forwarding (VRF) and connectivity to service endpoints for your account. Then, you can start creating services that support service endpoints for a private network connection.
{: shortdesc}

Complete the following steps to ensure that your account is set up to create and use services that support service endpoints:

1. Check that you have access to {{site.data.keyword.cloud_notm}} infrastructure in your account. Go to the **Menu** icon ![Menu icon](../icons/icon_hamburger.svg) > **Classic Infrastructure** to verify that you have access.
2. Enable your account for VRF. For more information, see [Enabling virtual routing and forwarding](/docs/account?topic=account-vrf-service-endpoint#vrf).
3. Enable your account for connectivity to service endpoints. For more information, see [Enabling service endpoints](/docs/account?topic=account-vrf-service-endpoint#service-endpoint).

After you enable the VRF and service endpoint account settings, you can create resources from the catalog that support service endpoints. The following table lists the services that support using service endpoints.

Refer to the documentation for the specific service for more information about using service endpoints.
{: tip}

## Services that support service endpoints
{: #services-support-service-endpoints}

| Service | Documentation |
|-------------------|-------------------------------|
| {{site.data.keyword.iae_short}} | [{{site.data.keyword.iae_short}} cloud service endpoints integration](/docs/services/AnalyticsEngine?topic=AnalyticsEngine-service-endpoint-integration) |
| {{site.data.keyword.databases-for-elasticsearch}} | [{{site.data.keyword.databases-for-elasticsearch}} service endpoints integration](/docs/services/databases-for-elasticsearch?topic=cloud-databases-service-endpoints) |
| {{site.data.keyword.databases-for-etcd}} | [{{site.data.keyword.databases-for-etcd}} service endpoints integration](/docs/services/databases-for-etcd?topic=cloud-databases-service-endpoints) |
| {{site.data.keyword.databases-for-mongodb}} | [{{site.data.keyword.databases-for-mongodb}} service endpoints integration](/docs/services/databases-for-mongodb?topic=cloud-databases-service-endpoints) |
| {{site.data.keyword.databases-for-postgresql}} | [{{site.data.keyword.databases-for-postgresql}} service endpoints integration](/docs/services/databases-for-postgresql?topic=cloud-databases-service-endpoints)|
| {{site.data.keyword.databases-for-redis}} | [{{site.data.keyword.databases-for-redis}} service endpoints integration](/docs/services/databases-for-redis?topic=cloud-databases-service-endpoints)|
| {{site.data.keyword.Db2_on_Cloud_short}} | [Connectivity options](/docs/services/Db2onCloud?topic=Db2onCloud-connect_options) |
| {{site.data.keyword.dashdbshort}} | [Connecting to a private endpoint](/docs/services/Db2whc?topic=Db2whc-connect_options#priv_endpt) |
|{{site.data.keyword.messagehub}} | [Restricting network access using the Enterprise plan](/docs/EventStreams?topic=EventStreams-restrict_access) |
| {{site.data.keyword.hscrypto}} | [{{site.data.keyword.hscrypto}} service endpoints integration](/docs/services/hs-crypto?topic=hs-crypto-private-endpoints)|
| {{site.data.keyword.cloudant}}  |  [Available for all dedicated hardware plans deployed after 1 January 2019](//docs/Cloudant?topic=Cloudant-ibm-cloud-public#dedicated-hardware-plan) |
| {{site.data.keyword.registryshort_notm}} | {{site.data.keyword.containershort}} clusters with [private service endpoints only](/docs/containers?topic=containers-plan_clusters#workeruser-master) pull container images by using the [{{site.data.keyword.registryshort_notm}}](/docs/Registry?topic=Registry-registry_overview) service endpoint. |
| {{site.data.keyword.cfee_full}} | [{{site.data.keyword.cfee_full_notm}} service endpoints integration](/docs/cloud-foundry?topic=cloud-foundry-isolated-network#private-access)|
| {{site.data.keyword.streaminganalyticsfull}} |  [Managing service endpoints for {{site.data.keyword.streaminganalyticsshort}}](/docs/services/StreamingAnalytics?topic=StreamingAnalytics-manage_endpoints#manage_endpoints) |
| {{site.data.keyword.keymanagementserviceshort}} | [Connecting to {{site.data.keyword.keymanagementserviceshort}} on the {{site.data.keyword.cloud_notm}} private network](/docs/services/key-protect?topic=key-protect-private-endpoints) |
| KMIP for VMware on {{site.data.keyword.cloud_notm}} | [KMIP for VMware on {{site.data.keyword.cloud_notm}} documentation](/docs/vmwaresolutions?topic=vmwaresolutions-kmip_standalone_considerations#kmip_standalone_considerations-install)|
| {{site.data.keyword.containershort}} | [Public and private service endpoints for {{site.data.keyword.containershort_notm}}](/docs/containers?topic=containers-plan_clusters#workeruser-master) |
| {{site.data.keyword.messages-for-rabbitmq}} | [{{site.data.keyword.messages-for-rabbitmq}} service endpoints integration](/docs/services/messages-for-rabbitmq?topic=cloud-databases-service-endpoints)|
| {{site.data.keyword.cos_short}} | [{{site.data.keyword.cos_short}}](/docs/services/cloud-object-storage?topic=cloud-object-storage-advanced-endpoints) utilizes {{site.data.keyword.keymanagementserviceshort}}'s service endpoint for its BYOK integration|
| {{site.data.keyword.la_full}} | [{{site.data.keyword.la_full_notm}} service endpoints integration](/docs/Log-Analysis-with-LogDNA?topic=Log-Analysis-with-LogDNA-endpoints)|
| {{site.data.keyword.mon_full_notm}} | [{{site.data.keyword.mon_full_notm}} service endpoints integration](/docs/Monitoring-with-Sysdig?topic=Monitoring-with-Sysdig-endpoints#endpoints_ingestion)|
| {{site.data.keyword.bpshort}} | [Using private endpoints](/docs/schematics?topic=schematics-private-endpoints) |
| {{site.data.keyword.conversationshort}} | [Protecting sensitive information](/docs/assistant?topic=assistant-security) with {{site.data.keyword.conversationshort}} |
| {{site.data.keyword.ibmwatson_notm}} {{site.data.keyword.cncshort}} | [Public and private network endpoints](/docs/compare-comply?topic=watson-public-private-endpoints) with {{site.data.keyword.cncshort}} |
| {{site.data.keyword.ibmwatson_notm}} {{site.data.keyword.discoveryshort}} | [Public and private network endpoints](/docs/discovery?topic=watson-public-private-endpoints) with {{site.data.keyword.discoveryshort}} |
| {{site.data.keyword.ibmwatson_notm}} {{site.data.keyword.wh-iml_short}} | [Public and private network endpoints](/docs/wh-iml?topic=watson-public-private-endpoints) with {{site.data.keyword.wh-iml_short}} |
| {{site.data.keyword.ibmwatson_notm}} {{site.data.keyword.knowledgestudioshort}} | [Public and private network endpoints](/docs/services/watson-knowledge-studio?topic=watson-public-private-endpoints) with {{site.data.keyword.knowledgestudioshort}} |
| {{site.data.keyword.ibmwatson_notm}} {{site.data.keyword.languagetranslatorshort}} | [Public and private network endpoints](/docs/services/language-translator?topic=watson-public-private-endpoints) with {{site.data.keyword.languagetranslatorshort}} |
| {{site.data.keyword.ibmwatson_notm}} {{site.data.keyword.nlushort}} | [Public and private network endpoints](/docs/services/natural-language-understanding?topic=watson-public-private-endpoints) with {{site.data.keyword.nlushort}} |
| {{site.data.keyword.ibmwatson_notm}} {{site.data.keyword.personalityinsightsshort}} | [Public and private network endpoints](/docs/services/personality-insights?topic=watson-public-private-endpoints) with {{site.data.keyword.personalityinsightsshort}} |
| {{site.data.keyword.ibmwatson_notm}} {{site.data.keyword.speechtotextshort}} | [Public and private network endpoints](/docs/services/speech-to-text?topic=watson-public-private-endpoints) with {{site.data.keyword.speechtotextshort}} |
| {{site.data.keyword.ibmwatson_notm}} {{site.data.keyword.texttospeechshort}} | [Public and private network endpoints](/docs/services/text-to-speech?topic=watson-public-private-endpoints) with {{site.data.keyword.texttospeechshort}} |
| {{site.data.keyword.ibmwatson_notm}} {{site.data.keyword.toneanalyzershort}} | [Public and private network endpoints](/docs/services/tone-analyzer?topic=watson-public-private-endpoints) with {{site.data.keyword.toneanalyzershort}} |
{: caption="Table 1. Services that support using service endpoints" caption-side="top"}

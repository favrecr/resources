---

copyright:

  years: 2015, 2020
lastupdated: "2020-06-16"

keywords: location, regions, data centers, service location, service availability, multizone region, MZR

subcollection: resources

---
{:
{:new_window: target="_blank"}
{:shortdesc: .shortdesc}

# Service  and infrastructure availability
{: #services_region}

{{site.data.keyword.Bluemix}} makes it easy for you to implement, host, and scale services, infrastructure, and apps so you can focus on your application logic and application design. However, not all services and infrastructure are available for purchase in every {{site.data.keyword.Bluemix_notm}} location.
{:shortdesc} 

IBM provides SDKs and APIs for all services that are general availablity. Check out the reference docs in the [API & SDK reference library](/docs?tab=api-docs).

## Services
{: #paas-services}

Some services are available to purchase in a location, but that service's data might be hosted in a different location. The following table shows the services that are provided by IBM. For the full list of resources that are available, see the [catalog](https://cloud.ibm.com/catalog){: new_window} ![External link icon](../icons/launch-glyph.svg "External link icon") in the {{site.data.keyword.Bluemix_notm}} console.

Services that are hosted globally create resources that operate across multiple locations. For example, with {{site.data.keyword.cos_full_notm}}, you can choose to deploy data in a single data center, or even a combination of locations by selecting the endpoint where your application sends REST API requests.

<!-- Everthing above, can be changed, edited, modified in this Markdown file. Everything after, is maintained in the script file -->
<!-- Do not manually change the table or add content in this table or after this table. -->

<!-- Everything is deleted after this line. -->
| Service | Dallas | Washington DC | 
|-----|-----|-----|
| API Connect | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| API Gateway | Hosted Globally | Hosted Globally | 
| Analytics Engine | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| Annotator for Clinical Data | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| App Connect | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| App ID | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Automated Accessibility Tester | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| Availability Monitoring | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| BigInsights for Apache Hadoop (Subscription) | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| Block Storage for VPC | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Blockchain | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| Blockchain Platform | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Certificate Manager | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Cloud Foundry Enterprise Environment | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Cloud Object Storage | Hosted Globally | Hosted Globally | 
| Cloudant | Hosted Globally | Hosted Globally | 
| Compare and Comply | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Compose Enterprise | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Compose for Elasticsearch | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Compose for JanusGraph | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Compose for MongoDB | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Compose for MySQL | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Compose for PostgreSQL | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Compose for RabbitMQ | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Compose for Redis | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Compose for RethinkDB | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Compose for ScyllaDB | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Compose for etcd | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Consult with IBM Garage | Hosted Globally | Hosted Globally | 
| Container Registry | Hosted Globally | Hosted Globally | 
| Continuous Delivery | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Cost and Asset Management | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| DNS Services | Hosted Globally | Hosted Globally | 
| Databases for Elasticsearch | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Databases for MongoDB | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Databases for PostgreSQL | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Databases for Redis | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Databases for etcd | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Db2 | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| Db2 Hosted | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| Db2 Warehouse | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| Digital Content Checker | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| Direct Link Dedicated | Hosted Globally | Hosted Globally | 
| Discovery | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Event Streams | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Floating IP for VPC | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Functions | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Globalization Pipeline | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| Historical Instrument Analytics | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| Hyper Protect Crypto Services | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| Hyper Protect DBaaS for MongoDB | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| Hyper Protect DBaaS for PostgreSQL | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| Hyper Protect Virtual Server | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| IBM Cloud Activity Tracker with LogDNA | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| IBM Cloud Data Shield | Hosted Globally | Hosted Globally | 
| IBM Cognos Dashboard Embedded | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| IBM Log Analysis with LogDNA | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Image Service for VPC | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Information Server | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| Informix | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| Instrument Analytics | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| Internet Services | Hosted Globally | Hosted Globally | 
| Internet of Things Platform | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Investment Portfolio | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| Key Protect | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Knowledge Catalog | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| Knowledge Studio | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Kubernetes Service | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Language Translator | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Lift CLI | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| Load Balancer for VPC | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| MQ | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| Machine Learning | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| Mass Data Migration | Hosted Globally | Hosted Globally | 
| Master Data Management | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| Messages for RabbitMQ | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Mobile Foundation | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Natural Language Classifier | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Natural Language Understanding | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Network ACL | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Personality Insights | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Portfolio Optimization | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| Power Systems Virtual Server | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Predictive Market Scenarios | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| Project Coligo | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| Public Gateway for VPC | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Push Notifications | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Real-Time Payments | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| Red Hat OpenShift on IBM Cloud | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| SQL Query | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| SSH Key for VPC | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Schematics | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Secure Gateway | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Security Advisor | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| Security Group for VPC | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Simulated Historical Instrument Analytics | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| Simulated Instrument Analytics | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| Speech to Text | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Streaming Analytics | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Subnet | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Text to Speech | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Tone Analyzer | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Toolchain | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Transit Gateway | Hosted Globally | Hosted Globally | 
| VMware Solutions | Hosted Globally | Hosted Globally | 
| VPN for VPC | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Virtual Private Cloud | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Virtual Server for VPC | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Visual Recognition | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| Voice Agent with Watson | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Watson Assistant | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Watson OpenScale | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| Watson Studio | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| WebSphere Application Server | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
{: row-headers}
{: caption="Table 1. Service availability - Americas" caption-side="top"}
{: #paas-table1}
{: tab-title="Americas"}
{: tab-group="PaaS"}
{: class="simple-tab-table"}
{: summary="Use the buttons for the countries to change the context of the table. This table has row and column headers. The row headers identify the service. The column headers indentify where that service is located. To understand where a service is located in the table, navigate to the row, and find the for the location you are interested in."}

| Service | London | Frankfurt | 
|-----|-----|-----|
| API Connect | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| API Gateway | Hosted Globally | Hosted Globally | 
| Analytics Engine | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Annotator for Clinical Data |  |  | 
| App Connect | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| App ID | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Automated Accessibility Tester | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| Availability Monitoring | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| BigInsights for Apache Hadoop (Subscription) |  |  | 
| Block Storage for VPC | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Blockchain | ![Checkmark icon](../icons/checkmark-icon.svg)<br>*Data hosted in London* | ![Checkmark icon](../icons/checkmark-icon.svg)<br>*Data hosted in Frankfurt* | 
| Blockchain Platform | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Certificate Manager | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Cloud Foundry Enterprise Environment | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Cloud Object Storage | Hosted Globally | Hosted Globally | 
| Cloudant | Hosted Globally | Hosted Globally | 
| Compare and Comply |  | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Compose Enterprise | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Compose for Elasticsearch | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Compose for JanusGraph | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Compose for MongoDB | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Compose for MySQL | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Compose for PostgreSQL | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Compose for RabbitMQ | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Compose for Redis | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Compose for RethinkDB | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Compose for ScyllaDB | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Compose for etcd | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Consult with IBM Garage | Hosted Globally | Hosted Globally | 
| Container Registry | Hosted Globally | Hosted Globally | 
| Continuous Delivery | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Cost and Asset Management |  |  | 
| DNS Services | Hosted Globally | Hosted Globally | 
| Databases for Elasticsearch | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Databases for MongoDB | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Databases for PostgreSQL | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Databases for Redis | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Databases for etcd | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Db2 | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Db2 Hosted | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Db2 Warehouse | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Digital Content Checker | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| Direct Link Dedicated | Hosted Globally | Hosted Globally | 
| Discovery | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Event Streams | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Floating IP for VPC | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Functions | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Globalization Pipeline | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Historical Instrument Analytics |  |  | 
| Hyper Protect Crypto Services |  | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Hyper Protect DBaaS for MongoDB |  | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Hyper Protect DBaaS for PostgreSQL |  | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Hyper Protect Virtual Server |  | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| IBM Cloud Activity Tracker with LogDNA | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| IBM Cloud Data Shield | Hosted Globally | Hosted Globally | 
| IBM Cognos Dashboard Embedded | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| IBM Log Analysis with LogDNA | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Image Service for VPC | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Information Server | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Informix | ![Checkmark icon](../icons/checkmark-icon.svg)<br>*Data hosted in London* |  | 
| Instrument Analytics |  |  | 
| Internet Services | Hosted Globally | Hosted Globally | 
| Internet of Things Platform | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Investment Portfolio |  |  | 
| Key Protect | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Knowledge Catalog | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Knowledge Studio | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Kubernetes Service | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Language Translator | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Lift CLI |  |  | 
| Load Balancer for VPC | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| MQ | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Machine Learning | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Mass Data Migration | Hosted Globally | Hosted Globally | 
| Master Data Management | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Messages for RabbitMQ | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Mobile Foundation | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Natural Language Classifier | ![Checkmark icon](../icons/checkmark-icon.svg)<br>*Data hosted in London* | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Natural Language Understanding | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Network ACL | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Personality Insights | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Portfolio Optimization |  |  | 
| Power Systems Virtual Server | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Predictive Market Scenarios |  |  | 
| Project Coligo |  |  | 
| Public Gateway for VPC | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Push Notifications | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Real-Time Payments |  |  | 
| Red Hat OpenShift on IBM Cloud | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| SQL Query |  | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| SSH Key for VPC | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Schematics |  | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Secure Gateway | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg)<br>*Data hosted in Frankfurt* | 
| Security Advisor | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| Security Group for VPC | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Simulated Historical Instrument Analytics |  |  | 
| Simulated Instrument Analytics |  |  | 
| Speech to Text | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Streaming Analytics | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Subnet | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Text to Speech | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Tone Analyzer | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Toolchain | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Transit Gateway | Hosted Globally | Hosted Globally | 
| VMware Solutions | Hosted Globally | Hosted Globally | 
| VPN for VPC | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Virtual Private Cloud | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Virtual Server for VPC | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Visual Recognition |  | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Voice Agent with Watson |  | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Watson Assistant | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Watson OpenScale |  | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Watson Studio | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| WebSphere Application Server | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
{: row-headers}
{: caption="Table 2. Service availability - Europe" caption-side="top"}
{: #paas-table2}
{: tab-title="Europe"}
{: tab-group="PaaS"}
{: class="simple-tab-table"}
{: summary="Use the buttons for the countries to change the context of the table. This table has row and column headers. The row headers identify the service. The column headers indentify where that service is located. To understand where a service is located in the table, navigate to the row, and find the for the location you are interested in."}

| Service | Sydney | Tokyo | Seoul | Singapore | 
|-----|-----|-----|-----|-----|
| API Connect | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  |  | 
| API Gateway | Hosted Globally | Hosted Globally | Hosted Globally | Hosted Globally | 
| Analytics Engine |  | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  | 
| Annotator for Clinical Data |  |  |  |  | 
| App Connect | ![Checkmark icon](../icons/checkmark-icon.svg)<br>*Data hosted in Sydney* |  |  |  | 
| App ID | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  | 
| Automated Accessibility Tester | ![Checkmark icon](../icons/checkmark-icon.svg)<br>*Data hosted in Sydney* |  |  |  | 
| Availability Monitoring | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  |  | 
| BigInsights for Apache Hadoop (Subscription) |  |  |  |  | 
| Block Storage for VPC | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  | 
| Blockchain | ![Checkmark icon](../icons/checkmark-icon.svg)<br>*Data hosted in Sydney* |  |  |  | 
| Blockchain Platform | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  | 
| Certificate Manager | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  | 
| Cloud Foundry Enterprise Environment | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Cloud Object Storage | Hosted Globally | Hosted Globally | Hosted Globally | Hosted Globally | 
| Cloudant | Hosted Globally | Hosted Globally | Hosted Globally | Hosted Globally | 
| Compare and Comply |  |  |  |  | 
| Compose Enterprise | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  |  | 
| Compose for Elasticsearch | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  |  | 
| Compose for JanusGraph | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  |  | 
| Compose for MongoDB | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  |  | 
| Compose for MySQL | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  |  | 
| Compose for PostgreSQL | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  |  | 
| Compose for RabbitMQ | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  |  | 
| Compose for Redis | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  |  | 
| Compose for RethinkDB | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  |  | 
| Compose for ScyllaDB | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  |  | 
| Compose for etcd | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  |  | 
| Consult with IBM Garage | Hosted Globally | Hosted Globally | Hosted Globally | Hosted Globally | 
| Container Registry | Hosted Globally | Hosted Globally | Hosted Globally | Hosted Globally | 
| Continuous Delivery |  | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  | 
| Cost and Asset Management |  |  |  |  | 
| DNS Services | Hosted Globally | Hosted Globally | Hosted Globally | Hosted Globally | 
| Databases for Elasticsearch | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| Databases for MongoDB | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| Databases for PostgreSQL | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| Databases for Redis | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| Databases for etcd | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| Db2 | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  |  | 
| Db2 Hosted | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  |  | 
| Db2 Warehouse | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  |  | 
| Digital Content Checker | ![Checkmark icon](../icons/checkmark-icon.svg)<br>*Data hosted in Sydney* |  |  |  | 
| Direct Link Dedicated | Hosted Globally | Hosted Globally | Hosted Globally | Hosted Globally | 
| Discovery | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| Event Streams | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| Floating IP for VPC | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  | 
| Functions |  | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  | 
| Globalization Pipeline | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  |  | 
| Historical Instrument Analytics |  |  |  |  | 
| Hyper Protect Crypto Services | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  |  | 
| Hyper Protect DBaaS for MongoDB | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  |  | 
| Hyper Protect DBaaS for PostgreSQL | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  |  | 
| Hyper Protect Virtual Server | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  |  | 
| IBM Cloud Activity Tracker with LogDNA | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| IBM Cloud Data Shield | Hosted Globally | Hosted Globally | Hosted Globally | Hosted Globally | 
| IBM Cognos Dashboard Embedded |  |  |  |  | 
| IBM Log Analysis with LogDNA | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| Image Service for VPC | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  | 
| Information Server | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  |  | 
| Informix | ![Checkmark icon](../icons/checkmark-icon.svg)<br>*Data hosted in Sydney* |  |  |  | 
| Instrument Analytics |  |  |  |  | 
| Internet Services | Hosted Globally | Hosted Globally | Hosted Globally | Hosted Globally | 
| Internet of Things Platform |  |  |  |  | 
| Investment Portfolio |  |  |  |  | 
| Key Protect | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  | 
| Knowledge Catalog |  | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  | 
| Knowledge Studio | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| Kubernetes Service | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Language Translator | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| Lift CLI |  |  |  |  | 
| Load Balancer for VPC | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  | 
| MQ | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  |  | 
| Machine Learning |  | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  | 
| Mass Data Migration | Hosted Globally | Hosted Globally | Hosted Globally | Hosted Globally | 
| Master Data Management | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  |  | 
| Messages for RabbitMQ | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| Mobile Foundation | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  |  | 
| Natural Language Classifier | ![Checkmark icon](../icons/checkmark-icon.svg)<br>*Data hosted in Sydney* | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| Natural Language Understanding | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| Network ACL |  | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  | 
| Personality Insights | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| Portfolio Optimization |  |  |  |  | 
| Power Systems Virtual Server |  |  |  |  | 
| Predictive Market Scenarios |  |  |  |  | 
| Project Coligo |  |  |  |  | 
| Public Gateway for VPC | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  | 
| Push Notifications | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  | 
| Real-Time Payments |  |  |  |  | 
| Red Hat OpenShift on IBM Cloud | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| SQL Query |  |  |  |  | 
| SSH Key for VPC | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  | 
| Schematics |  |  |  |  | 
| Secure Gateway | ![Checkmark icon](../icons/checkmark-icon.svg)<br>*Data hosted in Sydney* |  |  |  | 
| Security Advisor |  |  |  |  | 
| Security Group for VPC | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  | 
| Simulated Historical Instrument Analytics |  |  |  |  | 
| Simulated Instrument Analytics |  |  |  |  | 
| Speech to Text | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| Streaming Analytics |  |  |  |  | 
| Subnet | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  | 
| Text to Speech | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| Tone Analyzer | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| Toolchain | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  | 
| Transit Gateway | Hosted Globally | Hosted Globally | Hosted Globally | Hosted Globally | 
| VMware Solutions | Hosted Globally | Hosted Globally | Hosted Globally | Hosted Globally | 
| VPN for VPC | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  | 
| Virtual Private Cloud | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  | 
| Virtual Server for VPC | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  | 
| Visual Recognition |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| Voice Agent with Watson |  |  |  |  | 
| Watson Assistant | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| Watson OpenScale |  |  |  |  | 
| Watson Studio |  | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  | 
| WebSphere Application Server | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  |  | 
{: row-headers}
{: caption="Table 3. Service availability - Asia Pacific" caption-side="top"}
{: #paas-table3}
{: tab-title="Asia Pacific"}
{: tab-group="PaaS"}
{: class="simple-tab-table"}
{: summary="Use the buttons for the countries to change the context of the table. This table has row and column headers. The row headers identify the service. The column headers indentify where that service is located. To understand where a service is located in the table, navigate to the row, and find the for the location you are interested in."}



## Infrastructure
{: #iaas-service-infra}

Infrastructure services are available to be deployed in data centers. Each column header that ends with a number represents a data center or multi-zone region (MZR). Columns marked (MZR) represent a location where resources are automatically deployed and managed across several data centers.

### Americas
{: #iaas-service-americas}

The following infrastructure resources are available in North and South America. Match the resource row with the column representing the data center or multi-zone region. A check mark indicates the resource is available in that location. The Dallas (MZR) and Washington DC (MZR) columns represent multi-zone regions where deployment is managed automatically across several data centers.

| Service | Montreal 01 | Toronto 01 | 
|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|
| Bare Metal Server | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Block Storage | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Citrix NetScaler VPX | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Cloud HSM | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Content Delivery Network | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Direct Link Connect on Classic |  |  | 
| Direct Link Dedicated Hosting on Classic |  | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Direct Link Dedicated on Classic | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Direct Link Exchange on Classic |  |  | 
| File Storage | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| FortiGate Security Appliance 10Gbps |  | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| FortiGate Security Appliance 1Gbps | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Gateway Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Hardware Firewall | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Hardware Firewall (Dedicated) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| IBM Cloud Backup | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| IBM Cloud Load Balancer | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| IPSec VPN | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Juniper vSRX | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| SSL Certificates | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Subnets/IPs | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Virtual Router Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
{: row-headers}
{: caption="Table 4. Americas infrastructure availability - Canada" caption-side="top"}
{: #iaas-table1}
{: tab-title="Canada"}
{: tab-group="Americas"}
{: class="comparison-tab-table"}
{: summary="Use the buttons for the countries to change the context of the table. This table has row and column headers. The row headers identify the service. The column headers indentify where that service is located. To understand where a service is located in the table, navigate to the row, and find the for the location you are interested in."}


| Service | Dallas (MZR) | Dallas 01 | Dallas 05 | Dallas 06 | Dallas 07 | Dallas 09 | Dallas 10 | Dallas 12 | Dallas 13 | Houston 01 | Houston 02 | Seattle 01 | San Jose 01 | San Jose 03 | San Jose 04 | Washington DC (MZR) | Washington DC 01 | Washington DC 04 | Washington DC 06 | Washington DC 07 | 
|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|
| Bare Metal Server | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Block Storage | ![Checkmark icon](../icons/checkmark-icon.svg) |  | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Citrix NetScaler VPX | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Cloud HSM | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Content Delivery Network | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Direct Link Connect on Classic | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  |  |  |  |  |  |  |  |  |  |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  |  |  | 
| Direct Link Dedicated Hosting on Classic |  |  |  |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  | 
| Direct Link Dedicated on Classic | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Direct Link Exchange on Classic | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  |  |  |  |  |  |  |  |  |  |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  |  |  | 
| File Storage | ![Checkmark icon](../icons/checkmark-icon.svg) |  | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| FortiGate Security Appliance 10Gbps | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| FortiGate Security Appliance 1Gbps | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Gateway Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Hardware Firewall | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Hardware Firewall (Dedicated) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| IBM Cloud Backup |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| IBM Cloud Load Balancer | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| IPSec VPN | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Juniper vSRX | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| SSL Certificates | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Subnets/IPs | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Virtual Router Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
{: row-headers}
{: caption="Table 5. Americas infrastructure availability - United States" caption-side="top"}
{: #iaas-table2}
{: tab-title="United States"}
{: tab-group="Americas"}
{: class="comparison-tab-table"}
{: summary="Use the buttons for the countries to change the context of the table. This table has row and column headers. The row headers identify the service. The column headers indentify where that service is located. To understand where a service is located in the table, navigate to the row, and find the for the location you are interested in."}


| Service | Mexico 01 | 
|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|
| Bare Metal Server | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Block Storage | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Citrix NetScaler VPX | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Cloud HSM |  | 
| Content Delivery Network | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Direct Link Connect on Classic |  | 
| Direct Link Dedicated Hosting on Classic |  | 
| Direct Link Dedicated on Classic | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Direct Link Exchange on Classic |  | 
| File Storage | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| FortiGate Security Appliance 10Gbps | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| FortiGate Security Appliance 1Gbps | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Gateway Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Hardware Firewall | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Hardware Firewall (Dedicated) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| IBM Cloud Backup | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| IBM Cloud Load Balancer | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| IPSec VPN | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Juniper vSRX | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| SSL Certificates | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Subnets/IPs | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Virtual Router Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) | 
{: row-headers}
{: caption="Table 6. Americas infrastructure availability - Mexico" caption-side="top"}
{: #iaas-table3}
{: tab-title="Mexico"}
{: tab-group="Americas"}
{: class="comparison-tab-table"}
{: summary="Use the buttons for the countries to change the context of the table. This table has row and column headers. The row headers identify the service. The column headers indentify where that service is located. To understand where a service is located in the table, navigate to the row, and find the for the location you are interested in."}


| Service | Sao Paulo 01 | 
|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|
| Bare Metal Server | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Block Storage | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Citrix NetScaler VPX | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Cloud HSM |  | 
| Content Delivery Network | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Direct Link Connect on Classic |  | 
| Direct Link Dedicated Hosting on Classic | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Direct Link Dedicated on Classic | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Direct Link Exchange on Classic |  | 
| File Storage | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| FortiGate Security Appliance 10Gbps |  | 
| FortiGate Security Appliance 1Gbps | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Gateway Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Hardware Firewall | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Hardware Firewall (Dedicated) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| IBM Cloud Backup | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| IBM Cloud Load Balancer | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| IPSec VPN | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Juniper vSRX | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| SSL Certificates | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Subnets/IPs | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Virtual Router Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) | 
{: row-headers}
{: caption="Table 7. Americas infrastructure availability - Brazil" caption-side="top"}
{: #iaas-table4}
{: tab-title="Brazil"}
{: tab-group="Americas"}
{: class="comparison-tab-table"}
{: summary="Use the buttons for the countries to change the context of the table. This table has row and column headers. The row headers identify the service. The column headers indentify where that service is located. To understand where a service is located in the table, navigate to the row, and find the for the location you are interested in."}


### Europe
{: #iaas-service-europe}

The following infrastructure resources are available in Europe. Match the resource row with the column representing the data center or multi-zone region. A check mark indicates the resource is available in that location. The London (MZR) and Frankfurt (MZR) columns represent multi-zone regions where deployment is managed automatically across several data centers.

| Service | Amsterdam 01 | Amsterdam 03 | 
|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|
| Bare Metal Server |  |  | 
| Block Storage |  | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Citrix NetScaler VPX |  | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Cloud HSM |  | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Content Delivery Network |  | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Direct Link Connect on Classic |  |  | 
| Direct Link Dedicated Hosting on Classic |  |  | 
| Direct Link Dedicated on Classic |  |  | 
| Direct Link Exchange on Classic |  |  | 
| File Storage |  | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| FortiGate Security Appliance 10Gbps |  |  | 
| FortiGate Security Appliance 1Gbps |  | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Gateway Appliance |  | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Hardware Firewall |  | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Hardware Firewall (Dedicated) |  | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| IBM Cloud Backup |  | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| IBM Cloud Load Balancer |  | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| IPSec VPN |  | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Juniper vSRX |  | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| SSL Certificates |  | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Subnets/IPs |  | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Virtual Router Appliance |  | ![Checkmark icon](../icons/checkmark-icon.svg) | 
{: row-headers}
{: caption="Table 8. Europe infrastructure availability - Netherlands" caption-side="top"}
{: #iaas-table5}
{: tab-title="Netherlands"}
{: tab-group="Europe"}
{: class="comparison-tab-table"}
{: summary="Use the buttons for the countries to change the context of the table. This table has row and column headers. The row headers identify the service. The column headers indentify where that service is located. To understand where a service is located in the table, navigate to the row, and find the for the location you are interested in."}


| Service | Frankfurt (MZR) | Frankfurt 02 | Frankfurt 04 | Frankfurt 05 | 
|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|
| Bare Metal Server | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Block Storage | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Citrix NetScaler VPX | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Cloud HSM | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  | 
| Content Delivery Network | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Direct Link Connect on Classic | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  |  | 
| Direct Link Dedicated Hosting on Classic |  | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  | 
| Direct Link Dedicated on Classic | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Direct Link Exchange on Classic | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  |  | 
| File Storage | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| FortiGate Security Appliance 10Gbps | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| FortiGate Security Appliance 1Gbps | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Gateway Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Hardware Firewall | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Hardware Firewall (Dedicated) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| IBM Cloud Backup |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| IBM Cloud Load Balancer | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| IPSec VPN | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Juniper vSRX | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| SSL Certificates | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Subnets/IPs | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Virtual Router Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
{: row-headers}
{: caption="Table 9. Europe infrastructure availability - Germany" caption-side="top"}
{: #iaas-table6}
{: tab-title="Germany"}
{: tab-group="Europe"}
{: class="comparison-tab-table"}
{: summary="Use the buttons for the countries to change the context of the table. This table has row and column headers. The row headers identify the service. The column headers indentify where that service is located. To understand where a service is located in the table, navigate to the row, and find the for the location you are interested in."}


| Service | London (MZR) | London 02 | London 04 | London 05 | London 06 | 
|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|
| Bare Metal Server | ![Checkmark icon](../icons/checkmark-icon.svg) |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Block Storage | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Citrix NetScaler VPX | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Cloud HSM | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  | 
| Content Delivery Network | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Direct Link Connect on Classic | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  |  |  | 
| Direct Link Dedicated Hosting on Classic |  | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Direct Link Dedicated on Classic | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Direct Link Exchange on Classic | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  |  |  | 
| File Storage | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| FortiGate Security Appliance 10Gbps |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  | 
| FortiGate Security Appliance 1Gbps | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Gateway Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Hardware Firewall | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Hardware Firewall (Dedicated) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| IBM Cloud Backup |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| IBM Cloud Load Balancer | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| IPSec VPN | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Juniper vSRX | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| SSL Certificates | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Subnets/IPs | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Virtual Router Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
{: row-headers}
{: caption="Table 10. Europe infrastructure availability - United Kingdom" caption-side="top"}
{: #iaas-table7}
{: tab-title="United Kingdom"}
{: tab-group="Europe"}
{: class="comparison-tab-table"}
{: summary="Use the buttons for the countries to change the context of the table. This table has row and column headers. The row headers identify the service. The column headers indentify where that service is located. To understand where a service is located in the table, navigate to the row, and find the for the location you are interested in."}


| Service | Milan 01 | 
|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|
| Bare Metal Server | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Block Storage | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Citrix NetScaler VPX | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Cloud HSM |  | 
| Content Delivery Network | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Direct Link Connect on Classic |  | 
| Direct Link Dedicated Hosting on Classic |  | 
| Direct Link Dedicated on Classic | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Direct Link Exchange on Classic |  | 
| File Storage | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| FortiGate Security Appliance 10Gbps |  | 
| FortiGate Security Appliance 1Gbps | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Gateway Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Hardware Firewall | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Hardware Firewall (Dedicated) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| IBM Cloud Backup | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| IBM Cloud Load Balancer | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| IPSec VPN | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Juniper vSRX | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| SSL Certificates | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Subnets/IPs | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Virtual Router Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) | 
{: row-headers}
{: caption="Table 11. Europe infrastructure availability - Italy" caption-side="top"}
{: #iaas-table8}
{: tab-title="Italy"}
{: tab-group="Europe"}
{: class="comparison-tab-table"}
{: summary="Use the buttons for the countries to change the context of the table. This table has row and column headers. The row headers identify the service. The column headers indentify where that service is located. To understand where a service is located in the table, navigate to the row, and find the for the location you are interested in."}


| Service | Oslo 01 | 
|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|
| Bare Metal Server |  | 
| Block Storage | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Citrix NetScaler VPX | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Cloud HSM |  | 
| Content Delivery Network | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Direct Link Connect on Classic |  | 
| Direct Link Dedicated Hosting on Classic |  | 
| Direct Link Dedicated on Classic | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Direct Link Exchange on Classic |  | 
| File Storage | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| FortiGate Security Appliance 10Gbps |  | 
| FortiGate Security Appliance 1Gbps | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Gateway Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Hardware Firewall | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Hardware Firewall (Dedicated) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| IBM Cloud Backup | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| IBM Cloud Load Balancer | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| IPSec VPN | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Juniper vSRX | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| SSL Certificates | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Subnets/IPs | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Virtual Router Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) | 
{: row-headers}
{: caption="Table 12. Europe infrastructure availability - Norway" caption-side="top"}
{: #iaas-table9}
{: tab-title="Norway"}
{: tab-group="Europe"}
{: class="comparison-tab-table"}
{: summary="Use the buttons for the countries to change the context of the table. This table has row and column headers. The row headers identify the service. The column headers indentify where that service is located. To understand where a service is located in the table, navigate to the row, and find the for the location you are interested in."}


| Service | Paris 01 | 
|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|
| Bare Metal Server | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Block Storage | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Citrix NetScaler VPX | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Cloud HSM | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Content Delivery Network | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Direct Link Connect on Classic |  | 
| Direct Link Dedicated Hosting on Classic | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Direct Link Dedicated on Classic | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Direct Link Exchange on Classic |  | 
| File Storage | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| FortiGate Security Appliance 10Gbps | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| FortiGate Security Appliance 1Gbps | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Gateway Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Hardware Firewall | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Hardware Firewall (Dedicated) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| IBM Cloud Backup | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| IBM Cloud Load Balancer | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| IPSec VPN | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Juniper vSRX | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| SSL Certificates | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Subnets/IPs | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Virtual Router Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) | 
{: row-headers}
{: caption="Table 13. Europe infrastructure availability - France" caption-side="top"}
{: #iaas-table10}
{: tab-title="France"}
{: tab-group="Europe"}
{: class="comparison-tab-table"}
{: summary="Use the buttons for the countries to change the context of the table. This table has row and column headers. The row headers identify the service. The column headers indentify where that service is located. To understand where a service is located in the table, navigate to the row, and find the for the location you are interested in."}


### Asia Pacific
{: #iaas-service-asia}

The following infrastructure resources are available in Asia and the Pacific region. Match the resource row with the column representing the data center or multi-zone region. A check mark indicates the resource is available in that location. The Sydney (MZR) and Tokyo (MZR) columns represent multi-zone regions where deployment is managed automatically across several data centers.

| Service | Melbourne 01 | Sydney (MZR) | Sydney 01 | Sydney 04 | Sydney 05 | 
|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|
| Bare Metal Server | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Block Storage | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Citrix NetScaler VPX | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Cloud HSM | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| Content Delivery Network | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Direct Link Connect on Classic |  |  |  |  |  | 
| Direct Link Dedicated Hosting on Classic | ![Checkmark icon](../icons/checkmark-icon.svg) |  | ![Checkmark icon](../icons/checkmark-icon.svg) |  | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Direct Link Dedicated on Classic | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Direct Link Exchange on Classic |  |  |  |  |  | 
| File Storage | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| FortiGate Security Appliance 10Gbps |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  | 
| FortiGate Security Appliance 1Gbps | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Gateway Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Hardware Firewall | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Hardware Firewall (Dedicated) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| IBM Cloud Backup | ![Checkmark icon](../icons/checkmark-icon.svg) |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| IBM Cloud Load Balancer | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| IPSec VPN | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Juniper vSRX | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| SSL Certificates | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Subnets/IPs | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Virtual Router Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
{: row-headers}
{: caption="Table 14. Asia Pacific infrastructure availability - Australia" caption-side="top"}
{: #iaas-table11}
{: tab-title="Australia"}
{: tab-group="Asia Pacific"}
{: class="comparison-tab-table"}
{: summary="Use the buttons for the countries to change the context of the table. This table has row and column headers. The row headers identify the service. The column headers indentify where that service is located. To understand where a service is located in the table, navigate to the row, and find the for the location you are interested in."}


| Service | Hong Kong 02 | 
|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|
| Bare Metal Server |  | 
| Block Storage | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Citrix NetScaler VPX | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Cloud HSM |  | 
| Content Delivery Network | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Direct Link Connect on Classic |  | 
| Direct Link Dedicated Hosting on Classic |  | 
| Direct Link Dedicated on Classic |  | 
| Direct Link Exchange on Classic |  | 
| File Storage | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| FortiGate Security Appliance 10Gbps | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| FortiGate Security Appliance 1Gbps | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Gateway Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Hardware Firewall | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Hardware Firewall (Dedicated) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| IBM Cloud Backup | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| IBM Cloud Load Balancer | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| IPSec VPN | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Juniper vSRX | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| SSL Certificates | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Subnets/IPs | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Virtual Router Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) | 
{: row-headers}
{: caption="Table 15. Asia Pacific infrastructure availability - Hong Kong" caption-side="top"}
{: #iaas-table12}
{: tab-title="Hong Kong"}
{: tab-group="Asia Pacific"}
{: class="comparison-tab-table"}
{: summary="Use the buttons for the countries to change the context of the table. This table has row and column headers. The row headers identify the service. The column headers indentify where that service is located. To understand where a service is located in the table, navigate to the row, and find the for the location you are interested in."}


| Service | Chennai 01 | 
|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|
| Bare Metal Server | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Block Storage | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Citrix NetScaler VPX | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Cloud HSM | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Content Delivery Network | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Direct Link Connect on Classic | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Direct Link Dedicated Hosting on Classic |  | 
| Direct Link Dedicated on Classic | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Direct Link Exchange on Classic |  | 
| File Storage | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| FortiGate Security Appliance 10Gbps |  | 
| FortiGate Security Appliance 1Gbps | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Gateway Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Hardware Firewall | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Hardware Firewall (Dedicated) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| IBM Cloud Backup | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| IBM Cloud Load Balancer | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| IPSec VPN | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Juniper vSRX | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| SSL Certificates | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Subnets/IPs | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Virtual Router Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) | 
{: row-headers}
{: caption="Table 16. Asia Pacific infrastructure availability - India" caption-side="top"}
{: #iaas-table13}
{: tab-title="India"}
{: tab-group="Asia Pacific"}
{: class="comparison-tab-table"}
{: summary="Use the buttons for the countries to change the context of the table. This table has row and column headers. The row headers identify the service. The column headers indentify where that service is located. To understand where a service is located in the table, navigate to the row, and find the for the location you are interested in."}


| Service | Tokyo (MZR) | Tokyo 01 | Tokyo 02 | Tokyo 04 | Tokyo 05 | 
|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|
| Bare Metal Server | ![Checkmark icon](../icons/checkmark-icon.svg) |  | ![Checkmark icon](../icons/checkmark-icon.svg) |  | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Block Storage | ![Checkmark icon](../icons/checkmark-icon.svg) |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Citrix NetScaler VPX | ![Checkmark icon](../icons/checkmark-icon.svg) |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Cloud HSM | ![Checkmark icon](../icons/checkmark-icon.svg) |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| Content Delivery Network | ![Checkmark icon](../icons/checkmark-icon.svg) |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Direct Link Connect on Classic | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) |  | 
| Direct Link Dedicated Hosting on Classic |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  | 
| Direct Link Dedicated on Classic | ![Checkmark icon](../icons/checkmark-icon.svg) |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Direct Link Exchange on Classic | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  |  |  | 
| File Storage | ![Checkmark icon](../icons/checkmark-icon.svg) |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| FortiGate Security Appliance 10Gbps |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  | 
| FortiGate Security Appliance 1Gbps | ![Checkmark icon](../icons/checkmark-icon.svg) |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Gateway Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Hardware Firewall | ![Checkmark icon](../icons/checkmark-icon.svg) |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Hardware Firewall (Dedicated) | ![Checkmark icon](../icons/checkmark-icon.svg) |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| IBM Cloud Backup |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| IBM Cloud Load Balancer | ![Checkmark icon](../icons/checkmark-icon.svg) |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| IPSec VPN | ![Checkmark icon](../icons/checkmark-icon.svg) |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Juniper vSRX | ![Checkmark icon](../icons/checkmark-icon.svg) |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| SSL Certificates | ![Checkmark icon](../icons/checkmark-icon.svg) |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Subnets/IPs | ![Checkmark icon](../icons/checkmark-icon.svg) |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Virtual Router Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
{: row-headers}
{: caption="Table 17. Asia Pacific infrastructure availability - Japan" caption-side="top"}
{: #iaas-table14}
{: tab-title="Japan"}
{: tab-group="Asia Pacific"}
{: class="comparison-tab-table"}
{: summary="Use the buttons for the countries to change the context of the table. This table has row and column headers. The row headers identify the service. The column headers indentify where that service is located. To understand where a service is located in the table, navigate to the row, and find the for the location you are interested in."}


| Service | Seoul 01 | 
|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|
| Bare Metal Server |  | 
| Block Storage | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Citrix NetScaler VPX | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Cloud HSM |  | 
| Content Delivery Network | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Direct Link Connect on Classic |  | 
| Direct Link Dedicated Hosting on Classic | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Direct Link Dedicated on Classic | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Direct Link Exchange on Classic |  | 
| File Storage | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| FortiGate Security Appliance 10Gbps | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| FortiGate Security Appliance 1Gbps | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Gateway Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Hardware Firewall | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Hardware Firewall (Dedicated) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| IBM Cloud Backup | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| IBM Cloud Load Balancer | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| IPSec VPN | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Juniper vSRX | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| SSL Certificates | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Subnets/IPs | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Virtual Router Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) | 
{: row-headers}
{: caption="Table 18. Asia Pacific infrastructure availability - Korea" caption-side="top"}
{: #iaas-table15}
{: tab-title="Korea"}
{: tab-group="Asia Pacific"}
{: class="comparison-tab-table"}
{: summary="Use the buttons for the countries to change the context of the table. This table has row and column headers. The row headers identify the service. The column headers indentify where that service is located. To understand where a service is located in the table, navigate to the row, and find the for the location you are interested in."}


| Service | Singapore 01 | 
|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|
| Bare Metal Server |  | 
| Block Storage | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Citrix NetScaler VPX | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Cloud HSM |  | 
| Content Delivery Network | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Direct Link Connect on Classic |  | 
| Direct Link Dedicated Hosting on Classic | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Direct Link Dedicated on Classic | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Direct Link Exchange on Classic |  | 
| File Storage | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| FortiGate Security Appliance 10Gbps | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| FortiGate Security Appliance 1Gbps | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Gateway Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Hardware Firewall | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Hardware Firewall (Dedicated) | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| IBM Cloud Backup | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| IBM Cloud Load Balancer | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| IPSec VPN | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Juniper vSRX | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| SSL Certificates | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Subnets/IPs | ![Checkmark icon](../icons/checkmark-icon.svg) | 
| Virtual Router Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) | 
{: row-headers}
{: caption="Table 19. Asia Pacific infrastructure availability - Singapore" caption-side="top"}
{: #iaas-table16}
{: tab-title="Singapore"}
{: tab-group="Asia Pacific"}
{: class="comparison-tab-table"}
{: summary="Use the buttons for the countries to change the context of the table. This table has row and column headers. The row headers identify the service. The column headers indentify where that service is located. To understand where a service is located in the table, navigate to the row, and find the for the location you are interested in."}



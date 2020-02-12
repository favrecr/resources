---



copyright:

  years: 2019, 2020
lastupdated: "2020-02-12"

keywords: resource, account resources, create resource, delete resource, restore resource 

subcollection: resources

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:tip: .tip}
{:new_window: target="_blank"}
{:note: .note}
{:term: .term}

# Managing resources 
{: #manage_resource}

A [resource](x2004267){: term} is anything that you can create from the catalog that is managed by and contained within a resource group. You can create and manage resources by going to your [resource list](https://cloud.ibm.com/resources) in the {{site.data.keyword.cloud}} console or by using the command-line interface (CLI).

## Creating a resource 
{: #create-resource}

For users in your account to be able to create resources from the catalog and assign them to a resource group, they must be assigned two access policies:

* A policy with viewer role or higher on the resources group itself
* A policy with editor role or higher on the service in the account

### Creating resources in the console
{: #create-resource-console}

Use the following steps to create a resource in the console: 
1. From your dashboard, click **View resources** within the Resources summary widget.
2. Click **Create resource**. From here, you are directed to the catalog. You can search the offerings or filter based on a specific category, provider, pricing plan, type of compliance, or release type. Examples of resources include apps, service instances, container clusters, storage volumes, virtual servers, and software. 

After you create the resource, it is displayed in your list of resources on the My resources page.

### Creating resources by using the CLI
{: #create-resource-cli}

To create a resource by using the CLI, run the following command:

```
ibmcloud resource service-instance-create NAME (SERVICE_NAME | SERVICE_ID) SERVICE_PLAN_NAME LOCATION [-d, --deployment DEPLOYMENT_NAME] [-p, --parameters @JSON_FILE | JSON_STRING ] [-g RESOURCE_GROUP] [--service-endpoints SERVICE_ENDPOINTS_TYPE]
```
{: codeblock}

Enter the following command options:
  * **Name (required)**: The name of the service instance. 
  * **SERVICE_NAME or SERVICE_ID (required)**: The name or ID of the service. To list service offerings, use the [`ibmcloud catalog service-marketplace` command](/docs/cli/reference/ibmcloud?topic=cloud-cli-ibmcloud_catalog#ibmcloud_catalog_service_marketplace).
  * **SERVICE_PLAN_NAME or SERVICE_PLAN_ID (required)**: The name or ID of the service plan.
  * **LOCATION (required)**: The target location or environment to create the service instance.
  * **-d, --deployment DEPLOYMENT_NAME**: The name of the deployment. 
  * **-p, --parameters @JSONFILE or JSON_STRING**: The JSON file or JSON string of parameters to create service instance.
  * **-g RESOURCE_GROUP**: The resource group name. 
  * **--service-endpoints SERVICE_ENDPOINTS_TYPE**: The types of the service endpoints. The possible values are `public`, `private`, `public-and-private`.

The following example shows how to create a resource named `my-service-instance` that uses service plan `test-service-plan` of service `test-service` in the `eu-gb` location:

```
ibmcloud resource service-instance-create my-service-instance test-service test-service-plan eu-gb
```

## Deleting a resource 
{: #delete-resource}

### Deleting resources in the console
{: #delete-resource-console}

You can delete a resource in the console by using the following steps:

1. From your dashboard, click **View resources** in the Resources summary widget.
2. Expand the sections to locate the service instance that you want to delete.
3. Select the **Actions** ![List of actions icon](../icons/action-menu-icon.svg) menu for the row, and click **Delete**.

### Deleting resources by using the CLI
{: #delete-resource-cli}

To delete a resource by using the CLI, run the following command:

```
ibmcloud resource service-instance-delete (NAME|ID) [-f, --force] [--recursive]
```
{: codeblock}

Enter the following command options:
  * **Name**: The name of the service instance, exclusive with ID. (Required)
  * **ID**: The ID of the service instance, exclusive with NAME. (Required)
  * **-f, --force**: Force deletion without confirmation. 
  * **--recursive**: Delete all belonging resources. 

The following example shows how to delete a resource service-instance that's named `my-service-instance`:

```
ibmcloud resource service-instance-delete my-service-instance
```

## Restoring a resource
{: #restore-resource}

You can restore a resource within 7 days after you delete it. 

Not all resources can be restored. You can run the **`ibmcloud resource reclamations`** command to check the resources that you can restore.
{: important}

To restore a resource by using the CLI, run the following command:

```
ibmcloud resource reclamation-restore --id RECLAMATION_ID [--comment COMMENT] [--output FORMAT]
```
{: codeblock}

Enter the following command options:
  * **ID**: The ID of the resource reclamation. (Required)
  * **--comment**: Comments about the action.  
  * **--output**: Specify the output format. Only `JSON` is supported. 

The following example shows how to restore a resource with the `d9fendfwlw` ID:

```
ibmcloud resource reclamation-restore --id "d9fendfwlw"
```

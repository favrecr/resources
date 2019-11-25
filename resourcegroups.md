---



copyright:

  years: 2017, 2019
lastupdated: "2019-11-25"

keywords: resource group, account resources, users access to resource groups, create resource group

subcollection: resources

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:tip: .tip}
{:new_window: target="_blank"}
{:note: .note}

# Creating and managing resource groups
{: #rgs}

A resource group is a way for you to organize your account resources in customizable groupings so that you can quickly assign users access to more than one resource at a time. Any account resource that is managed by using {{site.data.keyword.Bluemix}} Identity and Access Management (IAM) access control belongs to a resource group within your account. The only exception is Kubernetes, which doesn't prompt you for a resource group assignment, but access to the service is controlled by using IAM roles. Cloud Foundry services are assigned to orgs and spaces and can't be added to a resource group.

To start managing your resource groups, go to **Manage** > **Account** > **Account resources** > **Resource groups**. You can create, view, and rename your resource groups, add resources and manage access to your resource groups, and you can delete any resource group that isn't the default one. For more information about working with resource groups, see [Best practices for organizing resources in resource groups](/docs/resources?topic=resources-bp_resourcegroups).


## Creating a resource group
{: #create_rgs}

If you have a Pay-As-You-Go or Subscription account, you can create multiple resource groups to easily manage quota and view billing usage for a set of resources. You can also group resources to make it easier for you to assign users access to more than one instance at a time. It's important to note that you can rename a resource group, but you can't delete a resource group after it's created. After a resouce group is created, you can delete it only if it doesn't contain any resources. To manage your resource groups, go to the [Resource groups page](https://cloud.ibm.com/account/resource-groups) in the console.

You must be assigned an IAM policy with the Administrator role on All Account Management services to create additional resource groups. If you have a Lite account or 30-day trial, you can't create extra resource groups, but you can rename your default resource group.

Connections between a resource group and a Cloud Foundry org or space are restricted by your quota. See [What is an alias?](/docs/resources?topic=resources-connect_app#what_is_alias) for more information.
{: note}

1. Go to **Manage** &gt; **Account**. Expand **Account resources** and then select **Resource groups**.
2. Click **Create a resource group**.
3. Enter a name for your resource group.
4. Click **Add**.

## Adding resources to a resource group
{: #add_to_rgs}

Services that are managed with IAM belong to a resource group instead of Cloud Foundry org or space. When you create a service instance for one of these services from the catalog, you're prompted to assign the instance to a resource group. Your resource group selection at the time of creating the instance is final and can't be changed.

For users in your account to be able to create resources from the catalog and assign them to a resource group, they must be assigned two access policies:

* A policy with viewer role or higher on the resources group itself
* A policy with editor role or higher on the service in the account

## Viewing resources within resource groups
{: #view_rg_resources}

To easily view the resources that are contained within a resource group, filter by resource group from your resource list.

## Renaming a resource group
{: #rename_rgs}

Your first resource group is created and named `Default` for you. You can choose to update the name of this group or any other groups that you create.

1. Go to **Manage** &gt; **Account**. Expand **Account resources** and then select **Resource groups**.
2. Select **Rename** from the **Actions** ![List of actions icon](../icons/action-menu-icon.svg) menu.
3. Enter a unique name and click **Save**.

## Managing resource groups and resources by using the {{site.data.keyword.Bluemix_notm}} CLI
{: #rgs_cli}

The {{site.data.keyword.Bluemix_notm}} CLI has multiple commands that support resource management. For more information, see [Working with resources and resource groups](/docs/cli/reference/ibmcloud?topic=cloud-cli-ibmcloud_commands_resource#ibmcloud_commands_resource).

## Giving users access to resources in your resource groups
{: #rgs_manage_access}

With {{site.data.keyword.Bluemix_notm}} IAM, you have the flexibility to provide fine-grained user access to the resources and resource groups in your account. See [Managing access to resources](/docs/iam?topic=iam-iammanidaccser) for more information. 

## Deleting a resource group 
{: #delete_rgs}

Besides the default resource group, you can delete any resource group if you're no longer using it. You can't delete the default resource group that's added to your account.

You can't delete a resource group if there are resources assigned to it. Go to your resource list to delete the assigned resources before you try to delete the resource group.
{: note}  

1. Go to **Manage** > **Account** > **Account resources** > **Resource groups**.
2. Click the **Actions** ![List of actions icon](../icons/action-menu-icon.svg) menu, and select **Delete**.

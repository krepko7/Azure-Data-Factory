<img style="float: right;" src="../../graphics/solutions-microsoft-logo-small.png">

## Azure Data Factory (ADF) 
# Lab 2 - Set up Data Lake Storage an ADF connection to it

Create a Storage Account for your Data Lake.  Go to portal.azure.com and click the Create Resource menu item from top left menu.

<img style="float: right;" src="../../graphics/createresource.png">

Then pick the Storage category and then click on Storage Account.  Fill in fields for the first screen similar to below.
Leave other screens as default for lab purposes.

<img style="float: right;" src="../../graphics/datalakecreate1.png">

Now go to your newly created storage account and click the Containers option.

<img style="float: right;" src="../../graphics/containers.png">

From here click the +Container icon at the top and give a lower case name, leave the public access level to "Private" and click OK.

Go to the Storage Account "blade" in Azure portal and clicke the Access keys menu item under the Settings section.
Just be familiar with this section in case you need the access keys later.

<img style="float: right;" src="../../graphics/storageaccesskeys.png">

Now go back to Data Factory, click the Author item and then click the bottom left Connections menu.
Create a new Linked Service for your data lake.

<img style="float: right;" src="../../graphics/datalakelinkedservice1.png">

<img style="float: right;" src="../../graphics/datalakelinkedservice2.png">



<img style="float: right;" src="../../graphics/.png">
<img style="float: right;" src="../../graphics/.png">


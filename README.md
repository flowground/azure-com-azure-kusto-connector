# ![LOGO](logo.png) KustoManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the KustoManagementClient API (version 2019-01-21).

Generated from: https://api.apis.guru/v2/specs/azure.com/azure-kusto/2019-01-21/swagger.json<br/>
Generated at: 2019-05-07T17:37:37+03:00

## API Description



## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists available operations for the Microsoft.Kusto provider.

*Tags:* `Operations`

#### Input Parameters
* `api-version` - _required_ - Client API Version.

### Lists all Kusto clusters within a subscription.

*Tags:* `Clusters`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API Version.

### Checks that the cluster name is valid and is not already in use.

*Tags:* `Clusters`

#### Input Parameters
* `api-version` - _required_ - Client API Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `location` - _required_ - Azure location.

### Lists eligible SKUs for Kusto resource provider.

#### Input Parameters
* `api-version` - _required_ - Client API Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Lists all Kusto clusters within a resource group.

*Tags:* `Clusters`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group containing the Kusto cluster.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API Version.

### Deletes a Kusto cluster.

*Tags:* `Clusters`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group containing the Kusto cluster.
* `clusterName` - _required_ - The name of the Kusto cluster.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API Version.

### Gets a Kusto cluster.

*Tags:* `Clusters`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group containing the Kusto cluster.
* `clusterName` - _required_ - The name of the Kusto cluster.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API Version.

### Update a Kusto cluster.

*Tags:* `Clusters`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group containing the Kusto cluster.
* `clusterName` - _required_ - The name of the Kusto cluster.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API Version.

### Create or update a Kusto cluster.

*Tags:* `Clusters`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group containing the Kusto cluster.
* `clusterName` - _required_ - The name of the Kusto cluster.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API Version.

### Checks that the database name is valid and is not already in use.

*Tags:* `Databases`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group containing the Kusto cluster.
* `clusterName` - _required_ - The name of the Kusto cluster.
* `api-version` - _required_ - Client API Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Returns the list of databases of the given Kusto cluster.

*Tags:* `Databases`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group containing the Kusto cluster.
* `clusterName` - _required_ - The name of the Kusto cluster.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API Version.

### Deletes the database with the given name.

*Tags:* `Databases`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group containing the Kusto cluster.
* `clusterName` - _required_ - The name of the Kusto cluster.
* `databaseName` - _required_ - The name of the database in the Kusto cluster.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API Version.

### Returns a database.

*Tags:* `Databases`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group containing the Kusto cluster.
* `clusterName` - _required_ - The name of the Kusto cluster.
* `databaseName` - _required_ - The name of the database in the Kusto cluster.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API Version.

### Updates a database.

*Tags:* `Databases`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group containing the Kusto cluster.
* `clusterName` - _required_ - The name of the Kusto cluster.
* `databaseName` - _required_ - The name of the database in the Kusto cluster.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API Version.

### Creates or updates a database.

*Tags:* `Databases`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group containing the Kusto cluster.
* `clusterName` - _required_ - The name of the Kusto cluster.
* `databaseName` - _required_ - The name of the database in the Kusto cluster.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API Version.

### Add Database principals permissions.

*Tags:* `Databases`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group containing the Kusto cluster.
* `clusterName` - _required_ - The name of the Kusto cluster.
* `databaseName` - _required_ - The name of the database in the Kusto cluster.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API Version.

### Checks that the data connection parameters are valid.

*Tags:* `DataConnections`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group containing the Kusto cluster.
* `clusterName` - _required_ - The name of the Kusto cluster.
* `databaseName` - _required_ - The name of the database in the Kusto cluster.
* `api-version` - _required_ - Client API Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Returns the list of data connections of the given Kusto database.

*Tags:* `DataConnections`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group containing the Kusto cluster.
* `clusterName` - _required_ - The name of the Kusto cluster.
* `databaseName` - _required_ - The name of the database in the Kusto cluster.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API Version.

### Deletes the data connection with the given name.

*Tags:* `DataConnections`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group containing the Kusto cluster.
* `clusterName` - _required_ - The name of the Kusto cluster.
* `databaseName` - _required_ - The name of the database in the Kusto cluster.
* `dataConnectionName` - _required_ - The name of the data connection.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API Version.

### Returns a data connection.

*Tags:* `DataConnections`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group containing the Kusto cluster.
* `clusterName` - _required_ - The name of the Kusto cluster.
* `databaseName` - _required_ - The name of the database in the Kusto cluster.
* `dataConnectionName` - _required_ - The name of the data connection.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API Version.

### Updates a data connection.

*Tags:* `DataConnections`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group containing the Kusto cluster.
* `clusterName` - _required_ - The name of the Kusto cluster.
* `databaseName` - _required_ - The name of the database in the Kusto cluster.
* `dataConnectionName` - _required_ - The name of the data connection.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API Version.

### Creates or updates a data connection.

*Tags:* `DataConnections`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group containing the Kusto cluster.
* `clusterName` - _required_ - The name of the Kusto cluster.
* `databaseName` - _required_ - The name of the database in the Kusto cluster.
* `dataConnectionName` - _required_ - The name of the data connection.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API Version.

### Returns a list of database principals of the given Kusto cluster and database.

*Tags:* `Databases`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group containing the Kusto cluster.
* `clusterName` - _required_ - The name of the Kusto cluster.
* `databaseName` - _required_ - The name of the database in the Kusto cluster.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API Version.

### Remove Database principals permissions.

*Tags:* `Databases`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group containing the Kusto cluster.
* `clusterName` - _required_ - The name of the Kusto cluster.
* `databaseName` - _required_ - The name of the database in the Kusto cluster.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API Version.

### Returns the SKUs available for the provided resource.

*Tags:* `Clusters`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group containing the Kusto cluster.
* `clusterName` - _required_ - The name of the Kusto cluster.
* `api-version` - _required_ - Client API Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Starts a Kusto cluster.

*Tags:* `Clusters`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group containing the Kusto cluster.
* `clusterName` - _required_ - The name of the Kusto cluster.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API Version.

### Stops a Kusto cluster.

*Tags:* `Clusters`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group containing the Kusto cluster.
* `clusterName` - _required_ - The name of the Kusto cluster.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API Version.

## License

**flow**ground :- Telekom iPaaS / azure-com-azure-kusto-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.

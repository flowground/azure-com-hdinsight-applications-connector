# ![LOGO](logo.png) HDInsightManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the HDInsightManagementClient API (version 2018-06-01-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/hdinsight-applications/2018-06-01-preview/swagger.json<br/>
Generated at: 2019-05-07T17:38:12+03:00

## API Description

The HDInsight Management Client.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists all of the applications for the HDInsight cluster.

*Tags:* `Applications`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `clusterName` - _required_ - The name of the cluster.
* `api-version` - _required_ - The HDInsight client API Version.

### Deletes the specified application on the HDInsight cluster.

*Tags:* `Applications`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `clusterName` - _required_ - The name of the cluster.
* `applicationName` - _required_ - The constant value for the application name.
* `api-version` - _required_ - The HDInsight client API Version.

### Gets properties of the specified application.

*Tags:* `Applications`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `clusterName` - _required_ - The name of the cluster.
* `applicationName` - _required_ - The constant value for the application name.
* `api-version` - _required_ - The HDInsight client API Version.

### Creates applications for the HDInsight cluster.

*Tags:* `Applications`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `clusterName` - _required_ - The name of the cluster.
* `applicationName` - _required_ - The constant value for the application name.
* `api-version` - _required_ - The HDInsight client API Version.

## License

**flow**ground :- Telekom iPaaS / azure-com-hdinsight-applications-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.

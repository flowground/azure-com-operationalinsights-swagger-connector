# ![LOGO](logo.png) Azure Log Analytics **flow**ground Connector

## Description

A generated **flow**ground connector for the Azure Log Analytics API (version 2017-10-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/operationalinsights-swagger/2017-10-01/swagger.json<br/>
Generated at: 2019-06-11T18:14:09+03:00

## API Description

This API exposes Azure Log Analytics query capabilities

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Execute an Analytics query

> Executes an Analytics query for data

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group to get. The name is case insensitive.
* `workspaceName` - _required_ - Name of the Log Analytics workspace.
* `query` - _required_ - The Analytics query. Learn more about the [Analytics query syntax](https://azure.microsoft.com/documentation/articles/app-insights-analytics-reference/)
* `timespan` - _optional_ - Optional. The timespan over which to query data. This is an ISO8601 time period value.  This timespan is applied in addition to any that are specified in the query expression.
* `apiVersion` - _required_ - Client API version.

### Execute an Analytics query

> Executes an Analytics query for data. [Here](https://dev.loganalytics.io/documentation/Using-the-API) is an example for using POST with an Analytics query.

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group to get. The name is case insensitive.
* `workspaceName` - _required_ - Name of the Log Analytics workspace.
* `apiVersion` - _required_ - Client API version.

## License

**flow**ground :- Telekom iPaaS / azure-com-operationalinsights-swagger-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.

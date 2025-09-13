# DomainUpdateResponseBody

Successful response

## Example Usage

```typescript
import { DomainUpdateResponseBody } from "dokploy-sdk/models/operations";

let value: DomainUpdateResponseBody = {
  applicationId: "<id>",
  certificateType: "custom",
  composeId: "<id>",
  createdAt: "1722732567473",
  customCertResolver: "<value>",
  domainId: "<id>",
  domainType: "application",
  host: "brave-comparison.org",
  https: false,
  internalPath: "<value>",
  path: "/var/spool",
  port: 183.63,
  previewDeploymentId: "<id>",
  serviceName: "<value>",
  stripPath: false,
  uniqueConfigKey: 2847.72,
};
```

## Fields

| Field                                                                                                            | Type                                                                                                             | Required                                                                                                         | Description                                                                                                      |
| ---------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- |
| `applicationId`                                                                                                  | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `certificateType`                                                                                                | [operations.DomainUpdateCertificateTypeResponse](../../models/operations/domainupdatecertificatetyperesponse.md) | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `composeId`                                                                                                      | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `createdAt`                                                                                                      | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `customCertResolver`                                                                                             | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `domainId`                                                                                                       | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `domainType`                                                                                                     | [operations.DomainUpdateDomainTypeResponse](../../models/operations/domainupdatedomaintyperesponse.md)           | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `host`                                                                                                           | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `https`                                                                                                          | *boolean*                                                                                                        | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `internalPath`                                                                                                   | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `path`                                                                                                           | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `port`                                                                                                           | *number*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `previewDeploymentId`                                                                                            | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `serviceName`                                                                                                    | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `stripPath`                                                                                                      | *boolean*                                                                                                        | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `uniqueConfigKey`                                                                                                | *number*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
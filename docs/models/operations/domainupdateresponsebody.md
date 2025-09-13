# DomainUpdateResponseBody

Successful response

## Example Usage

```typescript
import { DomainUpdateResponseBody } from "dokploy-sdk/models/operations";

let value: DomainUpdateResponseBody = {
  domainId: "<id>",
  host: "haunting-wasabi.info",
  https: false,
  port: 6580.24,
  path: "/etc",
  serviceName: "<value>",
  domainType: "application",
  uniqueConfigKey: 7877.47,
  createdAt: "1735216356957",
  composeId: "<id>",
  customCertResolver: "<value>",
  applicationId: null,
  previewDeploymentId: "<id>",
  certificateType: "custom",
  internalPath: "<value>",
  stripPath: true,
};
```

## Fields

| Field                                                                                                            | Type                                                                                                             | Required                                                                                                         | Description                                                                                                      |
| ---------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- |
| `domainId`                                                                                                       | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `host`                                                                                                           | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `https`                                                                                                          | *boolean*                                                                                                        | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `port`                                                                                                           | *number*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `path`                                                                                                           | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `serviceName`                                                                                                    | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `domainType`                                                                                                     | [operations.DomainUpdateDomainTypeResponse](../../models/operations/domainupdatedomaintyperesponse.md)           | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `uniqueConfigKey`                                                                                                | *number*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `createdAt`                                                                                                      | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `composeId`                                                                                                      | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `customCertResolver`                                                                                             | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `applicationId`                                                                                                  | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `previewDeploymentId`                                                                                            | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `certificateType`                                                                                                | [operations.DomainUpdateCertificateTypeResponse](../../models/operations/domainupdatecertificatetyperesponse.md) | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `internalPath`                                                                                                   | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `stripPath`                                                                                                      | *boolean*                                                                                                        | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
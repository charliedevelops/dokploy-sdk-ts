# DomainCreateResponseBody

Successful response

## Example Usage

```typescript
import { DomainCreateResponseBody } from "dokploy-sdk/models/operations";

let value: DomainCreateResponseBody = {
  domainId: "<id>",
  host: "emotional-brief.name",
  https: false,
  port: null,
  path: "/Library",
  serviceName: "<value>",
  domainType: "application",
  uniqueConfigKey: 1062.2,
  createdAt: "1714143304215",
  composeId: "<id>",
  customCertResolver: null,
  applicationId: "<id>",
  previewDeploymentId: "<id>",
  certificateType: "letsencrypt",
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
| `domainType`                                                                                                     | [operations.DomainCreateDomainTypeResponse](../../models/operations/domaincreatedomaintyperesponse.md)           | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `uniqueConfigKey`                                                                                                | *number*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `createdAt`                                                                                                      | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `composeId`                                                                                                      | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `customCertResolver`                                                                                             | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `applicationId`                                                                                                  | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `previewDeploymentId`                                                                                            | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `certificateType`                                                                                                | [operations.DomainCreateCertificateTypeResponse](../../models/operations/domaincreatecertificatetyperesponse.md) | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `internalPath`                                                                                                   | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `stripPath`                                                                                                      | *boolean*                                                                                                        | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
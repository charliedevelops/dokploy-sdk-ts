# DomainDeleteResponseBody

Successful response

## Example Usage

```typescript
import { DomainDeleteResponseBody } from "dokploy-sdk/models/operations";

let value: DomainDeleteResponseBody = {
  domainId: "<id>",
  host: "essential-experience.com",
  https: false,
  port: 4892.97,
  path: "/home/user",
  serviceName: "<value>",
  domainType: "compose",
  uniqueConfigKey: 5374.37,
  createdAt: "1706608142287",
  composeId: "<id>",
  customCertResolver: "<value>",
  applicationId: "<id>",
  previewDeploymentId: "<id>",
  certificateType: "letsencrypt",
  internalPath: "<value>",
  stripPath: false,
};
```

## Fields

| Field                                                                                            | Type                                                                                             | Required                                                                                         | Description                                                                                      |
| ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ |
| `domainId`                                                                                       | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `host`                                                                                           | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `https`                                                                                          | *boolean*                                                                                        | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `port`                                                                                           | *number*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `path`                                                                                           | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `serviceName`                                                                                    | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `domainType`                                                                                     | [operations.DomainDeleteDomainType](../../models/operations/domaindeletedomaintype.md)           | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `uniqueConfigKey`                                                                                | *number*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `createdAt`                                                                                      | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `composeId`                                                                                      | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `customCertResolver`                                                                             | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `applicationId`                                                                                  | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `previewDeploymentId`                                                                            | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `certificateType`                                                                                | [operations.DomainDeleteCertificateType](../../models/operations/domaindeletecertificatetype.md) | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `internalPath`                                                                                   | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `stripPath`                                                                                      | *boolean*                                                                                        | :heavy_check_mark:                                                                               | N/A                                                                                              |
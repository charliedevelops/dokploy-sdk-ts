# DomainByApplicationIdResponseBody

## Example Usage

```typescript
import { DomainByApplicationIdResponseBody } from "dokploy-sdk/models/operations";

let value: DomainByApplicationIdResponseBody = {
  applicationId: "<id>",
  certificateType: "none",
  composeId: "<id>",
  createdAt: "1719940704736",
  customCertResolver: "<value>",
  domainId: "<id>",
  domainType: "preview",
  host: "hidden-tomography.net",
  https: false,
  internalPath: "<value>",
  path: "/proc",
  port: 643.76,
  previewDeploymentId: "<id>",
  serviceName: "<value>",
  stripPath: true,
  uniqueConfigKey: 4759.51,
};
```

## Fields

| Field                                                                                                              | Type                                                                                                               | Required                                                                                                           | Description                                                                                                        |
| ------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------ |
| `applicationId`                                                                                                    | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `certificateType`                                                                                                  | [operations.DomainByApplicationIdCertificateType](../../models/operations/domainbyapplicationidcertificatetype.md) | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `composeId`                                                                                                        | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `createdAt`                                                                                                        | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `customCertResolver`                                                                                               | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `domainId`                                                                                                         | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `domainType`                                                                                                       | [operations.DomainByApplicationIdDomainType](../../models/operations/domainbyapplicationiddomaintype.md)           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `host`                                                                                                             | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `https`                                                                                                            | *boolean*                                                                                                          | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `internalPath`                                                                                                     | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `path`                                                                                                             | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `port`                                                                                                             | *number*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `previewDeploymentId`                                                                                              | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `serviceName`                                                                                                      | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `stripPath`                                                                                                        | *boolean*                                                                                                          | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `uniqueConfigKey`                                                                                                  | *number*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
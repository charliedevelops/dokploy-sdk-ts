# DomainByApplicationIdResponseBody

## Example Usage

```typescript
import { DomainByApplicationIdResponseBody } from "dokploy-sdk/models/operations";

let value: DomainByApplicationIdResponseBody = {
  domainId: "<id>",
  host: "creative-hutch.org",
  https: false,
  port: 6103.42,
  path: "/opt/bin",
  serviceName: "<value>",
  domainType: "preview",
  uniqueConfigKey: 3816.83,
  createdAt: "1725251823263",
  composeId: "<id>",
  customCertResolver: "<value>",
  applicationId: null,
  previewDeploymentId: "<id>",
  certificateType: "none",
  internalPath: "<value>",
  stripPath: true,
};
```

## Fields

| Field                                                                                                              | Type                                                                                                               | Required                                                                                                           | Description                                                                                                        |
| ------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------ |
| `domainId`                                                                                                         | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `host`                                                                                                             | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `https`                                                                                                            | *boolean*                                                                                                          | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `port`                                                                                                             | *number*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `path`                                                                                                             | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `serviceName`                                                                                                      | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `domainType`                                                                                                       | [operations.DomainByApplicationIdDomainType](../../models/operations/domainbyapplicationiddomaintype.md)           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `uniqueConfigKey`                                                                                                  | *number*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `createdAt`                                                                                                        | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `composeId`                                                                                                        | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `customCertResolver`                                                                                               | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `applicationId`                                                                                                    | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `previewDeploymentId`                                                                                              | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `certificateType`                                                                                                  | [operations.DomainByApplicationIdCertificateType](../../models/operations/domainbyapplicationidcertificatetype.md) | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `internalPath`                                                                                                     | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `stripPath`                                                                                                        | *boolean*                                                                                                          | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
# DomainByComposeIdResponseBody

## Example Usage

```typescript
import { DomainByComposeIdResponseBody } from "dokploy-sdk/models/operations";

let value: DomainByComposeIdResponseBody = {
  applicationId: "<id>",
  certificateType: "custom",
  composeId: "<id>",
  createdAt: "1726990166521",
  customCertResolver: "<value>",
  domainId: "<id>",
  domainType: "application",
  host: "wealthy-lender.org",
  https: true,
  internalPath: "<value>",
  path: null,
  port: 7639.35,
  previewDeploymentId: "<id>",
  serviceName: null,
  stripPath: false,
  uniqueConfigKey: 6227.48,
};
```

## Fields

| Field                                                                                                      | Type                                                                                                       | Required                                                                                                   | Description                                                                                                |
| ---------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- |
| `applicationId`                                                                                            | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `certificateType`                                                                                          | [operations.DomainByComposeIdCertificateType](../../models/operations/domainbycomposeidcertificatetype.md) | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `composeId`                                                                                                | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `createdAt`                                                                                                | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `customCertResolver`                                                                                       | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `domainId`                                                                                                 | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `domainType`                                                                                               | [operations.DomainByComposeIdDomainType](../../models/operations/domainbycomposeiddomaintype.md)           | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `host`                                                                                                     | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `https`                                                                                                    | *boolean*                                                                                                  | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `internalPath`                                                                                             | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `path`                                                                                                     | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `port`                                                                                                     | *number*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `previewDeploymentId`                                                                                      | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `serviceName`                                                                                              | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `stripPath`                                                                                                | *boolean*                                                                                                  | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `uniqueConfigKey`                                                                                          | *number*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
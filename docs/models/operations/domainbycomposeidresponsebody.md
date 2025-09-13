# DomainByComposeIdResponseBody

## Example Usage

```typescript
import { DomainByComposeIdResponseBody } from "dokploy-sdk/models/operations";

let value: DomainByComposeIdResponseBody = {
  domainId: "<id>",
  host: "prickly-platter.com",
  https: false,
  port: 9828.99,
  path: "/var/mail",
  serviceName: "<value>",
  domainType: "compose",
  uniqueConfigKey: 4981.69,
  createdAt: "1704352282334",
  composeId: "<id>",
  customCertResolver: "<value>",
  applicationId: "<id>",
  previewDeploymentId: null,
  certificateType: "none",
  internalPath: "<value>",
  stripPath: true,
};
```

## Fields

| Field                                                                                                      | Type                                                                                                       | Required                                                                                                   | Description                                                                                                |
| ---------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- |
| `domainId`                                                                                                 | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `host`                                                                                                     | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `https`                                                                                                    | *boolean*                                                                                                  | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `port`                                                                                                     | *number*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `path`                                                                                                     | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `serviceName`                                                                                              | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `domainType`                                                                                               | [operations.DomainByComposeIdDomainType](../../models/operations/domainbycomposeiddomaintype.md)           | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `uniqueConfigKey`                                                                                          | *number*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `createdAt`                                                                                                | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `composeId`                                                                                                | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `customCertResolver`                                                                                       | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `applicationId`                                                                                            | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `previewDeploymentId`                                                                                      | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `certificateType`                                                                                          | [operations.DomainByComposeIdCertificateType](../../models/operations/domainbycomposeidcertificatetype.md) | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `internalPath`                                                                                             | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `stripPath`                                                                                                | *boolean*                                                                                                  | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
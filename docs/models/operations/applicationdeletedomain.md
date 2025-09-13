# ApplicationDeleteDomain

## Example Usage

```typescript
import { ApplicationDeleteDomain } from "dokploy-sdk/models/operations";

let value: ApplicationDeleteDomain = {
  domainId: "<id>",
  host: "tame-toaster.biz",
  https: false,
  port: 1114.01,
  path: "/private/tmp",
  serviceName: "<value>",
  domainType: "preview",
  uniqueConfigKey: 5453.59,
  createdAt: "1708732086018",
  composeId: null,
  customCertResolver: "<value>",
  applicationId: "<id>",
  previewDeploymentId: "<id>",
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
| `domainType`                                                                                               | [operations.ApplicationDeleteDomainType](../../models/operations/applicationdeletedomaintype.md)           | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `uniqueConfigKey`                                                                                          | *number*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `createdAt`                                                                                                | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `composeId`                                                                                                | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `customCertResolver`                                                                                       | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `applicationId`                                                                                            | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `previewDeploymentId`                                                                                      | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `certificateType`                                                                                          | [operations.ApplicationDeleteCertificateType](../../models/operations/applicationdeletecertificatetype.md) | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `internalPath`                                                                                             | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `stripPath`                                                                                                | *boolean*                                                                                                  | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
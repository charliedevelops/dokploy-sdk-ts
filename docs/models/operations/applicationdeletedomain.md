# ApplicationDeleteDomain

## Example Usage

```typescript
import { ApplicationDeleteDomain } from "dokploy-sdk/models/operations";

let value: ApplicationDeleteDomain = {
  applicationId: "<id>",
  certificateType: "custom",
  composeId: "<id>",
  createdAt: "1728220790922",
  customCertResolver: "<value>",
  domainId: "<id>",
  domainType: "application",
  host: "limited-contractor.net",
  https: false,
  internalPath: "<value>",
  path: "/dev",
  port: 9863.09,
  previewDeploymentId: "<id>",
  serviceName: "<value>",
  stripPath: false,
  uniqueConfigKey: 3673.96,
};
```

## Fields

| Field                                                                                                      | Type                                                                                                       | Required                                                                                                   | Description                                                                                                |
| ---------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- |
| `applicationId`                                                                                            | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `certificateType`                                                                                          | [operations.ApplicationDeleteCertificateType](../../models/operations/applicationdeletecertificatetype.md) | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `composeId`                                                                                                | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `createdAt`                                                                                                | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `customCertResolver`                                                                                       | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `domainId`                                                                                                 | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `domainType`                                                                                               | [operations.ApplicationDeleteDomainType](../../models/operations/applicationdeletedomaintype.md)           | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `host`                                                                                                     | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `https`                                                                                                    | *boolean*                                                                                                  | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `internalPath`                                                                                             | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `path`                                                                                                     | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `port`                                                                                                     | *number*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `previewDeploymentId`                                                                                      | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `serviceName`                                                                                              | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `stripPath`                                                                                                | *boolean*                                                                                                  | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `uniqueConfigKey`                                                                                          | *number*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
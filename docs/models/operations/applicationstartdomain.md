# ApplicationStartDomain

## Example Usage

```typescript
import { ApplicationStartDomain } from "dokploy-sdk/models/operations";

let value: ApplicationStartDomain = {
  domainId: "<id>",
  host: "specific-championship.info",
  https: false,
  port: 4544.94,
  path: "/private/var",
  serviceName: "<value>",
  domainType: "compose",
  uniqueConfigKey: 5363.39,
  createdAt: "1720518982790",
  composeId: "<id>",
  customCertResolver: "<value>",
  applicationId: "<id>",
  previewDeploymentId: "<id>",
  certificateType: "custom",
  internalPath: "<value>",
  stripPath: true,
};
```

## Fields

| Field                                                                                                    | Type                                                                                                     | Required                                                                                                 | Description                                                                                              |
| -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- |
| `domainId`                                                                                               | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `host`                                                                                                   | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `https`                                                                                                  | *boolean*                                                                                                | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `port`                                                                                                   | *number*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `path`                                                                                                   | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `serviceName`                                                                                            | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `domainType`                                                                                             | [operations.ApplicationStartDomainType](../../models/operations/applicationstartdomaintype.md)           | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `uniqueConfigKey`                                                                                        | *number*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `createdAt`                                                                                              | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `composeId`                                                                                              | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `customCertResolver`                                                                                     | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `applicationId`                                                                                          | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `previewDeploymentId`                                                                                    | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `certificateType`                                                                                        | [operations.ApplicationStartCertificateType](../../models/operations/applicationstartcertificatetype.md) | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `internalPath`                                                                                           | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `stripPath`                                                                                              | *boolean*                                                                                                | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
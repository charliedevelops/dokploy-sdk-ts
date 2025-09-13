# ApplicationStartDomain

## Example Usage

```typescript
import { ApplicationStartDomain } from "dokploy-sdk/models/operations";

let value: ApplicationStartDomain = {
  applicationId: "<id>",
  certificateType: "letsencrypt",
  composeId: "<id>",
  createdAt: "1720750910018",
  customCertResolver: "<value>",
  domainId: "<id>",
  domainType: "preview",
  host: "lovable-release.biz",
  https: true,
  internalPath: "<value>",
  path: "/usr/share",
  port: 7670.64,
  previewDeploymentId: "<id>",
  serviceName: "<value>",
  stripPath: false,
  uniqueConfigKey: 1610.79,
};
```

## Fields

| Field                                                                                                    | Type                                                                                                     | Required                                                                                                 | Description                                                                                              |
| -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- |
| `applicationId`                                                                                          | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `certificateType`                                                                                        | [operations.ApplicationStartCertificateType](../../models/operations/applicationstartcertificatetype.md) | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `composeId`                                                                                              | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `createdAt`                                                                                              | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `customCertResolver`                                                                                     | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `domainId`                                                                                               | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `domainType`                                                                                             | [operations.ApplicationStartDomainType](../../models/operations/applicationstartdomaintype.md)           | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `host`                                                                                                   | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `https`                                                                                                  | *boolean*                                                                                                | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `internalPath`                                                                                           | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `path`                                                                                                   | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `port`                                                                                                   | *number*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `previewDeploymentId`                                                                                    | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `serviceName`                                                                                            | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `stripPath`                                                                                              | *boolean*                                                                                                | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `uniqueConfigKey`                                                                                        | *number*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
# ApplicationOneDomain

## Example Usage

```typescript
import { ApplicationOneDomain } from "dokploy-sdk/models/operations";

let value: ApplicationOneDomain = {
  applicationId: null,
  certificateType: "custom",
  composeId: null,
  createdAt: "1733118868094",
  customCertResolver: "<value>",
  domainId: "<id>",
  domainType: "preview",
  host: "neglected-scorpion.name",
  https: true,
  internalPath: "<value>",
  path: "/usr/share",
  port: 598.38,
  previewDeploymentId: "<id>",
  serviceName: "<value>",
  stripPath: false,
  uniqueConfigKey: 2397.1,
};
```

## Fields

| Field                                                                                                | Type                                                                                                 | Required                                                                                             | Description                                                                                          |
| ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- |
| `applicationId`                                                                                      | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `certificateType`                                                                                    | [operations.ApplicationOneCertificateType](../../models/operations/applicationonecertificatetype.md) | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `composeId`                                                                                          | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `createdAt`                                                                                          | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `customCertResolver`                                                                                 | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `domainId`                                                                                           | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `domainType`                                                                                         | [operations.ApplicationOneDomainType](../../models/operations/applicationonedomaintype.md)           | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `host`                                                                                               | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `https`                                                                                              | *boolean*                                                                                            | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `internalPath`                                                                                       | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `path`                                                                                               | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `port`                                                                                               | *number*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `previewDeploymentId`                                                                                | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `serviceName`                                                                                        | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `stripPath`                                                                                          | *boolean*                                                                                            | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `uniqueConfigKey`                                                                                    | *number*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
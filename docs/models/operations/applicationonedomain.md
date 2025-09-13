# ApplicationOneDomain

## Example Usage

```typescript
import { ApplicationOneDomain } from "dokploy-sdk/models/operations";

let value: ApplicationOneDomain = {
  domainId: "<id>",
  host: "burly-remark.com",
  https: false,
  port: 8632.92,
  path: "/root",
  serviceName: "<value>",
  domainType: "compose",
  uniqueConfigKey: 2134.5,
  createdAt: "1732277800395",
  composeId: "<id>",
  customCertResolver: "<value>",
  applicationId: null,
  previewDeploymentId: "<id>",
  certificateType: "letsencrypt",
  internalPath: "<value>",
  stripPath: true,
};
```

## Fields

| Field                                                                                                | Type                                                                                                 | Required                                                                                             | Description                                                                                          |
| ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- |
| `domainId`                                                                                           | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `host`                                                                                               | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `https`                                                                                              | *boolean*                                                                                            | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `port`                                                                                               | *number*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `path`                                                                                               | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `serviceName`                                                                                        | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `domainType`                                                                                         | [operations.ApplicationOneDomainType](../../models/operations/applicationonedomaintype.md)           | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `uniqueConfigKey`                                                                                    | *number*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `createdAt`                                                                                          | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `composeId`                                                                                          | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `customCertResolver`                                                                                 | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `applicationId`                                                                                      | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `previewDeploymentId`                                                                                | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `certificateType`                                                                                    | [operations.ApplicationOneCertificateType](../../models/operations/applicationonecertificatetype.md) | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `internalPath`                                                                                       | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `stripPath`                                                                                          | *boolean*                                                                                            | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
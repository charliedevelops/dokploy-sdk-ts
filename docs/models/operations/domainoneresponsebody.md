# DomainOneResponseBody

Successful response

## Example Usage

```typescript
import { DomainOneResponseBody } from "dokploy-sdk/models/operations";

let value: DomainOneResponseBody = {
  domainId: "<id>",
  host: "serpentine-address.org",
  https: true,
  port: 3868.29,
  path: "/home/user",
  serviceName: "<value>",
  domainType: "preview",
  uniqueConfigKey: 9138.92,
  createdAt: "1727978482213",
  composeId: null,
  customCertResolver: "<value>",
  applicationId: null,
  previewDeploymentId: null,
  certificateType: "letsencrypt",
  internalPath: "<value>",
  stripPath: false,
};
```

## Fields

| Field                                                                                      | Type                                                                                       | Required                                                                                   | Description                                                                                |
| ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ |
| `domainId`                                                                                 | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `host`                                                                                     | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `https`                                                                                    | *boolean*                                                                                  | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `port`                                                                                     | *number*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `path`                                                                                     | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `serviceName`                                                                              | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `domainType`                                                                               | [operations.DomainOneDomainType](../../models/operations/domainonedomaintype.md)           | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `uniqueConfigKey`                                                                          | *number*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `createdAt`                                                                                | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `composeId`                                                                                | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `customCertResolver`                                                                       | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `applicationId`                                                                            | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `previewDeploymentId`                                                                      | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `certificateType`                                                                          | [operations.DomainOneCertificateType](../../models/operations/domainonecertificatetype.md) | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `internalPath`                                                                             | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `stripPath`                                                                                | *boolean*                                                                                  | :heavy_check_mark:                                                                         | N/A                                                                                        |
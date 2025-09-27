# DomainOneResponseBody

Successful response

## Example Usage

```typescript
import { DomainOneResponseBody } from "dokploy-sdk/models/operations";

let value: DomainOneResponseBody = {
  applicationId: "<id>",
  certificateType: "letsencrypt",
  composeId: "<id>",
  createdAt: "1709120676710",
  customCertResolver: "<value>",
  domainId: "<id>",
  domainType: "preview",
  host: "early-tectonics.net",
  https: false,
  internalPath: "<value>",
  path: "/etc",
  port: 876.42,
  previewDeploymentId: null,
  serviceName: "<value>",
  stripPath: true,
  uniqueConfigKey: 8265.46,
};
```

## Fields

| Field                                                                                      | Type                                                                                       | Required                                                                                   | Description                                                                                |
| ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ |
| `applicationId`                                                                            | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `certificateType`                                                                          | [operations.DomainOneCertificateType](../../models/operations/domainonecertificatetype.md) | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `composeId`                                                                                | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `createdAt`                                                                                | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `customCertResolver`                                                                       | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `domainId`                                                                                 | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `domainType`                                                                               | [operations.DomainOneDomainType](../../models/operations/domainonedomaintype.md)           | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `host`                                                                                     | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `https`                                                                                    | *boolean*                                                                                  | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `internalPath`                                                                             | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `path`                                                                                     | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `port`                                                                                     | *number*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `previewDeploymentId`                                                                      | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `serviceName`                                                                              | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `stripPath`                                                                                | *boolean*                                                                                  | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `uniqueConfigKey`                                                                          | *number*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
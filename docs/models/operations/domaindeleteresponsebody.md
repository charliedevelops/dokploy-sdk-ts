# DomainDeleteResponseBody

Successful response

## Example Usage

```typescript
import { DomainDeleteResponseBody } from "dokploy-sdk/models/operations";

let value: DomainDeleteResponseBody = {
  applicationId: "<id>",
  certificateType: "letsencrypt",
  composeId: null,
  createdAt: "1725170296760",
  customCertResolver: "<value>",
  domainId: "<id>",
  domainType: "compose",
  host: "dull-thongs.org",
  https: true,
  internalPath: "<value>",
  path: null,
  port: 8405.83,
  previewDeploymentId: "<id>",
  serviceName: "<value>",
  stripPath: true,
  uniqueConfigKey: 4031.04,
};
```

## Fields

| Field                                                                                            | Type                                                                                             | Required                                                                                         | Description                                                                                      |
| ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ |
| `applicationId`                                                                                  | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `certificateType`                                                                                | [operations.DomainDeleteCertificateType](../../models/operations/domaindeletecertificatetype.md) | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `composeId`                                                                                      | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `createdAt`                                                                                      | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `customCertResolver`                                                                             | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `domainId`                                                                                       | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `domainType`                                                                                     | [operations.DomainDeleteDomainType](../../models/operations/domaindeletedomaintype.md)           | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `host`                                                                                           | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `https`                                                                                          | *boolean*                                                                                        | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `internalPath`                                                                                   | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `path`                                                                                           | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `port`                                                                                           | *number*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `previewDeploymentId`                                                                            | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `serviceName`                                                                                    | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `stripPath`                                                                                      | *boolean*                                                                                        | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `uniqueConfigKey`                                                                                | *number*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
# DomainCreateResponseBody

Successful response

## Example Usage

```typescript
import { DomainCreateResponseBody } from "dokploy-sdk/models/operations";

let value: DomainCreateResponseBody = {
  applicationId: "<id>",
  certificateType: "letsencrypt",
  composeId: "<id>",
  createdAt: "1727961937235",
  customCertResolver: null,
  domainId: "<id>",
  domainType: "compose",
  host: "stylish-rawhide.info",
  https: true,
  internalPath: "<value>",
  path: "/bin",
  port: 7323.82,
  previewDeploymentId: "<id>",
  serviceName: "<value>",
  stripPath: true,
  uniqueConfigKey: 6616.14,
};
```

## Fields

| Field                                                                                                            | Type                                                                                                             | Required                                                                                                         | Description                                                                                                      |
| ---------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- |
| `applicationId`                                                                                                  | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `certificateType`                                                                                                | [operations.DomainCreateCertificateTypeResponse](../../models/operations/domaincreatecertificatetyperesponse.md) | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `composeId`                                                                                                      | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `createdAt`                                                                                                      | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `customCertResolver`                                                                                             | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `domainId`                                                                                                       | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `domainType`                                                                                                     | [operations.DomainCreateDomainTypeResponse](../../models/operations/domaincreatedomaintyperesponse.md)           | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `host`                                                                                                           | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `https`                                                                                                          | *boolean*                                                                                                        | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `internalPath`                                                                                                   | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `path`                                                                                                           | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `port`                                                                                                           | *number*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `previewDeploymentId`                                                                                            | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `serviceName`                                                                                                    | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `stripPath`                                                                                                      | *boolean*                                                                                                        | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `uniqueConfigKey`                                                                                                | *number*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
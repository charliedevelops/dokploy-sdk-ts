# ApplicationStopDomain

## Example Usage

```typescript
import { ApplicationStopDomain } from "dokploy-sdk/models/operations";

let value: ApplicationStopDomain = {
  domainId: "<id>",
  host: "urban-gazebo.biz",
  https: true,
  port: 2680.5,
  path: "/lib",
  serviceName: "<value>",
  domainType: "compose",
  uniqueConfigKey: 622.09,
  createdAt: "1721356893415",
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

| Field                                                                                                  | Type                                                                                                   | Required                                                                                               | Description                                                                                            |
| ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ |
| `domainId`                                                                                             | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `host`                                                                                                 | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `https`                                                                                                | *boolean*                                                                                              | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `port`                                                                                                 | *number*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `path`                                                                                                 | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `serviceName`                                                                                          | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `domainType`                                                                                           | [operations.ApplicationStopDomainType](../../models/operations/applicationstopdomaintype.md)           | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `uniqueConfigKey`                                                                                      | *number*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `createdAt`                                                                                            | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `composeId`                                                                                            | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `customCertResolver`                                                                                   | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `applicationId`                                                                                        | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `previewDeploymentId`                                                                                  | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `certificateType`                                                                                      | [operations.ApplicationStopCertificateType](../../models/operations/applicationstopcertificatetype.md) | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `internalPath`                                                                                         | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `stripPath`                                                                                            | *boolean*                                                                                              | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
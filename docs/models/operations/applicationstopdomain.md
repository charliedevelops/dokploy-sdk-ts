# ApplicationStopDomain

## Example Usage

```typescript
import { ApplicationStopDomain } from "dokploy-sdk/models/operations";

let value: ApplicationStopDomain = {
  applicationId: "<id>",
  certificateType: "none",
  composeId: "<id>",
  createdAt: "1712508142199",
  customCertResolver: "<value>",
  domainId: "<id>",
  domainType: "compose",
  host: "ethical-roundabout.info",
  https: true,
  internalPath: null,
  path: "/root",
  port: 8175.28,
  previewDeploymentId: "<id>",
  serviceName: "<value>",
  stripPath: false,
  uniqueConfigKey: 2304.84,
};
```

## Fields

| Field                                                                                                  | Type                                                                                                   | Required                                                                                               | Description                                                                                            |
| ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ |
| `applicationId`                                                                                        | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `certificateType`                                                                                      | [operations.ApplicationStopCertificateType](../../models/operations/applicationstopcertificatetype.md) | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `composeId`                                                                                            | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `createdAt`                                                                                            | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `customCertResolver`                                                                                   | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `domainId`                                                                                             | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `domainType`                                                                                           | [operations.ApplicationStopDomainType](../../models/operations/applicationstopdomaintype.md)           | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `host`                                                                                                 | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `https`                                                                                                | *boolean*                                                                                              | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `internalPath`                                                                                         | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `path`                                                                                                 | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `port`                                                                                                 | *number*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `previewDeploymentId`                                                                                  | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `serviceName`                                                                                          | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `stripPath`                                                                                            | *boolean*                                                                                              | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `uniqueConfigKey`                                                                                      | *number*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
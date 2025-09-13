# ApplicationStopMount

## Example Usage

```typescript
import { ApplicationStopMount } from "dokploy-sdk/models/operations";

let value: ApplicationStopMount = {
  applicationId: "<id>",
  composeId: "<id>",
  content: "<value>",
  filePath: "/opt/include/hmph.azw",
  hostPath: "<value>",
  mariadbId: "<id>",
  mongoId: "<id>",
  mountId: "<id>",
  mountPath: "<value>",
  mysqlId: null,
  postgresId: "<id>",
  redisId: "<id>",
  serviceType: "mariadb",
  type: "volume",
  volumeName: "<value>",
};
```

## Fields

| Field                                                                                          | Type                                                                                           | Required                                                                                       | Description                                                                                    |
| ---------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- |
| `applicationId`                                                                                | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `composeId`                                                                                    | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `content`                                                                                      | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `filePath`                                                                                     | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `hostPath`                                                                                     | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `mariadbId`                                                                                    | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `mongoId`                                                                                      | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `mountId`                                                                                      | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `mountPath`                                                                                    | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `mysqlId`                                                                                      | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `postgresId`                                                                                   | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `redisId`                                                                                      | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `serviceType`                                                                                  | [operations.ApplicationStopServiceType](../../models/operations/applicationstopservicetype.md) | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `type`                                                                                         | [operations.ApplicationStopType](../../models/operations/applicationstoptype.md)               | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `volumeName`                                                                                   | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
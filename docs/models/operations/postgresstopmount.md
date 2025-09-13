# PostgresStopMount

## Example Usage

```typescript
import { PostgresStopMount } from "dokploy-sdk/models/operations";

let value: PostgresStopMount = {
  mountId: "<id>",
  type: "file",
  hostPath: "<value>",
  volumeName: "<value>",
  filePath: "/bin/ha_beret_unlike.rng",
  content: "<value>",
  serviceType: "postgres",
  mountPath: "<value>",
  applicationId: "<id>",
  postgresId: "<id>",
  mariadbId: "<id>",
  mongoId: "<id>",
  mysqlId: "<id>",
  redisId: "<id>",
  composeId: "<id>",
};
```

## Fields

| Field                                                                                    | Type                                                                                     | Required                                                                                 | Description                                                                              |
| ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- |
| `mountId`                                                                                | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `type`                                                                                   | [operations.PostgresStopType](../../models/operations/postgresstoptype.md)               | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `hostPath`                                                                               | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `volumeName`                                                                             | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `filePath`                                                                               | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `content`                                                                                | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `serviceType`                                                                            | [operations.PostgresStopServiceType](../../models/operations/postgresstopservicetype.md) | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `mountPath`                                                                              | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `applicationId`                                                                          | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `postgresId`                                                                             | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `mariadbId`                                                                              | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `mongoId`                                                                                | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `mysqlId`                                                                                | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `redisId`                                                                                | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `composeId`                                                                              | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
# PostgresStartMount

## Example Usage

```typescript
import { PostgresStartMount } from "dokploy-sdk/models/operations";

let value: PostgresStartMount = {
  applicationId: null,
  composeId: "<id>",
  content: "<value>",
  filePath: "/opt/sbin/what.m1v",
  hostPath: "<value>",
  mariadbId: "<id>",
  mongoId: "<id>",
  mountId: "<id>",
  mountPath: "<value>",
  mysqlId: "<id>",
  postgresId: "<id>",
  redisId: "<id>",
  serviceType: "compose",
  type: "file",
  volumeName: "<value>",
};
```

## Fields

| Field                                                                                      | Type                                                                                       | Required                                                                                   | Description                                                                                |
| ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ |
| `applicationId`                                                                            | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `composeId`                                                                                | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `content`                                                                                  | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `filePath`                                                                                 | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `hostPath`                                                                                 | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `mariadbId`                                                                                | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `mongoId`                                                                                  | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `mountId`                                                                                  | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `mountPath`                                                                                | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `mysqlId`                                                                                  | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `postgresId`                                                                               | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `redisId`                                                                                  | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `serviceType`                                                                              | [operations.PostgresStartServiceType](../../models/operations/postgresstartservicetype.md) | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `type`                                                                                     | [operations.PostgresStartType](../../models/operations/postgresstarttype.md)               | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `volumeName`                                                                               | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
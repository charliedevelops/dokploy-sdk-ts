# MysqlRemoveMount

## Example Usage

```typescript
import { MysqlRemoveMount } from "dokploy-sdk/models/operations";

let value: MysqlRemoveMount = {
  applicationId: "<id>",
  composeId: null,
  content: "<value>",
  filePath: "/opt/share/acquaintance_scheme_frightfully.json",
  hostPath: "<value>",
  mariadbId: "<id>",
  mongoId: "<id>",
  mountId: "<id>",
  mountPath: "<value>",
  mysqlId: "<id>",
  postgresId: "<id>",
  redisId: "<id>",
  serviceType: "mariadb",
  type: "bind",
  volumeName: "<value>",
};
```

## Fields

| Field                                                                                  | Type                                                                                   | Required                                                                               | Description                                                                            |
| -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- |
| `applicationId`                                                                        | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `composeId`                                                                            | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `content`                                                                              | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `filePath`                                                                             | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `hostPath`                                                                             | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `mariadbId`                                                                            | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `mongoId`                                                                              | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `mountId`                                                                              | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `mountPath`                                                                            | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `mysqlId`                                                                              | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `postgresId`                                                                           | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `redisId`                                                                              | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `serviceType`                                                                          | [operations.MysqlRemoveServiceType](../../models/operations/mysqlremoveservicetype.md) | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `type`                                                                                 | [operations.MysqlRemoveType](../../models/operations/mysqlremovetype.md)               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `volumeName`                                                                           | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
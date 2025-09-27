# RedisStartMount

## Example Usage

```typescript
import { RedisStartMount } from "dokploy-sdk/models/operations";

let value: RedisStartMount = {
  applicationId: "<id>",
  composeId: "<id>",
  content: "<value>",
  filePath: "/home/user/dir/brilliant_baa_than.mpg4",
  hostPath: null,
  mariadbId: "<id>",
  mongoId: "<id>",
  mountId: "<id>",
  mountPath: "<value>",
  mysqlId: "<id>",
  postgresId: "<id>",
  redisId: "<id>",
  serviceType: "redis",
  type: "file",
  volumeName: "<value>",
};
```

## Fields

| Field                                                                                | Type                                                                                 | Required                                                                             | Description                                                                          |
| ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ |
| `applicationId`                                                                      | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `composeId`                                                                          | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `content`                                                                            | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `filePath`                                                                           | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `hostPath`                                                                           | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `mariadbId`                                                                          | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `mongoId`                                                                            | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `mountId`                                                                            | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `mountPath`                                                                          | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `mysqlId`                                                                            | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `postgresId`                                                                         | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `redisId`                                                                            | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `serviceType`                                                                        | [operations.RedisStartServiceType](../../models/operations/redisstartservicetype.md) | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `type`                                                                               | [operations.RedisStartType](../../models/operations/redisstarttype.md)               | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `volumeName`                                                                         | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
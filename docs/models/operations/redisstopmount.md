# RedisStopMount

## Example Usage

```typescript
import { RedisStopMount } from "dokploy-sdk/models/operations";

let value: RedisStopMount = {
  mountId: "<id>",
  type: "bind",
  hostPath: "<value>",
  volumeName: "<value>",
  filePath: "/usr/local/src/avalanche.deb",
  content: "<value>",
  serviceType: "compose",
  mountPath: "<value>",
  applicationId: "<id>",
  postgresId: "<id>",
  mariadbId: "<id>",
  mongoId: null,
  mysqlId: "<id>",
  redisId: "<id>",
  composeId: "<id>",
};
```

## Fields

| Field                                                                              | Type                                                                               | Required                                                                           | Description                                                                        |
| ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- |
| `mountId`                                                                          | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `type`                                                                             | [operations.RedisStopType](../../models/operations/redisstoptype.md)               | :heavy_check_mark:                                                                 | N/A                                                                                |
| `hostPath`                                                                         | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `volumeName`                                                                       | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `filePath`                                                                         | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `content`                                                                          | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `serviceType`                                                                      | [operations.RedisStopServiceType](../../models/operations/redisstopservicetype.md) | :heavy_check_mark:                                                                 | N/A                                                                                |
| `mountPath`                                                                        | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `applicationId`                                                                    | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `postgresId`                                                                       | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `mariadbId`                                                                        | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `mongoId`                                                                          | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `mysqlId`                                                                          | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `redisId`                                                                          | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `composeId`                                                                        | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
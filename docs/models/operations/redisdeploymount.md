# RedisDeployMount

## Example Usage

```typescript
import { RedisDeployMount } from "dokploy-sdk/models/operations";

let value: RedisDeployMount = {
  applicationId: "<id>",
  composeId: "<id>",
  content: "<value>",
  filePath: "/opt/share/pfft_after.vst",
  hostPath: "<value>",
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
| `serviceType`                                                                          | [operations.RedisDeployServiceType](../../models/operations/redisdeployservicetype.md) | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `type`                                                                                 | [operations.RedisDeployType](../../models/operations/redisdeploytype.md)               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `volumeName`                                                                           | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
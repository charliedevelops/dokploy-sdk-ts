# RedisChangeStatusServer

## Example Usage

```typescript
import { RedisChangeStatusServer } from "dokploy-sdk/models/operations";

let value: RedisChangeStatusServer = {
  serverId: "<id>",
  name: "<value>",
  description:
    "gah meanwhile likewise nucleotidase onto definite video prance whenever distorted",
  ipAddress: "ebaa:d313:fcae:6d06:4e94:39d2:d984:ca4a",
  port: 8641.63,
  username: "Jadon28",
  appName: "<value>",
  enableDockerCleanup: true,
  createdAt: "1725006884176",
  organizationId: "<id>",
  serverStatus: "active",
  command: "<value>",
  sshKeyId: "<id>",
  metricsConfig: "<value>",
};
```

## Fields

| Field                                                                                                | Type                                                                                                 | Required                                                                                             | Description                                                                                          |
| ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- |
| `serverId`                                                                                           | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `name`                                                                                               | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `description`                                                                                        | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `ipAddress`                                                                                          | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `port`                                                                                               | *number*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `username`                                                                                           | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `appName`                                                                                            | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `enableDockerCleanup`                                                                                | *boolean*                                                                                            | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `createdAt`                                                                                          | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `organizationId`                                                                                     | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `serverStatus`                                                                                       | [operations.RedisChangeStatusServerStatus](../../models/operations/redischangestatusserverstatus.md) | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `command`                                                                                            | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `sshKeyId`                                                                                           | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `metricsConfig`                                                                                      | *operations.RedisChangeStatusMetricsConfigUnion2*                                                    | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
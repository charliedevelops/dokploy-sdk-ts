# RedisChangeStatusServer

## Example Usage

```typescript
import { RedisChangeStatusServer } from "dokploy-sdk/models/operations";

let value: RedisChangeStatusServer = {
  appName: "<value>",
  command: "<value>",
  createdAt: "1726144575945",
  description: "tenderly nightlife hence community",
  enableDockerCleanup: false,
  ipAddress: "9d3e:e4bf:bb34:c5ec:7fc7:d7f3:dc45:b94a",
  metricsConfig: {
    "key": "<value>",
    "key1": "<value>",
  },
  name: "<value>",
  organizationId: "<id>",
  port: 3851.94,
  serverId: "<id>",
  serverStatus: "inactive",
  sshKeyId: "<id>",
  username: "Malinda_McLaughlin",
};
```

## Fields

| Field                                                                                                | Type                                                                                                 | Required                                                                                             | Description                                                                                          |
| ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- |
| `appName`                                                                                            | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `command`                                                                                            | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `createdAt`                                                                                          | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `description`                                                                                        | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `enableDockerCleanup`                                                                                | *boolean*                                                                                            | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `ipAddress`                                                                                          | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `metricsConfig`                                                                                      | *operations.RedisChangeStatusMetricsConfigUnion2*                                                    | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `name`                                                                                               | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `organizationId`                                                                                     | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `port`                                                                                               | *number*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `serverId`                                                                                           | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `serverStatus`                                                                                       | [operations.RedisChangeStatusServerStatus](../../models/operations/redischangestatusserverstatus.md) | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `sshKeyId`                                                                                           | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `username`                                                                                           | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
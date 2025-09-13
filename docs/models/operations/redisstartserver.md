# RedisStartServer

## Example Usage

```typescript
import { RedisStartServer } from "dokploy-sdk/models/operations";

let value: RedisStartServer = {
  serverId: "<id>",
  name: "<value>",
  description: "till ick in solidly afore aha ape aw",
  ipAddress: "176.240.90.253",
  port: 6066.63,
  username: "Nestor45",
  appName: "<value>",
  enableDockerCleanup: false,
  createdAt: "1713809211096",
  organizationId: "<id>",
  serverStatus: "active",
  command: "<value>",
  sshKeyId: "<id>",
  metricsConfig: {
    "key": "<value>",
    "key1": "<value>",
    "key2": "<value>",
  },
};
```

## Fields

| Field                                                                                  | Type                                                                                   | Required                                                                               | Description                                                                            |
| -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- |
| `serverId`                                                                             | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `name`                                                                                 | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `description`                                                                          | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `ipAddress`                                                                            | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `port`                                                                                 | *number*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `username`                                                                             | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `appName`                                                                              | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `enableDockerCleanup`                                                                  | *boolean*                                                                              | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `createdAt`                                                                            | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `organizationId`                                                                       | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `serverStatus`                                                                         | [operations.RedisStartServerStatus](../../models/operations/redisstartserverstatus.md) | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `command`                                                                              | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `sshKeyId`                                                                             | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `metricsConfig`                                                                        | *operations.RedisStartMetricsConfigUnion2*                                             | :heavy_check_mark:                                                                     | N/A                                                                                    |
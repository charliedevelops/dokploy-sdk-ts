# RedisDeployServer

## Example Usage

```typescript
import { RedisDeployServer } from "dokploy-sdk/models/operations";

let value: RedisDeployServer = {
  serverId: "<id>",
  name: "<value>",
  description: "whose upbeat fray thongs gadzooks fooey because whoever",
  ipAddress: "47.151.81.85",
  port: 9142.59,
  username: "Wilford64",
  appName: "<value>",
  enableDockerCleanup: true,
  createdAt: "1728709419274",
  organizationId: "<id>",
  serverStatus: "inactive",
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

| Field                                                                                    | Type                                                                                     | Required                                                                                 | Description                                                                              |
| ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- |
| `serverId`                                                                               | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `name`                                                                                   | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `description`                                                                            | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `ipAddress`                                                                              | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `port`                                                                                   | *number*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `username`                                                                               | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `appName`                                                                                | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `enableDockerCleanup`                                                                    | *boolean*                                                                                | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `createdAt`                                                                              | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `organizationId`                                                                         | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `serverStatus`                                                                           | [operations.RedisDeployServerStatus](../../models/operations/redisdeployserverstatus.md) | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `command`                                                                                | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `sshKeyId`                                                                               | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `metricsConfig`                                                                          | *operations.RedisDeployMetricsConfigUnion2*                                              | :heavy_check_mark:                                                                       | N/A                                                                                      |
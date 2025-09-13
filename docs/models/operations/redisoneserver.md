# RedisOneServer

## Example Usage

```typescript
import { RedisOneServer } from "dokploy-sdk/models/operations";

let value: RedisOneServer = {
  serverId: "<id>",
  name: "<value>",
  description: "however or tightly not fervently indeed swelter",
  ipAddress: "95.39.97.9",
  port: 3536.28,
  username: "Michele.Gleichner",
  appName: "<value>",
  enableDockerCleanup: false,
  createdAt: "1715663312431",
  organizationId: "<id>",
  serverStatus: "inactive",
  command: "<value>",
  sshKeyId: "<id>",
  metricsConfig: {},
};
```

## Fields

| Field                                                                              | Type                                                                               | Required                                                                           | Description                                                                        |
| ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- |
| `serverId`                                                                         | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `name`                                                                             | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `description`                                                                      | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `ipAddress`                                                                        | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `port`                                                                             | *number*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `username`                                                                         | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `appName`                                                                          | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `enableDockerCleanup`                                                              | *boolean*                                                                          | :heavy_check_mark:                                                                 | N/A                                                                                |
| `createdAt`                                                                        | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `organizationId`                                                                   | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `serverStatus`                                                                     | [operations.RedisOneServerStatus](../../models/operations/redisoneserverstatus.md) | :heavy_check_mark:                                                                 | N/A                                                                                |
| `command`                                                                          | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `sshKeyId`                                                                         | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `metricsConfig`                                                                    | *operations.RedisOneMetricsConfigUnion2*                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
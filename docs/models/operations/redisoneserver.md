# RedisOneServer

## Example Usage

```typescript
import { RedisOneServer } from "dokploy-sdk/models/operations";

let value: RedisOneServer = {
  appName: "<value>",
  command: "<value>",
  createdAt: "1720666813180",
  description: "tarry agitated negative sans suspiciously speedily fathom ah",
  enableDockerCleanup: true,
  ipAddress: "10.118.165.93",
  metricsConfig: {},
  name: "<value>",
  organizationId: "<id>",
  port: 8743.12,
  serverId: "<id>",
  serverStatus: "active",
  sshKeyId: "<id>",
  username: "Doris61",
};
```

## Fields

| Field                                                                              | Type                                                                               | Required                                                                           | Description                                                                        |
| ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- |
| `appName`                                                                          | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `command`                                                                          | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `createdAt`                                                                        | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `description`                                                                      | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `enableDockerCleanup`                                                              | *boolean*                                                                          | :heavy_check_mark:                                                                 | N/A                                                                                |
| `ipAddress`                                                                        | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `metricsConfig`                                                                    | *operations.RedisOneMetricsConfigUnion2*                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `name`                                                                             | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `organizationId`                                                                   | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `port`                                                                             | *number*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `serverId`                                                                         | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `serverStatus`                                                                     | [operations.RedisOneServerStatus](../../models/operations/redisoneserverstatus.md) | :heavy_check_mark:                                                                 | N/A                                                                                |
| `sshKeyId`                                                                         | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `username`                                                                         | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
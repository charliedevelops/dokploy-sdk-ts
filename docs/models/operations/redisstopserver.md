# RedisStopServer

## Example Usage

```typescript
import { RedisStopServer } from "dokploy-sdk/models/operations";

let value: RedisStopServer = {
  appName: "<value>",
  command: "<value>",
  createdAt: "1720741110208",
  description:
    "even meander spirited provided boo miserly deselect affectionate",
  enableDockerCleanup: true,
  ipAddress: "182.233.183.185",
  metricsConfig: [
    "<value 1>",
    "<value 2>",
  ],
  name: "<value>",
  organizationId: "<id>",
  port: 4573.44,
  serverId: "<id>",
  serverStatus: "active",
  sshKeyId: "<id>",
  username: "Isabell_Purdy",
};
```

## Fields

| Field                                                                                | Type                                                                                 | Required                                                                             | Description                                                                          |
| ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ |
| `appName`                                                                            | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `command`                                                                            | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `createdAt`                                                                          | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `description`                                                                        | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `enableDockerCleanup`                                                                | *boolean*                                                                            | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `ipAddress`                                                                          | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `metricsConfig`                                                                      | *operations.RedisStopMetricsConfigUnion2*                                            | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `name`                                                                               | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `organizationId`                                                                     | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `port`                                                                               | *number*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `serverId`                                                                           | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `serverStatus`                                                                       | [operations.RedisStopServerStatus](../../models/operations/redisstopserverstatus.md) | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `sshKeyId`                                                                           | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `username`                                                                           | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
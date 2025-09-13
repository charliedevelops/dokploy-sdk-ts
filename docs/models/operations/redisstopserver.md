# RedisStopServer

## Example Usage

```typescript
import { RedisStopServer } from "dokploy-sdk/models/operations";

let value: RedisStopServer = {
  serverId: "<id>",
  name: "<value>",
  description:
    "usefully vulgarise sour elver that pave fat tomography repurpose along",
  ipAddress: "d9c1:2e7c:3c2d:ab19:f2a3:fe9c:b4db:fc5d",
  port: 3537.39,
  username: "Zackery_Gutmann-Cummings33",
  appName: "<value>",
  enableDockerCleanup: false,
  createdAt: "1719076049056",
  organizationId: "<id>",
  serverStatus: "inactive",
  command: "<value>",
  sshKeyId: null,
  metricsConfig: {
    "key": "<value>",
    "key1": "<value>",
    "key2": "<value>",
  },
};
```

## Fields

| Field                                                                                | Type                                                                                 | Required                                                                             | Description                                                                          |
| ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ |
| `serverId`                                                                           | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `name`                                                                               | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `description`                                                                        | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `ipAddress`                                                                          | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `port`                                                                               | *number*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `username`                                                                           | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `appName`                                                                            | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `enableDockerCleanup`                                                                | *boolean*                                                                            | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `createdAt`                                                                          | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `organizationId`                                                                     | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `serverStatus`                                                                       | [operations.RedisStopServerStatus](../../models/operations/redisstopserverstatus.md) | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `command`                                                                            | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `sshKeyId`                                                                           | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `metricsConfig`                                                                      | *operations.RedisStopMetricsConfigUnion2*                                            | :heavy_check_mark:                                                                   | N/A                                                                                  |
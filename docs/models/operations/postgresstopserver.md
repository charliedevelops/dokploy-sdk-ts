# PostgresStopServer

## Example Usage

```typescript
import { PostgresStopServer } from "dokploy-sdk/models/operations";

let value: PostgresStopServer = {
  serverId: "<id>",
  name: "<value>",
  description: "phew opposite worth concerning yet trusty that capitalize",
  ipAddress: "bfb3:ac77:adbe:bc9c:af4a:acbf:dfc9:1bea",
  port: 1937.01,
  username: "Eliseo_Herzog96",
  appName: "<value>",
  enableDockerCleanup: false,
  createdAt: "1731474510881",
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

| Field                                                                                      | Type                                                                                       | Required                                                                                   | Description                                                                                |
| ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ |
| `serverId`                                                                                 | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `name`                                                                                     | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `description`                                                                              | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `ipAddress`                                                                                | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `port`                                                                                     | *number*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `username`                                                                                 | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `appName`                                                                                  | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `enableDockerCleanup`                                                                      | *boolean*                                                                                  | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `createdAt`                                                                                | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `organizationId`                                                                           | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `serverStatus`                                                                             | [operations.PostgresStopServerStatus](../../models/operations/postgresstopserverstatus.md) | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `command`                                                                                  | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `sshKeyId`                                                                                 | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `metricsConfig`                                                                            | *operations.PostgresStopMetricsConfigUnion2*                                               | :heavy_check_mark:                                                                         | N/A                                                                                        |
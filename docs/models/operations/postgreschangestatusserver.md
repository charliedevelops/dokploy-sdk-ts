# PostgresChangeStatusServer

## Example Usage

```typescript
import { PostgresChangeStatusServer } from "dokploy-sdk/models/operations";

let value: PostgresChangeStatusServer = {
  appName: "<value>",
  command: "<value>",
  createdAt: "1727518584571",
  description: null,
  enableDockerCleanup: false,
  ipAddress: "204.148.147.173",
  metricsConfig: 5068.14,
  name: "<value>",
  organizationId: "<id>",
  port: 9560.48,
  serverId: "<id>",
  serverStatus: "inactive",
  sshKeyId: null,
  username: "Clementina.Casper",
};
```

## Fields

| Field                                                                                                      | Type                                                                                                       | Required                                                                                                   | Description                                                                                                |
| ---------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- |
| `appName`                                                                                                  | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `command`                                                                                                  | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `createdAt`                                                                                                | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `description`                                                                                              | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `enableDockerCleanup`                                                                                      | *boolean*                                                                                                  | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `ipAddress`                                                                                                | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `metricsConfig`                                                                                            | *operations.PostgresChangeStatusMetricsConfigUnion2*                                                       | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `name`                                                                                                     | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `organizationId`                                                                                           | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `port`                                                                                                     | *number*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `serverId`                                                                                                 | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `serverStatus`                                                                                             | [operations.PostgresChangeStatusServerStatus](../../models/operations/postgreschangestatusserverstatus.md) | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `sshKeyId`                                                                                                 | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `username`                                                                                                 | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
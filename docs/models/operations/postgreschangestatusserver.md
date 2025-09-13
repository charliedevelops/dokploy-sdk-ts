# PostgresChangeStatusServer

## Example Usage

```typescript
import { PostgresChangeStatusServer } from "dokploy-sdk/models/operations";

let value: PostgresChangeStatusServer = {
  serverId: "<id>",
  name: "<value>",
  description: "glum irritably finding",
  ipAddress: "45.234.109.21",
  port: 6905.87,
  username: "Halle_Hickle49",
  appName: "<value>",
  enableDockerCleanup: false,
  createdAt: "1710908621217",
  organizationId: "<id>",
  serverStatus: "inactive",
  command: "<value>",
  sshKeyId: "<id>",
  metricsConfig: [
    "<value 1>",
    "<value 2>",
  ],
};
```

## Fields

| Field                                                                                                      | Type                                                                                                       | Required                                                                                                   | Description                                                                                                |
| ---------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- |
| `serverId`                                                                                                 | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `name`                                                                                                     | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `description`                                                                                              | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `ipAddress`                                                                                                | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `port`                                                                                                     | *number*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `username`                                                                                                 | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `appName`                                                                                                  | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `enableDockerCleanup`                                                                                      | *boolean*                                                                                                  | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `createdAt`                                                                                                | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `organizationId`                                                                                           | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `serverStatus`                                                                                             | [operations.PostgresChangeStatusServerStatus](../../models/operations/postgreschangestatusserverstatus.md) | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `command`                                                                                                  | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `sshKeyId`                                                                                                 | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `metricsConfig`                                                                                            | *operations.PostgresChangeStatusMetricsConfigUnion2*                                                       | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
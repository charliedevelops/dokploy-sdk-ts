# MariadbStartServer

## Example Usage

```typescript
import { MariadbStartServer } from "dokploy-sdk/models/operations";

let value: MariadbStartServer = {
  appName: "<value>",
  command: "<value>",
  createdAt: "1713898695092",
  description: "solemnly meh waltz peaceful really plus incinerate",
  enableDockerCleanup: false,
  ipAddress: "bc9f:aebd:c90b:a855:febe:3c3c:1fe1:fcc3",
  metricsConfig: 573.57,
  name: "<value>",
  organizationId: "<id>",
  port: 5616.21,
  serverId: "<id>",
  serverStatus: "inactive",
  sshKeyId: "<id>",
  username: "Isabel72",
};
```

## Fields

| Field                                                                                      | Type                                                                                       | Required                                                                                   | Description                                                                                |
| ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ |
| `appName`                                                                                  | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `command`                                                                                  | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `createdAt`                                                                                | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `description`                                                                              | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `enableDockerCleanup`                                                                      | *boolean*                                                                                  | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `ipAddress`                                                                                | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `metricsConfig`                                                                            | *operations.MariadbStartMetricsConfigUnion2*                                               | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `name`                                                                                     | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `organizationId`                                                                           | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `port`                                                                                     | *number*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `serverId`                                                                                 | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `serverStatus`                                                                             | [operations.MariadbStartServerStatus](../../models/operations/mariadbstartserverstatus.md) | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `sshKeyId`                                                                                 | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `username`                                                                                 | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
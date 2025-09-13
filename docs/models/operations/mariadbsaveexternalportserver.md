# MariadbSaveExternalPortServer

## Example Usage

```typescript
import { MariadbSaveExternalPortServer } from "dokploy-sdk/models/operations";

let value: MariadbSaveExternalPortServer = {
  serverId: "<id>",
  name: "<value>",
  description: "tank instructor surprisingly so ack",
  ipAddress: "106.31.191.163",
  port: 6760.01,
  username: "Sean.Schamberger",
  appName: "<value>",
  enableDockerCleanup: true,
  createdAt: "1723293706660",
  organizationId: "<id>",
  serverStatus: "active",
  command: "<value>",
  sshKeyId: "<id>",
  metricsConfig: false,
};
```

## Fields

| Field                                                                                                            | Type                                                                                                             | Required                                                                                                         | Description                                                                                                      |
| ---------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- |
| `serverId`                                                                                                       | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `name`                                                                                                           | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `description`                                                                                                    | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `ipAddress`                                                                                                      | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `port`                                                                                                           | *number*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `username`                                                                                                       | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `appName`                                                                                                        | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `enableDockerCleanup`                                                                                            | *boolean*                                                                                                        | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `createdAt`                                                                                                      | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `organizationId`                                                                                                 | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `serverStatus`                                                                                                   | [operations.MariadbSaveExternalPortServerStatus](../../models/operations/mariadbsaveexternalportserverstatus.md) | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `command`                                                                                                        | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `sshKeyId`                                                                                                       | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `metricsConfig`                                                                                                  | *operations.MariadbSaveExternalPortMetricsConfigUnion2*                                                          | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
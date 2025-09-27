# MysqlStartServer

## Example Usage

```typescript
import { MysqlStartServer } from "dokploy-sdk/models/operations";

let value: MysqlStartServer = {
  appName: "<value>",
  command: "<value>",
  createdAt: "1707688699073",
  description: null,
  enableDockerCleanup: true,
  ipAddress: "204.203.36.86",
  metricsConfig: [
    "<value 1>",
    "<value 2>",
  ],
  name: "<value>",
  organizationId: "<id>",
  port: 8641.65,
  serverId: "<id>",
  serverStatus: "active",
  sshKeyId: "<id>",
  username: "Darien_Abshire",
};
```

## Fields

| Field                                                                                  | Type                                                                                   | Required                                                                               | Description                                                                            |
| -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- |
| `appName`                                                                              | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `command`                                                                              | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `createdAt`                                                                            | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `description`                                                                          | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `enableDockerCleanup`                                                                  | *boolean*                                                                              | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `ipAddress`                                                                            | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `metricsConfig`                                                                        | *operations.MysqlStartMetricsConfigUnion2*                                             | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `name`                                                                                 | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `organizationId`                                                                       | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `port`                                                                                 | *number*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `serverId`                                                                             | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `serverStatus`                                                                         | [operations.MysqlStartServerStatus](../../models/operations/mysqlstartserverstatus.md) | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `sshKeyId`                                                                             | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `username`                                                                             | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
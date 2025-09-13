# MysqlStartServer

## Example Usage

```typescript
import { MysqlStartServer } from "dokploy-sdk/models/operations";

let value: MysqlStartServer = {
  serverId: "<id>",
  name: "<value>",
  description: "irritably accept impressive",
  ipAddress: "35.149.168.224",
  port: 2578.78,
  username: "Korey24",
  appName: "<value>",
  enableDockerCleanup: true,
  createdAt: "1722588630800",
  organizationId: "<id>",
  serverStatus: "active",
  command: "<value>",
  sshKeyId: "<id>",
  metricsConfig: [
    "<value 1>",
    "<value 2>",
  ],
};
```

## Fields

| Field                                                                                  | Type                                                                                   | Required                                                                               | Description                                                                            |
| -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- |
| `serverId`                                                                             | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `name`                                                                                 | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `description`                                                                          | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `ipAddress`                                                                            | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `port`                                                                                 | *number*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `username`                                                                             | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `appName`                                                                              | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `enableDockerCleanup`                                                                  | *boolean*                                                                              | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `createdAt`                                                                            | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `organizationId`                                                                       | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `serverStatus`                                                                         | [operations.MysqlStartServerStatus](../../models/operations/mysqlstartserverstatus.md) | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `command`                                                                              | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `sshKeyId`                                                                             | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `metricsConfig`                                                                        | *operations.MysqlStartMetricsConfigUnion2*                                             | :heavy_check_mark:                                                                     | N/A                                                                                    |
# MysqlDeployServer

## Example Usage

```typescript
import { MysqlDeployServer } from "dokploy-sdk/models/operations";

let value: MysqlDeployServer = {
  serverId: "<id>",
  name: "<value>",
  description: "patroller gape meanwhile broadcast yearningly though captain",
  ipAddress: "158.120.152.2",
  port: 4835.77,
  username: "Dessie_Rempel38",
  appName: "<value>",
  enableDockerCleanup: true,
  createdAt: "1712424669870",
  organizationId: "<id>",
  serverStatus: "active",
  command: "<value>",
  sshKeyId: "<id>",
  metricsConfig: [
    "<value 1>",
    "<value 2>",
    "<value 3>",
  ],
};
```

## Fields

| Field                                                                                    | Type                                                                                     | Required                                                                                 | Description                                                                              |
| ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- |
| `serverId`                                                                               | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `name`                                                                                   | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `description`                                                                            | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `ipAddress`                                                                              | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `port`                                                                                   | *number*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `username`                                                                               | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `appName`                                                                                | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `enableDockerCleanup`                                                                    | *boolean*                                                                                | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `createdAt`                                                                              | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `organizationId`                                                                         | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `serverStatus`                                                                           | [operations.MysqlDeployServerStatus](../../models/operations/mysqldeployserverstatus.md) | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `command`                                                                                | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `sshKeyId`                                                                               | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `metricsConfig`                                                                          | *operations.MysqlDeployMetricsConfigUnion2*                                              | :heavy_check_mark:                                                                       | N/A                                                                                      |
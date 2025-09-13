# MysqlOneServer

## Example Usage

```typescript
import { MysqlOneServer } from "dokploy-sdk/models/operations";

let value: MysqlOneServer = {
  serverId: "<id>",
  name: "<value>",
  description: "grave oil towards yowza monasticism reiterate",
  ipAddress: "f853:aded:deac:db6e:b70f:581a:c62c:884f",
  port: 4921.13,
  username: "Frieda.Altenwerth",
  appName: "<value>",
  enableDockerCleanup: true,
  createdAt: "1733704853995",
  organizationId: "<id>",
  serverStatus: "inactive",
  command: "<value>",
  sshKeyId: "<id>",
  metricsConfig: [
    "<value 1>",
  ],
};
```

## Fields

| Field                                                                              | Type                                                                               | Required                                                                           | Description                                                                        |
| ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- |
| `serverId`                                                                         | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `name`                                                                             | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `description`                                                                      | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `ipAddress`                                                                        | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `port`                                                                             | *number*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `username`                                                                         | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `appName`                                                                          | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `enableDockerCleanup`                                                              | *boolean*                                                                          | :heavy_check_mark:                                                                 | N/A                                                                                |
| `createdAt`                                                                        | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `organizationId`                                                                   | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `serverStatus`                                                                     | [operations.MysqlOneServerStatus](../../models/operations/mysqloneserverstatus.md) | :heavy_check_mark:                                                                 | N/A                                                                                |
| `command`                                                                          | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `sshKeyId`                                                                         | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `metricsConfig`                                                                    | *operations.MysqlOneMetricsConfigUnion2*                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
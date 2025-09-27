# MysqlOneServer

## Example Usage

```typescript
import { MysqlOneServer } from "dokploy-sdk/models/operations";

let value: MysqlOneServer = {
  appName: "<value>",
  command: "<value>",
  createdAt: "1732643309793",
  description: "among huzzah writ daintily before where er metallic",
  enableDockerCleanup: true,
  ipAddress: "b70f:581a:c62c:884f:a850:4d95:ecd7:7eb3",
  metricsConfig: {
    "key": "<value>",
    "key1": "<value>",
  },
  name: "<value>",
  organizationId: "<id>",
  port: 9794.5,
  serverId: "<id>",
  serverStatus: "active",
  sshKeyId: "<id>",
  username: "Devan.Fritsch32",
};
```

## Fields

| Field                                                                              | Type                                                                               | Required                                                                           | Description                                                                        |
| ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- |
| `appName`                                                                          | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `command`                                                                          | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `createdAt`                                                                        | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `description`                                                                      | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `enableDockerCleanup`                                                              | *boolean*                                                                          | :heavy_check_mark:                                                                 | N/A                                                                                |
| `ipAddress`                                                                        | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `metricsConfig`                                                                    | *operations.MysqlOneMetricsConfigUnion2*                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `name`                                                                             | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `organizationId`                                                                   | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `port`                                                                             | *number*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `serverId`                                                                         | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `serverStatus`                                                                     | [operations.MysqlOneServerStatus](../../models/operations/mysqloneserverstatus.md) | :heavy_check_mark:                                                                 | N/A                                                                                |
| `sshKeyId`                                                                         | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `username`                                                                         | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
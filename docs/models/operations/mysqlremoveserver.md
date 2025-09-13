# MysqlRemoveServer

## Example Usage

```typescript
import { MysqlRemoveServer } from "dokploy-sdk/models/operations";

let value: MysqlRemoveServer = {
  serverId: "<id>",
  name: "<value>",
  description:
    "ferret digital after restfully gadzooks scarper oof sprinkles nearly",
  ipAddress: "49e2:e957:e265:a216:dc3b:fc6f:aeb3:68ae",
  port: 9758.56,
  username: "Caden82",
  appName: "<value>",
  enableDockerCleanup: true,
  createdAt: "1712721335473",
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
| `serverStatus`                                                                           | [operations.MysqlRemoveServerStatus](../../models/operations/mysqlremoveserverstatus.md) | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `command`                                                                                | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `sshKeyId`                                                                               | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `metricsConfig`                                                                          | *operations.MysqlRemoveMetricsConfigUnion2*                                              | :heavy_check_mark:                                                                       | N/A                                                                                      |
# MysqlStopServer

## Example Usage

```typescript
import { MysqlStopServer } from "dokploy-sdk/models/operations";

let value: MysqlStopServer = {
  serverId: "<id>",
  name: "<value>",
  description: "brr phew folklore airbus woot immediate",
  ipAddress: "216.28.63.219",
  port: 7585.93,
  username: "Christophe_Hyatt",
  appName: "<value>",
  enableDockerCleanup: false,
  createdAt: "1731384008208",
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

| Field                                                                                | Type                                                                                 | Required                                                                             | Description                                                                          |
| ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ |
| `serverId`                                                                           | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `name`                                                                               | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `description`                                                                        | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `ipAddress`                                                                          | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `port`                                                                               | *number*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `username`                                                                           | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `appName`                                                                            | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `enableDockerCleanup`                                                                | *boolean*                                                                            | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `createdAt`                                                                          | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `organizationId`                                                                     | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `serverStatus`                                                                       | [operations.MysqlStopServerStatus](../../models/operations/mysqlstopserverstatus.md) | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `command`                                                                            | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `sshKeyId`                                                                           | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `metricsConfig`                                                                      | *operations.MysqlStopMetricsConfigUnion2*                                            | :heavy_check_mark:                                                                   | N/A                                                                                  |
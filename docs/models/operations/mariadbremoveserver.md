# MariadbRemoveServer

## Example Usage

```typescript
import { MariadbRemoveServer } from "dokploy-sdk/models/operations";

let value: MariadbRemoveServer = {
  serverId: "<id>",
  name: "<value>",
  description: "comparison weakly via bashfully",
  ipAddress: "db7b:5a9d:ad8f:e3cd:7be9:ed8c:b4cd:c06b",
  port: 5533.12,
  username: "Lincoln_Okuneva95",
  appName: "<value>",
  enableDockerCleanup: true,
  createdAt: "1729284722374",
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

| Field                                                                                        | Type                                                                                         | Required                                                                                     | Description                                                                                  |
| -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- |
| `serverId`                                                                                   | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `name`                                                                                       | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `description`                                                                                | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `ipAddress`                                                                                  | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `port`                                                                                       | *number*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `username`                                                                                   | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `appName`                                                                                    | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `enableDockerCleanup`                                                                        | *boolean*                                                                                    | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `createdAt`                                                                                  | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `organizationId`                                                                             | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `serverStatus`                                                                               | [operations.MariadbRemoveServerStatus](../../models/operations/mariadbremoveserverstatus.md) | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `command`                                                                                    | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `sshKeyId`                                                                                   | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `metricsConfig`                                                                              | *operations.MariadbRemoveMetricsConfigUnion2*                                                | :heavy_check_mark:                                                                           | N/A                                                                                          |
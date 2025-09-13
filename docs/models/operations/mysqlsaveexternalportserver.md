# MysqlSaveExternalPortServer

## Example Usage

```typescript
import { MysqlSaveExternalPortServer } from "dokploy-sdk/models/operations";

let value: MysqlSaveExternalPortServer = {
  appName: "<value>",
  command: "<value>",
  createdAt: "1730475855274",
  description: "fooey zowie aftermath pleasant",
  enableDockerCleanup: false,
  ipAddress: "207.82.178.15",
  metricsConfig: {},
  name: "<value>",
  organizationId: "<id>",
  port: 1587.59,
  serverId: "<id>",
  serverStatus: "inactive",
  sshKeyId: "<id>",
  username: "Golda_Wehner",
};
```

## Fields

| Field                                                                                                        | Type                                                                                                         | Required                                                                                                     | Description                                                                                                  |
| ------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------ |
| `appName`                                                                                                    | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `command`                                                                                                    | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `createdAt`                                                                                                  | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `description`                                                                                                | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `enableDockerCleanup`                                                                                        | *boolean*                                                                                                    | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `ipAddress`                                                                                                  | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `metricsConfig`                                                                                              | *operations.MysqlSaveExternalPortMetricsConfigUnion2*                                                        | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `name`                                                                                                       | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `organizationId`                                                                                             | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `port`                                                                                                       | *number*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `serverId`                                                                                                   | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `serverStatus`                                                                                               | [operations.MysqlSaveExternalPortServerStatus](../../models/operations/mysqlsaveexternalportserverstatus.md) | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `sshKeyId`                                                                                                   | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `username`                                                                                                   | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
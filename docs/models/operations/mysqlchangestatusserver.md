# MysqlChangeStatusServer

## Example Usage

```typescript
import { MysqlChangeStatusServer } from "dokploy-sdk/models/operations";

let value: MysqlChangeStatusServer = {
  appName: "<value>",
  command: "<value>",
  createdAt: "1712723619765",
  description: "circa writhing pish wildly fondly ham",
  enableDockerCleanup: false,
  ipAddress: "221.44.165.102",
  metricsConfig: "<value>",
  name: "<value>",
  organizationId: "<id>",
  port: 1843.99,
  serverId: "<id>",
  serverStatus: "inactive",
  sshKeyId: "<id>",
  username: "Alyson68",
};
```

## Fields

| Field                                                                                                | Type                                                                                                 | Required                                                                                             | Description                                                                                          |
| ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- |
| `appName`                                                                                            | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `command`                                                                                            | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `createdAt`                                                                                          | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `description`                                                                                        | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `enableDockerCleanup`                                                                                | *boolean*                                                                                            | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `ipAddress`                                                                                          | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `metricsConfig`                                                                                      | *operations.MysqlChangeStatusMetricsConfigUnion2*                                                    | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `name`                                                                                               | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `organizationId`                                                                                     | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `port`                                                                                               | *number*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `serverId`                                                                                           | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `serverStatus`                                                                                       | [operations.MysqlChangeStatusServerStatus](../../models/operations/mysqlchangestatusserverstatus.md) | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `sshKeyId`                                                                                           | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `username`                                                                                           | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
# MariadbChangeStatusServer

## Example Usage

```typescript
import { MariadbChangeStatusServer } from "dokploy-sdk/models/operations";

let value: MariadbChangeStatusServer = {
  serverId: "<id>",
  name: "<value>",
  description: "armchair past ha embossing since yowza yuck nervously",
  ipAddress: "114b:aecc:dfe1:47ba:c19e:2d47:b85d:20bd",
  port: 8068.96,
  username: "Darrell.Raynor",
  appName: "<value>",
  enableDockerCleanup: false,
  createdAt: "1714795355383",
  organizationId: "<id>",
  serverStatus: "inactive",
  command: "<value>",
  sshKeyId: "<id>",
  metricsConfig: [],
};
```

## Fields

| Field                                                                                                    | Type                                                                                                     | Required                                                                                                 | Description                                                                                              |
| -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- |
| `serverId`                                                                                               | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `name`                                                                                                   | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `description`                                                                                            | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `ipAddress`                                                                                              | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `port`                                                                                                   | *number*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `username`                                                                                               | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `appName`                                                                                                | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `enableDockerCleanup`                                                                                    | *boolean*                                                                                                | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `createdAt`                                                                                              | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `organizationId`                                                                                         | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `serverStatus`                                                                                           | [operations.MariadbChangeStatusServerStatus](../../models/operations/mariadbchangestatusserverstatus.md) | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `command`                                                                                                | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `sshKeyId`                                                                                               | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `metricsConfig`                                                                                          | *operations.MariadbChangeStatusMetricsConfigUnion2*                                                      | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
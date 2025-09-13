# MariadbChangeStatusServer

## Example Usage

```typescript
import { MariadbChangeStatusServer } from "dokploy-sdk/models/operations";

let value: MariadbChangeStatusServer = {
  appName: "<value>",
  command: "<value>",
  createdAt: "1714940576107",
  description: "abnormally opposite considering profane but writ",
  enableDockerCleanup: true,
  ipAddress: "111.70.8.5",
  metricsConfig: {
    "key": "<value>",
    "key1": "<value>",
    "key2": "<value>",
  },
  name: "<value>",
  organizationId: "<id>",
  port: 9168.3,
  serverId: "<id>",
  serverStatus: "inactive",
  sshKeyId: "<id>",
  username: "Ciara.Mann7",
};
```

## Fields

| Field                                                                                                    | Type                                                                                                     | Required                                                                                                 | Description                                                                                              |
| -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- |
| `appName`                                                                                                | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `command`                                                                                                | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `createdAt`                                                                                              | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `description`                                                                                            | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `enableDockerCleanup`                                                                                    | *boolean*                                                                                                | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `ipAddress`                                                                                              | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `metricsConfig`                                                                                          | *operations.MariadbChangeStatusMetricsConfigUnion2*                                                      | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `name`                                                                                                   | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `organizationId`                                                                                         | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `port`                                                                                                   | *number*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `serverId`                                                                                               | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `serverStatus`                                                                                           | [operations.MariadbChangeStatusServerStatus](../../models/operations/mariadbchangestatusserverstatus.md) | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `sshKeyId`                                                                                               | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `username`                                                                                               | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
# MariadbOneServer

## Example Usage

```typescript
import { MariadbOneServer } from "dokploy-sdk/models/operations";

let value: MariadbOneServer = {
  serverId: "<id>",
  name: "<value>",
  description: "extricate furthermore creature configuration drat anti",
  ipAddress: "9.191.40.144",
  port: 215.91,
  username: "Erika81",
  appName: "<value>",
  enableDockerCleanup: true,
  createdAt: "1709937231725",
  organizationId: "<id>",
  serverStatus: "inactive",
  command: "<value>",
  sshKeyId: "<id>",
  metricsConfig: "<value>",
};
```

## Fields

| Field                                                                                  | Type                                                                                   | Required                                                                               | Description                                                                            |
| -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- |
| `serverId`                                                                             | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `name`                                                                                 | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `description`                                                                          | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `ipAddress`                                                                            | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `port`                                                                                 | *number*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `username`                                                                             | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `appName`                                                                              | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `enableDockerCleanup`                                                                  | *boolean*                                                                              | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `createdAt`                                                                            | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `organizationId`                                                                       | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `serverStatus`                                                                         | [operations.MariadbOneServerStatus](../../models/operations/mariadboneserverstatus.md) | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `command`                                                                              | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `sshKeyId`                                                                             | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `metricsConfig`                                                                        | *operations.MariadbOneMetricsConfigUnion2*                                             | :heavy_check_mark:                                                                     | N/A                                                                                    |
# ApplicationStopServer

## Example Usage

```typescript
import { ApplicationStopServer } from "dokploy-sdk/models/operations";

let value: ApplicationStopServer = {
  appName: "<value>",
  command: "<value>",
  createdAt: "1723576589604",
  description:
    "incidentally unless finally perfection from tattered catalyze watery",
  enableDockerCleanup: false,
  ipAddress: "83.254.192.221",
  metricsConfig: "null",
  name: "<value>",
  organizationId: "<id>",
  port: 1270.1,
  serverId: "<id>",
  serverStatus: "inactive",
  sshKeyId: "<id>",
  username: "Tremaine_Rolfson",
};
```

## Fields

| Field                                                                                            | Type                                                                                             | Required                                                                                         | Description                                                                                      |
| ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ |
| `appName`                                                                                        | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `command`                                                                                        | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `createdAt`                                                                                      | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `description`                                                                                    | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `enableDockerCleanup`                                                                            | *boolean*                                                                                        | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `ipAddress`                                                                                      | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `metricsConfig`                                                                                  | *operations.ApplicationStopMetricsConfigUnion2*                                                  | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `name`                                                                                           | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `organizationId`                                                                                 | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `port`                                                                                           | *number*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `serverId`                                                                                       | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `serverStatus`                                                                                   | [operations.ApplicationStopServerStatus](../../models/operations/applicationstopserverstatus.md) | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `sshKeyId`                                                                                       | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `username`                                                                                       | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
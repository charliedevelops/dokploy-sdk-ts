# ApplicationStopServer

## Example Usage

```typescript
import { ApplicationStopServer } from "dokploy-sdk/models/operations";

let value: ApplicationStopServer = {
  serverId: "<id>",
  name: "<value>",
  description: "ultimately lively before phew reassemble pepper",
  ipAddress: "d318:ac2c:f78a:fea4:7fad:1d2f:de0a:e2a4",
  port: 1610.96,
  username: "Deangelo36",
  appName: "<value>",
  enableDockerCleanup: false,
  createdAt: "1714733600482",
  organizationId: "<id>",
  serverStatus: "active",
  command: "<value>",
  sshKeyId: "<id>",
  metricsConfig: {
    "key": "<value>",
    "key1": "<value>",
  },
};
```

## Fields

| Field                                                                                            | Type                                                                                             | Required                                                                                         | Description                                                                                      |
| ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ |
| `serverId`                                                                                       | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `name`                                                                                           | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `description`                                                                                    | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `ipAddress`                                                                                      | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `port`                                                                                           | *number*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `username`                                                                                       | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `appName`                                                                                        | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `enableDockerCleanup`                                                                            | *boolean*                                                                                        | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `createdAt`                                                                                      | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `organizationId`                                                                                 | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `serverStatus`                                                                                   | [operations.ApplicationStopServerStatus](../../models/operations/applicationstopserverstatus.md) | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `command`                                                                                        | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `sshKeyId`                                                                                       | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `metricsConfig`                                                                                  | *operations.ApplicationStopMetricsConfigUnion2*                                                  | :heavy_check_mark:                                                                               | N/A                                                                                              |
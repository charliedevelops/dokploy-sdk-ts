# PostgresSaveExternalPortServer

## Example Usage

```typescript
import { PostgresSaveExternalPortServer } from "dokploy-sdk/models/operations";

let value: PostgresSaveExternalPortServer = {
  serverId: "<id>",
  name: "<value>",
  description: "geez tooth whereas boastfully",
  ipAddress: "ed02:6bd2:2c96:90bf:eae7:43fe:acc3:db24",
  port: 3581.63,
  username: "Lucy.Wuckert",
  appName: "<value>",
  enableDockerCleanup: false,
  createdAt: "1734884982475",
  organizationId: "<id>",
  serverStatus: "inactive",
  command: "<value>",
  sshKeyId: "<id>",
  metricsConfig: "<value>",
};
```

## Fields

| Field                                                                                                              | Type                                                                                                               | Required                                                                                                           | Description                                                                                                        |
| ------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------ |
| `serverId`                                                                                                         | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `name`                                                                                                             | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `description`                                                                                                      | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `ipAddress`                                                                                                        | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `port`                                                                                                             | *number*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `username`                                                                                                         | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `appName`                                                                                                          | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `enableDockerCleanup`                                                                                              | *boolean*                                                                                                          | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `createdAt`                                                                                                        | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `organizationId`                                                                                                   | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `serverStatus`                                                                                                     | [operations.PostgresSaveExternalPortServerStatus](../../models/operations/postgressaveexternalportserverstatus.md) | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `command`                                                                                                          | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `sshKeyId`                                                                                                         | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `metricsConfig`                                                                                                    | *operations.PostgresSaveExternalPortMetricsConfigUnion2*                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
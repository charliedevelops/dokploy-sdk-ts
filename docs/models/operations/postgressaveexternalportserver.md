# PostgresSaveExternalPortServer

## Example Usage

```typescript
import { PostgresSaveExternalPortServer } from "dokploy-sdk/models/operations";

let value: PostgresSaveExternalPortServer = {
  appName: "<value>",
  command: "<value>",
  createdAt: "1708052053245",
  description:
    "successfully round sandbar urgently supposing oh excitedly deep amidst step",
  enableDockerCleanup: true,
  ipAddress: "21.161.135.128",
  metricsConfig: "<value>",
  name: "<value>",
  organizationId: "<id>",
  port: 384.3,
  serverId: "<id>",
  serverStatus: "active",
  sshKeyId: "<id>",
  username: "Haskell28",
};
```

## Fields

| Field                                                                                                              | Type                                                                                                               | Required                                                                                                           | Description                                                                                                        |
| ------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------ |
| `appName`                                                                                                          | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `command`                                                                                                          | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `createdAt`                                                                                                        | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `description`                                                                                                      | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `enableDockerCleanup`                                                                                              | *boolean*                                                                                                          | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `ipAddress`                                                                                                        | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `metricsConfig`                                                                                                    | *operations.PostgresSaveExternalPortMetricsConfigUnion2*                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `name`                                                                                                             | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `organizationId`                                                                                                   | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `port`                                                                                                             | *number*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `serverId`                                                                                                         | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `serverStatus`                                                                                                     | [operations.PostgresSaveExternalPortServerStatus](../../models/operations/postgressaveexternalportserverstatus.md) | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `sshKeyId`                                                                                                         | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `username`                                                                                                         | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
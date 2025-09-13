# ApplicationStartServer

## Example Usage

```typescript
import { ApplicationStartServer } from "dokploy-sdk/models/operations";

let value: ApplicationStartServer = {
  serverId: "<id>",
  name: "<value>",
  description:
    "forenenst shell farm swat lest midst lively wriggler incidentally",
  ipAddress: "be0d:606c:29e2:dca5:a97c:c993:fb7f:4d4a",
  port: 6722.1,
  username: "Jessyca.Swift",
  appName: "<value>",
  enableDockerCleanup: false,
  createdAt: "1729132039542",
  organizationId: "<id>",
  serverStatus: "inactive",
  command: "<value>",
  sshKeyId: "<id>",
  metricsConfig: "<value>",
};
```

## Fields

| Field                                                                                              | Type                                                                                               | Required                                                                                           | Description                                                                                        |
| -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| `serverId`                                                                                         | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `name`                                                                                             | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `description`                                                                                      | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `ipAddress`                                                                                        | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `port`                                                                                             | *number*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `username`                                                                                         | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `appName`                                                                                          | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `enableDockerCleanup`                                                                              | *boolean*                                                                                          | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `createdAt`                                                                                        | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `organizationId`                                                                                   | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `serverStatus`                                                                                     | [operations.ApplicationStartServerStatus](../../models/operations/applicationstartserverstatus.md) | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `command`                                                                                          | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `sshKeyId`                                                                                         | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `metricsConfig`                                                                                    | *operations.ApplicationStartMetricsConfigUnion2*                                                   | :heavy_check_mark:                                                                                 | N/A                                                                                                |
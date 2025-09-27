# ApplicationStartServer

## Example Usage

```typescript
import { ApplicationStartServer } from "dokploy-sdk/models/operations";

let value: ApplicationStartServer = {
  appName: "<value>",
  command: "<value>",
  createdAt: "1728744987032",
  description: "not stool about white roughly scruple frankly admonish",
  enableDockerCleanup: false,
  ipAddress: "ed47:dbe0:d606:c29e:2dca:5a97:cc99:3fb7",
  metricsConfig: {},
  name: "<value>",
  organizationId: "<id>",
  port: 5947.13,
  serverId: "<id>",
  serverStatus: "active",
  sshKeyId: "<id>",
  username: "Margarett5",
};
```

## Fields

| Field                                                                                              | Type                                                                                               | Required                                                                                           | Description                                                                                        |
| -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| `appName`                                                                                          | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `command`                                                                                          | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `createdAt`                                                                                        | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `description`                                                                                      | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `enableDockerCleanup`                                                                              | *boolean*                                                                                          | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `ipAddress`                                                                                        | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `metricsConfig`                                                                                    | *operations.ApplicationStartMetricsConfigUnion2*                                                   | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `name`                                                                                             | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `organizationId`                                                                                   | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `port`                                                                                             | *number*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `serverId`                                                                                         | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `serverStatus`                                                                                     | [operations.ApplicationStartServerStatus](../../models/operations/applicationstartserverstatus.md) | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `sshKeyId`                                                                                         | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `username`                                                                                         | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
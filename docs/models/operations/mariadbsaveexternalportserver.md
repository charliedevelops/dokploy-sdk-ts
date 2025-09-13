# MariadbSaveExternalPortServer

## Example Usage

```typescript
import { MariadbSaveExternalPortServer } from "dokploy-sdk/models/operations";

let value: MariadbSaveExternalPortServer = {
  appName: "<value>",
  command: "<value>",
  createdAt: "1728183038422",
  description: "hutch throughout which gee however past phooey brandish",
  enableDockerCleanup: false,
  ipAddress: "202.169.112.7",
  metricsConfig: [
    "<value 1>",
  ],
  name: "<value>",
  organizationId: "<id>",
  port: 3307.83,
  serverId: "<id>",
  serverStatus: "active",
  sshKeyId: "<id>",
  username: "Christelle_Schuppe49",
};
```

## Fields

| Field                                                                                                            | Type                                                                                                             | Required                                                                                                         | Description                                                                                                      |
| ---------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- |
| `appName`                                                                                                        | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `command`                                                                                                        | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `createdAt`                                                                                                      | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `description`                                                                                                    | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `enableDockerCleanup`                                                                                            | *boolean*                                                                                                        | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `ipAddress`                                                                                                      | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `metricsConfig`                                                                                                  | *operations.MariadbSaveExternalPortMetricsConfigUnion2*                                                          | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `name`                                                                                                           | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `organizationId`                                                                                                 | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `port`                                                                                                           | *number*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `serverId`                                                                                                       | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `serverStatus`                                                                                                   | [operations.MariadbSaveExternalPortServerStatus](../../models/operations/mariadbsaveexternalportserverstatus.md) | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `sshKeyId`                                                                                                       | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `username`                                                                                                       | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
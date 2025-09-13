# PostgresStopServer

## Example Usage

```typescript
import { PostgresStopServer } from "dokploy-sdk/models/operations";

let value: PostgresStopServer = {
  appName: "<value>",
  command: "<value>",
  createdAt: "1725352721825",
  description: "zowie kiss courtroom even gee cheerful pro so",
  enableDockerCleanup: false,
  ipAddress: "b3ac:77ad:bebc:9caf:4aac:bfdf:c91b:ea46",
  metricsConfig: {
    "key": "<value>",
  },
  name: "<value>",
  organizationId: "<id>",
  port: 8779.81,
  serverId: "<id>",
  serverStatus: "inactive",
  sshKeyId: "<id>",
  username: "Mellie86",
};
```

## Fields

| Field                                                                                      | Type                                                                                       | Required                                                                                   | Description                                                                                |
| ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ |
| `appName`                                                                                  | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `command`                                                                                  | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `createdAt`                                                                                | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `description`                                                                              | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `enableDockerCleanup`                                                                      | *boolean*                                                                                  | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `ipAddress`                                                                                | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `metricsConfig`                                                                            | *operations.PostgresStopMetricsConfigUnion2*                                               | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `name`                                                                                     | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `organizationId`                                                                           | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `port`                                                                                     | *number*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `serverId`                                                                                 | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `serverStatus`                                                                             | [operations.PostgresStopServerStatus](../../models/operations/postgresstopserverstatus.md) | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `sshKeyId`                                                                                 | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `username`                                                                                 | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
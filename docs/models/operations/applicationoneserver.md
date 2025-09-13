# ApplicationOneServer

## Example Usage

```typescript
import { ApplicationOneServer } from "dokploy-sdk/models/operations";

let value: ApplicationOneServer = {
  appName: "<value>",
  command: "<value>",
  createdAt: "1731050009889",
  description: "emergent inferior pick sailor cavernous exhausted ack gee",
  enableDockerCleanup: false,
  ipAddress: "9dc0:7ae2:7952:a4b6:4056:e840:2a77:3aa7",
  metricsConfig: {
    "key": "<value>",
    "key1": "<value>",
    "key2": "<value>",
  },
  name: "<value>",
  organizationId: "<id>",
  port: 6308.65,
  serverId: "<id>",
  serverStatus: "active",
  sshKeyId: "<id>",
  username: "Rosendo.Borer",
};
```

## Fields

| Field                                                                                          | Type                                                                                           | Required                                                                                       | Description                                                                                    |
| ---------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- |
| `appName`                                                                                      | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `command`                                                                                      | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `createdAt`                                                                                    | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `description`                                                                                  | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `enableDockerCleanup`                                                                          | *boolean*                                                                                      | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `ipAddress`                                                                                    | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `metricsConfig`                                                                                | *operations.ApplicationOneMetricsConfigUnion2*                                                 | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `name`                                                                                         | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `organizationId`                                                                               | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `port`                                                                                         | *number*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `serverId`                                                                                     | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `serverStatus`                                                                                 | [operations.ApplicationOneServerStatus](../../models/operations/applicationoneserverstatus.md) | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `sshKeyId`                                                                                     | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `username`                                                                                     | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
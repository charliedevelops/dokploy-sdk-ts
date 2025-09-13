# ApplicationDeleteServer

## Example Usage

```typescript
import { ApplicationDeleteServer } from "dokploy-sdk/models/operations";

let value: ApplicationDeleteServer = {
  serverId: "<id>",
  name: "<value>",
  description:
    "afterwards operating physically once institutionalize comfortable",
  ipAddress: "f6eb:d450:7be1:3fe4:a2dd:ab46:f3b4:ddf8",
  port: 2996.67,
  username: "Lonzo12",
  appName: "<value>",
  enableDockerCleanup: true,
  createdAt: "1709334402458",
  organizationId: "<id>",
  serverStatus: "active",
  command: "<value>",
  sshKeyId: "<id>",
  metricsConfig: {
    "key": "<value>",
    "key1": "<value>",
    "key2": "<value>",
  },
};
```

## Fields

| Field                                                                                                | Type                                                                                                 | Required                                                                                             | Description                                                                                          |
| ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- |
| `serverId`                                                                                           | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `name`                                                                                               | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `description`                                                                                        | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `ipAddress`                                                                                          | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `port`                                                                                               | *number*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `username`                                                                                           | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `appName`                                                                                            | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `enableDockerCleanup`                                                                                | *boolean*                                                                                            | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `createdAt`                                                                                          | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `organizationId`                                                                                     | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `serverStatus`                                                                                       | [operations.ApplicationDeleteServerStatus](../../models/operations/applicationdeleteserverstatus.md) | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `command`                                                                                            | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `sshKeyId`                                                                                           | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `metricsConfig`                                                                                      | *operations.ApplicationDeleteMetricsConfigUnion2*                                                    | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
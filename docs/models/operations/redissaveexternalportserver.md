# RedisSaveExternalPortServer

## Example Usage

```typescript
import { RedisSaveExternalPortServer } from "dokploy-sdk/models/operations";

let value: RedisSaveExternalPortServer = {
  serverId: "<id>",
  name: "<value>",
  description: "instantly destock machine browse",
  ipAddress: "bde9:ff80:acfe:d6cf:e2c0:6cbf:c1a8:c54b",
  port: 1443.38,
  username: "Tracey29",
  appName: "<value>",
  enableDockerCleanup: true,
  createdAt: "1722300202024",
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

| Field                                                                                                        | Type                                                                                                         | Required                                                                                                     | Description                                                                                                  |
| ------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------ |
| `serverId`                                                                                                   | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `name`                                                                                                       | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `description`                                                                                                | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `ipAddress`                                                                                                  | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `port`                                                                                                       | *number*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `username`                                                                                                   | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `appName`                                                                                                    | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `enableDockerCleanup`                                                                                        | *boolean*                                                                                                    | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `createdAt`                                                                                                  | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `organizationId`                                                                                             | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `serverStatus`                                                                                               | [operations.RedisSaveExternalPortServerStatus](../../models/operations/redissaveexternalportserverstatus.md) | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `command`                                                                                                    | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `sshKeyId`                                                                                                   | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `metricsConfig`                                                                                              | *operations.RedisSaveExternalPortMetricsConfigUnion2*                                                        | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
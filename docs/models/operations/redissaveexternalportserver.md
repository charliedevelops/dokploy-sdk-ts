# RedisSaveExternalPortServer

## Example Usage

```typescript
import { RedisSaveExternalPortServer } from "dokploy-sdk/models/operations";

let value: RedisSaveExternalPortServer = {
  appName: "<value>",
  command: "<value>",
  createdAt: "1715722345081",
  description: "fiercely limply heartache while impartial entrench inasmuch",
  enableDockerCleanup: false,
  ipAddress: "fc1a:8c54:b3eb:dd6b:6c03:fdda:9e0a:bc56",
  metricsConfig: 9212.67,
  name: "<value>",
  organizationId: "<id>",
  port: 7024.3,
  serverId: "<id>",
  serverStatus: "inactive",
  sshKeyId: "<id>",
  username: "Polly22",
};
```

## Fields

| Field                                                                                                        | Type                                                                                                         | Required                                                                                                     | Description                                                                                                  |
| ------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------ |
| `appName`                                                                                                    | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `command`                                                                                                    | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `createdAt`                                                                                                  | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `description`                                                                                                | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `enableDockerCleanup`                                                                                        | *boolean*                                                                                                    | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `ipAddress`                                                                                                  | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `metricsConfig`                                                                                              | *operations.RedisSaveExternalPortMetricsConfigUnion2*                                                        | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `name`                                                                                                       | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `organizationId`                                                                                             | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `port`                                                                                                       | *number*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `serverId`                                                                                                   | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `serverStatus`                                                                                               | [operations.RedisSaveExternalPortServerStatus](../../models/operations/redissaveexternalportserverstatus.md) | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `sshKeyId`                                                                                                   | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `username`                                                                                                   | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
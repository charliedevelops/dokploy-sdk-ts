# PostgresRemoveServer

## Example Usage

```typescript
import { PostgresRemoveServer } from "dokploy-sdk/models/operations";

let value: PostgresRemoveServer = {
  appName: "<value>",
  command: "<value>",
  createdAt: "1716531979995",
  description:
    "briskly once gray even hateful consequently yieldingly blah slight minus",
  enableDockerCleanup: false,
  ipAddress: "6.196.102.226",
  metricsConfig: {
    "key": "<value>",
    "key1": "<value>",
  },
  name: "<value>",
  organizationId: "<id>",
  port: 9699.39,
  serverId: "<id>",
  serverStatus: "active",
  sshKeyId: null,
  username: "Laurine.Pfeffer49",
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
| `metricsConfig`                                                                                | *operations.PostgresRemoveMetricsConfigUnion2*                                                 | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `name`                                                                                         | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `organizationId`                                                                               | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `port`                                                                                         | *number*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `serverId`                                                                                     | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `serverStatus`                                                                                 | [operations.PostgresRemoveServerStatus](../../models/operations/postgresremoveserverstatus.md) | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `sshKeyId`                                                                                     | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `username`                                                                                     | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
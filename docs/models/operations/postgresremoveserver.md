# PostgresRemoveServer

## Example Usage

```typescript
import { PostgresRemoveServer } from "dokploy-sdk/models/operations";

let value: PostgresRemoveServer = {
  serverId: "<id>",
  name: "<value>",
  description: "oh railway outfox know scented into allegation oof stable",
  ipAddress: "8cfc:87cf:60a8:dcff:40da:f3a6:6f37:f4e9",
  port: 4985.01,
  username: "Kellie_Mayert4",
  appName: "<value>",
  enableDockerCleanup: true,
  createdAt: "1715863618222",
  organizationId: "<id>",
  serverStatus: "active",
  command: "<value>",
  sshKeyId: "<id>",
  metricsConfig: "null",
};
```

## Fields

| Field                                                                                          | Type                                                                                           | Required                                                                                       | Description                                                                                    |
| ---------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- |
| `serverId`                                                                                     | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `name`                                                                                         | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `description`                                                                                  | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `ipAddress`                                                                                    | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `port`                                                                                         | *number*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `username`                                                                                     | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `appName`                                                                                      | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `enableDockerCleanup`                                                                          | *boolean*                                                                                      | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `createdAt`                                                                                    | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `organizationId`                                                                               | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `serverStatus`                                                                                 | [operations.PostgresRemoveServerStatus](../../models/operations/postgresremoveserverstatus.md) | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `command`                                                                                      | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `sshKeyId`                                                                                     | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `metricsConfig`                                                                                | *operations.PostgresRemoveMetricsConfigUnion2*                                                 | :heavy_check_mark:                                                                             | N/A                                                                                            |
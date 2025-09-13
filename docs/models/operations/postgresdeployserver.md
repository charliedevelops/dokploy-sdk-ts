# PostgresDeployServer

## Example Usage

```typescript
import { PostgresDeployServer } from "dokploy-sdk/models/operations";

let value: PostgresDeployServer = {
  serverId: "<id>",
  name: "<value>",
  description: "apud amend sparkling ski who",
  ipAddress: "252.169.248.208",
  port: 1481.98,
  username: "Verlie_Goyette18",
  appName: "<value>",
  enableDockerCleanup: true,
  createdAt: "1713069214056",
  organizationId: "<id>",
  serverStatus: "active",
  command: "<value>",
  sshKeyId: null,
  metricsConfig: {
    "key": "<value>",
  },
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
| `serverStatus`                                                                                 | [operations.PostgresDeployServerStatus](../../models/operations/postgresdeployserverstatus.md) | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `command`                                                                                      | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `sshKeyId`                                                                                     | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `metricsConfig`                                                                                | *operations.PostgresDeployMetricsConfigUnion2*                                                 | :heavy_check_mark:                                                                             | N/A                                                                                            |
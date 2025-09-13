# PostgresDeployServer

## Example Usage

```typescript
import { PostgresDeployServer } from "dokploy-sdk/models/operations";

let value: PostgresDeployServer = {
  appName: "<value>",
  command: "<value>",
  createdAt: "1732853070810",
  description: "shrilly slime enchanting slake inventory hence",
  enableDockerCleanup: true,
  ipAddress: "4636:50c9:bb97:19dd:aeef:e7ef:de17:a48d",
  metricsConfig: true,
  name: "<value>",
  organizationId: "<id>",
  port: 8267.55,
  serverId: "<id>",
  serverStatus: "active",
  sshKeyId: null,
  username: "Jude34",
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
| `metricsConfig`                                                                                | *operations.PostgresDeployMetricsConfigUnion2*                                                 | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `name`                                                                                         | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `organizationId`                                                                               | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `port`                                                                                         | *number*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `serverId`                                                                                     | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `serverStatus`                                                                                 | [operations.PostgresDeployServerStatus](../../models/operations/postgresdeployserverstatus.md) | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `sshKeyId`                                                                                     | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `username`                                                                                     | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
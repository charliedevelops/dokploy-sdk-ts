# MongoSaveExternalPortServer

## Example Usage

```typescript
import { MongoSaveExternalPortServer } from "dokploy-sdk/models/operations";

let value: MongoSaveExternalPortServer = {
  appName: "<value>",
  command: "<value>",
  createdAt: "1734514903038",
  description: "jubilant following underneath versus",
  enableDockerCleanup: false,
  ipAddress: "e57a:e8e6:62b1:4ebb:2f77:cf4d:2d1f:cb2c",
  metricsConfig: {},
  name: "<value>",
  organizationId: "<id>",
  port: 4187.69,
  serverId: "<id>",
  serverStatus: "active",
  sshKeyId: "<id>",
  username: "Columbus_Ward86",
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
| `metricsConfig`                                                                                              | *operations.MongoSaveExternalPortMetricsConfigUnion2*                                                        | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `name`                                                                                                       | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `organizationId`                                                                                             | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `port`                                                                                                       | *number*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `serverId`                                                                                                   | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `serverStatus`                                                                                               | [operations.MongoSaveExternalPortServerStatus](../../models/operations/mongosaveexternalportserverstatus.md) | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `sshKeyId`                                                                                                   | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `username`                                                                                                   | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
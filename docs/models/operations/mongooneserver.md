# MongoOneServer

## Example Usage

```typescript
import { MongoOneServer } from "dokploy-sdk/models/operations";

let value: MongoOneServer = {
  serverId: "<id>",
  name: "<value>",
  description: "hydrolyze irritably porter grounded if pfft",
  ipAddress: "cff0:2bbf:827c:14a9:cedf:4f76:54ae:2048",
  port: 1981.06,
  username: "Marian.Sauer41",
  appName: "<value>",
  enableDockerCleanup: false,
  createdAt: "1709463125457",
  organizationId: "<id>",
  serverStatus: "inactive",
  command: "<value>",
  sshKeyId: "<id>",
  metricsConfig: {},
};
```

## Fields

| Field                                                                              | Type                                                                               | Required                                                                           | Description                                                                        |
| ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- |
| `serverId`                                                                         | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `name`                                                                             | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `description`                                                                      | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `ipAddress`                                                                        | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `port`                                                                             | *number*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `username`                                                                         | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `appName`                                                                          | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `enableDockerCleanup`                                                              | *boolean*                                                                          | :heavy_check_mark:                                                                 | N/A                                                                                |
| `createdAt`                                                                        | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `organizationId`                                                                   | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `serverStatus`                                                                     | [operations.MongoOneServerStatus](../../models/operations/mongooneserverstatus.md) | :heavy_check_mark:                                                                 | N/A                                                                                |
| `command`                                                                          | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `sshKeyId`                                                                         | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `metricsConfig`                                                                    | *operations.MongoOneMetricsConfigUnion2*                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
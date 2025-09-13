# MongoRemoveServer

## Example Usage

```typescript
import { MongoRemoveServer } from "dokploy-sdk/models/operations";

let value: MongoRemoveServer = {
  serverId: "<id>",
  name: "<value>",
  description: "equate sandbar correctly embalm drat disapprove frankly",
  ipAddress: "85.163.92.134",
  port: 8958.04,
  username: "Jerrod.Beier",
  appName: "<value>",
  enableDockerCleanup: true,
  createdAt: "1721454199871",
  organizationId: "<id>",
  serverStatus: "active",
  command: "<value>",
  sshKeyId: null,
  metricsConfig: [
    "<value 1>",
    "<value 2>",
    "<value 3>",
  ],
};
```

## Fields

| Field                                                                                    | Type                                                                                     | Required                                                                                 | Description                                                                              |
| ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- |
| `serverId`                                                                               | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `name`                                                                                   | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `description`                                                                            | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `ipAddress`                                                                              | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `port`                                                                                   | *number*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `username`                                                                               | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `appName`                                                                                | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `enableDockerCleanup`                                                                    | *boolean*                                                                                | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `createdAt`                                                                              | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `organizationId`                                                                         | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `serverStatus`                                                                           | [operations.MongoRemoveServerStatus](../../models/operations/mongoremoveserverstatus.md) | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `command`                                                                                | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `sshKeyId`                                                                               | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `metricsConfig`                                                                          | *operations.MongoRemoveMetricsConfigUnion2*                                              | :heavy_check_mark:                                                                       | N/A                                                                                      |
# MongoStopServer

## Example Usage

```typescript
import { MongoStopServer } from "dokploy-sdk/models/operations";

let value: MongoStopServer = {
  appName: "<value>",
  command: "<value>",
  createdAt: "1713337644387",
  description: null,
  enableDockerCleanup: true,
  ipAddress: "644f:7d91:19f7:95ab:1efb:61c4:d0c4:bd3a",
  metricsConfig: 5770.61,
  name: "<value>",
  organizationId: "<id>",
  port: 3269.07,
  serverId: "<id>",
  serverStatus: "active",
  sshKeyId: "<id>",
  username: "Alexandre.Bogisich61",
};
```

## Fields

| Field                                                                                | Type                                                                                 | Required                                                                             | Description                                                                          |
| ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ |
| `appName`                                                                            | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `command`                                                                            | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `createdAt`                                                                          | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `description`                                                                        | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `enableDockerCleanup`                                                                | *boolean*                                                                            | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `ipAddress`                                                                          | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `metricsConfig`                                                                      | *operations.MongoStopMetricsConfigUnion2*                                            | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `name`                                                                               | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `organizationId`                                                                     | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `port`                                                                               | *number*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `serverId`                                                                           | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `serverStatus`                                                                       | [operations.MongoStopServerStatus](../../models/operations/mongostopserverstatus.md) | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `sshKeyId`                                                                           | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `username`                                                                           | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
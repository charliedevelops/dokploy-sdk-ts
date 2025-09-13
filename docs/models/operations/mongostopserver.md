# MongoStopServer

## Example Usage

```typescript
import { MongoStopServer } from "dokploy-sdk/models/operations";

let value: MongoStopServer = {
  serverId: "<id>",
  name: "<value>",
  description: "inasmuch brr redact",
  ipAddress: "61c4:d0c4:bd3a:69c7:5e01:15d7:8bc1:5a65",
  port: 1679.07,
  username: "Colin69",
  appName: "<value>",
  enableDockerCleanup: false,
  createdAt: "1730417078169",
  organizationId: "<id>",
  serverStatus: "active",
  command: "<value>",
  sshKeyId: null,
  metricsConfig: [
    "<value 1>",
    "<value 2>",
  ],
};
```

## Fields

| Field                                                                                | Type                                                                                 | Required                                                                             | Description                                                                          |
| ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ |
| `serverId`                                                                           | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `name`                                                                               | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `description`                                                                        | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `ipAddress`                                                                          | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `port`                                                                               | *number*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `username`                                                                           | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `appName`                                                                            | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `enableDockerCleanup`                                                                | *boolean*                                                                            | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `createdAt`                                                                          | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `organizationId`                                                                     | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `serverStatus`                                                                       | [operations.MongoStopServerStatus](../../models/operations/mongostopserverstatus.md) | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `command`                                                                            | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `sshKeyId`                                                                           | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `metricsConfig`                                                                      | *operations.MongoStopMetricsConfigUnion2*                                            | :heavy_check_mark:                                                                   | N/A                                                                                  |
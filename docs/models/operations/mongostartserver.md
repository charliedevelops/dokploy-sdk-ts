# MongoStartServer

## Example Usage

```typescript
import { MongoStartServer } from "dokploy-sdk/models/operations";

let value: MongoStartServer = {
  serverId: "<id>",
  name: "<value>",
  description: "swing list oily primary",
  ipAddress: "7bf4:9afa:9089:a8af:badc:4a95:291a:08ae",
  port: 9969.73,
  username: "Bernita.Conn",
  appName: "<value>",
  enableDockerCleanup: false,
  createdAt: "1706282107364",
  organizationId: "<id>",
  serverStatus: "inactive",
  command: "<value>",
  sshKeyId: "<id>",
  metricsConfig: [
    "<value 1>",
  ],
};
```

## Fields

| Field                                                                                  | Type                                                                                   | Required                                                                               | Description                                                                            |
| -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- |
| `serverId`                                                                             | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `name`                                                                                 | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `description`                                                                          | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `ipAddress`                                                                            | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `port`                                                                                 | *number*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `username`                                                                             | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `appName`                                                                              | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `enableDockerCleanup`                                                                  | *boolean*                                                                              | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `createdAt`                                                                            | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `organizationId`                                                                       | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `serverStatus`                                                                         | [operations.MongoStartServerStatus](../../models/operations/mongostartserverstatus.md) | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `command`                                                                              | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `sshKeyId`                                                                             | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `metricsConfig`                                                                        | *operations.MongoStartMetricsConfigUnion2*                                             | :heavy_check_mark:                                                                     | N/A                                                                                    |
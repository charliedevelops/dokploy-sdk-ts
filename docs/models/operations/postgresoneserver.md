# PostgresOneServer

## Example Usage

```typescript
import { PostgresOneServer } from "dokploy-sdk/models/operations";

let value: PostgresOneServer = {
  serverId: "<id>",
  name: "<value>",
  description:
    "boohoo haversack whoever lest defendant hm speedily furthermore astride accessorise",
  ipAddress: "b3fe:cad2:52b1:7ccb:623b:ef8f:5abf:d47a",
  port: 287.49,
  username: "Ken_Rempel76",
  appName: "<value>",
  enableDockerCleanup: true,
  createdAt: "1720309093491",
  organizationId: "<id>",
  serverStatus: "inactive",
  command: "<value>",
  sshKeyId: "<id>",
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
| `serverStatus`                                                                           | [operations.PostgresOneServerStatus](../../models/operations/postgresoneserverstatus.md) | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `command`                                                                                | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `sshKeyId`                                                                               | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `metricsConfig`                                                                          | *operations.PostgresOneMetricsConfigUnion2*                                              | :heavy_check_mark:                                                                       | N/A                                                                                      |
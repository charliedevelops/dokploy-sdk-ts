# MariadbDeployServer

## Example Usage

```typescript
import { MariadbDeployServer } from "dokploy-sdk/models/operations";

let value: MariadbDeployServer = {
  appName: "<value>",
  command: "<value>",
  createdAt: "1724829040045",
  description: "qua haze broadside",
  enableDockerCleanup: true,
  ipAddress: "070b:c36e:09a4:5d39:95ff:faeb:2508:8d1f",
  metricsConfig: "null",
  name: "<value>",
  organizationId: "<id>",
  port: 8226.42,
  serverId: "<id>",
  serverStatus: "active",
  sshKeyId: "<id>",
  username: "Bernard53",
};
```

## Fields

| Field                                                                                        | Type                                                                                         | Required                                                                                     | Description                                                                                  |
| -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- |
| `appName`                                                                                    | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `command`                                                                                    | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `createdAt`                                                                                  | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `description`                                                                                | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `enableDockerCleanup`                                                                        | *boolean*                                                                                    | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `ipAddress`                                                                                  | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `metricsConfig`                                                                              | *operations.MariadbDeployMetricsConfigUnion2*                                                | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `name`                                                                                       | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `organizationId`                                                                             | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `port`                                                                                       | *number*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `serverId`                                                                                   | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `serverStatus`                                                                               | [operations.MariadbDeployServerStatus](../../models/operations/mariadbdeployserverstatus.md) | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `sshKeyId`                                                                                   | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `username`                                                                                   | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
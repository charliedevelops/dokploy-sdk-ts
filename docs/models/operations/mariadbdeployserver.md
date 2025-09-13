# MariadbDeployServer

## Example Usage

```typescript
import { MariadbDeployServer } from "dokploy-sdk/models/operations";

let value: MariadbDeployServer = {
  serverId: "<id>",
  name: "<value>",
  description: "yearly low throughout lay insolence how compassionate",
  ipAddress: "8.95.98.225",
  port: 584.33,
  username: "Martina45",
  appName: "<value>",
  enableDockerCleanup: true,
  createdAt: "1730109085369",
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

| Field                                                                                        | Type                                                                                         | Required                                                                                     | Description                                                                                  |
| -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- |
| `serverId`                                                                                   | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `name`                                                                                       | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `description`                                                                                | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `ipAddress`                                                                                  | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `port`                                                                                       | *number*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `username`                                                                                   | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `appName`                                                                                    | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `enableDockerCleanup`                                                                        | *boolean*                                                                                    | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `createdAt`                                                                                  | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `organizationId`                                                                             | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `serverStatus`                                                                               | [operations.MariadbDeployServerStatus](../../models/operations/mariadbdeployserverstatus.md) | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `command`                                                                                    | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `sshKeyId`                                                                                   | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `metricsConfig`                                                                              | *operations.MariadbDeployMetricsConfigUnion2*                                                | :heavy_check_mark:                                                                           | N/A                                                                                          |
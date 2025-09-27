# MariadbRemoveServer

## Example Usage

```typescript
import { MariadbRemoveServer } from "dokploy-sdk/models/operations";

let value: MariadbRemoveServer = {
  appName: "<value>",
  command: "<value>",
  createdAt: "1729315080465",
  description: "excepting meanwhile amount provided",
  enableDockerCleanup: false,
  ipAddress: "7b5a:9dad:8fe3:cd7b:e9ed:8cb4:cdc0:6bcd",
  metricsConfig: {
    "key": "<value>",
    "key1": "<value>",
  },
  name: "<value>",
  organizationId: "<id>",
  port: 9628.83,
  serverId: "<id>",
  serverStatus: "inactive",
  sshKeyId: null,
  username: "Bonnie_Towne",
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
| `metricsConfig`                                                                              | *operations.MariadbRemoveMetricsConfigUnion2*                                                | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `name`                                                                                       | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `organizationId`                                                                             | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `port`                                                                                       | *number*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `serverId`                                                                                   | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `serverStatus`                                                                               | [operations.MariadbRemoveServerStatus](../../models/operations/mariadbremoveserverstatus.md) | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `sshKeyId`                                                                                   | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `username`                                                                                   | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
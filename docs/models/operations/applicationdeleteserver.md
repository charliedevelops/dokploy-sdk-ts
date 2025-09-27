# ApplicationDeleteServer

## Example Usage

```typescript
import { ApplicationDeleteServer } from "dokploy-sdk/models/operations";

let value: ApplicationDeleteServer = {
  appName: "<value>",
  command: "<value>",
  createdAt: "1730832379827",
  description: "very why unless",
  enableDockerCleanup: true,
  ipAddress: "92.31.152.126",
  metricsConfig: "null",
  name: "<value>",
  organizationId: "<id>",
  port: 7101.47,
  serverId: "<id>",
  serverStatus: "inactive",
  sshKeyId: "<id>",
  username: "Kenneth20",
};
```

## Fields

| Field                                                                                                | Type                                                                                                 | Required                                                                                             | Description                                                                                          |
| ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- |
| `appName`                                                                                            | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `command`                                                                                            | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `createdAt`                                                                                          | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `description`                                                                                        | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `enableDockerCleanup`                                                                                | *boolean*                                                                                            | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `ipAddress`                                                                                          | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `metricsConfig`                                                                                      | *operations.ApplicationDeleteMetricsConfigUnion2*                                                    | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `name`                                                                                               | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `organizationId`                                                                                     | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `port`                                                                                               | *number*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `serverId`                                                                                           | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `serverStatus`                                                                                       | [operations.ApplicationDeleteServerStatus](../../models/operations/applicationdeleteserverstatus.md) | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `sshKeyId`                                                                                           | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `username`                                                                                           | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
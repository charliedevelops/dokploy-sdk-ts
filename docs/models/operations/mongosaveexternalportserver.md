# MongoSaveExternalPortServer

## Example Usage

```typescript
import { MongoSaveExternalPortServer } from "dokploy-sdk/models/operations";

let value: MongoSaveExternalPortServer = {
  serverId: "<id>",
  name: "<value>",
  description:
    "whether since hence pfft sheepishly uh-huh until whoa skyscraper",
  ipAddress: "492e:4fed:d34d:defd:d3e7:b284:2139:b8b2",
  port: 4463.24,
  username: "Valentina2",
  appName: "<value>",
  enableDockerCleanup: true,
  createdAt: "1709192405231",
  organizationId: "<id>",
  serverStatus: "active",
  command: "<value>",
  sshKeyId: "<id>",
  metricsConfig: [],
};
```

## Fields

| Field                                                                                                        | Type                                                                                                         | Required                                                                                                     | Description                                                                                                  |
| ------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------ |
| `serverId`                                                                                                   | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `name`                                                                                                       | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `description`                                                                                                | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `ipAddress`                                                                                                  | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `port`                                                                                                       | *number*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `username`                                                                                                   | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `appName`                                                                                                    | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `enableDockerCleanup`                                                                                        | *boolean*                                                                                                    | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `createdAt`                                                                                                  | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `organizationId`                                                                                             | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `serverStatus`                                                                                               | [operations.MongoSaveExternalPortServerStatus](../../models/operations/mongosaveexternalportserverstatus.md) | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `command`                                                                                                    | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `sshKeyId`                                                                                                   | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `metricsConfig`                                                                                              | *operations.MongoSaveExternalPortMetricsConfigUnion2*                                                        | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
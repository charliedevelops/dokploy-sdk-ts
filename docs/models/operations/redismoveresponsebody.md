# RedisMoveResponseBody

Successful response

## Example Usage

```typescript
import { RedisMoveResponseBody } from "dokploy-sdk/models/operations";

let value: RedisMoveResponseBody = {
  redisId: "<id>",
  name: "<value>",
  appName: "<value>",
  description: "drag fooey apud save oh salty",
  databasePassword: "<value>",
  dockerImage: "<value>",
  command: "<value>",
  env: "<value>",
  memoryReservation: "<value>",
  memoryLimit: "<value>",
  cpuReservation: "<value>",
  cpuLimit: "<value>",
  externalPort: 5012.46,
  createdAt: "1711354000040",
  applicationStatus: "running",
  healthCheckSwarm: {},
  restartPolicySwarm: {},
  placementSwarm: {},
  updateConfigSwarm: {
    parallelism: 1552.41,
    order: "<value>",
  },
  rollbackConfigSwarm: {
    parallelism: 892.21,
    order: "<value>",
  },
  modeSwarm: null,
  labelsSwarm: {
    "key": "<value>",
    "key1": "<value>",
  },
  networkSwarm: [],
  replicas: 439.14,
  environmentId: "<id>",
  serverId: "<id>",
};
```

## Fields

| Field                                                                                              | Type                                                                                               | Required                                                                                           | Description                                                                                        |
| -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| `redisId`                                                                                          | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `name`                                                                                             | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `appName`                                                                                          | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `description`                                                                                      | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `databasePassword`                                                                                 | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `dockerImage`                                                                                      | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `command`                                                                                          | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `env`                                                                                              | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `memoryReservation`                                                                                | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `memoryLimit`                                                                                      | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `cpuReservation`                                                                                   | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `cpuLimit`                                                                                         | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `externalPort`                                                                                     | *number*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `createdAt`                                                                                        | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `applicationStatus`                                                                                | [operations.RedisMoveApplicationStatus](../../models/operations/redismoveapplicationstatus.md)     | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `healthCheckSwarm`                                                                                 | [operations.RedisMoveHealthCheckSwarm](../../models/operations/redismovehealthcheckswarm.md)       | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `restartPolicySwarm`                                                                               | [operations.RedisMoveRestartPolicySwarm](../../models/operations/redismoverestartpolicyswarm.md)   | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `placementSwarm`                                                                                   | [operations.RedisMovePlacementSwarm](../../models/operations/redismoveplacementswarm.md)           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `updateConfigSwarm`                                                                                | [operations.RedisMoveUpdateConfigSwarm](../../models/operations/redismoveupdateconfigswarm.md)     | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `rollbackConfigSwarm`                                                                              | [operations.RedisMoveRollbackConfigSwarm](../../models/operations/redismoverollbackconfigswarm.md) | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `modeSwarm`                                                                                        | [operations.RedisMoveModeSwarm](../../models/operations/redismovemodeswarm.md)                     | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `labelsSwarm`                                                                                      | Record<string, *string*>                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `networkSwarm`                                                                                     | [operations.RedisMoveNetworkSwarm](../../models/operations/redismovenetworkswarm.md)[]             | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `replicas`                                                                                         | *number*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `environmentId`                                                                                    | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `serverId`                                                                                         | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
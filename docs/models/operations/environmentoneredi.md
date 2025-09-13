# EnvironmentOneRedi

## Example Usage

```typescript
import { EnvironmentOneRedi } from "dokploy-sdk/models/operations";

let value: EnvironmentOneRedi = {
  appName: "<value>",
  applicationStatus: "done",
  command: "<value>",
  cpuLimit: "<value>",
  cpuReservation: "<value>",
  createdAt: "1719307855141",
  databasePassword: "<value>",
  description: "fooey um shyly phew what mmm ugh carelessly except",
  dockerImage: "<value>",
  env: "<value>",
  environmentId: "<id>",
  externalPort: 8226.83,
  healthCheckSwarm: {
    "key": "<value>",
  },
  labelsSwarm: false,
  memoryLimit: "<value>",
  memoryReservation: "<value>",
  modeSwarm: 1124.59,
  name: "<value>",
  networkSwarm: 2262.97,
  placementSwarm: 3349.8,
  redisId: "<id>",
  replicas: 7851.51,
  restartPolicySwarm: {
    "key": "<value>",
    "key1": "<value>",
    "key2": "<value>",
  },
  rollbackConfigSwarm: "null",
  serverId: null,
  updateConfigSwarm: 3.73,
};
```

## Fields

| Field                                                                                                            | Type                                                                                                             | Required                                                                                                         | Description                                                                                                      |
| ---------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- |
| `appName`                                                                                                        | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `applicationStatus`                                                                                              | [operations.EnvironmentOneRediApplicationStatus](../../models/operations/environmentonerediapplicationstatus.md) | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `command`                                                                                                        | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `cpuLimit`                                                                                                       | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `cpuReservation`                                                                                                 | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `createdAt`                                                                                                      | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `databasePassword`                                                                                               | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `description`                                                                                                    | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `dockerImage`                                                                                                    | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `env`                                                                                                            | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `environmentId`                                                                                                  | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `externalPort`                                                                                                   | *number*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `healthCheckSwarm`                                                                                               | *operations.EnvironmentOneRediHealthCheckSwarmUnion*                                                             | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `labelsSwarm`                                                                                                    | *operations.EnvironmentOneRediLabelsSwarmUnion*                                                                  | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `memoryLimit`                                                                                                    | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `memoryReservation`                                                                                              | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `modeSwarm`                                                                                                      | *operations.EnvironmentOneRediModeSwarmUnion*                                                                    | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `name`                                                                                                           | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `networkSwarm`                                                                                                   | *operations.EnvironmentOneRediNetworkSwarmUnion*                                                                 | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `placementSwarm`                                                                                                 | *operations.EnvironmentOneRediPlacementSwarmUnion*                                                               | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `redisId`                                                                                                        | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `replicas`                                                                                                       | *number*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `restartPolicySwarm`                                                                                             | *operations.EnvironmentOneRediRestartPolicySwarmUnion*                                                           | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `rollbackConfigSwarm`                                                                                            | *operations.EnvironmentOneRediRollbackConfigSwarmUnion*                                                          | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `serverId`                                                                                                       | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `updateConfigSwarm`                                                                                              | *operations.EnvironmentOneRediUpdateConfigSwarmUnion*                                                            | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
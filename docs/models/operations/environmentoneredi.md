# EnvironmentOneRedi

## Example Usage

```typescript
import { EnvironmentOneRedi } from "dokploy-sdk/models/operations";

let value: EnvironmentOneRedi = {
  redisId: "<id>",
  name: "<value>",
  appName: "<value>",
  description: "thorough intensely into at ha troubled following ick yowza",
  databasePassword: "<value>",
  dockerImage: "<value>",
  command: "<value>",
  env: "<value>",
  memoryReservation: "<value>",
  memoryLimit: "<value>",
  cpuReservation: "<value>",
  cpuLimit: "<value>",
  externalPort: 8226.83,
  createdAt: "1708983615035",
  applicationStatus: "error",
  healthCheckSwarm: "<value>",
  restartPolicySwarm: {
    "key": "<value>",
    "key1": "<value>",
    "key2": "<value>",
  },
  placementSwarm: "<value>",
  updateConfigSwarm: "null",
  rollbackConfigSwarm: [],
  modeSwarm: 3349.8,
  labelsSwarm: {
    "key": "<value>",
    "key1": "<value>",
    "key2": "<value>",
  },
  networkSwarm: [],
  replicas: 9728.09,
  environmentId: "<id>",
  serverId: null,
};
```

## Fields

| Field                                                                                                            | Type                                                                                                             | Required                                                                                                         | Description                                                                                                      |
| ---------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- |
| `redisId`                                                                                                        | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `name`                                                                                                           | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `appName`                                                                                                        | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `description`                                                                                                    | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `databasePassword`                                                                                               | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `dockerImage`                                                                                                    | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `command`                                                                                                        | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `env`                                                                                                            | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `memoryReservation`                                                                                              | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `memoryLimit`                                                                                                    | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `cpuReservation`                                                                                                 | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `cpuLimit`                                                                                                       | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `externalPort`                                                                                                   | *number*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `createdAt`                                                                                                      | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `applicationStatus`                                                                                              | [operations.EnvironmentOneRediApplicationStatus](../../models/operations/environmentonerediapplicationstatus.md) | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `healthCheckSwarm`                                                                                               | *operations.EnvironmentOneRediHealthCheckSwarmUnion*                                                             | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `restartPolicySwarm`                                                                                             | *operations.EnvironmentOneRediRestartPolicySwarmUnion*                                                           | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `placementSwarm`                                                                                                 | *operations.EnvironmentOneRediPlacementSwarmUnion*                                                               | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `updateConfigSwarm`                                                                                              | *operations.EnvironmentOneRediUpdateConfigSwarmUnion*                                                            | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `rollbackConfigSwarm`                                                                                            | *operations.EnvironmentOneRediRollbackConfigSwarmUnion*                                                          | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `modeSwarm`                                                                                                      | *operations.EnvironmentOneRediModeSwarmUnion*                                                                    | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `labelsSwarm`                                                                                                    | *operations.EnvironmentOneRediLabelsSwarmUnion*                                                                  | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `networkSwarm`                                                                                                   | *operations.EnvironmentOneRediNetworkSwarmUnion*                                                                 | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `replicas`                                                                                                       | *number*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `environmentId`                                                                                                  | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `serverId`                                                                                                       | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
# EnvironmentByProjectIdRedi

## Example Usage

```typescript
import { EnvironmentByProjectIdRedi } from "dokploy-sdk/models/operations";

let value: EnvironmentByProjectIdRedi = {
  redisId: "<id>",
  name: "<value>",
  appName: "<value>",
  description: "upward bookend forswear lest up ah throughout brr",
  databasePassword: "<value>",
  dockerImage: "<value>",
  command: "<value>",
  env: null,
  memoryReservation: "<value>",
  memoryLimit: "<value>",
  cpuReservation: "<value>",
  cpuLimit: "<value>",
  externalPort: 438.03,
  createdAt: "1721248652643",
  applicationStatus: "running",
  healthCheckSwarm: {
    "key": "<value>",
    "key1": "<value>",
  },
  restartPolicySwarm: 1529.45,
  placementSwarm: "<value>",
  updateConfigSwarm: {
    "key": "<value>",
  },
  rollbackConfigSwarm: true,
  modeSwarm: {
    "key": "<value>",
    "key1": "<value>",
    "key2": "<value>",
  },
  labelsSwarm: [
    "<value 1>",
  ],
  networkSwarm: {
    "key": "<value>",
    "key1": "<value>",
    "key2": "<value>",
  },
  replicas: 1504.27,
  environmentId: "<id>",
  serverId: "<id>",
};
```

## Fields

| Field                                                                                                                            | Type                                                                                                                             | Required                                                                                                                         | Description                                                                                                                      |
| -------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------- |
| `redisId`                                                                                                                        | *string*                                                                                                                         | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `name`                                                                                                                           | *string*                                                                                                                         | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `appName`                                                                                                                        | *string*                                                                                                                         | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `description`                                                                                                                    | *string*                                                                                                                         | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `databasePassword`                                                                                                               | *string*                                                                                                                         | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `dockerImage`                                                                                                                    | *string*                                                                                                                         | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `command`                                                                                                                        | *string*                                                                                                                         | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `env`                                                                                                                            | *string*                                                                                                                         | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `memoryReservation`                                                                                                              | *string*                                                                                                                         | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `memoryLimit`                                                                                                                    | *string*                                                                                                                         | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `cpuReservation`                                                                                                                 | *string*                                                                                                                         | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `cpuLimit`                                                                                                                       | *string*                                                                                                                         | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `externalPort`                                                                                                                   | *number*                                                                                                                         | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `createdAt`                                                                                                                      | *string*                                                                                                                         | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `applicationStatus`                                                                                                              | [operations.EnvironmentByProjectIdRediApplicationStatus](../../models/operations/environmentbyprojectidrediapplicationstatus.md) | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `healthCheckSwarm`                                                                                                               | *operations.EnvironmentByProjectIdRediHealthCheckSwarmUnion*                                                                     | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `restartPolicySwarm`                                                                                                             | *operations.EnvironmentByProjectIdRediRestartPolicySwarmUnion*                                                                   | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `placementSwarm`                                                                                                                 | *operations.EnvironmentByProjectIdRediPlacementSwarmUnion*                                                                       | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `updateConfigSwarm`                                                                                                              | *operations.EnvironmentByProjectIdRediUpdateConfigSwarmUnion*                                                                    | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `rollbackConfigSwarm`                                                                                                            | *operations.EnvironmentByProjectIdRediRollbackConfigSwarmUnion*                                                                  | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `modeSwarm`                                                                                                                      | *operations.EnvironmentByProjectIdRediModeSwarmUnion*                                                                            | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `labelsSwarm`                                                                                                                    | *operations.EnvironmentByProjectIdRediLabelsSwarmUnion*                                                                          | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `networkSwarm`                                                                                                                   | *operations.EnvironmentByProjectIdRediNetworkSwarmUnion*                                                                         | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `replicas`                                                                                                                       | *number*                                                                                                                         | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `environmentId`                                                                                                                  | *string*                                                                                                                         | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `serverId`                                                                                                                       | *string*                                                                                                                         | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
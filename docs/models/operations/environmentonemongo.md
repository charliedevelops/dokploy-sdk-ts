# EnvironmentOneMongo

## Example Usage

```typescript
import { EnvironmentOneMongo } from "dokploy-sdk/models/operations";

let value: EnvironmentOneMongo = {
  mongoId: "<id>",
  name: "<value>",
  appName: "<value>",
  description: "shrilly dress compassionate instead",
  databaseUser: "<value>",
  databasePassword: "<value>",
  dockerImage: "<value>",
  command: "<value>",
  env: "<value>",
  memoryReservation: "<value>",
  memoryLimit: "<value>",
  cpuReservation: "<value>",
  cpuLimit: "<value>",
  externalPort: 2146.5,
  applicationStatus: "running",
  healthCheckSwarm: false,
  restartPolicySwarm: {
    "key": "<value>",
    "key1": "<value>",
    "key2": "<value>",
  },
  placementSwarm: "null",
  updateConfigSwarm: {
    "key": "<value>",
    "key1": "<value>",
  },
  rollbackConfigSwarm: {
    "key": "<value>",
    "key1": "<value>",
    "key2": "<value>",
  },
  modeSwarm: [],
  labelsSwarm: [
    "<value 1>",
    "<value 2>",
  ],
  networkSwarm: "null",
  replicas: 6142.54,
  createdAt: "1729242566311",
  environmentId: "<id>",
  serverId: "<id>",
  replicaSets: false,
};
```

## Fields

| Field                                                                                                              | Type                                                                                                               | Required                                                                                                           | Description                                                                                                        |
| ------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------ |
| `mongoId`                                                                                                          | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `name`                                                                                                             | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `appName`                                                                                                          | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `description`                                                                                                      | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `databaseUser`                                                                                                     | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `databasePassword`                                                                                                 | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `dockerImage`                                                                                                      | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `command`                                                                                                          | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `env`                                                                                                              | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `memoryReservation`                                                                                                | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `memoryLimit`                                                                                                      | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `cpuReservation`                                                                                                   | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `cpuLimit`                                                                                                         | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `externalPort`                                                                                                     | *number*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `applicationStatus`                                                                                                | [operations.EnvironmentOneMongoApplicationStatus](../../models/operations/environmentonemongoapplicationstatus.md) | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `healthCheckSwarm`                                                                                                 | *operations.EnvironmentOneMongoHealthCheckSwarmUnion*                                                              | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `restartPolicySwarm`                                                                                               | *operations.EnvironmentOneMongoRestartPolicySwarmUnion*                                                            | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `placementSwarm`                                                                                                   | *operations.EnvironmentOneMongoPlacementSwarmUnion*                                                                | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `updateConfigSwarm`                                                                                                | *operations.EnvironmentOneMongoUpdateConfigSwarmUnion*                                                             | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `rollbackConfigSwarm`                                                                                              | *operations.EnvironmentOneMongoRollbackConfigSwarmUnion*                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `modeSwarm`                                                                                                        | *operations.EnvironmentOneMongoModeSwarmUnion*                                                                     | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `labelsSwarm`                                                                                                      | *operations.EnvironmentOneMongoLabelsSwarmUnion*                                                                   | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `networkSwarm`                                                                                                     | *operations.EnvironmentOneMongoNetworkSwarmUnion*                                                                  | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `replicas`                                                                                                         | *number*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `createdAt`                                                                                                        | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `environmentId`                                                                                                    | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `serverId`                                                                                                         | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `replicaSets`                                                                                                      | *boolean*                                                                                                          | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
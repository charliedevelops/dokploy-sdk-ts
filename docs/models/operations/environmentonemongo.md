# EnvironmentOneMongo

## Example Usage

```typescript
import { EnvironmentOneMongo } from "dokploy-sdk/models/operations";

let value: EnvironmentOneMongo = {
  appName: "<value>",
  applicationStatus: "error",
  command: "<value>",
  cpuLimit: "<value>",
  cpuReservation: "<value>",
  createdAt: "1735049498733",
  databasePassword: "<value>",
  databaseUser: "<value>",
  description: "mid wherever readily aha",
  dockerImage: "<value>",
  env: "<value>",
  environmentId: "<id>",
  externalPort: 2146.5,
  healthCheckSwarm: {},
  labelsSwarm: {
    "key": "<value>",
    "key1": "<value>",
    "key2": "<value>",
  },
  memoryLimit: "<value>",
  memoryReservation: "<value>",
  modeSwarm: "null",
  mongoId: "<id>",
  name: "<value>",
  networkSwarm: {
    "key": "<value>",
    "key1": "<value>",
  },
  placementSwarm: {
    "key": "<value>",
    "key1": "<value>",
    "key2": "<value>",
  },
  replicaSets: true,
  replicas: 1278.99,
  restartPolicySwarm: [
    "<value 1>",
    "<value 2>",
  ],
  rollbackConfigSwarm: "null",
  serverId: "<id>",
  updateConfigSwarm: "null",
};
```

## Fields

| Field                                                                                                              | Type                                                                                                               | Required                                                                                                           | Description                                                                                                        |
| ------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------ |
| `appName`                                                                                                          | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `applicationStatus`                                                                                                | [operations.EnvironmentOneMongoApplicationStatus](../../models/operations/environmentonemongoapplicationstatus.md) | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `command`                                                                                                          | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `cpuLimit`                                                                                                         | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `cpuReservation`                                                                                                   | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `createdAt`                                                                                                        | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `databasePassword`                                                                                                 | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `databaseUser`                                                                                                     | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `description`                                                                                                      | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `dockerImage`                                                                                                      | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `env`                                                                                                              | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `environmentId`                                                                                                    | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `externalPort`                                                                                                     | *number*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `healthCheckSwarm`                                                                                                 | *operations.EnvironmentOneMongoHealthCheckSwarmUnion*                                                              | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `labelsSwarm`                                                                                                      | *operations.EnvironmentOneMongoLabelsSwarmUnion*                                                                   | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `memoryLimit`                                                                                                      | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `memoryReservation`                                                                                                | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `modeSwarm`                                                                                                        | *operations.EnvironmentOneMongoModeSwarmUnion*                                                                     | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `mongoId`                                                                                                          | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `name`                                                                                                             | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `networkSwarm`                                                                                                     | *operations.EnvironmentOneMongoNetworkSwarmUnion*                                                                  | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `placementSwarm`                                                                                                   | *operations.EnvironmentOneMongoPlacementSwarmUnion*                                                                | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `replicaSets`                                                                                                      | *boolean*                                                                                                          | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `replicas`                                                                                                         | *number*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `restartPolicySwarm`                                                                                               | *operations.EnvironmentOneMongoRestartPolicySwarmUnion*                                                            | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `rollbackConfigSwarm`                                                                                              | *operations.EnvironmentOneMongoRollbackConfigSwarmUnion*                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `serverId`                                                                                                         | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `updateConfigSwarm`                                                                                                | *operations.EnvironmentOneMongoUpdateConfigSwarmUnion*                                                             | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
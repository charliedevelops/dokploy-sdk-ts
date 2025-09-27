# EnvironmentOneMysql

## Example Usage

```typescript
import { EnvironmentOneMysql } from "dokploy-sdk/models/operations";

let value: EnvironmentOneMysql = {
  appName: "<value>",
  applicationStatus: "done",
  command: "<value>",
  cpuLimit: "<value>",
  cpuReservation: "<value>",
  createdAt: "1721729727655",
  databaseName: "<value>",
  databasePassword: "<value>",
  databaseRootPassword: "<value>",
  databaseUser: "<value>",
  description: null,
  dockerImage: "<value>",
  env: "<value>",
  environmentId: "<id>",
  externalPort: 7495.84,
  healthCheckSwarm: {},
  labelsSwarm: {
    "key": "<value>",
    "key1": "<value>",
  },
  memoryLimit: "<value>",
  memoryReservation: "<value>",
  modeSwarm: {
    "key": "<value>",
    "key1": "<value>",
  },
  mysqlId: "<id>",
  name: "<value>",
  networkSwarm: [
    "<value 1>",
    "<value 2>",
    "<value 3>",
  ],
  placementSwarm: "null",
  replicas: 6429.57,
  restartPolicySwarm: [],
  rollbackConfigSwarm: [
    "<value 1>",
  ],
  serverId: "<id>",
  updateConfigSwarm: [
    "<value 1>",
  ],
};
```

## Fields

| Field                                                                                                              | Type                                                                                                               | Required                                                                                                           | Description                                                                                                        |
| ------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------ |
| `appName`                                                                                                          | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `applicationStatus`                                                                                                | [operations.EnvironmentOneMysqlApplicationStatus](../../models/operations/environmentonemysqlapplicationstatus.md) | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `command`                                                                                                          | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `cpuLimit`                                                                                                         | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `cpuReservation`                                                                                                   | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `createdAt`                                                                                                        | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `databaseName`                                                                                                     | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `databasePassword`                                                                                                 | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `databaseRootPassword`                                                                                             | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `databaseUser`                                                                                                     | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `description`                                                                                                      | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `dockerImage`                                                                                                      | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `env`                                                                                                              | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `environmentId`                                                                                                    | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `externalPort`                                                                                                     | *number*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `healthCheckSwarm`                                                                                                 | *operations.EnvironmentOneMysqlHealthCheckSwarmUnion*                                                              | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `labelsSwarm`                                                                                                      | *operations.EnvironmentOneMysqlLabelsSwarmUnion*                                                                   | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `memoryLimit`                                                                                                      | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `memoryReservation`                                                                                                | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `modeSwarm`                                                                                                        | *operations.EnvironmentOneMysqlModeSwarmUnion*                                                                     | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `mysqlId`                                                                                                          | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `name`                                                                                                             | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `networkSwarm`                                                                                                     | *operations.EnvironmentOneMysqlNetworkSwarmUnion*                                                                  | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `placementSwarm`                                                                                                   | *operations.EnvironmentOneMysqlPlacementSwarmUnion*                                                                | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `replicas`                                                                                                         | *number*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `restartPolicySwarm`                                                                                               | *operations.EnvironmentOneMysqlRestartPolicySwarmUnion*                                                            | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `rollbackConfigSwarm`                                                                                              | *operations.EnvironmentOneMysqlRollbackConfigSwarmUnion*                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `serverId`                                                                                                         | *string*                                                                                                           | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
| `updateConfigSwarm`                                                                                                | *operations.EnvironmentOneMysqlUpdateConfigSwarmUnion*                                                             | :heavy_check_mark:                                                                                                 | N/A                                                                                                                |
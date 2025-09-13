# EnvironmentOnePostgre

## Example Usage

```typescript
import { EnvironmentOnePostgre } from "dokploy-sdk/models/operations";

let value: EnvironmentOnePostgre = {
  postgresId: "<id>",
  name: "<value>",
  appName: "<value>",
  databaseName: "<value>",
  databaseUser: "<value>",
  databasePassword: "<value>",
  description:
    "coordinated worse underneath outside nor harp meadow affiliate roadway under",
  dockerImage: "<value>",
  command: "<value>",
  env: "<value>",
  memoryReservation: "<value>",
  externalPort: 40.67,
  memoryLimit: null,
  cpuReservation: "<value>",
  cpuLimit: null,
  applicationStatus: "error",
  healthCheckSwarm: [
    "<value 1>",
  ],
  restartPolicySwarm: [
    "<value 1>",
    "<value 2>",
    "<value 3>",
  ],
  placementSwarm: [
    "<value 1>",
    "<value 2>",
  ],
  updateConfigSwarm: "null",
  rollbackConfigSwarm: [
    "<value 1>",
    "<value 2>",
    "<value 3>",
  ],
  modeSwarm: [
    "<value 1>",
    "<value 2>",
    "<value 3>",
  ],
  labelsSwarm: [
    "<value 1>",
    "<value 2>",
  ],
  networkSwarm: [
    "<value 1>",
    "<value 2>",
  ],
  replicas: 8476.07,
  createdAt: "1732448580350",
  environmentId: "<id>",
  serverId: null,
};
```

## Fields

| Field                                                                                                                  | Type                                                                                                                   | Required                                                                                                               | Description                                                                                                            |
| ---------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| `postgresId`                                                                                                           | *string*                                                                                                               | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `name`                                                                                                                 | *string*                                                                                                               | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `appName`                                                                                                              | *string*                                                                                                               | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `databaseName`                                                                                                         | *string*                                                                                                               | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `databaseUser`                                                                                                         | *string*                                                                                                               | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `databasePassword`                                                                                                     | *string*                                                                                                               | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `description`                                                                                                          | *string*                                                                                                               | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `dockerImage`                                                                                                          | *string*                                                                                                               | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `command`                                                                                                              | *string*                                                                                                               | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `env`                                                                                                                  | *string*                                                                                                               | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `memoryReservation`                                                                                                    | *string*                                                                                                               | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `externalPort`                                                                                                         | *number*                                                                                                               | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `memoryLimit`                                                                                                          | *string*                                                                                                               | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `cpuReservation`                                                                                                       | *string*                                                                                                               | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `cpuLimit`                                                                                                             | *string*                                                                                                               | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `applicationStatus`                                                                                                    | [operations.EnvironmentOnePostgreApplicationStatus](../../models/operations/environmentonepostgreapplicationstatus.md) | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `healthCheckSwarm`                                                                                                     | *operations.EnvironmentOnePostgreHealthCheckSwarmUnion*                                                                | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `restartPolicySwarm`                                                                                                   | *operations.EnvironmentOnePostgreRestartPolicySwarmUnion*                                                              | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `placementSwarm`                                                                                                       | *operations.EnvironmentOnePostgrePlacementSwarmUnion*                                                                  | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `updateConfigSwarm`                                                                                                    | *operations.EnvironmentOnePostgreUpdateConfigSwarmUnion*                                                               | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `rollbackConfigSwarm`                                                                                                  | *operations.EnvironmentOnePostgreRollbackConfigSwarmUnion*                                                             | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `modeSwarm`                                                                                                            | *operations.EnvironmentOnePostgreModeSwarmUnion*                                                                       | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `labelsSwarm`                                                                                                          | *operations.EnvironmentOnePostgreLabelsSwarmUnion*                                                                     | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `networkSwarm`                                                                                                         | *operations.EnvironmentOnePostgreNetworkSwarmUnion*                                                                    | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `replicas`                                                                                                             | *number*                                                                                                               | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `createdAt`                                                                                                            | *string*                                                                                                               | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `environmentId`                                                                                                        | *string*                                                                                                               | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `serverId`                                                                                                             | *string*                                                                                                               | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
# EnvironmentOneMariadb

## Example Usage

```typescript
import { EnvironmentOneMariadb } from "dokploy-sdk/models/operations";

let value: EnvironmentOneMariadb = {
  appName: "<value>",
  applicationStatus: "idle",
  command: "<value>",
  cpuLimit: "<value>",
  cpuReservation: "<value>",
  createdAt: "1718502448041",
  databaseName: "<value>",
  databasePassword: "<value>",
  databaseRootPassword: "<value>",
  databaseUser: "<value>",
  description: "whose defrag among",
  dockerImage: "<value>",
  env: "<value>",
  environmentId: "<id>",
  externalPort: 3830.81,
  healthCheckSwarm: "<value>",
  labelsSwarm: [
    "<value 1>",
    "<value 2>",
  ],
  mariadbId: "<id>",
  memoryLimit: null,
  memoryReservation: "<value>",
  modeSwarm: {
    "key": "<value>",
    "key1": "<value>",
    "key2": "<value>",
  },
  name: "<value>",
  networkSwarm: "<value>",
  placementSwarm: "<value>",
  replicas: 5288.78,
  restartPolicySwarm: {},
  rollbackConfigSwarm: 5726.82,
  serverId: null,
  updateConfigSwarm: {
    "key": "<value>",
    "key1": "<value>",
  },
};
```

## Fields

| Field                                                                                                                  | Type                                                                                                                   | Required                                                                                                               | Description                                                                                                            |
| ---------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| `appName`                                                                                                              | *string*                                                                                                               | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `applicationStatus`                                                                                                    | [operations.EnvironmentOneMariadbApplicationStatus](../../models/operations/environmentonemariadbapplicationstatus.md) | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `command`                                                                                                              | *string*                                                                                                               | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `cpuLimit`                                                                                                             | *string*                                                                                                               | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `cpuReservation`                                                                                                       | *string*                                                                                                               | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `createdAt`                                                                                                            | *string*                                                                                                               | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `databaseName`                                                                                                         | *string*                                                                                                               | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `databasePassword`                                                                                                     | *string*                                                                                                               | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `databaseRootPassword`                                                                                                 | *string*                                                                                                               | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `databaseUser`                                                                                                         | *string*                                                                                                               | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `description`                                                                                                          | *string*                                                                                                               | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `dockerImage`                                                                                                          | *string*                                                                                                               | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `env`                                                                                                                  | *string*                                                                                                               | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `environmentId`                                                                                                        | *string*                                                                                                               | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `externalPort`                                                                                                         | *number*                                                                                                               | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `healthCheckSwarm`                                                                                                     | *operations.EnvironmentOneMariadbHealthCheckSwarmUnion*                                                                | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `labelsSwarm`                                                                                                          | *operations.EnvironmentOneMariadbLabelsSwarmUnion*                                                                     | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `mariadbId`                                                                                                            | *string*                                                                                                               | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `memoryLimit`                                                                                                          | *string*                                                                                                               | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `memoryReservation`                                                                                                    | *string*                                                                                                               | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `modeSwarm`                                                                                                            | *operations.EnvironmentOneMariadbModeSwarmUnion*                                                                       | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `name`                                                                                                                 | *string*                                                                                                               | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `networkSwarm`                                                                                                         | *operations.EnvironmentOneMariadbNetworkSwarmUnion*                                                                    | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `placementSwarm`                                                                                                       | *operations.EnvironmentOneMariadbPlacementSwarmUnion*                                                                  | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `replicas`                                                                                                             | *number*                                                                                                               | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `restartPolicySwarm`                                                                                                   | *operations.EnvironmentOneMariadbRestartPolicySwarmUnion*                                                              | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `rollbackConfigSwarm`                                                                                                  | *operations.EnvironmentOneMariadbRollbackConfigSwarmUnion*                                                             | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `serverId`                                                                                                             | *string*                                                                                                               | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `updateConfigSwarm`                                                                                                    | *operations.EnvironmentOneMariadbUpdateConfigSwarmUnion*                                                               | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
# MysqlMoveResponseBody

Successful response

## Example Usage

```typescript
import { MysqlMoveResponseBody } from "dokploy-sdk/models/operations";

let value: MysqlMoveResponseBody = {
  mysqlId: "<id>",
  name: "<value>",
  appName: "<value>",
  description: "apropos atomize sham word pro hence searchingly",
  databaseName: "<value>",
  databaseUser: "<value>",
  databasePassword: "<value>",
  databaseRootPassword: "<value>",
  dockerImage: "<value>",
  command: "<value>",
  env: "<value>",
  memoryReservation: "<value>",
  memoryLimit: "<value>",
  cpuReservation: "<value>",
  cpuLimit: "<value>",
  externalPort: 9077.83,
  applicationStatus: "done",
  healthCheckSwarm: {},
  restartPolicySwarm: {},
  placementSwarm: {},
  updateConfigSwarm: {
    parallelism: 8005.81,
    order: "<value>",
  },
  rollbackConfigSwarm: null,
  modeSwarm: {},
  labelsSwarm: {
    "key": "<value>",
  },
  networkSwarm: [
    {},
  ],
  replicas: 6175.68,
  createdAt: "1724585844746",
  environmentId: "<id>",
  serverId: "<id>",
};
```

## Fields

| Field                                                                                              | Type                                                                                               | Required                                                                                           | Description                                                                                        |
| -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| `mysqlId`                                                                                          | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `name`                                                                                             | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `appName`                                                                                          | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `description`                                                                                      | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `databaseName`                                                                                     | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `databaseUser`                                                                                     | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `databasePassword`                                                                                 | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `databaseRootPassword`                                                                             | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `dockerImage`                                                                                      | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `command`                                                                                          | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `env`                                                                                              | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `memoryReservation`                                                                                | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `memoryLimit`                                                                                      | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `cpuReservation`                                                                                   | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `cpuLimit`                                                                                         | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `externalPort`                                                                                     | *number*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `applicationStatus`                                                                                | [operations.MysqlMoveApplicationStatus](../../models/operations/mysqlmoveapplicationstatus.md)     | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `healthCheckSwarm`                                                                                 | [operations.MysqlMoveHealthCheckSwarm](../../models/operations/mysqlmovehealthcheckswarm.md)       | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `restartPolicySwarm`                                                                               | [operations.MysqlMoveRestartPolicySwarm](../../models/operations/mysqlmoverestartpolicyswarm.md)   | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `placementSwarm`                                                                                   | [operations.MysqlMovePlacementSwarm](../../models/operations/mysqlmoveplacementswarm.md)           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `updateConfigSwarm`                                                                                | [operations.MysqlMoveUpdateConfigSwarm](../../models/operations/mysqlmoveupdateconfigswarm.md)     | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `rollbackConfigSwarm`                                                                              | [operations.MysqlMoveRollbackConfigSwarm](../../models/operations/mysqlmoverollbackconfigswarm.md) | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `modeSwarm`                                                                                        | [operations.MysqlMoveModeSwarm](../../models/operations/mysqlmovemodeswarm.md)                     | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `labelsSwarm`                                                                                      | Record<string, *string*>                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `networkSwarm`                                                                                     | [operations.MysqlMoveNetworkSwarm](../../models/operations/mysqlmovenetworkswarm.md)[]             | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `replicas`                                                                                         | *number*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `createdAt`                                                                                        | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `environmentId`                                                                                    | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `serverId`                                                                                         | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
# MongoMoveResponseBody

Successful response

## Example Usage

```typescript
import { MongoMoveResponseBody } from "dokploy-sdk/models/operations";

let value: MongoMoveResponseBody = {
  appName: "<value>",
  applicationStatus: "error",
  command: "<value>",
  cpuLimit: "<value>",
  cpuReservation: "<value>",
  createdAt: "1728917275717",
  databasePassword: "<value>",
  databaseUser: "<value>",
  description: "lazy ick modulo insist celebrate quickly yuck kissingly before",
  dockerImage: "<value>",
  env: "<value>",
  environmentId: "<id>",
  externalPort: 3213.26,
  healthCheckSwarm: {},
  labelsSwarm: {
    "key": "<value>",
    "key1": "<value>",
  },
  memoryLimit: "<value>",
  memoryReservation: "<value>",
  modeSwarm: {},
  mongoId: "<id>",
  name: "<value>",
  networkSwarm: [],
  placementSwarm: {},
  replicaSets: false,
  replicas: 5232.11,
  restartPolicySwarm: {},
  rollbackConfigSwarm: {
    order: "<value>",
    parallelism: 8057.66,
  },
  serverId: "<id>",
  updateConfigSwarm: {
    order: "<value>",
    parallelism: 8091.17,
  },
};
```

## Fields

| Field                                                                                              | Type                                                                                               | Required                                                                                           | Description                                                                                        |
| -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| `appName`                                                                                          | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `applicationStatus`                                                                                | [operations.MongoMoveApplicationStatus](../../models/operations/mongomoveapplicationstatus.md)     | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `command`                                                                                          | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `cpuLimit`                                                                                         | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `cpuReservation`                                                                                   | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `createdAt`                                                                                        | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `databasePassword`                                                                                 | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `databaseUser`                                                                                     | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `description`                                                                                      | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `dockerImage`                                                                                      | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `env`                                                                                              | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `environmentId`                                                                                    | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `externalPort`                                                                                     | *number*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `healthCheckSwarm`                                                                                 | [operations.MongoMoveHealthCheckSwarm](../../models/operations/mongomovehealthcheckswarm.md)       | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `labelsSwarm`                                                                                      | Record<string, *string*>                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `memoryLimit`                                                                                      | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `memoryReservation`                                                                                | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `modeSwarm`                                                                                        | [operations.MongoMoveModeSwarm](../../models/operations/mongomovemodeswarm.md)                     | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `mongoId`                                                                                          | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `name`                                                                                             | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `networkSwarm`                                                                                     | [operations.MongoMoveNetworkSwarm](../../models/operations/mongomovenetworkswarm.md)[]             | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `placementSwarm`                                                                                   | [operations.MongoMovePlacementSwarm](../../models/operations/mongomoveplacementswarm.md)           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `replicaSets`                                                                                      | *boolean*                                                                                          | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `replicas`                                                                                         | *number*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `restartPolicySwarm`                                                                               | [operations.MongoMoveRestartPolicySwarm](../../models/operations/mongomoverestartpolicyswarm.md)   | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `rollbackConfigSwarm`                                                                              | [operations.MongoMoveRollbackConfigSwarm](../../models/operations/mongomoverollbackconfigswarm.md) | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `serverId`                                                                                         | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `updateConfigSwarm`                                                                                | [operations.MongoMoveUpdateConfigSwarm](../../models/operations/mongomoveupdateconfigswarm.md)     | :heavy_check_mark:                                                                                 | N/A                                                                                                |
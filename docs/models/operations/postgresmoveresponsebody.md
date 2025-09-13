# PostgresMoveResponseBody

Successful response

## Example Usage

```typescript
import { PostgresMoveResponseBody } from "dokploy-sdk/models/operations";

let value: PostgresMoveResponseBody = {
  postgresId: "<id>",
  name: "<value>",
  appName: "<value>",
  databaseName: "<value>",
  databaseUser: "<value>",
  databasePassword: "<value>",
  description:
    "depart productive um wedge pfft familiar despite frightfully searchingly doorpost",
  dockerImage: "<value>",
  command: "<value>",
  env: "<value>",
  memoryReservation: null,
  externalPort: 6214.87,
  memoryLimit: "<value>",
  cpuReservation: "<value>",
  cpuLimit: "<value>",
  applicationStatus: "error",
  healthCheckSwarm: null,
  restartPolicySwarm: {},
  placementSwarm: {},
  updateConfigSwarm: {
    parallelism: 3667.35,
    order: "<value>",
  },
  rollbackConfigSwarm: {
    parallelism: 5646.93,
    order: "<value>",
  },
  modeSwarm: {},
  labelsSwarm: {},
  networkSwarm: [
    {},
  ],
  replicas: 7263.91,
  createdAt: "1715559383415",
  environmentId: "<id>",
  serverId: "<id>",
};
```

## Fields

| Field                                                                                                    | Type                                                                                                     | Required                                                                                                 | Description                                                                                              |
| -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- |
| `postgresId`                                                                                             | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `name`                                                                                                   | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `appName`                                                                                                | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `databaseName`                                                                                           | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `databaseUser`                                                                                           | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `databasePassword`                                                                                       | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `description`                                                                                            | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `dockerImage`                                                                                            | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `command`                                                                                                | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `env`                                                                                                    | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `memoryReservation`                                                                                      | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `externalPort`                                                                                           | *number*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `memoryLimit`                                                                                            | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `cpuReservation`                                                                                         | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `cpuLimit`                                                                                               | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `applicationStatus`                                                                                      | [operations.PostgresMoveApplicationStatus](../../models/operations/postgresmoveapplicationstatus.md)     | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `healthCheckSwarm`                                                                                       | [operations.PostgresMoveHealthCheckSwarm](../../models/operations/postgresmovehealthcheckswarm.md)       | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `restartPolicySwarm`                                                                                     | [operations.PostgresMoveRestartPolicySwarm](../../models/operations/postgresmoverestartpolicyswarm.md)   | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `placementSwarm`                                                                                         | [operations.PostgresMovePlacementSwarm](../../models/operations/postgresmoveplacementswarm.md)           | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `updateConfigSwarm`                                                                                      | [operations.PostgresMoveUpdateConfigSwarm](../../models/operations/postgresmoveupdateconfigswarm.md)     | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `rollbackConfigSwarm`                                                                                    | [operations.PostgresMoveRollbackConfigSwarm](../../models/operations/postgresmoverollbackconfigswarm.md) | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `modeSwarm`                                                                                              | [operations.PostgresMoveModeSwarm](../../models/operations/postgresmovemodeswarm.md)                     | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `labelsSwarm`                                                                                            | Record<string, *string*>                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `networkSwarm`                                                                                           | [operations.PostgresMoveNetworkSwarm](../../models/operations/postgresmovenetworkswarm.md)[]             | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `replicas`                                                                                               | *number*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `createdAt`                                                                                              | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `environmentId`                                                                                          | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `serverId`                                                                                               | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
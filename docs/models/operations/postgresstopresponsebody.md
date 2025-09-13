# PostgresStopResponseBody

Successful response

## Example Usage

```typescript
import { PostgresStopResponseBody } from "dokploy-sdk/models/operations";

let value: PostgresStopResponseBody = {
  appName: "<value>",
  applicationStatus: "idle",
  backups: [],
  command: "<value>",
  cpuLimit: "<value>",
  cpuReservation: "<value>",
  createdAt: "1705678954173",
  databaseName: "<value>",
  databasePassword: "<value>",
  databaseUser: "<value>",
  description: "general kiddingly torn minus quicker notwithstanding lox since",
  dockerImage: "<value>",
  env: "<value>",
  environment: {
    createdAt: "1709899479925",
    description: null,
    env: "<value>",
    environmentId: "<id>",
    name: "<value>",
    project: {
      createdAt: "1707969860361",
      description:
        "phooey bolster deer oof clone merrily ugh silky draw overplay",
      env: "<value>",
      name: "<value>",
      organizationId: "<id>",
      projectId: "<id>",
    },
    projectId: "<id>",
  },
  environmentId: "<id>",
  externalPort: null,
  healthCheckSwarm: {},
  labelsSwarm: {
    "key": "<value>",
    "key1": "<value>",
  },
  memoryLimit: "<value>",
  memoryReservation: "<value>",
  modeSwarm: null,
  mounts: [
    {
      applicationId: "<id>",
      composeId: "<id>",
      content: "<value>",
      filePath: "/usr/libexec/singing_hunger.rar",
      hostPath: "<value>",
      mariadbId: "<id>",
      mongoId: "<id>",
      mountId: "<id>",
      mountPath: "<value>",
      mysqlId: "<id>",
      postgresId: "<id>",
      redisId: "<id>",
      serviceType: "compose",
      type: "file",
      volumeName: null,
    },
  ],
  name: "<value>",
  networkSwarm: [
    {},
  ],
  placementSwarm: {},
  postgresId: "<id>",
  replicas: 9182.93,
  restartPolicySwarm: {},
  rollbackConfigSwarm: null,
  server: null,
  serverId: "<id>",
  updateConfigSwarm: {
    order: "<value>",
    parallelism: 8816.22,
  },
};
```

## Fields

| Field                                                                                                    | Type                                                                                                     | Required                                                                                                 | Description                                                                                              |
| -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- |
| `appName`                                                                                                | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `applicationStatus`                                                                                      | [operations.PostgresStopApplicationStatus](../../models/operations/postgresstopapplicationstatus.md)     | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `backups`                                                                                                | [operations.PostgresStopBackup](../../models/operations/postgresstopbackup.md)[]                         | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `command`                                                                                                | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `cpuLimit`                                                                                               | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `cpuReservation`                                                                                         | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `createdAt`                                                                                              | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `databaseName`                                                                                           | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `databasePassword`                                                                                       | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `databaseUser`                                                                                           | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `description`                                                                                            | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `dockerImage`                                                                                            | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `env`                                                                                                    | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `environment`                                                                                            | [operations.PostgresStopEnvironment](../../models/operations/postgresstopenvironment.md)                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `environmentId`                                                                                          | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `externalPort`                                                                                           | *number*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `healthCheckSwarm`                                                                                       | [operations.PostgresStopHealthCheckSwarm](../../models/operations/postgresstophealthcheckswarm.md)       | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `labelsSwarm`                                                                                            | Record<string, *string*>                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `memoryLimit`                                                                                            | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `memoryReservation`                                                                                      | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `modeSwarm`                                                                                              | [operations.PostgresStopModeSwarm](../../models/operations/postgresstopmodeswarm.md)                     | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `mounts`                                                                                                 | [operations.PostgresStopMount](../../models/operations/postgresstopmount.md)[]                           | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `name`                                                                                                   | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `networkSwarm`                                                                                           | [operations.PostgresStopNetworkSwarm](../../models/operations/postgresstopnetworkswarm.md)[]             | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `placementSwarm`                                                                                         | [operations.PostgresStopPlacementSwarm](../../models/operations/postgresstopplacementswarm.md)           | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `postgresId`                                                                                             | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `replicas`                                                                                               | *number*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `restartPolicySwarm`                                                                                     | [operations.PostgresStopRestartPolicySwarm](../../models/operations/postgresstoprestartpolicyswarm.md)   | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `rollbackConfigSwarm`                                                                                    | [operations.PostgresStopRollbackConfigSwarm](../../models/operations/postgresstoprollbackconfigswarm.md) | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `server`                                                                                                 | [operations.PostgresStopServer](../../models/operations/postgresstopserver.md)                           | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `serverId`                                                                                               | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `updateConfigSwarm`                                                                                      | [operations.PostgresStopUpdateConfigSwarm](../../models/operations/postgresstopupdateconfigswarm.md)     | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
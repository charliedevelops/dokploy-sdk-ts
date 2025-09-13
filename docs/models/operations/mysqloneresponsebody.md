# MysqlOneResponseBody

Successful response

## Example Usage

```typescript
import { MysqlOneResponseBody } from "dokploy-sdk/models/operations";

let value: MysqlOneResponseBody = {
  mysqlId: "<id>",
  name: "<value>",
  appName: "<value>",
  description: null,
  databaseName: "<value>",
  databaseUser: "<value>",
  databasePassword: "<value>",
  databaseRootPassword: "<value>",
  dockerImage: "<value>",
  command: null,
  env: "<value>",
  memoryReservation: "<value>",
  memoryLimit: "<value>",
  cpuReservation: "<value>",
  cpuLimit: "<value>",
  externalPort: 3224.27,
  applicationStatus: "done",
  healthCheckSwarm: null,
  restartPolicySwarm: {},
  placementSwarm: {},
  updateConfigSwarm: null,
  rollbackConfigSwarm: {
    parallelism: 6573.9,
    order: "<value>",
  },
  modeSwarm: {},
  labelsSwarm: {
    "key": "<value>",
  },
  networkSwarm: null,
  replicas: 9938.77,
  createdAt: "1712559561299",
  environmentId: "<id>",
  serverId: null,
  environment: {
    environmentId: "<id>",
    name: "<value>",
    description: "oof valiantly mmm tired never truly tuxedo",
    createdAt: "1729355553936",
    env: "<value>",
    projectId: "<id>",
    project: {
      projectId: "<id>",
      name: "<value>",
      description: "hourly how lecture quixotic hole drive as scale what but",
      createdAt: "1732002276444",
      organizationId: "<id>",
      env: "<value>",
    },
  },
  mounts: [],
  server: {
    serverId: "<id>",
    name: "<value>",
    description: null,
    ipAddress: "156.130.205.219",
    port: 5651.27,
    username: "Genevieve_Jakubowski43",
    appName: "<value>",
    enableDockerCleanup: true,
    createdAt: "1706323874487",
    organizationId: "<id>",
    serverStatus: "active",
    command: "<value>",
    sshKeyId: "<id>",
    metricsConfig: true,
  },
  backups: [],
};
```

## Fields

| Field                                                                                            | Type                                                                                             | Required                                                                                         | Description                                                                                      |
| ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ |
| `mysqlId`                                                                                        | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `name`                                                                                           | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `appName`                                                                                        | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `description`                                                                                    | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `databaseName`                                                                                   | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `databaseUser`                                                                                   | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `databasePassword`                                                                               | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `databaseRootPassword`                                                                           | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `dockerImage`                                                                                    | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `command`                                                                                        | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `env`                                                                                            | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `memoryReservation`                                                                              | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `memoryLimit`                                                                                    | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `cpuReservation`                                                                                 | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `cpuLimit`                                                                                       | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `externalPort`                                                                                   | *number*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `applicationStatus`                                                                              | [operations.MysqlOneApplicationStatus](../../models/operations/mysqloneapplicationstatus.md)     | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `healthCheckSwarm`                                                                               | [operations.MysqlOneHealthCheckSwarm](../../models/operations/mysqlonehealthcheckswarm.md)       | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `restartPolicySwarm`                                                                             | [operations.MysqlOneRestartPolicySwarm](../../models/operations/mysqlonerestartpolicyswarm.md)   | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `placementSwarm`                                                                                 | [operations.MysqlOnePlacementSwarm](../../models/operations/mysqloneplacementswarm.md)           | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `updateConfigSwarm`                                                                              | [operations.MysqlOneUpdateConfigSwarm](../../models/operations/mysqloneupdateconfigswarm.md)     | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `rollbackConfigSwarm`                                                                            | [operations.MysqlOneRollbackConfigSwarm](../../models/operations/mysqlonerollbackconfigswarm.md) | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `modeSwarm`                                                                                      | [operations.MysqlOneModeSwarm](../../models/operations/mysqlonemodeswarm.md)                     | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `labelsSwarm`                                                                                    | Record<string, *string*>                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `networkSwarm`                                                                                   | [operations.MysqlOneNetworkSwarm](../../models/operations/mysqlonenetworkswarm.md)[]             | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `replicas`                                                                                       | *number*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `createdAt`                                                                                      | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `environmentId`                                                                                  | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `serverId`                                                                                       | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `environment`                                                                                    | [operations.MysqlOneEnvironment](../../models/operations/mysqloneenvironment.md)                 | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `mounts`                                                                                         | [operations.MysqlOneMount](../../models/operations/mysqlonemount.md)[]                           | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `server`                                                                                         | [operations.MysqlOneServer](../../models/operations/mysqloneserver.md)                           | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `backups`                                                                                        | [operations.MysqlOneBackup](../../models/operations/mysqlonebackup.md)[]                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
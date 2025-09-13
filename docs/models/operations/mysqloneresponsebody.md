# MysqlOneResponseBody

Successful response

## Example Usage

```typescript
import { MysqlOneResponseBody } from "dokploy-sdk/models/operations";

let value: MysqlOneResponseBody = {
  appName: "<value>",
  applicationStatus: "idle",
  backups: [],
  command: "<value>",
  cpuLimit: "<value>",
  cpuReservation: "<value>",
  createdAt: "1713180856207",
  databaseName: "<value>",
  databasePassword: "<value>",
  databaseRootPassword: "<value>",
  databaseUser: "<value>",
  description: "repeatedly drain recovery ape",
  dockerImage: "<value>",
  env: "<value>",
  environment: {
    createdAt: "1704858389051",
    description: "now bouncy majestic for sediment shell excluding mostly",
    env: "<value>",
    environmentId: "<id>",
    name: "<value>",
    project: {
      createdAt: "1721492658720",
      description:
        "micromanage aha though mmm upside-down serpentine row cow excepting after",
      env: "<value>",
      name: "<value>",
      organizationId: "<id>",
      projectId: "<id>",
    },
    projectId: "<id>",
  },
  environmentId: "<id>",
  externalPort: 1741.22,
  healthCheckSwarm: null,
  labelsSwarm: {
    "key": "<value>",
    "key1": "<value>",
  },
  memoryLimit: "<value>",
  memoryReservation: "<value>",
  modeSwarm: {},
  mounts: [],
  mysqlId: "<id>",
  name: "<value>",
  networkSwarm: [
    {},
  ],
  placementSwarm: {},
  replicas: 7363.93,
  restartPolicySwarm: {},
  rollbackConfigSwarm: {
    order: "<value>",
    parallelism: 8924.79,
  },
  server: {
    appName: "<value>",
    command: "<value>",
    createdAt: "1711169556654",
    description:
      "as crossly likely skyline until drat idealistic gladly deceivingly",
    enableDockerCleanup: false,
    ipAddress: "a3a4:0cb6:b572:3f5e:950b:f2a9:514d:28dc",
    metricsConfig: "null",
    name: "<value>",
    organizationId: "<id>",
    port: 3388.39,
    serverId: "<id>",
    serverStatus: "inactive",
    sshKeyId: "<id>",
    username: "Sallie.Corwin46",
  },
  serverId: "<id>",
  updateConfigSwarm: {
    order: "<value>",
    parallelism: 8349.85,
  },
};
```

## Fields

| Field                                                                                            | Type                                                                                             | Required                                                                                         | Description                                                                                      |
| ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ |
| `appName`                                                                                        | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `applicationStatus`                                                                              | [operations.MysqlOneApplicationStatus](../../models/operations/mysqloneapplicationstatus.md)     | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `backups`                                                                                        | [operations.MysqlOneBackup](../../models/operations/mysqlonebackup.md)[]                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `command`                                                                                        | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `cpuLimit`                                                                                       | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `cpuReservation`                                                                                 | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `createdAt`                                                                                      | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `databaseName`                                                                                   | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `databasePassword`                                                                               | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `databaseRootPassword`                                                                           | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `databaseUser`                                                                                   | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `description`                                                                                    | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `dockerImage`                                                                                    | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `env`                                                                                            | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `environment`                                                                                    | [operations.MysqlOneEnvironment](../../models/operations/mysqloneenvironment.md)                 | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `environmentId`                                                                                  | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `externalPort`                                                                                   | *number*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `healthCheckSwarm`                                                                               | [operations.MysqlOneHealthCheckSwarm](../../models/operations/mysqlonehealthcheckswarm.md)       | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `labelsSwarm`                                                                                    | Record<string, *string*>                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `memoryLimit`                                                                                    | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `memoryReservation`                                                                              | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `modeSwarm`                                                                                      | [operations.MysqlOneModeSwarm](../../models/operations/mysqlonemodeswarm.md)                     | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `mounts`                                                                                         | [operations.MysqlOneMount](../../models/operations/mysqlonemount.md)[]                           | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `mysqlId`                                                                                        | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `name`                                                                                           | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `networkSwarm`                                                                                   | [operations.MysqlOneNetworkSwarm](../../models/operations/mysqlonenetworkswarm.md)[]             | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `placementSwarm`                                                                                 | [operations.MysqlOnePlacementSwarm](../../models/operations/mysqloneplacementswarm.md)           | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `replicas`                                                                                       | *number*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `restartPolicySwarm`                                                                             | [operations.MysqlOneRestartPolicySwarm](../../models/operations/mysqlonerestartpolicyswarm.md)   | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `rollbackConfigSwarm`                                                                            | [operations.MysqlOneRollbackConfigSwarm](../../models/operations/mysqlonerollbackconfigswarm.md) | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `server`                                                                                         | [operations.MysqlOneServer](../../models/operations/mysqloneserver.md)                           | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `serverId`                                                                                       | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `updateConfigSwarm`                                                                              | [operations.MysqlOneUpdateConfigSwarm](../../models/operations/mysqloneupdateconfigswarm.md)     | :heavy_check_mark:                                                                               | N/A                                                                                              |
# MysqlRemoveResponseBody

Successful response

## Example Usage

```typescript
import { MysqlRemoveResponseBody } from "dokploy-sdk/models/operations";

let value: MysqlRemoveResponseBody = {
  mysqlId: "<id>",
  name: "<value>",
  appName: "<value>",
  description: "qua aha cheerful against",
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
  externalPort: 4217.25,
  applicationStatus: "error",
  healthCheckSwarm: {},
  restartPolicySwarm: {},
  placementSwarm: {},
  updateConfigSwarm: {
    parallelism: 2576.95,
    order: "<value>",
  },
  rollbackConfigSwarm: {
    parallelism: 6663.16,
    order: "<value>",
  },
  modeSwarm: {},
  labelsSwarm: {
    "key": "<value>",
  },
  networkSwarm: [],
  replicas: 4940.81,
  createdAt: "1720267687163",
  environmentId: "<id>",
  serverId: null,
  environment: {
    environmentId: "<id>",
    name: "<value>",
    description: "willfully relative until verify peninsula although",
    createdAt: "1730661546395",
    env: "<value>",
    projectId: "<id>",
    project: {
      projectId: "<id>",
      name: "<value>",
      description:
        "hmph hence than officially so border furthermore so phew obedience",
      createdAt: "1706704360529",
      organizationId: "<id>",
      env: "<value>",
    },
  },
  mounts: [],
  server: {
    serverId: "<id>",
    name: "<value>",
    description: "shrilly tenement qua definite ew eyeliner",
    ipAddress: "232.228.99.16",
    port: 7027.75,
    username: "Billy_Kirlin27",
    appName: "<value>",
    enableDockerCleanup: false,
    createdAt: "1728572112041",
    organizationId: "<id>",
    serverStatus: "active",
    command: "<value>",
    sshKeyId: null,
    metricsConfig: {
      "key": "<value>",
      "key1": "<value>",
      "key2": "<value>",
    },
  },
  backups: [],
};
```

## Fields

| Field                                                                                                  | Type                                                                                                   | Required                                                                                               | Description                                                                                            |
| ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ |
| `mysqlId`                                                                                              | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `name`                                                                                                 | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `appName`                                                                                              | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `description`                                                                                          | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `databaseName`                                                                                         | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `databaseUser`                                                                                         | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `databasePassword`                                                                                     | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `databaseRootPassword`                                                                                 | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `dockerImage`                                                                                          | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `command`                                                                                              | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `env`                                                                                                  | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `memoryReservation`                                                                                    | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `memoryLimit`                                                                                          | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `cpuReservation`                                                                                       | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `cpuLimit`                                                                                             | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `externalPort`                                                                                         | *number*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `applicationStatus`                                                                                    | [operations.MysqlRemoveApplicationStatus](../../models/operations/mysqlremoveapplicationstatus.md)     | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `healthCheckSwarm`                                                                                     | [operations.MysqlRemoveHealthCheckSwarm](../../models/operations/mysqlremovehealthcheckswarm.md)       | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `restartPolicySwarm`                                                                                   | [operations.MysqlRemoveRestartPolicySwarm](../../models/operations/mysqlremoverestartpolicyswarm.md)   | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `placementSwarm`                                                                                       | [operations.MysqlRemovePlacementSwarm](../../models/operations/mysqlremoveplacementswarm.md)           | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `updateConfigSwarm`                                                                                    | [operations.MysqlRemoveUpdateConfigSwarm](../../models/operations/mysqlremoveupdateconfigswarm.md)     | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `rollbackConfigSwarm`                                                                                  | [operations.MysqlRemoveRollbackConfigSwarm](../../models/operations/mysqlremoverollbackconfigswarm.md) | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `modeSwarm`                                                                                            | [operations.MysqlRemoveModeSwarm](../../models/operations/mysqlremovemodeswarm.md)                     | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `labelsSwarm`                                                                                          | Record<string, *string*>                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `networkSwarm`                                                                                         | [operations.MysqlRemoveNetworkSwarm](../../models/operations/mysqlremovenetworkswarm.md)[]             | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `replicas`                                                                                             | *number*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `createdAt`                                                                                            | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `environmentId`                                                                                        | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `serverId`                                                                                             | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `environment`                                                                                          | [operations.MysqlRemoveEnvironment](../../models/operations/mysqlremoveenvironment.md)                 | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `mounts`                                                                                               | [operations.MysqlRemoveMount](../../models/operations/mysqlremovemount.md)[]                           | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `server`                                                                                               | [operations.MysqlRemoveServer](../../models/operations/mysqlremoveserver.md)                           | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `backups`                                                                                              | [operations.MysqlRemoveBackup](../../models/operations/mysqlremovebackup.md)[]                         | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
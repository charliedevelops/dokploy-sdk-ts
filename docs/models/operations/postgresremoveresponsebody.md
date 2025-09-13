# PostgresRemoveResponseBody

Successful response

## Example Usage

```typescript
import { PostgresRemoveResponseBody } from "dokploy-sdk/models/operations";

let value: PostgresRemoveResponseBody = {
  appName: "<value>",
  applicationStatus: "running",
  backups: [
    {
      appName: "<value>",
      backupId: "<id>",
      backupType: "database",
      composeId: "<id>",
      database: "<value>",
      databaseType: "postgres",
      destinationId: "<id>",
      enabled: true,
      keepLatestCount: 1789.86,
      mariadbId: "<id>",
      mongoId: "<id>",
      mysqlId: "<id>",
      postgresId: "<id>",
      prefix: "<value>",
      schedule: "<value>",
      serviceName: null,
      userId: "<id>",
    },
  ],
  command: "<value>",
  cpuLimit: "<value>",
  cpuReservation: "<value>",
  createdAt: "1734404093273",
  databaseName: "<value>",
  databasePassword: "<value>",
  databaseUser: "<value>",
  description: null,
  dockerImage: "<value>",
  env: null,
  environment: {
    createdAt: "1719202281066",
    description: null,
    env: "<value>",
    environmentId: "<id>",
    name: "<value>",
    project: {
      createdAt: "1722918008081",
      description: "sanity beyond slink purse euphonium",
      env: "<value>",
      name: "<value>",
      organizationId: "<id>",
      projectId: "<id>",
    },
    projectId: "<id>",
  },
  environmentId: "<id>",
  externalPort: 7688.54,
  healthCheckSwarm: {},
  labelsSwarm: {
    "key": "<value>",
    "key1": "<value>",
    "key2": "<value>",
  },
  memoryLimit: "<value>",
  memoryReservation: "<value>",
  modeSwarm: {},
  mounts: [
    {
      applicationId: null,
      composeId: "<id>",
      content: "<value>",
      filePath: null,
      hostPath: "<value>",
      mariadbId: "<id>",
      mongoId: "<id>",
      mountId: "<id>",
      mountPath: "<value>",
      mysqlId: "<id>",
      postgresId: "<id>",
      redisId: "<id>",
      serviceType: "mariadb",
      type: "file",
      volumeName: "<value>",
    },
  ],
  name: "<value>",
  networkSwarm: [],
  placementSwarm: {},
  postgresId: "<id>",
  replicas: 4756.12,
  restartPolicySwarm: {},
  rollbackConfigSwarm: {
    order: "<value>",
    parallelism: 2467,
  },
  server: null,
  serverId: null,
  updateConfigSwarm: {
    order: "<value>",
    parallelism: 6449.82,
  },
};
```

## Fields

| Field                                                                                                        | Type                                                                                                         | Required                                                                                                     | Description                                                                                                  |
| ------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------ |
| `appName`                                                                                                    | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `applicationStatus`                                                                                          | [operations.PostgresRemoveApplicationStatus](../../models/operations/postgresremoveapplicationstatus.md)     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `backups`                                                                                                    | [operations.PostgresRemoveBackup](../../models/operations/postgresremovebackup.md)[]                         | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `command`                                                                                                    | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `cpuLimit`                                                                                                   | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `cpuReservation`                                                                                             | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `createdAt`                                                                                                  | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `databaseName`                                                                                               | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `databasePassword`                                                                                           | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `databaseUser`                                                                                               | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `description`                                                                                                | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `dockerImage`                                                                                                | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `env`                                                                                                        | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `environment`                                                                                                | [operations.PostgresRemoveEnvironment](../../models/operations/postgresremoveenvironment.md)                 | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `environmentId`                                                                                              | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `externalPort`                                                                                               | *number*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `healthCheckSwarm`                                                                                           | [operations.PostgresRemoveHealthCheckSwarm](../../models/operations/postgresremovehealthcheckswarm.md)       | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `labelsSwarm`                                                                                                | Record<string, *string*>                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `memoryLimit`                                                                                                | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `memoryReservation`                                                                                          | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `modeSwarm`                                                                                                  | [operations.PostgresRemoveModeSwarm](../../models/operations/postgresremovemodeswarm.md)                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `mounts`                                                                                                     | [operations.PostgresRemoveMount](../../models/operations/postgresremovemount.md)[]                           | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `name`                                                                                                       | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `networkSwarm`                                                                                               | [operations.PostgresRemoveNetworkSwarm](../../models/operations/postgresremovenetworkswarm.md)[]             | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `placementSwarm`                                                                                             | [operations.PostgresRemovePlacementSwarm](../../models/operations/postgresremoveplacementswarm.md)           | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `postgresId`                                                                                                 | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `replicas`                                                                                                   | *number*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `restartPolicySwarm`                                                                                         | [operations.PostgresRemoveRestartPolicySwarm](../../models/operations/postgresremoverestartpolicyswarm.md)   | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `rollbackConfigSwarm`                                                                                        | [operations.PostgresRemoveRollbackConfigSwarm](../../models/operations/postgresremoverollbackconfigswarm.md) | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `server`                                                                                                     | [operations.PostgresRemoveServer](../../models/operations/postgresremoveserver.md)                           | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `serverId`                                                                                                   | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `updateConfigSwarm`                                                                                          | [operations.PostgresRemoveUpdateConfigSwarm](../../models/operations/postgresremoveupdateconfigswarm.md)     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
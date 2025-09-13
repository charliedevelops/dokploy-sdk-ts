# MariadbRemoveResponseBody

Successful response

## Example Usage

```typescript
import { MariadbRemoveResponseBody } from "dokploy-sdk/models/operations";

let value: MariadbRemoveResponseBody = {
  appName: "<value>",
  applicationStatus: "error",
  backups: [
    {
      appName: "<value>",
      backupId: "<id>",
      backupType: "compose",
      composeId: "<id>",
      database: "<value>",
      databaseType: "mysql",
      destinationId: "<id>",
      enabled: false,
      keepLatestCount: 5485.5,
      mariadbId: "<id>",
      mongoId: "<id>",
      mysqlId: "<id>",
      postgresId: "<id>",
      prefix: "<value>",
      schedule: "<value>",
      serviceName: "<value>",
      userId: "<id>",
    },
  ],
  command: "<value>",
  cpuLimit: "<value>",
  cpuReservation: "<value>",
  createdAt: "1713153825006",
  databaseName: "<value>",
  databasePassword: "<value>",
  databaseRootPassword: "<value>",
  databaseUser: "<value>",
  description:
    "magnificent deploy goodwill foodstuffs shakily certainly as fatally split showy",
  dockerImage: "<value>",
  env: "<value>",
  environment: {
    createdAt: "1707769703708",
    description:
      "boo decide blank tightly abaft supposing smooth completion underneath till",
    env: "<value>",
    environmentId: "<id>",
    name: "<value>",
    project: {
      createdAt: "1728866695967",
      description: "sheathe lovingly freely",
      env: "<value>",
      name: "<value>",
      organizationId: "<id>",
      projectId: "<id>",
    },
    projectId: "<id>",
  },
  environmentId: "<id>",
  externalPort: 4214.67,
  healthCheckSwarm: {},
  labelsSwarm: {
    "key": "<value>",
    "key1": "<value>",
    "key2": "<value>",
  },
  mariadbId: "<id>",
  memoryLimit: "<value>",
  memoryReservation: "<value>",
  modeSwarm: {},
  mounts: [],
  name: "<value>",
  networkSwarm: [
    {},
  ],
  placementSwarm: {},
  replicas: 6249.32,
  restartPolicySwarm: {},
  rollbackConfigSwarm: {
    order: "<value>",
    parallelism: 7647.64,
  },
  server: {
    appName: "<value>",
    command: "<value>",
    createdAt: "1727218210474",
    description: null,
    enableDockerCleanup: true,
    ipAddress: "3cfc:bb15:9736:6eae:6b5f:baed:2dfe:7ab7",
    metricsConfig: {
      "key": "<value>",
    },
    name: "<value>",
    organizationId: "<id>",
    port: 2997.69,
    serverId: "<id>",
    serverStatus: "active",
    sshKeyId: "<id>",
    username: "Arlie.Parker1",
  },
  serverId: null,
  updateConfigSwarm: {
    order: "<value>",
    parallelism: 6803.16,
  },
};
```

## Fields

| Field                                                                                                      | Type                                                                                                       | Required                                                                                                   | Description                                                                                                |
| ---------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- |
| `appName`                                                                                                  | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `applicationStatus`                                                                                        | [operations.MariadbRemoveApplicationStatus](../../models/operations/mariadbremoveapplicationstatus.md)     | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `backups`                                                                                                  | [operations.MariadbRemoveBackup](../../models/operations/mariadbremovebackup.md)[]                         | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `command`                                                                                                  | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `cpuLimit`                                                                                                 | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `cpuReservation`                                                                                           | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `createdAt`                                                                                                | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `databaseName`                                                                                             | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `databasePassword`                                                                                         | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `databaseRootPassword`                                                                                     | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `databaseUser`                                                                                             | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `description`                                                                                              | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `dockerImage`                                                                                              | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `env`                                                                                                      | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `environment`                                                                                              | [operations.MariadbRemoveEnvironment](../../models/operations/mariadbremoveenvironment.md)                 | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `environmentId`                                                                                            | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `externalPort`                                                                                             | *number*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `healthCheckSwarm`                                                                                         | [operations.MariadbRemoveHealthCheckSwarm](../../models/operations/mariadbremovehealthcheckswarm.md)       | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `labelsSwarm`                                                                                              | Record<string, *string*>                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `mariadbId`                                                                                                | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `memoryLimit`                                                                                              | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `memoryReservation`                                                                                        | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `modeSwarm`                                                                                                | [operations.MariadbRemoveModeSwarm](../../models/operations/mariadbremovemodeswarm.md)                     | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `mounts`                                                                                                   | [operations.MariadbRemoveMount](../../models/operations/mariadbremovemount.md)[]                           | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `name`                                                                                                     | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `networkSwarm`                                                                                             | [operations.MariadbRemoveNetworkSwarm](../../models/operations/mariadbremovenetworkswarm.md)[]             | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `placementSwarm`                                                                                           | [operations.MariadbRemovePlacementSwarm](../../models/operations/mariadbremoveplacementswarm.md)           | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `replicas`                                                                                                 | *number*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `restartPolicySwarm`                                                                                       | [operations.MariadbRemoveRestartPolicySwarm](../../models/operations/mariadbremoverestartpolicyswarm.md)   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `rollbackConfigSwarm`                                                                                      | [operations.MariadbRemoveRollbackConfigSwarm](../../models/operations/mariadbremoverollbackconfigswarm.md) | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `server`                                                                                                   | [operations.MariadbRemoveServer](../../models/operations/mariadbremoveserver.md)                           | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `serverId`                                                                                                 | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `updateConfigSwarm`                                                                                        | [operations.MariadbRemoveUpdateConfigSwarm](../../models/operations/mariadbremoveupdateconfigswarm.md)     | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
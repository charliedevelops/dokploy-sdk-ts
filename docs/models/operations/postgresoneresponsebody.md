# PostgresOneResponseBody

Successful response

## Example Usage

```typescript
import { PostgresOneResponseBody } from "dokploy-sdk/models/operations";

let value: PostgresOneResponseBody = {
  appName: "<value>",
  applicationStatus: "idle",
  backups: [
    {
      appName: "<value>",
      backupId: "<id>",
      backupType: "compose",
      composeId: null,
      database: "<value>",
      databaseType: "mysql",
      destinationId: "<id>",
      enabled: false,
      keepLatestCount: 4781.95,
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
  createdAt: "1733806182342",
  databaseName: "<value>",
  databasePassword: "<value>",
  databaseUser: "<value>",
  description: "knitting along co-producer atop possible boohoo pomelo",
  dockerImage: "<value>",
  env: "<value>",
  environment: {
    createdAt: "1721666022691",
    description: "instead burly nor knavishly upbeat elver",
    env: "<value>",
    environmentId: "<id>",
    name: "<value>",
    project: {
      createdAt: "1705027263361",
      description: "softly for than who aw",
      env: "<value>",
      name: "<value>",
      organizationId: "<id>",
      projectId: "<id>",
    },
    projectId: "<id>",
  },
  environmentId: "<id>",
  externalPort: 8384.93,
  healthCheckSwarm: {},
  labelsSwarm: {},
  memoryLimit: "<value>",
  memoryReservation: "<value>",
  modeSwarm: null,
  mounts: [
    {
      applicationId: "<id>",
      composeId: "<id>",
      content: "<value>",
      filePath: "/bin/sure_footed_soft_archaeology.m2a",
      hostPath: null,
      mariadbId: "<id>",
      mongoId: "<id>",
      mountId: "<id>",
      mountPath: "<value>",
      mysqlId: "<id>",
      postgresId: "<id>",
      redisId: "<id>",
      serviceType: "application",
      type: "bind",
      volumeName: null,
    },
  ],
  name: "<value>",
  networkSwarm: [
    {},
  ],
  placementSwarm: {},
  postgresId: "<id>",
  replicas: 375.64,
  restartPolicySwarm: {},
  rollbackConfigSwarm: {
    order: "<value>",
    parallelism: 7805.99,
  },
  server: {
    appName: "<value>",
    command: "<value>",
    createdAt: "1731901264634",
    description: "stratify yowza eek urgently impact gee crushing ick",
    enableDockerCleanup: false,
    ipAddress: "195.108.223.13",
    metricsConfig: [
      "<value 1>",
      "<value 2>",
    ],
    name: "<value>",
    organizationId: "<id>",
    port: 8305.37,
    serverId: "<id>",
    serverStatus: "inactive",
    sshKeyId: "<id>",
    username: "Earnestine_Larkin",
  },
  serverId: "<id>",
  updateConfigSwarm: {
    order: "<value>",
    parallelism: 9205.54,
  },
};
```

## Fields

| Field                                                                                                  | Type                                                                                                   | Required                                                                                               | Description                                                                                            |
| ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ |
| `appName`                                                                                              | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `applicationStatus`                                                                                    | [operations.PostgresOneApplicationStatus](../../models/operations/postgresoneapplicationstatus.md)     | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `backups`                                                                                              | [operations.PostgresOneBackup](../../models/operations/postgresonebackup.md)[]                         | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `command`                                                                                              | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `cpuLimit`                                                                                             | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `cpuReservation`                                                                                       | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `createdAt`                                                                                            | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `databaseName`                                                                                         | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `databasePassword`                                                                                     | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `databaseUser`                                                                                         | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `description`                                                                                          | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `dockerImage`                                                                                          | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `env`                                                                                                  | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `environment`                                                                                          | [operations.PostgresOneEnvironment](../../models/operations/postgresoneenvironment.md)                 | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `environmentId`                                                                                        | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `externalPort`                                                                                         | *number*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `healthCheckSwarm`                                                                                     | [operations.PostgresOneHealthCheckSwarm](../../models/operations/postgresonehealthcheckswarm.md)       | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `labelsSwarm`                                                                                          | Record<string, *string*>                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `memoryLimit`                                                                                          | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `memoryReservation`                                                                                    | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `modeSwarm`                                                                                            | [operations.PostgresOneModeSwarm](../../models/operations/postgresonemodeswarm.md)                     | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `mounts`                                                                                               | [operations.PostgresOneMount](../../models/operations/postgresonemount.md)[]                           | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `name`                                                                                                 | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `networkSwarm`                                                                                         | [operations.PostgresOneNetworkSwarm](../../models/operations/postgresonenetworkswarm.md)[]             | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `placementSwarm`                                                                                       | [operations.PostgresOnePlacementSwarm](../../models/operations/postgresoneplacementswarm.md)           | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `postgresId`                                                                                           | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `replicas`                                                                                             | *number*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `restartPolicySwarm`                                                                                   | [operations.PostgresOneRestartPolicySwarm](../../models/operations/postgresonerestartpolicyswarm.md)   | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `rollbackConfigSwarm`                                                                                  | [operations.PostgresOneRollbackConfigSwarm](../../models/operations/postgresonerollbackconfigswarm.md) | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `server`                                                                                               | [operations.PostgresOneServer](../../models/operations/postgresoneserver.md)                           | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `serverId`                                                                                             | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `updateConfigSwarm`                                                                                    | [operations.PostgresOneUpdateConfigSwarm](../../models/operations/postgresoneupdateconfigswarm.md)     | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
# PostgresOneResponseBody

Successful response

## Example Usage

```typescript
import { PostgresOneResponseBody } from "dokploy-sdk/models/operations";

let value: PostgresOneResponseBody = {
  postgresId: "<id>",
  name: "<value>",
  appName: "<value>",
  databaseName: "<value>",
  databaseUser: "<value>",
  databasePassword: "<value>",
  description:
    "liberalize neat if settle as misappropriate round young iridescence",
  dockerImage: "<value>",
  command: "<value>",
  env: "<value>",
  memoryReservation: "<value>",
  externalPort: 6900.12,
  memoryLimit: "<value>",
  cpuReservation: "<value>",
  cpuLimit: "<value>",
  applicationStatus: "running",
  healthCheckSwarm: null,
  restartPolicySwarm: {},
  placementSwarm: {},
  updateConfigSwarm: {
    parallelism: 6267.78,
    order: "<value>",
  },
  rollbackConfigSwarm: {
    parallelism: 3788.88,
    order: "<value>",
  },
  modeSwarm: {},
  labelsSwarm: {
    "key": "<value>",
    "key1": "<value>",
  },
  networkSwarm: [],
  replicas: 5973.1,
  createdAt: "1707162415224",
  environmentId: "<id>",
  serverId: "<id>",
  environment: {
    environmentId: "<id>",
    name: "<value>",
    description: "after drat supposing hence management",
    createdAt: "1731917924351",
    env: "<value>",
    projectId: "<id>",
    project: {
      projectId: "<id>",
      name: "<value>",
      description: "fully yearly fooey usefully oh phew above",
      createdAt: "1729177506214",
      organizationId: "<id>",
      env: "<value>",
    },
  },
  mounts: [
    {
      mountId: "<id>",
      type: "volume",
      hostPath: null,
      volumeName: "<value>",
      filePath: "/opt/sbin/playfully_haircut_how.png",
      content: "<value>",
      serviceType: "postgres",
      mountPath: "<value>",
      applicationId: "<id>",
      postgresId: null,
      mariadbId: "<id>",
      mongoId: null,
      mysqlId: "<id>",
      redisId: "<id>",
      composeId: "<id>",
    },
  ],
  server: null,
  backups: [
    {
      backupId: "<id>",
      appName: "<value>",
      schedule: "<value>",
      enabled: false,
      database: "<value>",
      prefix: "<value>",
      serviceName: "<value>",
      destinationId: "<id>",
      keepLatestCount: 2579.45,
      backupType: "compose",
      databaseType: "mysql",
      composeId: "<id>",
      postgresId: "<id>",
      mariadbId: "<id>",
      mysqlId: "<id>",
      mongoId: "<id>",
      userId: "<id>",
    },
  ],
};
```

## Fields

| Field                                                                                                  | Type                                                                                                   | Required                                                                                               | Description                                                                                            |
| ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ |
| `postgresId`                                                                                           | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `name`                                                                                                 | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `appName`                                                                                              | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `databaseName`                                                                                         | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `databaseUser`                                                                                         | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `databasePassword`                                                                                     | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `description`                                                                                          | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `dockerImage`                                                                                          | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `command`                                                                                              | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `env`                                                                                                  | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `memoryReservation`                                                                                    | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `externalPort`                                                                                         | *number*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `memoryLimit`                                                                                          | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `cpuReservation`                                                                                       | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `cpuLimit`                                                                                             | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `applicationStatus`                                                                                    | [operations.PostgresOneApplicationStatus](../../models/operations/postgresoneapplicationstatus.md)     | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `healthCheckSwarm`                                                                                     | [operations.PostgresOneHealthCheckSwarm](../../models/operations/postgresonehealthcheckswarm.md)       | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `restartPolicySwarm`                                                                                   | [operations.PostgresOneRestartPolicySwarm](../../models/operations/postgresonerestartpolicyswarm.md)   | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `placementSwarm`                                                                                       | [operations.PostgresOnePlacementSwarm](../../models/operations/postgresoneplacementswarm.md)           | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `updateConfigSwarm`                                                                                    | [operations.PostgresOneUpdateConfigSwarm](../../models/operations/postgresoneupdateconfigswarm.md)     | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `rollbackConfigSwarm`                                                                                  | [operations.PostgresOneRollbackConfigSwarm](../../models/operations/postgresonerollbackconfigswarm.md) | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `modeSwarm`                                                                                            | [operations.PostgresOneModeSwarm](../../models/operations/postgresonemodeswarm.md)                     | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `labelsSwarm`                                                                                          | Record<string, *string*>                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `networkSwarm`                                                                                         | [operations.PostgresOneNetworkSwarm](../../models/operations/postgresonenetworkswarm.md)[]             | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `replicas`                                                                                             | *number*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `createdAt`                                                                                            | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `environmentId`                                                                                        | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `serverId`                                                                                             | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `environment`                                                                                          | [operations.PostgresOneEnvironment](../../models/operations/postgresoneenvironment.md)                 | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `mounts`                                                                                               | [operations.PostgresOneMount](../../models/operations/postgresonemount.md)[]                           | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `server`                                                                                               | [operations.PostgresOneServer](../../models/operations/postgresoneserver.md)                           | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `backups`                                                                                              | [operations.PostgresOneBackup](../../models/operations/postgresonebackup.md)[]                         | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
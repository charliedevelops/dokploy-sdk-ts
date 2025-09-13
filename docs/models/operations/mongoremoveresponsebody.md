# MongoRemoveResponseBody

Successful response

## Example Usage

```typescript
import { MongoRemoveResponseBody } from "dokploy-sdk/models/operations";

let value: MongoRemoveResponseBody = {
  appName: "<value>",
  applicationStatus: "error",
  backups: [
    {
      appName: "<value>",
      backupId: "<id>",
      backupType: "compose",
      composeId: "<id>",
      database: "<value>",
      databaseType: "web-server",
      destinationId: "<id>",
      enabled: null,
      keepLatestCount: 3008.02,
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
  cpuReservation: null,
  createdAt: "1720263241079",
  databasePassword: "<value>",
  databaseUser: "<value>",
  description: "tragic fooey phooey impressionable condense nudge",
  dockerImage: "<value>",
  env: "<value>",
  environment: {
    createdAt: "1731845761406",
    description: "thyme inexperienced vainly service um phew",
    env: "<value>",
    environmentId: "<id>",
    name: "<value>",
    project: {
      createdAt: "1720183877882",
      description:
        "supposing from where release tabulate drat bob pish uselessly once",
      env: "<value>",
      name: "<value>",
      organizationId: "<id>",
      projectId: "<id>",
    },
    projectId: "<id>",
  },
  environmentId: "<id>",
  externalPort: 7742.91,
  healthCheckSwarm: {},
  labelsSwarm: {},
  memoryLimit: "<value>",
  memoryReservation: "<value>",
  modeSwarm: {},
  mongoId: "<id>",
  mounts: [
    {
      applicationId: "<id>",
      composeId: "<id>",
      content: "<value>",
      filePath: "/boot/defaults/birdbath_range_but.rar",
      hostPath: "<value>",
      mariadbId: "<id>",
      mongoId: "<id>",
      mountId: "<id>",
      mountPath: "<value>",
      mysqlId: "<id>",
      postgresId: "<id>",
      redisId: null,
      serviceType: "compose",
      type: "bind",
      volumeName: "<value>",
    },
  ],
  name: "<value>",
  networkSwarm: [],
  placementSwarm: {},
  replicaSets: false,
  replicas: 5271.16,
  restartPolicySwarm: {},
  rollbackConfigSwarm: {
    order: "<value>",
    parallelism: 3035.55,
  },
  server: {
    appName: "<value>",
    command: "<value>",
    createdAt: "1730665355632",
    description: "deliberately oh meh gadzooks",
    enableDockerCleanup: false,
    ipAddress: "253.143.127.44",
    metricsConfig: 3094,
    name: "<value>",
    organizationId: "<id>",
    port: 5305.36,
    serverId: "<id>",
    serverStatus: "inactive",
    sshKeyId: "<id>",
    username: "Kristoffer_Larkin66",
  },
  serverId: "<id>",
  updateConfigSwarm: {
    order: "<value>",
    parallelism: 4544.66,
  },
};
```

## Fields

| Field                                                                                                  | Type                                                                                                   | Required                                                                                               | Description                                                                                            |
| ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ |
| `appName`                                                                                              | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `applicationStatus`                                                                                    | [operations.MongoRemoveApplicationStatus](../../models/operations/mongoremoveapplicationstatus.md)     | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `backups`                                                                                              | [operations.MongoRemoveBackup](../../models/operations/mongoremovebackup.md)[]                         | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `command`                                                                                              | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `cpuLimit`                                                                                             | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `cpuReservation`                                                                                       | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `createdAt`                                                                                            | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `databasePassword`                                                                                     | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `databaseUser`                                                                                         | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `description`                                                                                          | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `dockerImage`                                                                                          | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `env`                                                                                                  | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `environment`                                                                                          | [operations.MongoRemoveEnvironment](../../models/operations/mongoremoveenvironment.md)                 | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `environmentId`                                                                                        | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `externalPort`                                                                                         | *number*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `healthCheckSwarm`                                                                                     | [operations.MongoRemoveHealthCheckSwarm](../../models/operations/mongoremovehealthcheckswarm.md)       | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `labelsSwarm`                                                                                          | Record<string, *string*>                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `memoryLimit`                                                                                          | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `memoryReservation`                                                                                    | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `modeSwarm`                                                                                            | [operations.MongoRemoveModeSwarm](../../models/operations/mongoremovemodeswarm.md)                     | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `mongoId`                                                                                              | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `mounts`                                                                                               | [operations.MongoRemoveMount](../../models/operations/mongoremovemount.md)[]                           | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `name`                                                                                                 | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `networkSwarm`                                                                                         | [operations.MongoRemoveNetworkSwarm](../../models/operations/mongoremovenetworkswarm.md)[]             | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `placementSwarm`                                                                                       | [operations.MongoRemovePlacementSwarm](../../models/operations/mongoremoveplacementswarm.md)           | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `replicaSets`                                                                                          | *boolean*                                                                                              | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `replicas`                                                                                             | *number*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `restartPolicySwarm`                                                                                   | [operations.MongoRemoveRestartPolicySwarm](../../models/operations/mongoremoverestartpolicyswarm.md)   | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `rollbackConfigSwarm`                                                                                  | [operations.MongoRemoveRollbackConfigSwarm](../../models/operations/mongoremoverollbackconfigswarm.md) | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `server`                                                                                               | [operations.MongoRemoveServer](../../models/operations/mongoremoveserver.md)                           | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `serverId`                                                                                             | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `updateConfigSwarm`                                                                                    | [operations.MongoRemoveUpdateConfigSwarm](../../models/operations/mongoremoveupdateconfigswarm.md)     | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
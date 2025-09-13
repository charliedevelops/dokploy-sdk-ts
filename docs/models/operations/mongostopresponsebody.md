# MongoStopResponseBody

Successful response

## Example Usage

```typescript
import { MongoStopResponseBody } from "dokploy-sdk/models/operations";

let value: MongoStopResponseBody = {
  appName: "<value>",
  applicationStatus: "done",
  backups: [
    {
      appName: "<value>",
      backupId: "<id>",
      backupType: "database",
      composeId: "<id>",
      database: "<value>",
      databaseType: "web-server",
      destinationId: "<id>",
      enabled: true,
      keepLatestCount: 6130.66,
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
  command: null,
  cpuLimit: "<value>",
  cpuReservation: "<value>",
  createdAt: "1712703478305",
  databasePassword: "<value>",
  databaseUser: "<value>",
  description: "doodle opposite beside cautiously",
  dockerImage: "<value>",
  env: "<value>",
  environment: {
    createdAt: "1712067260170",
    description: "volunteer devastation sushi menacing",
    env: "<value>",
    environmentId: "<id>",
    name: "<value>",
    project: {
      createdAt: "1718458472155",
      description: "guilt next pessimistic so surprisingly massage because",
      env: "<value>",
      name: "<value>",
      organizationId: "<id>",
      projectId: "<id>",
    },
    projectId: "<id>",
  },
  environmentId: "<id>",
  externalPort: 5904.39,
  healthCheckSwarm: {},
  labelsSwarm: {
    "key": "<value>",
  },
  memoryLimit: "<value>",
  memoryReservation: "<value>",
  modeSwarm: {},
  mongoId: "<id>",
  mounts: [
    {
      applicationId: "<id>",
      composeId: "<id>",
      content: "<value>",
      filePath: "/lib/weep.rng",
      hostPath: null,
      mariadbId: "<id>",
      mongoId: "<id>",
      mountId: "<id>",
      mountPath: "<value>",
      mysqlId: null,
      postgresId: null,
      redisId: "<id>",
      serviceType: "application",
      type: "volume",
      volumeName: "<value>",
    },
  ],
  name: "<value>",
  networkSwarm: [
    {},
  ],
  placementSwarm: {},
  replicaSets: true,
  replicas: 7109.54,
  restartPolicySwarm: null,
  rollbackConfigSwarm: {
    order: "<value>",
    parallelism: 8515.77,
  },
  server: {
    appName: "<value>",
    command: "<value>",
    createdAt: "1722969510891",
    description: "till boo towards sock around brightly tender what",
    enableDockerCleanup: true,
    ipAddress: "da0a:daeb:affa:fdcb:cceb:13af:6f4d:d124",
    metricsConfig: "null",
    name: "<value>",
    organizationId: "<id>",
    port: 1892.14,
    serverId: "<id>",
    serverStatus: "inactive",
    sshKeyId: "<id>",
    username: "Joseph_Lueilwitz",
  },
  serverId: "<id>",
  updateConfigSwarm: {
    order: "<value>",
    parallelism: 3053.55,
  },
};
```

## Fields

| Field                                                                                              | Type                                                                                               | Required                                                                                           | Description                                                                                        |
| -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| `appName`                                                                                          | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `applicationStatus`                                                                                | [operations.MongoStopApplicationStatus](../../models/operations/mongostopapplicationstatus.md)     | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `backups`                                                                                          | [operations.MongoStopBackup](../../models/operations/mongostopbackup.md)[]                         | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `command`                                                                                          | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `cpuLimit`                                                                                         | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `cpuReservation`                                                                                   | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `createdAt`                                                                                        | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `databasePassword`                                                                                 | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `databaseUser`                                                                                     | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `description`                                                                                      | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `dockerImage`                                                                                      | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `env`                                                                                              | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `environment`                                                                                      | [operations.MongoStopEnvironment](../../models/operations/mongostopenvironment.md)                 | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `environmentId`                                                                                    | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `externalPort`                                                                                     | *number*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `healthCheckSwarm`                                                                                 | [operations.MongoStopHealthCheckSwarm](../../models/operations/mongostophealthcheckswarm.md)       | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `labelsSwarm`                                                                                      | Record<string, *string*>                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `memoryLimit`                                                                                      | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `memoryReservation`                                                                                | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `modeSwarm`                                                                                        | [operations.MongoStopModeSwarm](../../models/operations/mongostopmodeswarm.md)                     | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `mongoId`                                                                                          | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `mounts`                                                                                           | [operations.MongoStopMount](../../models/operations/mongostopmount.md)[]                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `name`                                                                                             | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `networkSwarm`                                                                                     | [operations.MongoStopNetworkSwarm](../../models/operations/mongostopnetworkswarm.md)[]             | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `placementSwarm`                                                                                   | [operations.MongoStopPlacementSwarm](../../models/operations/mongostopplacementswarm.md)           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `replicaSets`                                                                                      | *boolean*                                                                                          | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `replicas`                                                                                         | *number*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `restartPolicySwarm`                                                                               | [operations.MongoStopRestartPolicySwarm](../../models/operations/mongostoprestartpolicyswarm.md)   | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `rollbackConfigSwarm`                                                                              | [operations.MongoStopRollbackConfigSwarm](../../models/operations/mongostoprollbackconfigswarm.md) | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `server`                                                                                           | [operations.MongoStopServer](../../models/operations/mongostopserver.md)                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `serverId`                                                                                         | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `updateConfigSwarm`                                                                                | [operations.MongoStopUpdateConfigSwarm](../../models/operations/mongostopupdateconfigswarm.md)     | :heavy_check_mark:                                                                                 | N/A                                                                                                |
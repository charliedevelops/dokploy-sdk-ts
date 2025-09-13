# MongoStopResponseBody

Successful response

## Example Usage

```typescript
import { MongoStopResponseBody } from "dokploy-sdk/models/operations";

let value: MongoStopResponseBody = {
  mongoId: "<id>",
  name: "<value>",
  appName: "<value>",
  description:
    "quarrelsomely absent that briskly ack opposite hence darling neatly against",
  databaseUser: "<value>",
  databasePassword: "<value>",
  dockerImage: "<value>",
  command: "<value>",
  env: "<value>",
  memoryReservation: "<value>",
  memoryLimit: "<value>",
  cpuReservation: "<value>",
  cpuLimit: "<value>",
  externalPort: 5989.84,
  applicationStatus: "done",
  healthCheckSwarm: {},
  restartPolicySwarm: {},
  placementSwarm: {},
  updateConfigSwarm: {
    parallelism: 3407.28,
    order: "<value>",
  },
  rollbackConfigSwarm: {
    parallelism: 6553.82,
    order: "<value>",
  },
  modeSwarm: {},
  labelsSwarm: {
    "key": "<value>",
  },
  networkSwarm: [
    {},
  ],
  replicas: 5931.13,
  createdAt: "1711749282257",
  environmentId: "<id>",
  serverId: "<id>",
  replicaSets: false,
  environment: {
    environmentId: "<id>",
    name: "<value>",
    description: "gosh horst midst exaggerate the",
    createdAt: "1732605263973",
    env: "<value>",
    projectId: "<id>",
    project: {
      projectId: "<id>",
      name: "<value>",
      description: "unwelcome hopelessly anneal",
      createdAt: "1725708514063",
      organizationId: "<id>",
      env: "<value>",
    },
  },
  mounts: [
    {
      mountId: "<id>",
      type: "volume",
      hostPath: "<value>",
      volumeName: "<value>",
      filePath: "/proc/shear_upon_absent.svg",
      content: "<value>",
      serviceType: "postgres",
      mountPath: "<value>",
      applicationId: null,
      postgresId: "<id>",
      mariadbId: "<id>",
      mongoId: "<id>",
      mysqlId: "<id>",
      redisId: "<id>",
      composeId: "<id>",
    },
  ],
  server: {
    serverId: "<id>",
    name: "<value>",
    description: "outfox ick poor better pish",
    ipAddress: "1241:c4ec:b5cf:c999:6b3e:5228:7fa1:5e63",
    port: 9567.89,
    username: "Reinhold_Connelly",
    appName: "<value>",
    enableDockerCleanup: true,
    createdAt: "1705659501380",
    organizationId: "<id>",
    serverStatus: "active",
    command: "<value>",
    sshKeyId: "<id>",
    metricsConfig: "<value>",
  },
  backups: [
    {
      backupId: "<id>",
      appName: "<value>",
      schedule: "<value>",
      enabled: null,
      database: "<value>",
      prefix: "<value>",
      serviceName: "<value>",
      destinationId: "<id>",
      keepLatestCount: 5395.88,
      backupType: "database",
      databaseType: "mongo",
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

| Field                                                                                              | Type                                                                                               | Required                                                                                           | Description                                                                                        |
| -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| `mongoId`                                                                                          | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `name`                                                                                             | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `appName`                                                                                          | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `description`                                                                                      | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `databaseUser`                                                                                     | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `databasePassword`                                                                                 | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `dockerImage`                                                                                      | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `command`                                                                                          | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `env`                                                                                              | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `memoryReservation`                                                                                | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `memoryLimit`                                                                                      | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `cpuReservation`                                                                                   | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `cpuLimit`                                                                                         | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `externalPort`                                                                                     | *number*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `applicationStatus`                                                                                | [operations.MongoStopApplicationStatus](../../models/operations/mongostopapplicationstatus.md)     | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `healthCheckSwarm`                                                                                 | [operations.MongoStopHealthCheckSwarm](../../models/operations/mongostophealthcheckswarm.md)       | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `restartPolicySwarm`                                                                               | [operations.MongoStopRestartPolicySwarm](../../models/operations/mongostoprestartpolicyswarm.md)   | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `placementSwarm`                                                                                   | [operations.MongoStopPlacementSwarm](../../models/operations/mongostopplacementswarm.md)           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `updateConfigSwarm`                                                                                | [operations.MongoStopUpdateConfigSwarm](../../models/operations/mongostopupdateconfigswarm.md)     | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `rollbackConfigSwarm`                                                                              | [operations.MongoStopRollbackConfigSwarm](../../models/operations/mongostoprollbackconfigswarm.md) | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `modeSwarm`                                                                                        | [operations.MongoStopModeSwarm](../../models/operations/mongostopmodeswarm.md)                     | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `labelsSwarm`                                                                                      | Record<string, *string*>                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `networkSwarm`                                                                                     | [operations.MongoStopNetworkSwarm](../../models/operations/mongostopnetworkswarm.md)[]             | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `replicas`                                                                                         | *number*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `createdAt`                                                                                        | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `environmentId`                                                                                    | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `serverId`                                                                                         | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `replicaSets`                                                                                      | *boolean*                                                                                          | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `environment`                                                                                      | [operations.MongoStopEnvironment](../../models/operations/mongostopenvironment.md)                 | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `mounts`                                                                                           | [operations.MongoStopMount](../../models/operations/mongostopmount.md)[]                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `server`                                                                                           | [operations.MongoStopServer](../../models/operations/mongostopserver.md)                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `backups`                                                                                          | [operations.MongoStopBackup](../../models/operations/mongostopbackup.md)[]                         | :heavy_check_mark:                                                                                 | N/A                                                                                                |
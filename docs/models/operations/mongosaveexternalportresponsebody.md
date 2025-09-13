# MongoSaveExternalPortResponseBody

Successful response

## Example Usage

```typescript
import { MongoSaveExternalPortResponseBody } from "dokploy-sdk/models/operations";

let value: MongoSaveExternalPortResponseBody = {
  mongoId: "<id>",
  name: "<value>",
  appName: "<value>",
  description: "sense for modulo scholarship",
  databaseUser: "<value>",
  databasePassword: "<value>",
  dockerImage: "<value>",
  command: "<value>",
  env: "<value>",
  memoryReservation: null,
  memoryLimit: "<value>",
  cpuReservation: "<value>",
  cpuLimit: "<value>",
  externalPort: 1148.94,
  applicationStatus: "done",
  healthCheckSwarm: {},
  restartPolicySwarm: {},
  placementSwarm: {},
  updateConfigSwarm: {
    parallelism: 6930.95,
    order: "<value>",
  },
  rollbackConfigSwarm: {
    parallelism: 9258.44,
    order: "<value>",
  },
  modeSwarm: {},
  labelsSwarm: {
    "key": "<value>",
    "key1": "<value>",
  },
  networkSwarm: [
    {},
  ],
  replicas: 5940.89,
  createdAt: "1704258420488",
  environmentId: "<id>",
  serverId: "<id>",
  replicaSets: false,
  environment: {
    environmentId: "<id>",
    name: "<value>",
    description:
      "anenst ill overload source suspiciously appliance meatloaf loyally qua",
    createdAt: "1716137948019",
    env: "<value>",
    projectId: "<id>",
    project: {
      projectId: "<id>",
      name: "<value>",
      description: "fisherman given till tattered",
      createdAt: "1711813881104",
      organizationId: "<id>",
      env: "<value>",
    },
  },
  mounts: [],
  server: null,
  backups: [
    {
      backupId: "<id>",
      appName: "<value>",
      schedule: "<value>",
      enabled: true,
      database: "<value>",
      prefix: "<value>",
      serviceName: "<value>",
      destinationId: "<id>",
      keepLatestCount: 3086.92,
      backupType: "compose",
      databaseType: "mariadb",
      composeId: "<id>",
      postgresId: "<id>",
      mariadbId: null,
      mysqlId: "<id>",
      mongoId: "<id>",
      userId: null,
    },
  ],
};
```

## Fields

| Field                                                                                                                      | Type                                                                                                                       | Required                                                                                                                   | Description                                                                                                                |
| -------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------- |
| `mongoId`                                                                                                                  | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `name`                                                                                                                     | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `appName`                                                                                                                  | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `description`                                                                                                              | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `databaseUser`                                                                                                             | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `databasePassword`                                                                                                         | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `dockerImage`                                                                                                              | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `command`                                                                                                                  | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `env`                                                                                                                      | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `memoryReservation`                                                                                                        | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `memoryLimit`                                                                                                              | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `cpuReservation`                                                                                                           | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `cpuLimit`                                                                                                                 | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `externalPort`                                                                                                             | *number*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `applicationStatus`                                                                                                        | [operations.MongoSaveExternalPortApplicationStatus](../../models/operations/mongosaveexternalportapplicationstatus.md)     | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `healthCheckSwarm`                                                                                                         | [operations.MongoSaveExternalPortHealthCheckSwarm](../../models/operations/mongosaveexternalporthealthcheckswarm.md)       | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `restartPolicySwarm`                                                                                                       | [operations.MongoSaveExternalPortRestartPolicySwarm](../../models/operations/mongosaveexternalportrestartpolicyswarm.md)   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `placementSwarm`                                                                                                           | [operations.MongoSaveExternalPortPlacementSwarm](../../models/operations/mongosaveexternalportplacementswarm.md)           | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `updateConfigSwarm`                                                                                                        | [operations.MongoSaveExternalPortUpdateConfigSwarm](../../models/operations/mongosaveexternalportupdateconfigswarm.md)     | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `rollbackConfigSwarm`                                                                                                      | [operations.MongoSaveExternalPortRollbackConfigSwarm](../../models/operations/mongosaveexternalportrollbackconfigswarm.md) | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `modeSwarm`                                                                                                                | [operations.MongoSaveExternalPortModeSwarm](../../models/operations/mongosaveexternalportmodeswarm.md)                     | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `labelsSwarm`                                                                                                              | Record<string, *string*>                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `networkSwarm`                                                                                                             | [operations.MongoSaveExternalPortNetworkSwarm](../../models/operations/mongosaveexternalportnetworkswarm.md)[]             | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `replicas`                                                                                                                 | *number*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `createdAt`                                                                                                                | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `environmentId`                                                                                                            | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `serverId`                                                                                                                 | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `replicaSets`                                                                                                              | *boolean*                                                                                                                  | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `environment`                                                                                                              | [operations.MongoSaveExternalPortEnvironment](../../models/operations/mongosaveexternalportenvironment.md)                 | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `mounts`                                                                                                                   | [operations.MongoSaveExternalPortMount](../../models/operations/mongosaveexternalportmount.md)[]                           | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `server`                                                                                                                   | [operations.MongoSaveExternalPortServer](../../models/operations/mongosaveexternalportserver.md)                           | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `backups`                                                                                                                  | [operations.MongoSaveExternalPortBackup](../../models/operations/mongosaveexternalportbackup.md)[]                         | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
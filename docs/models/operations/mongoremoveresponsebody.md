# MongoRemoveResponseBody

Successful response

## Example Usage

```typescript
import { MongoRemoveResponseBody } from "dokploy-sdk/models/operations";

let value: MongoRemoveResponseBody = {
  mongoId: "<id>",
  name: "<value>",
  appName: "<value>",
  description: "deceivingly rough inside incidentally snuggle scheme bony woot",
  databaseUser: "<value>",
  databasePassword: "<value>",
  dockerImage: "<value>",
  command: "<value>",
  env: null,
  memoryReservation: "<value>",
  memoryLimit: "<value>",
  cpuReservation: "<value>",
  cpuLimit: "<value>",
  externalPort: 4980.8,
  applicationStatus: "running",
  healthCheckSwarm: {},
  restartPolicySwarm: {},
  placementSwarm: {},
  updateConfigSwarm: {
    parallelism: 8000.53,
    order: "<value>",
  },
  rollbackConfigSwarm: {
    parallelism: 1873.33,
    order: "<value>",
  },
  modeSwarm: {},
  labelsSwarm: {
    "key": "<value>",
    "key1": "<value>",
    "key2": "<value>",
  },
  networkSwarm: [
    {},
  ],
  replicas: 4143.4,
  createdAt: "1733888989517",
  environmentId: "<id>",
  serverId: "<id>",
  replicaSets: true,
  environment: {
    environmentId: "<id>",
    name: "<value>",
    description: "hmph diligently pomelo",
    createdAt: "1728378436858",
    env: "<value>",
    projectId: "<id>",
    project: {
      projectId: "<id>",
      name: "<value>",
      description: null,
      createdAt: "1719526613270",
      organizationId: "<id>",
      env: "<value>",
    },
  },
  mounts: [],
  server: {
    serverId: "<id>",
    name: "<value>",
    description: "redress gee yippee amidst",
    ipAddress: "7728:759b:c1f5:d90a:3eb8:b6dc:d30f:b1e8",
    port: 1678.44,
    username: "Kylee.Franey",
    appName: "<value>",
    enableDockerCleanup: true,
    createdAt: "1735119930004",
    organizationId: "<id>",
    serverStatus: "active",
    command: "<value>",
    sshKeyId: "<id>",
    metricsConfig: 7443.89,
  },
  backups: [],
};
```

## Fields

| Field                                                                                                  | Type                                                                                                   | Required                                                                                               | Description                                                                                            |
| ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ |
| `mongoId`                                                                                              | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `name`                                                                                                 | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `appName`                                                                                              | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `description`                                                                                          | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `databaseUser`                                                                                         | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `databasePassword`                                                                                     | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `dockerImage`                                                                                          | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `command`                                                                                              | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `env`                                                                                                  | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `memoryReservation`                                                                                    | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `memoryLimit`                                                                                          | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `cpuReservation`                                                                                       | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `cpuLimit`                                                                                             | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `externalPort`                                                                                         | *number*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `applicationStatus`                                                                                    | [operations.MongoRemoveApplicationStatus](../../models/operations/mongoremoveapplicationstatus.md)     | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `healthCheckSwarm`                                                                                     | [operations.MongoRemoveHealthCheckSwarm](../../models/operations/mongoremovehealthcheckswarm.md)       | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `restartPolicySwarm`                                                                                   | [operations.MongoRemoveRestartPolicySwarm](../../models/operations/mongoremoverestartpolicyswarm.md)   | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `placementSwarm`                                                                                       | [operations.MongoRemovePlacementSwarm](../../models/operations/mongoremoveplacementswarm.md)           | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `updateConfigSwarm`                                                                                    | [operations.MongoRemoveUpdateConfigSwarm](../../models/operations/mongoremoveupdateconfigswarm.md)     | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `rollbackConfigSwarm`                                                                                  | [operations.MongoRemoveRollbackConfigSwarm](../../models/operations/mongoremoverollbackconfigswarm.md) | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `modeSwarm`                                                                                            | [operations.MongoRemoveModeSwarm](../../models/operations/mongoremovemodeswarm.md)                     | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `labelsSwarm`                                                                                          | Record<string, *string*>                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `networkSwarm`                                                                                         | [operations.MongoRemoveNetworkSwarm](../../models/operations/mongoremovenetworkswarm.md)[]             | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `replicas`                                                                                             | *number*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `createdAt`                                                                                            | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `environmentId`                                                                                        | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `serverId`                                                                                             | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `replicaSets`                                                                                          | *boolean*                                                                                              | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `environment`                                                                                          | [operations.MongoRemoveEnvironment](../../models/operations/mongoremoveenvironment.md)                 | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `mounts`                                                                                               | [operations.MongoRemoveMount](../../models/operations/mongoremovemount.md)[]                           | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `server`                                                                                               | [operations.MongoRemoveServer](../../models/operations/mongoremoveserver.md)                           | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `backups`                                                                                              | [operations.MongoRemoveBackup](../../models/operations/mongoremovebackup.md)[]                         | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
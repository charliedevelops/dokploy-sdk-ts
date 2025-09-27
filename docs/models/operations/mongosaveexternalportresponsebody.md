# MongoSaveExternalPortResponseBody

Successful response

## Example Usage

```typescript
import { MongoSaveExternalPortResponseBody } from "dokploy-sdk/models/operations";

let value: MongoSaveExternalPortResponseBody = {
  appName: "<value>",
  applicationStatus: "idle",
  backups: [],
  command: "<value>",
  cpuLimit: "<value>",
  cpuReservation: "<value>",
  createdAt: "1726274799339",
  databasePassword: "<value>",
  databaseUser: "<value>",
  description: "pleasure marketplace pip grouper mixture",
  dockerImage: "<value>",
  env: "<value>",
  environment: {
    createdAt: "1720926766672",
    description:
      "for range quaintly onto haunting chip give confusion lighthearted nor",
    env: "<value>",
    environmentId: "<id>",
    name: "<value>",
    project: {
      createdAt: "1731078943940",
      description: "bookcase disinherit excitable upbeat um phooey within and",
      env: "<value>",
      name: "<value>",
      organizationId: "<id>",
      projectId: "<id>",
    },
    projectId: "<id>",
  },
  environmentId: "<id>",
  externalPort: 9938.39,
  healthCheckSwarm: {},
  labelsSwarm: {
    "key": "<value>",
  },
  memoryLimit: null,
  memoryReservation: null,
  modeSwarm: {},
  mongoId: "<id>",
  mounts: [],
  name: "<value>",
  networkSwarm: [
    {},
  ],
  placementSwarm: {},
  replicaSets: false,
  replicas: 2516.19,
  restartPolicySwarm: {},
  rollbackConfigSwarm: {
    order: "<value>",
    parallelism: 232.6,
  },
  server: {
    appName: "<value>",
    command: "<value>",
    createdAt: "1714293104580",
    description: null,
    enableDockerCleanup: true,
    ipAddress: "0.76.85.88",
    metricsConfig: [
      "<value 1>",
      "<value 2>",
      "<value 3>",
    ],
    name: "<value>",
    organizationId: "<id>",
    port: 6048.1,
    serverId: "<id>",
    serverStatus: "inactive",
    sshKeyId: "<id>",
    username: "Jerad20",
  },
  serverId: "<id>",
  updateConfigSwarm: {
    order: "<value>",
    parallelism: 4864.19,
  },
};
```

## Fields

| Field                                                                                                                      | Type                                                                                                                       | Required                                                                                                                   | Description                                                                                                                |
| -------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------- |
| `appName`                                                                                                                  | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `applicationStatus`                                                                                                        | [operations.MongoSaveExternalPortApplicationStatus](../../models/operations/mongosaveexternalportapplicationstatus.md)     | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `backups`                                                                                                                  | [operations.MongoSaveExternalPortBackup](../../models/operations/mongosaveexternalportbackup.md)[]                         | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `command`                                                                                                                  | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `cpuLimit`                                                                                                                 | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `cpuReservation`                                                                                                           | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `createdAt`                                                                                                                | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `databasePassword`                                                                                                         | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `databaseUser`                                                                                                             | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `description`                                                                                                              | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `dockerImage`                                                                                                              | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `env`                                                                                                                      | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `environment`                                                                                                              | [operations.MongoSaveExternalPortEnvironment](../../models/operations/mongosaveexternalportenvironment.md)                 | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `environmentId`                                                                                                            | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `externalPort`                                                                                                             | *number*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `healthCheckSwarm`                                                                                                         | [operations.MongoSaveExternalPortHealthCheckSwarm](../../models/operations/mongosaveexternalporthealthcheckswarm.md)       | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `labelsSwarm`                                                                                                              | Record<string, *string*>                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `memoryLimit`                                                                                                              | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `memoryReservation`                                                                                                        | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `modeSwarm`                                                                                                                | [operations.MongoSaveExternalPortModeSwarm](../../models/operations/mongosaveexternalportmodeswarm.md)                     | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `mongoId`                                                                                                                  | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `mounts`                                                                                                                   | [operations.MongoSaveExternalPortMount](../../models/operations/mongosaveexternalportmount.md)[]                           | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `name`                                                                                                                     | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `networkSwarm`                                                                                                             | [operations.MongoSaveExternalPortNetworkSwarm](../../models/operations/mongosaveexternalportnetworkswarm.md)[]             | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `placementSwarm`                                                                                                           | [operations.MongoSaveExternalPortPlacementSwarm](../../models/operations/mongosaveexternalportplacementswarm.md)           | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `replicaSets`                                                                                                              | *boolean*                                                                                                                  | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `replicas`                                                                                                                 | *number*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `restartPolicySwarm`                                                                                                       | [operations.MongoSaveExternalPortRestartPolicySwarm](../../models/operations/mongosaveexternalportrestartpolicyswarm.md)   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `rollbackConfigSwarm`                                                                                                      | [operations.MongoSaveExternalPortRollbackConfigSwarm](../../models/operations/mongosaveexternalportrollbackconfigswarm.md) | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `server`                                                                                                                   | [operations.MongoSaveExternalPortServer](../../models/operations/mongosaveexternalportserver.md)                           | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `serverId`                                                                                                                 | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `updateConfigSwarm`                                                                                                        | [operations.MongoSaveExternalPortUpdateConfigSwarm](../../models/operations/mongosaveexternalportupdateconfigswarm.md)     | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
# MongoOneResponseBody

Successful response

## Example Usage

```typescript
import { MongoOneResponseBody } from "dokploy-sdk/models/operations";

let value: MongoOneResponseBody = {
  mongoId: "<id>",
  name: "<value>",
  appName: "<value>",
  description: "bicycle degenerate gah via stark dishonor tabletop",
  databaseUser: "<value>",
  databasePassword: "<value>",
  dockerImage: "<value>",
  command: "<value>",
  env: "<value>",
  memoryReservation: "<value>",
  memoryLimit: "<value>",
  cpuReservation: "<value>",
  cpuLimit: "<value>",
  externalPort: 8142.26,
  applicationStatus: "running",
  healthCheckSwarm: {},
  restartPolicySwarm: {},
  placementSwarm: null,
  updateConfigSwarm: {
    parallelism: 3200.2,
    order: "<value>",
  },
  rollbackConfigSwarm: {
    parallelism: 5555.34,
    order: "<value>",
  },
  modeSwarm: {},
  labelsSwarm: null,
  networkSwarm: [
    {},
  ],
  replicas: 8782.77,
  createdAt: "1730655705105",
  environmentId: "<id>",
  serverId: "<id>",
  replicaSets: true,
  environment: {
    environmentId: "<id>",
    name: "<value>",
    description: "oh stuff awkwardly fooey hmph gee fond oof longingly boohoo",
    createdAt: "1717344415541",
    env: "<value>",
    projectId: "<id>",
    project: {
      projectId: "<id>",
      name: "<value>",
      description: "smoke accredit shred incidentally how guzzle",
      createdAt: "1709765042867",
      organizationId: "<id>",
      env: "<value>",
    },
  },
  mounts: [],
  server: {
    serverId: "<id>",
    name: "<value>",
    description: "shameful between aggravating incomparable hmph",
    ipAddress: "965a:6121:d4a4:9bba:c099:b298:5747:e57b",
    port: 8314.78,
    username: "Jarrell38",
    appName: "<value>",
    enableDockerCleanup: true,
    createdAt: "1717461297021",
    organizationId: "<id>",
    serverStatus: "active",
    command: "<value>",
    sshKeyId: "<id>",
    metricsConfig: "null",
  },
  backups: [],
};
```

## Fields

| Field                                                                                            | Type                                                                                             | Required                                                                                         | Description                                                                                      |
| ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ |
| `mongoId`                                                                                        | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `name`                                                                                           | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `appName`                                                                                        | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `description`                                                                                    | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `databaseUser`                                                                                   | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `databasePassword`                                                                               | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `dockerImage`                                                                                    | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `command`                                                                                        | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `env`                                                                                            | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `memoryReservation`                                                                              | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `memoryLimit`                                                                                    | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `cpuReservation`                                                                                 | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `cpuLimit`                                                                                       | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `externalPort`                                                                                   | *number*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `applicationStatus`                                                                              | [operations.MongoOneApplicationStatus](../../models/operations/mongooneapplicationstatus.md)     | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `healthCheckSwarm`                                                                               | [operations.MongoOneHealthCheckSwarm](../../models/operations/mongoonehealthcheckswarm.md)       | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `restartPolicySwarm`                                                                             | [operations.MongoOneRestartPolicySwarm](../../models/operations/mongoonerestartpolicyswarm.md)   | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `placementSwarm`                                                                                 | [operations.MongoOnePlacementSwarm](../../models/operations/mongooneplacementswarm.md)           | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `updateConfigSwarm`                                                                              | [operations.MongoOneUpdateConfigSwarm](../../models/operations/mongooneupdateconfigswarm.md)     | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `rollbackConfigSwarm`                                                                            | [operations.MongoOneRollbackConfigSwarm](../../models/operations/mongoonerollbackconfigswarm.md) | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `modeSwarm`                                                                                      | [operations.MongoOneModeSwarm](../../models/operations/mongoonemodeswarm.md)                     | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `labelsSwarm`                                                                                    | Record<string, *string*>                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `networkSwarm`                                                                                   | [operations.MongoOneNetworkSwarm](../../models/operations/mongoonenetworkswarm.md)[]             | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `replicas`                                                                                       | *number*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `createdAt`                                                                                      | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `environmentId`                                                                                  | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `serverId`                                                                                       | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `replicaSets`                                                                                    | *boolean*                                                                                        | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `environment`                                                                                    | [operations.MongoOneEnvironment](../../models/operations/mongooneenvironment.md)                 | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `mounts`                                                                                         | [operations.MongoOneMount](../../models/operations/mongoonemount.md)[]                           | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `server`                                                                                         | [operations.MongoOneServer](../../models/operations/mongooneserver.md)                           | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `backups`                                                                                        | [operations.MongoOneBackup](../../models/operations/mongoonebackup.md)[]                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
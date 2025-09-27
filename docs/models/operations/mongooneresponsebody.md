# MongoOneResponseBody

Successful response

## Example Usage

```typescript
import { MongoOneResponseBody } from "dokploy-sdk/models/operations";

let value: MongoOneResponseBody = {
  appName: "<value>",
  applicationStatus: "running",
  backups: [
    {
      appName: "<value>",
      backupId: "<id>",
      backupType: "compose",
      composeId: "<id>",
      database: "<value>",
      databaseType: "mariadb",
      destinationId: "<id>",
      enabled: true,
      keepLatestCount: 658.14,
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
  createdAt: "1718038727529",
  databasePassword: "<value>",
  databaseUser: "<value>",
  description: null,
  dockerImage: "<value>",
  env: "<value>",
  environment: {
    createdAt: "1725889942277",
    description: "intermix little ew",
    env: "<value>",
    environmentId: "<id>",
    name: "<value>",
    project: {
      createdAt: "1715567682812",
      description: "sticker uh-huh drag habit",
      env: "<value>",
      name: "<value>",
      organizationId: "<id>",
      projectId: "<id>",
    },
    projectId: "<id>",
  },
  environmentId: "<id>",
  externalPort: 5791.43,
  healthCheckSwarm: {},
  labelsSwarm: {
    "key": "<value>",
    "key1": "<value>",
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
      filePath: "/usr/local/src/ugh_minus.pkg",
      hostPath: "<value>",
      mariadbId: "<id>",
      mongoId: "<id>",
      mountId: "<id>",
      mountPath: "<value>",
      mysqlId: "<id>",
      postgresId: "<id>",
      redisId: "<id>",
      serviceType: "application",
      type: "file",
      volumeName: "<value>",
    },
  ],
  name: "<value>",
  networkSwarm: null,
  placementSwarm: {},
  replicaSets: true,
  replicas: 6169.68,
  restartPolicySwarm: {},
  rollbackConfigSwarm: {
    order: "<value>",
    parallelism: 8770.1,
  },
  server: {
    appName: "<value>",
    command: "<value>",
    createdAt: "1723566649209",
    description: "or ha jealous lucky what after gee yippee silver quadruple",
    enableDockerCleanup: true,
    ipAddress: "66.240.170.253",
    metricsConfig: {},
    name: "<value>",
    organizationId: "<id>",
    port: 6210.51,
    serverId: "<id>",
    serverStatus: "inactive",
    sshKeyId: "<id>",
    username: "Harley35",
  },
  serverId: null,
  updateConfigSwarm: {
    order: "<value>",
    parallelism: 9809.39,
  },
};
```

## Fields

| Field                                                                                            | Type                                                                                             | Required                                                                                         | Description                                                                                      |
| ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ |
| `appName`                                                                                        | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `applicationStatus`                                                                              | [operations.MongoOneApplicationStatus](../../models/operations/mongooneapplicationstatus.md)     | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `backups`                                                                                        | [operations.MongoOneBackup](../../models/operations/mongoonebackup.md)[]                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `command`                                                                                        | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `cpuLimit`                                                                                       | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `cpuReservation`                                                                                 | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `createdAt`                                                                                      | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `databasePassword`                                                                               | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `databaseUser`                                                                                   | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `description`                                                                                    | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `dockerImage`                                                                                    | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `env`                                                                                            | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `environment`                                                                                    | [operations.MongoOneEnvironment](../../models/operations/mongooneenvironment.md)                 | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `environmentId`                                                                                  | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `externalPort`                                                                                   | *number*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `healthCheckSwarm`                                                                               | [operations.MongoOneHealthCheckSwarm](../../models/operations/mongoonehealthcheckswarm.md)       | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `labelsSwarm`                                                                                    | Record<string, *string*>                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `memoryLimit`                                                                                    | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `memoryReservation`                                                                              | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `modeSwarm`                                                                                      | [operations.MongoOneModeSwarm](../../models/operations/mongoonemodeswarm.md)                     | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `mongoId`                                                                                        | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `mounts`                                                                                         | [operations.MongoOneMount](../../models/operations/mongoonemount.md)[]                           | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `name`                                                                                           | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `networkSwarm`                                                                                   | [operations.MongoOneNetworkSwarm](../../models/operations/mongoonenetworkswarm.md)[]             | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `placementSwarm`                                                                                 | [operations.MongoOnePlacementSwarm](../../models/operations/mongooneplacementswarm.md)           | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `replicaSets`                                                                                    | *boolean*                                                                                        | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `replicas`                                                                                       | *number*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `restartPolicySwarm`                                                                             | [operations.MongoOneRestartPolicySwarm](../../models/operations/mongoonerestartpolicyswarm.md)   | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `rollbackConfigSwarm`                                                                            | [operations.MongoOneRollbackConfigSwarm](../../models/operations/mongoonerollbackconfigswarm.md) | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `server`                                                                                         | [operations.MongoOneServer](../../models/operations/mongooneserver.md)                           | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `serverId`                                                                                       | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `updateConfigSwarm`                                                                              | [operations.MongoOneUpdateConfigSwarm](../../models/operations/mongooneupdateconfigswarm.md)     | :heavy_check_mark:                                                                               | N/A                                                                                              |
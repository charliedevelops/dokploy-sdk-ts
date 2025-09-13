# MysqlSaveExternalPortResponseBody

Successful response

## Example Usage

```typescript
import { MysqlSaveExternalPortResponseBody } from "dokploy-sdk/models/operations";

let value: MysqlSaveExternalPortResponseBody = {
  mysqlId: "<id>",
  name: "<value>",
  appName: "<value>",
  description:
    "covenant midst whoa cross physically naturally owlishly certify meh",
  databaseName: "<value>",
  databaseUser: "<value>",
  databasePassword: "<value>",
  databaseRootPassword: "<value>",
  dockerImage: "<value>",
  command: "<value>",
  env: "<value>",
  memoryReservation: "<value>",
  memoryLimit: "<value>",
  cpuReservation: "<value>",
  cpuLimit: "<value>",
  externalPort: 2105.73,
  applicationStatus: "done",
  healthCheckSwarm: {},
  restartPolicySwarm: {},
  placementSwarm: {},
  updateConfigSwarm: {
    parallelism: 3055.41,
    order: "<value>",
  },
  rollbackConfigSwarm: {
    parallelism: 739.59,
    order: "<value>",
  },
  modeSwarm: {},
  labelsSwarm: {
    "key": "<value>",
    "key1": "<value>",
  },
  networkSwarm: [],
  replicas: 3178.72,
  createdAt: "1716968843079",
  environmentId: "<id>",
  serverId: "<id>",
  environment: {
    environmentId: "<id>",
    name: "<value>",
    description: null,
    createdAt: "1719054654952",
    env: "<value>",
    projectId: "<id>",
    project: {
      projectId: "<id>",
      name: "<value>",
      description:
        "bad fat anenst diver showboat fooey across yowza internalise",
      createdAt: "1718950932828",
      organizationId: "<id>",
      env: "<value>",
    },
  },
  mounts: [
    {
      mountId: "<id>",
      type: "file",
      hostPath: "<value>",
      volumeName: "<value>",
      filePath: "/etc/defaults/hmph.opus",
      content: "<value>",
      serviceType: "mongo",
      mountPath: "<value>",
      applicationId: "<id>",
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
    description: null,
    ipAddress: "78.24.180.222",
    port: 1273.67,
    username: "Lisette_Jenkins",
    appName: "<value>",
    enableDockerCleanup: false,
    createdAt: "1734994155315",
    organizationId: "<id>",
    serverStatus: "inactive",
    command: "<value>",
    sshKeyId: "<id>",
    metricsConfig: {
      "key": "<value>",
    },
  },
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
      keepLatestCount: 1797.02,
      backupType: "compose",
      databaseType: "mysql",
      composeId: "<id>",
      postgresId: "<id>",
      mariadbId: "<id>",
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
| `mysqlId`                                                                                                                  | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `name`                                                                                                                     | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `appName`                                                                                                                  | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `description`                                                                                                              | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `databaseName`                                                                                                             | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `databaseUser`                                                                                                             | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `databasePassword`                                                                                                         | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `databaseRootPassword`                                                                                                     | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `dockerImage`                                                                                                              | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `command`                                                                                                                  | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `env`                                                                                                                      | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `memoryReservation`                                                                                                        | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `memoryLimit`                                                                                                              | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `cpuReservation`                                                                                                           | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `cpuLimit`                                                                                                                 | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `externalPort`                                                                                                             | *number*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `applicationStatus`                                                                                                        | [operations.MysqlSaveExternalPortApplicationStatus](../../models/operations/mysqlsaveexternalportapplicationstatus.md)     | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `healthCheckSwarm`                                                                                                         | [operations.MysqlSaveExternalPortHealthCheckSwarm](../../models/operations/mysqlsaveexternalporthealthcheckswarm.md)       | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `restartPolicySwarm`                                                                                                       | [operations.MysqlSaveExternalPortRestartPolicySwarm](../../models/operations/mysqlsaveexternalportrestartpolicyswarm.md)   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `placementSwarm`                                                                                                           | [operations.MysqlSaveExternalPortPlacementSwarm](../../models/operations/mysqlsaveexternalportplacementswarm.md)           | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `updateConfigSwarm`                                                                                                        | [operations.MysqlSaveExternalPortUpdateConfigSwarm](../../models/operations/mysqlsaveexternalportupdateconfigswarm.md)     | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `rollbackConfigSwarm`                                                                                                      | [operations.MysqlSaveExternalPortRollbackConfigSwarm](../../models/operations/mysqlsaveexternalportrollbackconfigswarm.md) | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `modeSwarm`                                                                                                                | [operations.MysqlSaveExternalPortModeSwarm](../../models/operations/mysqlsaveexternalportmodeswarm.md)                     | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `labelsSwarm`                                                                                                              | Record<string, *string*>                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `networkSwarm`                                                                                                             | [operations.MysqlSaveExternalPortNetworkSwarm](../../models/operations/mysqlsaveexternalportnetworkswarm.md)[]             | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `replicas`                                                                                                                 | *number*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `createdAt`                                                                                                                | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `environmentId`                                                                                                            | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `serverId`                                                                                                                 | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `environment`                                                                                                              | [operations.MysqlSaveExternalPortEnvironment](../../models/operations/mysqlsaveexternalportenvironment.md)                 | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `mounts`                                                                                                                   | [operations.MysqlSaveExternalPortMount](../../models/operations/mysqlsaveexternalportmount.md)[]                           | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `server`                                                                                                                   | [operations.MysqlSaveExternalPortServer](../../models/operations/mysqlsaveexternalportserver.md)                           | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `backups`                                                                                                                  | [operations.MysqlSaveExternalPortBackup](../../models/operations/mysqlsaveexternalportbackup.md)[]                         | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
# MariadbStartResponseBody

Successful response

## Example Usage

```typescript
import { MariadbStartResponseBody } from "dokploy-sdk/models/operations";

let value: MariadbStartResponseBody = {
  appName: "<value>",
  applicationStatus: "error",
  backups: [],
  command: "<value>",
  cpuLimit: "<value>",
  cpuReservation: "<value>",
  createdAt: "1720536947069",
  databaseName: "<value>",
  databasePassword: "<value>",
  databaseRootPassword: "<value>",
  databaseUser: "<value>",
  description: "woefully despite strategy ah duh stealthily for",
  dockerImage: "<value>",
  env: null,
  environment: {
    createdAt: "1728590061063",
    description: "wherever astride vivid sensitize concerning",
    env: "<value>",
    environmentId: "<id>",
    name: "<value>",
    project: {
      createdAt: "1723904933546",
      description: "punctually gosh perfectly likewise pupil",
      env: "<value>",
      name: "<value>",
      organizationId: "<id>",
      projectId: "<id>",
    },
    projectId: "<id>",
  },
  environmentId: "<id>",
  externalPort: 9579.93,
  healthCheckSwarm: {},
  labelsSwarm: {
    "key": "<value>",
    "key1": "<value>",
    "key2": "<value>",
  },
  mariadbId: "<id>",
  memoryLimit: "<value>",
  memoryReservation: "<value>",
  modeSwarm: {},
  mounts: [
    {
      applicationId: "<id>",
      composeId: "<id>",
      content: "<value>",
      filePath: null,
      hostPath: "<value>",
      mariadbId: "<id>",
      mongoId: "<id>",
      mountId: "<id>",
      mountPath: "<value>",
      mysqlId: "<id>",
      postgresId: "<id>",
      redisId: "<id>",
      serviceType: "application",
      type: "bind",
      volumeName: "<value>",
    },
  ],
  name: "<value>",
  networkSwarm: [],
  placementSwarm: {},
  replicas: 5957.01,
  restartPolicySwarm: {},
  rollbackConfigSwarm: {
    order: "<value>",
    parallelism: 9463.63,
  },
  server: {
    appName: "<value>",
    command: "<value>",
    createdAt: "1729727548045",
    description: "famously square before opposite less innovate",
    enableDockerCleanup: true,
    ipAddress: "2c80:acfe:dccf:f58a:ccf0:0f36:c1dc:b34b",
    metricsConfig: [
      "<value 1>",
    ],
    name: "<value>",
    organizationId: "<id>",
    port: 4777.32,
    serverId: "<id>",
    serverStatus: "inactive",
    sshKeyId: "<id>",
    username: "Darrick61",
  },
  serverId: "<id>",
  updateConfigSwarm: {
    order: "<value>",
    parallelism: 5118.23,
  },
};
```

## Fields

| Field                                                                                                    | Type                                                                                                     | Required                                                                                                 | Description                                                                                              |
| -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- |
| `appName`                                                                                                | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `applicationStatus`                                                                                      | [operations.MariadbStartApplicationStatus](../../models/operations/mariadbstartapplicationstatus.md)     | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `backups`                                                                                                | [operations.MariadbStartBackup](../../models/operations/mariadbstartbackup.md)[]                         | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `command`                                                                                                | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `cpuLimit`                                                                                               | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `cpuReservation`                                                                                         | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `createdAt`                                                                                              | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `databaseName`                                                                                           | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `databasePassword`                                                                                       | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `databaseRootPassword`                                                                                   | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `databaseUser`                                                                                           | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `description`                                                                                            | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `dockerImage`                                                                                            | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `env`                                                                                                    | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `environment`                                                                                            | [operations.MariadbStartEnvironment](../../models/operations/mariadbstartenvironment.md)                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `environmentId`                                                                                          | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `externalPort`                                                                                           | *number*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `healthCheckSwarm`                                                                                       | [operations.MariadbStartHealthCheckSwarm](../../models/operations/mariadbstarthealthcheckswarm.md)       | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `labelsSwarm`                                                                                            | Record<string, *string*>                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `mariadbId`                                                                                              | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `memoryLimit`                                                                                            | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `memoryReservation`                                                                                      | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `modeSwarm`                                                                                              | [operations.MariadbStartModeSwarm](../../models/operations/mariadbstartmodeswarm.md)                     | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `mounts`                                                                                                 | [operations.MariadbStartMount](../../models/operations/mariadbstartmount.md)[]                           | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `name`                                                                                                   | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `networkSwarm`                                                                                           | [operations.MariadbStartNetworkSwarm](../../models/operations/mariadbstartnetworkswarm.md)[]             | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `placementSwarm`                                                                                         | [operations.MariadbStartPlacementSwarm](../../models/operations/mariadbstartplacementswarm.md)           | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `replicas`                                                                                               | *number*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `restartPolicySwarm`                                                                                     | [operations.MariadbStartRestartPolicySwarm](../../models/operations/mariadbstartrestartpolicyswarm.md)   | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `rollbackConfigSwarm`                                                                                    | [operations.MariadbStartRollbackConfigSwarm](../../models/operations/mariadbstartrollbackconfigswarm.md) | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `server`                                                                                                 | [operations.MariadbStartServer](../../models/operations/mariadbstartserver.md)                           | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `serverId`                                                                                               | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `updateConfigSwarm`                                                                                      | [operations.MariadbStartUpdateConfigSwarm](../../models/operations/mariadbstartupdateconfigswarm.md)     | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
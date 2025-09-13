# MariadbStartResponseBody

Successful response

## Example Usage

```typescript
import { MariadbStartResponseBody } from "dokploy-sdk/models/operations";

let value: MariadbStartResponseBody = {
  mariadbId: "<id>",
  name: "<value>",
  appName: "<value>",
  description: "circa likewise hover",
  databaseName: "<value>",
  databaseUser: "<value>",
  databasePassword: "<value>",
  databaseRootPassword: "<value>",
  dockerImage: "<value>",
  command: "<value>",
  env: null,
  memoryReservation: "<value>",
  memoryLimit: "<value>",
  cpuReservation: "<value>",
  cpuLimit: "<value>",
  externalPort: 1878.76,
  applicationStatus: "running",
  healthCheckSwarm: null,
  restartPolicySwarm: {},
  placementSwarm: {},
  updateConfigSwarm: {
    parallelism: 7990.15,
    order: "<value>",
  },
  rollbackConfigSwarm: null,
  modeSwarm: {},
  labelsSwarm: {
    "key": "<value>",
  },
  networkSwarm: [
    {},
  ],
  replicas: 9931.05,
  createdAt: "1723060914230",
  environmentId: "<id>",
  serverId: "<id>",
  environment: {
    environmentId: "<id>",
    name: "<value>",
    description: "ah onto yum",
    createdAt: "1707971815327",
    env: "<value>",
    projectId: "<id>",
    project: {
      projectId: "<id>",
      name: "<value>",
      description:
        "arbitrate supposing jovially solemnly out yuppify thankfully obligation",
      createdAt: "1713099423384",
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
      filePath: "/usr/swift.otf",
      content: null,
      serviceType: "compose",
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
    description: "willing gosh license undergo even whoever swelter pish",
    ipAddress: "105.38.167.156",
    port: 1001.17,
    username: "Mary.Durgan43",
    appName: "<value>",
    enableDockerCleanup: false,
    createdAt: "1729355165705",
    organizationId: "<id>",
    serverStatus: "inactive",
    command: "<value>",
    sshKeyId: "<id>",
    metricsConfig: 382.2,
  },
  backups: [
    {
      backupId: "<id>",
      appName: "<value>",
      schedule: "<value>",
      enabled: false,
      database: "<value>",
      prefix: "<value>",
      serviceName: "<value>",
      destinationId: "<id>",
      keepLatestCount: null,
      backupType: "compose",
      databaseType: "web-server",
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

| Field                                                                                                    | Type                                                                                                     | Required                                                                                                 | Description                                                                                              |
| -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- |
| `mariadbId`                                                                                              | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `name`                                                                                                   | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `appName`                                                                                                | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `description`                                                                                            | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `databaseName`                                                                                           | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `databaseUser`                                                                                           | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `databasePassword`                                                                                       | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `databaseRootPassword`                                                                                   | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `dockerImage`                                                                                            | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `command`                                                                                                | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `env`                                                                                                    | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `memoryReservation`                                                                                      | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `memoryLimit`                                                                                            | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `cpuReservation`                                                                                         | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `cpuLimit`                                                                                               | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `externalPort`                                                                                           | *number*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `applicationStatus`                                                                                      | [operations.MariadbStartApplicationStatus](../../models/operations/mariadbstartapplicationstatus.md)     | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `healthCheckSwarm`                                                                                       | [operations.MariadbStartHealthCheckSwarm](../../models/operations/mariadbstarthealthcheckswarm.md)       | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `restartPolicySwarm`                                                                                     | [operations.MariadbStartRestartPolicySwarm](../../models/operations/mariadbstartrestartpolicyswarm.md)   | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `placementSwarm`                                                                                         | [operations.MariadbStartPlacementSwarm](../../models/operations/mariadbstartplacementswarm.md)           | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `updateConfigSwarm`                                                                                      | [operations.MariadbStartUpdateConfigSwarm](../../models/operations/mariadbstartupdateconfigswarm.md)     | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `rollbackConfigSwarm`                                                                                    | [operations.MariadbStartRollbackConfigSwarm](../../models/operations/mariadbstartrollbackconfigswarm.md) | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `modeSwarm`                                                                                              | [operations.MariadbStartModeSwarm](../../models/operations/mariadbstartmodeswarm.md)                     | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `labelsSwarm`                                                                                            | Record<string, *string*>                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `networkSwarm`                                                                                           | [operations.MariadbStartNetworkSwarm](../../models/operations/mariadbstartnetworkswarm.md)[]             | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `replicas`                                                                                               | *number*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `createdAt`                                                                                              | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `environmentId`                                                                                          | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `serverId`                                                                                               | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `environment`                                                                                            | [operations.MariadbStartEnvironment](../../models/operations/mariadbstartenvironment.md)                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `mounts`                                                                                                 | [operations.MariadbStartMount](../../models/operations/mariadbstartmount.md)[]                           | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `server`                                                                                                 | [operations.MariadbStartServer](../../models/operations/mariadbstartserver.md)                           | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `backups`                                                                                                | [operations.MariadbStartBackup](../../models/operations/mariadbstartbackup.md)[]                         | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
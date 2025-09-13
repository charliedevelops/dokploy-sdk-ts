# MariadbRemoveResponseBody

Successful response

## Example Usage

```typescript
import { MariadbRemoveResponseBody } from "dokploy-sdk/models/operations";

let value: MariadbRemoveResponseBody = {
  mariadbId: "<id>",
  name: "<value>",
  appName: "<value>",
  description: "like once fussy an psst aboard surface eek",
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
  cpuLimit: null,
  externalPort: 534.94,
  applicationStatus: "running",
  healthCheckSwarm: {},
  restartPolicySwarm: {},
  placementSwarm: {},
  updateConfigSwarm: {
    parallelism: 7793.22,
    order: "<value>",
  },
  rollbackConfigSwarm: {
    parallelism: 5872.78,
    order: "<value>",
  },
  modeSwarm: {},
  labelsSwarm: {},
  networkSwarm: [],
  replicas: 8097.94,
  createdAt: "1729382718431",
  environmentId: "<id>",
  serverId: "<id>",
  environment: {
    environmentId: "<id>",
    name: "<value>",
    description:
      "showy wound knavishly gratefully manipulate miserable agreement unto sans",
    createdAt: "1711395483111",
    env: "<value>",
    projectId: "<id>",
    project: {
      projectId: "<id>",
      name: "<value>",
      description: "spook whenever soup airbus zealous for deduct amid",
      createdAt: "1712617458655",
      organizationId: "<id>",
      env: "<value>",
    },
  },
  mounts: [
    {
      mountId: "<id>",
      type: "file",
      hostPath: "<value>",
      volumeName: null,
      filePath: "/System/ack_rare_which.opus",
      content: "<value>",
      serviceType: "redis",
      mountPath: "<value>",
      applicationId: "<id>",
      postgresId: "<id>",
      mariadbId: "<id>",
      mongoId: "<id>",
      mysqlId: null,
      redisId: "<id>",
      composeId: "<id>",
    },
  ],
  server: {
    serverId: "<id>",
    name: "<value>",
    description:
      "helplessly glass petty tenderly book unlike nor where showy now",
    ipAddress: "105.35.32.70",
    port: 7292.08,
    username: "Karli_Thiel",
    appName: "<value>",
    enableDockerCleanup: true,
    createdAt: "1707525257665",
    organizationId: "<id>",
    serverStatus: "inactive",
    command: "<value>",
    sshKeyId: "<id>",
    metricsConfig: {},
  },
  backups: [],
};
```

## Fields

| Field                                                                                                      | Type                                                                                                       | Required                                                                                                   | Description                                                                                                |
| ---------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- |
| `mariadbId`                                                                                                | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `name`                                                                                                     | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `appName`                                                                                                  | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `description`                                                                                              | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `databaseName`                                                                                             | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `databaseUser`                                                                                             | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `databasePassword`                                                                                         | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `databaseRootPassword`                                                                                     | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `dockerImage`                                                                                              | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `command`                                                                                                  | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `env`                                                                                                      | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `memoryReservation`                                                                                        | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `memoryLimit`                                                                                              | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `cpuReservation`                                                                                           | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `cpuLimit`                                                                                                 | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `externalPort`                                                                                             | *number*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `applicationStatus`                                                                                        | [operations.MariadbRemoveApplicationStatus](../../models/operations/mariadbremoveapplicationstatus.md)     | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `healthCheckSwarm`                                                                                         | [operations.MariadbRemoveHealthCheckSwarm](../../models/operations/mariadbremovehealthcheckswarm.md)       | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `restartPolicySwarm`                                                                                       | [operations.MariadbRemoveRestartPolicySwarm](../../models/operations/mariadbremoverestartpolicyswarm.md)   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `placementSwarm`                                                                                           | [operations.MariadbRemovePlacementSwarm](../../models/operations/mariadbremoveplacementswarm.md)           | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `updateConfigSwarm`                                                                                        | [operations.MariadbRemoveUpdateConfigSwarm](../../models/operations/mariadbremoveupdateconfigswarm.md)     | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `rollbackConfigSwarm`                                                                                      | [operations.MariadbRemoveRollbackConfigSwarm](../../models/operations/mariadbremoverollbackconfigswarm.md) | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `modeSwarm`                                                                                                | [operations.MariadbRemoveModeSwarm](../../models/operations/mariadbremovemodeswarm.md)                     | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `labelsSwarm`                                                                                              | Record<string, *string*>                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `networkSwarm`                                                                                             | [operations.MariadbRemoveNetworkSwarm](../../models/operations/mariadbremovenetworkswarm.md)[]             | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `replicas`                                                                                                 | *number*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `createdAt`                                                                                                | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `environmentId`                                                                                            | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `serverId`                                                                                                 | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `environment`                                                                                              | [operations.MariadbRemoveEnvironment](../../models/operations/mariadbremoveenvironment.md)                 | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `mounts`                                                                                                   | [operations.MariadbRemoveMount](../../models/operations/mariadbremovemount.md)[]                           | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `server`                                                                                                   | [operations.MariadbRemoveServer](../../models/operations/mariadbremoveserver.md)                           | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `backups`                                                                                                  | [operations.MariadbRemoveBackup](../../models/operations/mariadbremovebackup.md)[]                         | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
# PostgresChangeStatusResponseBody

Successful response

## Example Usage

```typescript
import { PostgresChangeStatusResponseBody } from "dokploy-sdk/models/operations";

let value: PostgresChangeStatusResponseBody = {
  appName: "<value>",
  applicationStatus: "done",
  backups: [
    {
      appName: "<value>",
      backupId: "<id>",
      backupType: "database",
      composeId: "<id>",
      database: "<value>",
      databaseType: "postgres",
      destinationId: "<id>",
      enabled: true,
      keepLatestCount: 8061.76,
      mariadbId: "<id>",
      mongoId: null,
      mysqlId: "<id>",
      postgresId: "<id>",
      prefix: "<value>",
      schedule: "<value>",
      serviceName: "<value>",
      userId: "<id>",
    },
  ],
  command: null,
  cpuLimit: null,
  cpuReservation: "<value>",
  createdAt: "1720974373942",
  databaseName: "<value>",
  databasePassword: "<value>",
  databaseUser: "<value>",
  description: "seriously reschedule whereas",
  dockerImage: "<value>",
  env: "<value>",
  environment: {
    createdAt: "1710471816361",
    description: "like puritan victoriously decide grubby bah but",
    env: "<value>",
    environmentId: "<id>",
    name: "<value>",
    project: {
      createdAt: "1725186984913",
      description: "gosh hexagon giggle carefully spear abaft meander",
      env: "<value>",
      name: "<value>",
      organizationId: "<id>",
      projectId: "<id>",
    },
    projectId: "<id>",
  },
  environmentId: "<id>",
  externalPort: 6192.25,
  healthCheckSwarm: {},
  labelsSwarm: {
    "key": "<value>",
    "key1": "<value>",
    "key2": "<value>",
  },
  memoryLimit: "<value>",
  memoryReservation: "<value>",
  modeSwarm: {},
  mounts: [],
  name: "<value>",
  networkSwarm: [],
  placementSwarm: null,
  postgresId: "<id>",
  replicas: 8082.57,
  restartPolicySwarm: {},
  rollbackConfigSwarm: {
    order: "<value>",
    parallelism: 2528.32,
  },
  server: {
    appName: "<value>",
    command: "<value>",
    createdAt: "1726949439085",
    description:
      "lest digit to rapidly smart sympathetically in progress hutch",
    enableDockerCleanup: false,
    ipAddress: "38.3.184.244",
    metricsConfig: "null",
    name: "<value>",
    organizationId: "<id>",
    port: 2782.73,
    serverId: "<id>",
    serverStatus: "inactive",
    sshKeyId: "<id>",
    username: "Luciano_Schumm",
  },
  serverId: "<id>",
  updateConfigSwarm: {
    order: "<value>",
    parallelism: 8370.89,
  },
};
```

## Fields

| Field                                                                                                                                | Type                                                                                                                                 | Required                                                                                                                             | Description                                                                                                                          |
| ------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------ |
| `appName`                                                                                                                            | *string*                                                                                                                             | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `applicationStatus`                                                                                                                  | [operations.PostgresChangeStatusApplicationStatusResponse](../../models/operations/postgreschangestatusapplicationstatusresponse.md) | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `backups`                                                                                                                            | [operations.PostgresChangeStatusBackup](../../models/operations/postgreschangestatusbackup.md)[]                                     | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `command`                                                                                                                            | *string*                                                                                                                             | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `cpuLimit`                                                                                                                           | *string*                                                                                                                             | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `cpuReservation`                                                                                                                     | *string*                                                                                                                             | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `createdAt`                                                                                                                          | *string*                                                                                                                             | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `databaseName`                                                                                                                       | *string*                                                                                                                             | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `databasePassword`                                                                                                                   | *string*                                                                                                                             | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `databaseUser`                                                                                                                       | *string*                                                                                                                             | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `description`                                                                                                                        | *string*                                                                                                                             | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `dockerImage`                                                                                                                        | *string*                                                                                                                             | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `env`                                                                                                                                | *string*                                                                                                                             | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `environment`                                                                                                                        | [operations.PostgresChangeStatusEnvironment](../../models/operations/postgreschangestatusenvironment.md)                             | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `environmentId`                                                                                                                      | *string*                                                                                                                             | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `externalPort`                                                                                                                       | *number*                                                                                                                             | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `healthCheckSwarm`                                                                                                                   | [operations.PostgresChangeStatusHealthCheckSwarm](../../models/operations/postgreschangestatushealthcheckswarm.md)                   | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `labelsSwarm`                                                                                                                        | Record<string, *string*>                                                                                                             | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `memoryLimit`                                                                                                                        | *string*                                                                                                                             | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `memoryReservation`                                                                                                                  | *string*                                                                                                                             | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `modeSwarm`                                                                                                                          | [operations.PostgresChangeStatusModeSwarm](../../models/operations/postgreschangestatusmodeswarm.md)                                 | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `mounts`                                                                                                                             | [operations.PostgresChangeStatusMount](../../models/operations/postgreschangestatusmount.md)[]                                       | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `name`                                                                                                                               | *string*                                                                                                                             | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `networkSwarm`                                                                                                                       | [operations.PostgresChangeStatusNetworkSwarm](../../models/operations/postgreschangestatusnetworkswarm.md)[]                         | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `placementSwarm`                                                                                                                     | [operations.PostgresChangeStatusPlacementSwarm](../../models/operations/postgreschangestatusplacementswarm.md)                       | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `postgresId`                                                                                                                         | *string*                                                                                                                             | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `replicas`                                                                                                                           | *number*                                                                                                                             | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `restartPolicySwarm`                                                                                                                 | [operations.PostgresChangeStatusRestartPolicySwarm](../../models/operations/postgreschangestatusrestartpolicyswarm.md)               | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `rollbackConfigSwarm`                                                                                                                | [operations.PostgresChangeStatusRollbackConfigSwarm](../../models/operations/postgreschangestatusrollbackconfigswarm.md)             | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `server`                                                                                                                             | [operations.PostgresChangeStatusServer](../../models/operations/postgreschangestatusserver.md)                                       | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `serverId`                                                                                                                           | *string*                                                                                                                             | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `updateConfigSwarm`                                                                                                                  | [operations.PostgresChangeStatusUpdateConfigSwarm](../../models/operations/postgreschangestatusupdateconfigswarm.md)                 | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
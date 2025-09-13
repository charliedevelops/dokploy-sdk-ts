# MariadbChangeStatusResponseBody

Successful response

## Example Usage

```typescript
import { MariadbChangeStatusResponseBody } from "dokploy-sdk/models/operations";

let value: MariadbChangeStatusResponseBody = {
  mariadbId: "<id>",
  name: "<value>",
  appName: "<value>",
  description:
    "tough agitated parody typify nor for except petticoat delightfully duh",
  databaseName: "<value>",
  databaseUser: "<value>",
  databasePassword: "<value>",
  databaseRootPassword: "<value>",
  dockerImage: "<value>",
  command: "<value>",
  env: "<value>",
  memoryReservation: null,
  memoryLimit: "<value>",
  cpuReservation: "<value>",
  cpuLimit: "<value>",
  externalPort: 8913.22,
  applicationStatus: "running",
  healthCheckSwarm: {},
  restartPolicySwarm: {},
  placementSwarm: {},
  updateConfigSwarm: {
    parallelism: 8083.44,
    order: "<value>",
  },
  rollbackConfigSwarm: {
    parallelism: 1437.34,
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
  replicas: 8309.19,
  createdAt: "1725775864468",
  environmentId: "<id>",
  serverId: "<id>",
  environment: {
    environmentId: "<id>",
    name: "<value>",
    description: "polished platter pish prance",
    createdAt: "1725269878288",
    env: "<value>",
    projectId: "<id>",
    project: {
      projectId: "<id>",
      name: "<value>",
      description:
        "councilman language frightfully pish aha perfectly fearless whether",
      createdAt: "1719623363118",
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
      filePath: "/var/mail/save.m3a",
      content: "<value>",
      serviceType: "mariadb",
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
    description: "powerfully stratify inculcate",
    ipAddress: "46.103.73.34",
    port: 233.23,
    username: "Hayden.Denesik-Welch",
    appName: "<value>",
    enableDockerCleanup: true,
    createdAt: "1719862083759",
    organizationId: "<id>",
    serverStatus: "inactive",
    command: "<value>",
    sshKeyId: "<id>",
    metricsConfig: true,
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
      keepLatestCount: 3921.61,
      backupType: "database",
      databaseType: "mysql",
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

| Field                                                                                                                              | Type                                                                                                                               | Required                                                                                                                           | Description                                                                                                                        |
| ---------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- |
| `mariadbId`                                                                                                                        | *string*                                                                                                                           | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `name`                                                                                                                             | *string*                                                                                                                           | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `appName`                                                                                                                          | *string*                                                                                                                           | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `description`                                                                                                                      | *string*                                                                                                                           | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `databaseName`                                                                                                                     | *string*                                                                                                                           | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `databaseUser`                                                                                                                     | *string*                                                                                                                           | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `databasePassword`                                                                                                                 | *string*                                                                                                                           | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `databaseRootPassword`                                                                                                             | *string*                                                                                                                           | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `dockerImage`                                                                                                                      | *string*                                                                                                                           | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `command`                                                                                                                          | *string*                                                                                                                           | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `env`                                                                                                                              | *string*                                                                                                                           | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `memoryReservation`                                                                                                                | *string*                                                                                                                           | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `memoryLimit`                                                                                                                      | *string*                                                                                                                           | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `cpuReservation`                                                                                                                   | *string*                                                                                                                           | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `cpuLimit`                                                                                                                         | *string*                                                                                                                           | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `externalPort`                                                                                                                     | *number*                                                                                                                           | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `applicationStatus`                                                                                                                | [operations.MariadbChangeStatusApplicationStatusResponse](../../models/operations/mariadbchangestatusapplicationstatusresponse.md) | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `healthCheckSwarm`                                                                                                                 | [operations.MariadbChangeStatusHealthCheckSwarm](../../models/operations/mariadbchangestatushealthcheckswarm.md)                   | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `restartPolicySwarm`                                                                                                               | [operations.MariadbChangeStatusRestartPolicySwarm](../../models/operations/mariadbchangestatusrestartpolicyswarm.md)               | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `placementSwarm`                                                                                                                   | [operations.MariadbChangeStatusPlacementSwarm](../../models/operations/mariadbchangestatusplacementswarm.md)                       | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `updateConfigSwarm`                                                                                                                | [operations.MariadbChangeStatusUpdateConfigSwarm](../../models/operations/mariadbchangestatusupdateconfigswarm.md)                 | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `rollbackConfigSwarm`                                                                                                              | [operations.MariadbChangeStatusRollbackConfigSwarm](../../models/operations/mariadbchangestatusrollbackconfigswarm.md)             | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `modeSwarm`                                                                                                                        | [operations.MariadbChangeStatusModeSwarm](../../models/operations/mariadbchangestatusmodeswarm.md)                                 | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `labelsSwarm`                                                                                                                      | Record<string, *string*>                                                                                                           | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `networkSwarm`                                                                                                                     | [operations.MariadbChangeStatusNetworkSwarm](../../models/operations/mariadbchangestatusnetworkswarm.md)[]                         | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `replicas`                                                                                                                         | *number*                                                                                                                           | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `createdAt`                                                                                                                        | *string*                                                                                                                           | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `environmentId`                                                                                                                    | *string*                                                                                                                           | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `serverId`                                                                                                                         | *string*                                                                                                                           | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `environment`                                                                                                                      | [operations.MariadbChangeStatusEnvironment](../../models/operations/mariadbchangestatusenvironment.md)                             | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `mounts`                                                                                                                           | [operations.MariadbChangeStatusMount](../../models/operations/mariadbchangestatusmount.md)[]                                       | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `server`                                                                                                                           | [operations.MariadbChangeStatusServer](../../models/operations/mariadbchangestatusserver.md)                                       | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `backups`                                                                                                                          | [operations.MariadbChangeStatusBackup](../../models/operations/mariadbchangestatusbackup.md)[]                                     | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
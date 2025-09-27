# MariadbChangeStatusResponseBody

Successful response

## Example Usage

```typescript
import { MariadbChangeStatusResponseBody } from "dokploy-sdk/models/operations";

let value: MariadbChangeStatusResponseBody = {
  appName: "<value>",
  applicationStatus: "error",
  backups: [
    {
      appName: "<value>",
      backupId: "<id>",
      backupType: "database",
      composeId: "<id>",
      database: "<value>",
      databaseType: "web-server",
      destinationId: "<id>",
      enabled: false,
      keepLatestCount: 8624.52,
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
  command: null,
  cpuLimit: "<value>",
  cpuReservation: "<value>",
  createdAt: "1707141354984",
  databaseName: "<value>",
  databasePassword: "<value>",
  databaseRootPassword: "<value>",
  databaseUser: "<value>",
  description:
    "peony boo orientate vol straw whose chromakey crackle unpleasant up",
  dockerImage: "<value>",
  env: "<value>",
  environment: {
    createdAt: "1726236661044",
    description:
      "what incidentally cleverly brr but nicely intrepid frantically",
    env: "<value>",
    environmentId: "<id>",
    name: "<value>",
    project: {
      createdAt: "1723810700183",
      description: "stunt unnaturally whole gratefully indeed yuck",
      env: "<value>",
      name: "<value>",
      organizationId: "<id>",
      projectId: "<id>",
    },
    projectId: "<id>",
  },
  environmentId: "<id>",
  externalPort: 7773.67,
  healthCheckSwarm: null,
  labelsSwarm: {},
  mariadbId: "<id>",
  memoryLimit: "<value>",
  memoryReservation: "<value>",
  modeSwarm: {},
  mounts: [],
  name: "<value>",
  networkSwarm: [],
  placementSwarm: {},
  replicas: 7836.98,
  restartPolicySwarm: {},
  rollbackConfigSwarm: {
    order: "<value>",
    parallelism: 822.63,
  },
  server: {
    appName: "<value>",
    command: "<value>",
    createdAt: "1725295121679",
    description: "aha ick reservation convince moral slimy apud yogurt",
    enableDockerCleanup: false,
    ipAddress: "72.86.199.124",
    metricsConfig: false,
    name: "<value>",
    organizationId: "<id>",
    port: 6527.49,
    serverId: "<id>",
    serverStatus: "inactive",
    sshKeyId: "<id>",
    username: "Ellsworth_Reinger",
  },
  serverId: "<id>",
  updateConfigSwarm: {
    order: "<value>",
    parallelism: 7092.58,
  },
};
```

## Fields

| Field                                                                                                                              | Type                                                                                                                               | Required                                                                                                                           | Description                                                                                                                        |
| ---------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- |
| `appName`                                                                                                                          | *string*                                                                                                                           | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `applicationStatus`                                                                                                                | [operations.MariadbChangeStatusApplicationStatusResponse](../../models/operations/mariadbchangestatusapplicationstatusresponse.md) | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `backups`                                                                                                                          | [operations.MariadbChangeStatusBackup](../../models/operations/mariadbchangestatusbackup.md)[]                                     | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `command`                                                                                                                          | *string*                                                                                                                           | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `cpuLimit`                                                                                                                         | *string*                                                                                                                           | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `cpuReservation`                                                                                                                   | *string*                                                                                                                           | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `createdAt`                                                                                                                        | *string*                                                                                                                           | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `databaseName`                                                                                                                     | *string*                                                                                                                           | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `databasePassword`                                                                                                                 | *string*                                                                                                                           | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `databaseRootPassword`                                                                                                             | *string*                                                                                                                           | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `databaseUser`                                                                                                                     | *string*                                                                                                                           | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `description`                                                                                                                      | *string*                                                                                                                           | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `dockerImage`                                                                                                                      | *string*                                                                                                                           | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `env`                                                                                                                              | *string*                                                                                                                           | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `environment`                                                                                                                      | [operations.MariadbChangeStatusEnvironment](../../models/operations/mariadbchangestatusenvironment.md)                             | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `environmentId`                                                                                                                    | *string*                                                                                                                           | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `externalPort`                                                                                                                     | *number*                                                                                                                           | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `healthCheckSwarm`                                                                                                                 | [operations.MariadbChangeStatusHealthCheckSwarm](../../models/operations/mariadbchangestatushealthcheckswarm.md)                   | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `labelsSwarm`                                                                                                                      | Record<string, *string*>                                                                                                           | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `mariadbId`                                                                                                                        | *string*                                                                                                                           | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `memoryLimit`                                                                                                                      | *string*                                                                                                                           | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `memoryReservation`                                                                                                                | *string*                                                                                                                           | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `modeSwarm`                                                                                                                        | [operations.MariadbChangeStatusModeSwarm](../../models/operations/mariadbchangestatusmodeswarm.md)                                 | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `mounts`                                                                                                                           | [operations.MariadbChangeStatusMount](../../models/operations/mariadbchangestatusmount.md)[]                                       | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `name`                                                                                                                             | *string*                                                                                                                           | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `networkSwarm`                                                                                                                     | [operations.MariadbChangeStatusNetworkSwarm](../../models/operations/mariadbchangestatusnetworkswarm.md)[]                         | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `placementSwarm`                                                                                                                   | [operations.MariadbChangeStatusPlacementSwarm](../../models/operations/mariadbchangestatusplacementswarm.md)                       | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `replicas`                                                                                                                         | *number*                                                                                                                           | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `restartPolicySwarm`                                                                                                               | [operations.MariadbChangeStatusRestartPolicySwarm](../../models/operations/mariadbchangestatusrestartpolicyswarm.md)               | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `rollbackConfigSwarm`                                                                                                              | [operations.MariadbChangeStatusRollbackConfigSwarm](../../models/operations/mariadbchangestatusrollbackconfigswarm.md)             | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `server`                                                                                                                           | [operations.MariadbChangeStatusServer](../../models/operations/mariadbchangestatusserver.md)                                       | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `serverId`                                                                                                                         | *string*                                                                                                                           | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `updateConfigSwarm`                                                                                                                | [operations.MariadbChangeStatusUpdateConfigSwarm](../../models/operations/mariadbchangestatusupdateconfigswarm.md)                 | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
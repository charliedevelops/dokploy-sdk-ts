# PostgresChangeStatusResponseBody

Successful response

## Example Usage

```typescript
import { PostgresChangeStatusResponseBody } from "dokploy-sdk/models/operations";

let value: PostgresChangeStatusResponseBody = {
  postgresId: "<id>",
  name: "<value>",
  appName: "<value>",
  databaseName: "<value>",
  databaseUser: "<value>",
  databasePassword: "<value>",
  description:
    "whereas although sharply bide against fooey upright seemingly shiny",
  dockerImage: "<value>",
  command: null,
  env: "<value>",
  memoryReservation: "<value>",
  externalPort: 3518.67,
  memoryLimit: "<value>",
  cpuReservation: "<value>",
  cpuLimit: "<value>",
  applicationStatus: "idle",
  healthCheckSwarm: {},
  restartPolicySwarm: {},
  placementSwarm: {},
  updateConfigSwarm: {
    parallelism: 5388.18,
    order: "<value>",
  },
  rollbackConfigSwarm: {
    parallelism: 3453.72,
    order: "<value>",
  },
  modeSwarm: {},
  labelsSwarm: {
    "key": "<value>",
  },
  networkSwarm: [],
  replicas: 2183.87,
  createdAt: "1724294624489",
  environmentId: "<id>",
  serverId: "<id>",
  environment: {
    environmentId: "<id>",
    name: "<value>",
    description: "or ultimately celebrate gracefully section other sweetly off",
    createdAt: "1721168637867",
    env: "<value>",
    projectId: "<id>",
    project: {
      projectId: "<id>",
      name: "<value>",
      description: "crushing colorfully regulate",
      createdAt: "1704457250165",
      organizationId: "<id>",
      env: "<value>",
    },
  },
  mounts: [
    {
      mountId: "<id>",
      type: "file",
      hostPath: null,
      volumeName: "<value>",
      filePath: "/home/ha_bustling_who.dll",
      content: "<value>",
      serviceType: "mongo",
      mountPath: "<value>",
      applicationId: null,
      postgresId: "<id>",
      mariadbId: null,
      mongoId: "<id>",
      mysqlId: "<id>",
      redisId: "<id>",
      composeId: "<id>",
    },
  ],
  server: {
    serverId: "<id>",
    name: "<value>",
    description: "wrongly putrefy cosset while searchingly",
    ipAddress: "0fba:085f:6bfb:a6d6:53eb:feff:5fcd:26bc",
    port: 6728.08,
    username: "Alexandrea.Glover",
    appName: "<value>",
    enableDockerCleanup: false,
    createdAt: "1717119302280",
    organizationId: "<id>",
    serverStatus: "active",
    command: "<value>",
    sshKeyId: "<id>",
    metricsConfig: {
      "key": "<value>",
      "key1": "<value>",
      "key2": "<value>",
    },
  },
  backups: [],
};
```

## Fields

| Field                                                                                                                                | Type                                                                                                                                 | Required                                                                                                                             | Description                                                                                                                          |
| ------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------ |
| `postgresId`                                                                                                                         | *string*                                                                                                                             | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `name`                                                                                                                               | *string*                                                                                                                             | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `appName`                                                                                                                            | *string*                                                                                                                             | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `databaseName`                                                                                                                       | *string*                                                                                                                             | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `databaseUser`                                                                                                                       | *string*                                                                                                                             | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `databasePassword`                                                                                                                   | *string*                                                                                                                             | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `description`                                                                                                                        | *string*                                                                                                                             | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `dockerImage`                                                                                                                        | *string*                                                                                                                             | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `command`                                                                                                                            | *string*                                                                                                                             | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `env`                                                                                                                                | *string*                                                                                                                             | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `memoryReservation`                                                                                                                  | *string*                                                                                                                             | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `externalPort`                                                                                                                       | *number*                                                                                                                             | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `memoryLimit`                                                                                                                        | *string*                                                                                                                             | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `cpuReservation`                                                                                                                     | *string*                                                                                                                             | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `cpuLimit`                                                                                                                           | *string*                                                                                                                             | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `applicationStatus`                                                                                                                  | [operations.PostgresChangeStatusApplicationStatusResponse](../../models/operations/postgreschangestatusapplicationstatusresponse.md) | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `healthCheckSwarm`                                                                                                                   | [operations.PostgresChangeStatusHealthCheckSwarm](../../models/operations/postgreschangestatushealthcheckswarm.md)                   | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `restartPolicySwarm`                                                                                                                 | [operations.PostgresChangeStatusRestartPolicySwarm](../../models/operations/postgreschangestatusrestartpolicyswarm.md)               | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `placementSwarm`                                                                                                                     | [operations.PostgresChangeStatusPlacementSwarm](../../models/operations/postgreschangestatusplacementswarm.md)                       | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `updateConfigSwarm`                                                                                                                  | [operations.PostgresChangeStatusUpdateConfigSwarm](../../models/operations/postgreschangestatusupdateconfigswarm.md)                 | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `rollbackConfigSwarm`                                                                                                                | [operations.PostgresChangeStatusRollbackConfigSwarm](../../models/operations/postgreschangestatusrollbackconfigswarm.md)             | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `modeSwarm`                                                                                                                          | [operations.PostgresChangeStatusModeSwarm](../../models/operations/postgreschangestatusmodeswarm.md)                                 | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `labelsSwarm`                                                                                                                        | Record<string, *string*>                                                                                                             | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `networkSwarm`                                                                                                                       | [operations.PostgresChangeStatusNetworkSwarm](../../models/operations/postgreschangestatusnetworkswarm.md)[]                         | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `replicas`                                                                                                                           | *number*                                                                                                                             | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `createdAt`                                                                                                                          | *string*                                                                                                                             | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `environmentId`                                                                                                                      | *string*                                                                                                                             | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `serverId`                                                                                                                           | *string*                                                                                                                             | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `environment`                                                                                                                        | [operations.PostgresChangeStatusEnvironment](../../models/operations/postgreschangestatusenvironment.md)                             | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `mounts`                                                                                                                             | [operations.PostgresChangeStatusMount](../../models/operations/postgreschangestatusmount.md)[]                                       | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `server`                                                                                                                             | [operations.PostgresChangeStatusServer](../../models/operations/postgreschangestatusserver.md)                                       | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `backups`                                                                                                                            | [operations.PostgresChangeStatusBackup](../../models/operations/postgreschangestatusbackup.md)[]                                     | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
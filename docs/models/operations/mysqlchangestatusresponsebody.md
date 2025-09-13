# MysqlChangeStatusResponseBody

Successful response

## Example Usage

```typescript
import { MysqlChangeStatusResponseBody } from "dokploy-sdk/models/operations";

let value: MysqlChangeStatusResponseBody = {
  mysqlId: "<id>",
  name: "<value>",
  appName: "<value>",
  description: "impressive likewise upright hubris pish",
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
  externalPort: null,
  applicationStatus: "idle",
  healthCheckSwarm: {},
  restartPolicySwarm: {},
  placementSwarm: {},
  updateConfigSwarm: {
    parallelism: 9001.33,
    order: "<value>",
  },
  rollbackConfigSwarm: {
    parallelism: 8863.81,
    order: "<value>",
  },
  modeSwarm: {},
  labelsSwarm: {},
  networkSwarm: null,
  replicas: 1406.5,
  createdAt: "1725057734996",
  environmentId: "<id>",
  serverId: "<id>",
  environment: {
    environmentId: "<id>",
    name: "<value>",
    description: "emergent loaf immediately",
    createdAt: "1719638568650",
    env: "<value>",
    projectId: "<id>",
    project: {
      projectId: "<id>",
      name: "<value>",
      description:
        "but refine dampen violently casement for quarrel unlucky refine highly",
      createdAt: "1727451506644",
      organizationId: "<id>",
      env: "<value>",
    },
  },
  mounts: [
    {
      mountId: "<id>",
      type: "bind",
      hostPath: "<value>",
      volumeName: "<value>",
      filePath: null,
      content: "<value>",
      serviceType: "mariadb",
      mountPath: "<value>",
      applicationId: "<id>",
      postgresId: null,
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
    description: "psst noon sans wildly astride",
    ipAddress: "c18b:2e06:3605:b2ac:eb95:cb89:2dbe:20ad",
    port: 3999.4,
    username: "Oral_Jakubowski",
    appName: "<value>",
    enableDockerCleanup: true,
    createdAt: "1723653149901",
    organizationId: "<id>",
    serverStatus: "active",
    command: "<value>",
    sshKeyId: "<id>",
    metricsConfig: false,
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
      keepLatestCount: 9899.08,
      backupType: "compose",
      databaseType: "mariadb",
      composeId: null,
      postgresId: "<id>",
      mariadbId: "<id>",
      mysqlId: null,
      mongoId: "<id>",
      userId: "<id>",
    },
  ],
};
```

## Fields

| Field                                                                                                                          | Type                                                                                                                           | Required                                                                                                                       | Description                                                                                                                    |
| ------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------ |
| `mysqlId`                                                                                                                      | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `name`                                                                                                                         | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `appName`                                                                                                                      | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `description`                                                                                                                  | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `databaseName`                                                                                                                 | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `databaseUser`                                                                                                                 | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `databasePassword`                                                                                                             | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `databaseRootPassword`                                                                                                         | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `dockerImage`                                                                                                                  | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `command`                                                                                                                      | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `env`                                                                                                                          | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `memoryReservation`                                                                                                            | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `memoryLimit`                                                                                                                  | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `cpuReservation`                                                                                                               | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `cpuLimit`                                                                                                                     | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `externalPort`                                                                                                                 | *number*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `applicationStatus`                                                                                                            | [operations.MysqlChangeStatusApplicationStatusResponse](../../models/operations/mysqlchangestatusapplicationstatusresponse.md) | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `healthCheckSwarm`                                                                                                             | [operations.MysqlChangeStatusHealthCheckSwarm](../../models/operations/mysqlchangestatushealthcheckswarm.md)                   | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `restartPolicySwarm`                                                                                                           | [operations.MysqlChangeStatusRestartPolicySwarm](../../models/operations/mysqlchangestatusrestartpolicyswarm.md)               | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `placementSwarm`                                                                                                               | [operations.MysqlChangeStatusPlacementSwarm](../../models/operations/mysqlchangestatusplacementswarm.md)                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `updateConfigSwarm`                                                                                                            | [operations.MysqlChangeStatusUpdateConfigSwarm](../../models/operations/mysqlchangestatusupdateconfigswarm.md)                 | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `rollbackConfigSwarm`                                                                                                          | [operations.MysqlChangeStatusRollbackConfigSwarm](../../models/operations/mysqlchangestatusrollbackconfigswarm.md)             | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `modeSwarm`                                                                                                                    | [operations.MysqlChangeStatusModeSwarm](../../models/operations/mysqlchangestatusmodeswarm.md)                                 | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `labelsSwarm`                                                                                                                  | Record<string, *string*>                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `networkSwarm`                                                                                                                 | [operations.MysqlChangeStatusNetworkSwarm](../../models/operations/mysqlchangestatusnetworkswarm.md)[]                         | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `replicas`                                                                                                                     | *number*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `createdAt`                                                                                                                    | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `environmentId`                                                                                                                | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `serverId`                                                                                                                     | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `environment`                                                                                                                  | [operations.MysqlChangeStatusEnvironment](../../models/operations/mysqlchangestatusenvironment.md)                             | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `mounts`                                                                                                                       | [operations.MysqlChangeStatusMount](../../models/operations/mysqlchangestatusmount.md)[]                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `server`                                                                                                                       | [operations.MysqlChangeStatusServer](../../models/operations/mysqlchangestatusserver.md)                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `backups`                                                                                                                      | [operations.MysqlChangeStatusBackup](../../models/operations/mysqlchangestatusbackup.md)[]                                     | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
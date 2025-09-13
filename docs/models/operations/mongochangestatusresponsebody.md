# MongoChangeStatusResponseBody

Successful response

## Example Usage

```typescript
import { MongoChangeStatusResponseBody } from "dokploy-sdk/models/operations";

let value: MongoChangeStatusResponseBody = {
  mongoId: "<id>",
  name: "<value>",
  appName: "<value>",
  description: "times section case overstay",
  databaseUser: "<value>",
  databasePassword: "<value>",
  dockerImage: "<value>",
  command: "<value>",
  env: "<value>",
  memoryReservation: "<value>",
  memoryLimit: "<value>",
  cpuReservation: "<value>",
  cpuLimit: null,
  externalPort: 5166.96,
  applicationStatus: "done",
  healthCheckSwarm: {},
  restartPolicySwarm: {},
  placementSwarm: {},
  updateConfigSwarm: {
    parallelism: 5650.49,
    order: "<value>",
  },
  rollbackConfigSwarm: null,
  modeSwarm: {},
  labelsSwarm: {
    "key": "<value>",
    "key1": "<value>",
    "key2": "<value>",
  },
  networkSwarm: null,
  replicas: 8402.87,
  createdAt: "1708104569587",
  environmentId: "<id>",
  serverId: "<id>",
  replicaSets: true,
  environment: {
    environmentId: "<id>",
    name: "<value>",
    description: "ring aha as openly to dispose shinny",
    createdAt: "1711226127339",
    env: "<value>",
    projectId: "<id>",
    project: {
      projectId: "<id>",
      name: "<value>",
      description:
        "furthermore drat hmph boulevard shear loudly relieve unlike",
      createdAt: "1721693165698",
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
      filePath: "/usr/sbin/far_off.so",
      content: null,
      serviceType: "application",
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
    description: "at consequently before regarding bran rebel",
    ipAddress: "200.119.145.223",
    port: 5704.33,
    username: "Jaime_Mohr",
    appName: "<value>",
    enableDockerCleanup: true,
    createdAt: "1727917310222",
    organizationId: "<id>",
    serverStatus: "inactive",
    command: "<value>",
    sshKeyId: "<id>",
    metricsConfig: "<value>",
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
      keepLatestCount: 9227.88,
      backupType: "database",
      databaseType: "mariadb",
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

| Field                                                                                                                          | Type                                                                                                                           | Required                                                                                                                       | Description                                                                                                                    |
| ------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------ |
| `mongoId`                                                                                                                      | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `name`                                                                                                                         | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `appName`                                                                                                                      | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `description`                                                                                                                  | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `databaseUser`                                                                                                                 | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `databasePassword`                                                                                                             | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `dockerImage`                                                                                                                  | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `command`                                                                                                                      | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `env`                                                                                                                          | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `memoryReservation`                                                                                                            | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `memoryLimit`                                                                                                                  | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `cpuReservation`                                                                                                               | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `cpuLimit`                                                                                                                     | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `externalPort`                                                                                                                 | *number*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `applicationStatus`                                                                                                            | [operations.MongoChangeStatusApplicationStatusResponse](../../models/operations/mongochangestatusapplicationstatusresponse.md) | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `healthCheckSwarm`                                                                                                             | [operations.MongoChangeStatusHealthCheckSwarm](../../models/operations/mongochangestatushealthcheckswarm.md)                   | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `restartPolicySwarm`                                                                                                           | [operations.MongoChangeStatusRestartPolicySwarm](../../models/operations/mongochangestatusrestartpolicyswarm.md)               | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `placementSwarm`                                                                                                               | [operations.MongoChangeStatusPlacementSwarm](../../models/operations/mongochangestatusplacementswarm.md)                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `updateConfigSwarm`                                                                                                            | [operations.MongoChangeStatusUpdateConfigSwarm](../../models/operations/mongochangestatusupdateconfigswarm.md)                 | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `rollbackConfigSwarm`                                                                                                          | [operations.MongoChangeStatusRollbackConfigSwarm](../../models/operations/mongochangestatusrollbackconfigswarm.md)             | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `modeSwarm`                                                                                                                    | [operations.MongoChangeStatusModeSwarm](../../models/operations/mongochangestatusmodeswarm.md)                                 | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `labelsSwarm`                                                                                                                  | Record<string, *string*>                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `networkSwarm`                                                                                                                 | [operations.MongoChangeStatusNetworkSwarm](../../models/operations/mongochangestatusnetworkswarm.md)[]                         | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `replicas`                                                                                                                     | *number*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `createdAt`                                                                                                                    | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `environmentId`                                                                                                                | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `serverId`                                                                                                                     | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `replicaSets`                                                                                                                  | *boolean*                                                                                                                      | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `environment`                                                                                                                  | [operations.MongoChangeStatusEnvironment](../../models/operations/mongochangestatusenvironment.md)                             | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `mounts`                                                                                                                       | [operations.MongoChangeStatusMount](../../models/operations/mongochangestatusmount.md)[]                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `server`                                                                                                                       | [operations.MongoChangeStatusServer](../../models/operations/mongochangestatusserver.md)                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `backups`                                                                                                                      | [operations.MongoChangeStatusBackup](../../models/operations/mongochangestatusbackup.md)[]                                     | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
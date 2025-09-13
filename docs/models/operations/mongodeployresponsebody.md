# MongoDeployResponseBody

Successful response

## Example Usage

```typescript
import { MongoDeployResponseBody } from "dokploy-sdk/models/operations";

let value: MongoDeployResponseBody = {
  appName: "<value>",
  applicationStatus: "idle",
  backups: [
    {
      appName: "<value>",
      backupId: "<id>",
      backupType: "database",
      composeId: "<id>",
      database: "<value>",
      databaseType: "mongo",
      destinationId: "<id>",
      enabled: true,
      keepLatestCount: 9501.22,
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
  command: "<value>",
  cpuLimit: "<value>",
  cpuReservation: "<value>",
  createdAt: "1710352257027",
  databasePassword: "<value>",
  databaseUser: "<value>",
  description: "midwife whoever terraform trick resource cluttered",
  dockerImage: "<value>",
  env: "<value>",
  environment: {
    createdAt: "1724787539235",
    description: "advocate ick ack concerning",
    env: "<value>",
    environmentId: "<id>",
    name: "<value>",
    project: {
      createdAt: "1718805513776",
      description: "zowie gracefully nightlife by whereas queasily",
      env: "<value>",
      name: "<value>",
      organizationId: "<id>",
      projectId: "<id>",
    },
    projectId: "<id>",
  },
  environmentId: "<id>",
  externalPort: null,
  healthCheckSwarm: {},
  labelsSwarm: {
    "key": "<value>",
    "key1": "<value>",
  },
  memoryLimit: null,
  memoryReservation: "<value>",
  modeSwarm: {},
  mongoId: "<id>",
  mounts: [
    {
      applicationId: "<id>",
      composeId: "<id>",
      content: "<value>",
      filePath: null,
      hostPath: "<value>",
      mariadbId: "<id>",
      mongoId: null,
      mountId: "<id>",
      mountPath: "<value>",
      mysqlId: "<id>",
      postgresId: "<id>",
      redisId: "<id>",
      serviceType: "mariadb",
      type: "file",
      volumeName: "<value>",
    },
  ],
  name: "<value>",
  networkSwarm: [
    {},
  ],
  placementSwarm: {},
  replicaSets: null,
  replicas: 2374.3,
  restartPolicySwarm: {},
  rollbackConfigSwarm: {
    order: "<value>",
    parallelism: 4478.82,
  },
  server: {
    appName: "<value>",
    command: "<value>",
    createdAt: "1714328443045",
    description: "accurate mid heavily usually aha butter",
    enableDockerCleanup: true,
    ipAddress: "80.47.206.243",
    metricsConfig: "null",
    name: "<value>",
    organizationId: "<id>",
    port: 3587.65,
    serverId: "<id>",
    serverStatus: "inactive",
    sshKeyId: "<id>",
    username: "Naomie.Mayert77",
  },
  serverId: "<id>",
  updateConfigSwarm: {
    order: "<value>",
    parallelism: 9215,
  },
};
```

## Fields

| Field                                                                                                  | Type                                                                                                   | Required                                                                                               | Description                                                                                            |
| ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ |
| `appName`                                                                                              | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `applicationStatus`                                                                                    | [operations.MongoDeployApplicationStatus](../../models/operations/mongodeployapplicationstatus.md)     | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `backups`                                                                                              | [operations.MongoDeployBackup](../../models/operations/mongodeploybackup.md)[]                         | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `command`                                                                                              | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `cpuLimit`                                                                                             | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `cpuReservation`                                                                                       | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `createdAt`                                                                                            | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `databasePassword`                                                                                     | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `databaseUser`                                                                                         | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `description`                                                                                          | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `dockerImage`                                                                                          | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `env`                                                                                                  | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `environment`                                                                                          | [operations.MongoDeployEnvironment](../../models/operations/mongodeployenvironment.md)                 | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `environmentId`                                                                                        | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `externalPort`                                                                                         | *number*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `healthCheckSwarm`                                                                                     | [operations.MongoDeployHealthCheckSwarm](../../models/operations/mongodeployhealthcheckswarm.md)       | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `labelsSwarm`                                                                                          | Record<string, *string*>                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `memoryLimit`                                                                                          | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `memoryReservation`                                                                                    | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `modeSwarm`                                                                                            | [operations.MongoDeployModeSwarm](../../models/operations/mongodeploymodeswarm.md)                     | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `mongoId`                                                                                              | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `mounts`                                                                                               | [operations.MongoDeployMount](../../models/operations/mongodeploymount.md)[]                           | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `name`                                                                                                 | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `networkSwarm`                                                                                         | [operations.MongoDeployNetworkSwarm](../../models/operations/mongodeploynetworkswarm.md)[]             | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `placementSwarm`                                                                                       | [operations.MongoDeployPlacementSwarm](../../models/operations/mongodeployplacementswarm.md)           | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `replicaSets`                                                                                          | *boolean*                                                                                              | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `replicas`                                                                                             | *number*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `restartPolicySwarm`                                                                                   | [operations.MongoDeployRestartPolicySwarm](../../models/operations/mongodeployrestartpolicyswarm.md)   | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `rollbackConfigSwarm`                                                                                  | [operations.MongoDeployRollbackConfigSwarm](../../models/operations/mongodeployrollbackconfigswarm.md) | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `server`                                                                                               | [operations.MongoDeployServer](../../models/operations/mongodeployserver.md)                           | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `serverId`                                                                                             | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `updateConfigSwarm`                                                                                    | [operations.MongoDeployUpdateConfigSwarm](../../models/operations/mongodeployupdateconfigswarm.md)     | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
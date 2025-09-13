# PostgresDeployResponseBody

Successful response

## Example Usage

```typescript
import { PostgresDeployResponseBody } from "dokploy-sdk/models/operations";

let value: PostgresDeployResponseBody = {
  appName: "<value>",
  applicationStatus: "running",
  backups: [
    {
      appName: "<value>",
      backupId: "<id>",
      backupType: "database",
      composeId: "<id>",
      database: "<value>",
      databaseType: "mysql",
      destinationId: "<id>",
      enabled: true,
      keepLatestCount: 5679.37,
      mariadbId: "<id>",
      mongoId: "<id>",
      mysqlId: "<id>",
      postgresId: null,
      prefix: "<value>",
      schedule: "<value>",
      serviceName: "<value>",
      userId: "<id>",
    },
  ],
  command: "<value>",
  cpuLimit: "<value>",
  cpuReservation: "<value>",
  createdAt: "1730011592067",
  databaseName: "<value>",
  databasePassword: "<value>",
  databaseUser: "<value>",
  description: "for worth boohoo",
  dockerImage: "<value>",
  env: null,
  environment: {
    createdAt: "1706562213350",
    description: "as considerate ack",
    env: "<value>",
    environmentId: "<id>",
    name: "<value>",
    project: {
      createdAt: "1721924550637",
      description:
        "instantly reboot joyous opposite nor rural inasmuch comestible wherever bah",
      env: "<value>",
      name: "<value>",
      organizationId: "<id>",
      projectId: "<id>",
    },
    projectId: "<id>",
  },
  environmentId: "<id>",
  externalPort: 9351.3,
  healthCheckSwarm: {},
  labelsSwarm: {
    "key": "<value>",
    "key1": "<value>",
  },
  memoryLimit: "<value>",
  memoryReservation: "<value>",
  modeSwarm: {},
  mounts: [],
  name: "<value>",
  networkSwarm: [],
  placementSwarm: null,
  postgresId: "<id>",
  replicas: 4797.58,
  restartPolicySwarm: {},
  rollbackConfigSwarm: {
    order: "<value>",
    parallelism: 7110.21,
  },
  server: {
    appName: "<value>",
    command: "<value>",
    createdAt: "1721471978556",
    description: "honestly powerful geez shark toothbrush",
    enableDockerCleanup: true,
    ipAddress: "9241:64e3:7a2a:b4ba:0adb:eac6:3bbb:0e3d",
    metricsConfig: [
      "<value 1>",
      "<value 2>",
      "<value 3>",
    ],
    name: "<value>",
    organizationId: "<id>",
    port: 712.65,
    serverId: "<id>",
    serverStatus: "active",
    sshKeyId: "<id>",
    username: "Hyman75",
  },
  serverId: "<id>",
  updateConfigSwarm: {
    order: "<value>",
    parallelism: 4468.67,
  },
};
```

## Fields

| Field                                                                                                        | Type                                                                                                         | Required                                                                                                     | Description                                                                                                  |
| ------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------ |
| `appName`                                                                                                    | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `applicationStatus`                                                                                          | [operations.PostgresDeployApplicationStatus](../../models/operations/postgresdeployapplicationstatus.md)     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `backups`                                                                                                    | [operations.PostgresDeployBackup](../../models/operations/postgresdeploybackup.md)[]                         | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `command`                                                                                                    | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `cpuLimit`                                                                                                   | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `cpuReservation`                                                                                             | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `createdAt`                                                                                                  | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `databaseName`                                                                                               | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `databasePassword`                                                                                           | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `databaseUser`                                                                                               | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `description`                                                                                                | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `dockerImage`                                                                                                | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `env`                                                                                                        | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `environment`                                                                                                | [operations.PostgresDeployEnvironment](../../models/operations/postgresdeployenvironment.md)                 | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `environmentId`                                                                                              | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `externalPort`                                                                                               | *number*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `healthCheckSwarm`                                                                                           | [operations.PostgresDeployHealthCheckSwarm](../../models/operations/postgresdeployhealthcheckswarm.md)       | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `labelsSwarm`                                                                                                | Record<string, *string*>                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `memoryLimit`                                                                                                | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `memoryReservation`                                                                                          | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `modeSwarm`                                                                                                  | [operations.PostgresDeployModeSwarm](../../models/operations/postgresdeploymodeswarm.md)                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `mounts`                                                                                                     | [operations.PostgresDeployMount](../../models/operations/postgresdeploymount.md)[]                           | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `name`                                                                                                       | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `networkSwarm`                                                                                               | [operations.PostgresDeployNetworkSwarm](../../models/operations/postgresdeploynetworkswarm.md)[]             | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `placementSwarm`                                                                                             | [operations.PostgresDeployPlacementSwarm](../../models/operations/postgresdeployplacementswarm.md)           | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `postgresId`                                                                                                 | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `replicas`                                                                                                   | *number*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `restartPolicySwarm`                                                                                         | [operations.PostgresDeployRestartPolicySwarm](../../models/operations/postgresdeployrestartpolicyswarm.md)   | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `rollbackConfigSwarm`                                                                                        | [operations.PostgresDeployRollbackConfigSwarm](../../models/operations/postgresdeployrollbackconfigswarm.md) | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `server`                                                                                                     | [operations.PostgresDeployServer](../../models/operations/postgresdeployserver.md)                           | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `serverId`                                                                                                   | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `updateConfigSwarm`                                                                                          | [operations.PostgresDeployUpdateConfigSwarm](../../models/operations/postgresdeployupdateconfigswarm.md)     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
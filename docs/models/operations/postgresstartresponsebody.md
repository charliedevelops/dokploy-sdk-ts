# PostgresStartResponseBody

Successful response

## Example Usage

```typescript
import { PostgresStartResponseBody } from "dokploy-sdk/models/operations";

let value: PostgresStartResponseBody = {
  postgresId: "<id>",
  name: "<value>",
  appName: "<value>",
  databaseName: "<value>",
  databaseUser: "<value>",
  databasePassword: "<value>",
  description:
    "including incandescence all ouch hypothesise meh respectful who fisherman coal",
  dockerImage: "<value>",
  command: "<value>",
  env: "<value>",
  memoryReservation: "<value>",
  externalPort: 2539.32,
  memoryLimit: "<value>",
  cpuReservation: "<value>",
  cpuLimit: "<value>",
  applicationStatus: "running",
  healthCheckSwarm: null,
  restartPolicySwarm: null,
  placementSwarm: {},
  updateConfigSwarm: {
    parallelism: 9272,
    order: "<value>",
  },
  rollbackConfigSwarm: {
    parallelism: 1702.89,
    order: "<value>",
  },
  modeSwarm: null,
  labelsSwarm: {
    "key": "<value>",
    "key1": "<value>",
  },
  networkSwarm: [
    {},
  ],
  replicas: 2002.17,
  createdAt: "1722144452683",
  environmentId: "<id>",
  serverId: null,
  environment: {
    environmentId: "<id>",
    name: "<value>",
    description: "publicize expert humiliating",
    createdAt: "1719805395931",
    env: "<value>",
    projectId: "<id>",
    project: {
      projectId: "<id>",
      name: "<value>",
      description: "general unless striking unless ick",
      createdAt: "1707999818079",
      organizationId: "<id>",
      env: "<value>",
    },
  },
  mounts: [],
  server: {
    serverId: "<id>",
    name: "<value>",
    description: null,
    ipAddress: "197.88.211.12",
    port: 3622.44,
    username: "Sanford86",
    appName: "<value>",
    enableDockerCleanup: false,
    createdAt: "1718029108548",
    organizationId: "<id>",
    serverStatus: "inactive",
    command: "<value>",
    sshKeyId: "<id>",
    metricsConfig: {
      "key": "<value>",
      "key1": "<value>",
    },
  },
  backups: [
    {
      backupId: "<id>",
      appName: "<value>",
      schedule: "<value>",
      enabled: null,
      database: "<value>",
      prefix: "<value>",
      serviceName: "<value>",
      destinationId: "<id>",
      keepLatestCount: 9773.94,
      backupType: "database",
      databaseType: "postgres",
      composeId: null,
      postgresId: "<id>",
      mariadbId: "<id>",
      mysqlId: "<id>",
      mongoId: null,
      userId: null,
    },
  ],
};
```

## Fields

| Field                                                                                                      | Type                                                                                                       | Required                                                                                                   | Description                                                                                                |
| ---------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- |
| `postgresId`                                                                                               | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `name`                                                                                                     | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `appName`                                                                                                  | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `databaseName`                                                                                             | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `databaseUser`                                                                                             | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `databasePassword`                                                                                         | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `description`                                                                                              | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `dockerImage`                                                                                              | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `command`                                                                                                  | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `env`                                                                                                      | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `memoryReservation`                                                                                        | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `externalPort`                                                                                             | *number*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `memoryLimit`                                                                                              | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `cpuReservation`                                                                                           | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `cpuLimit`                                                                                                 | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `applicationStatus`                                                                                        | [operations.PostgresStartApplicationStatus](../../models/operations/postgresstartapplicationstatus.md)     | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `healthCheckSwarm`                                                                                         | [operations.PostgresStartHealthCheckSwarm](../../models/operations/postgresstarthealthcheckswarm.md)       | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `restartPolicySwarm`                                                                                       | [operations.PostgresStartRestartPolicySwarm](../../models/operations/postgresstartrestartpolicyswarm.md)   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `placementSwarm`                                                                                           | [operations.PostgresStartPlacementSwarm](../../models/operations/postgresstartplacementswarm.md)           | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `updateConfigSwarm`                                                                                        | [operations.PostgresStartUpdateConfigSwarm](../../models/operations/postgresstartupdateconfigswarm.md)     | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `rollbackConfigSwarm`                                                                                      | [operations.PostgresStartRollbackConfigSwarm](../../models/operations/postgresstartrollbackconfigswarm.md) | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `modeSwarm`                                                                                                | [operations.PostgresStartModeSwarm](../../models/operations/postgresstartmodeswarm.md)                     | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `labelsSwarm`                                                                                              | Record<string, *string*>                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `networkSwarm`                                                                                             | [operations.PostgresStartNetworkSwarm](../../models/operations/postgresstartnetworkswarm.md)[]             | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `replicas`                                                                                                 | *number*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `createdAt`                                                                                                | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `environmentId`                                                                                            | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `serverId`                                                                                                 | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `environment`                                                                                              | [operations.PostgresStartEnvironment](../../models/operations/postgresstartenvironment.md)                 | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `mounts`                                                                                                   | [operations.PostgresStartMount](../../models/operations/postgresstartmount.md)[]                           | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `server`                                                                                                   | [operations.PostgresStartServer](../../models/operations/postgresstartserver.md)                           | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `backups`                                                                                                  | [operations.PostgresStartBackup](../../models/operations/postgresstartbackup.md)[]                         | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
# PostgresStopResponseBody

Successful response

## Example Usage

```typescript
import { PostgresStopResponseBody } from "dokploy-sdk/models/operations";

let value: PostgresStopResponseBody = {
  postgresId: "<id>",
  name: "<value>",
  appName: "<value>",
  databaseName: "<value>",
  databaseUser: "<value>",
  databasePassword: "<value>",
  description: null,
  dockerImage: "<value>",
  command: "<value>",
  env: "<value>",
  memoryReservation: "<value>",
  externalPort: 483.68,
  memoryLimit: "<value>",
  cpuReservation: "<value>",
  cpuLimit: "<value>",
  applicationStatus: "error",
  healthCheckSwarm: {},
  restartPolicySwarm: {},
  placementSwarm: {},
  updateConfigSwarm: {
    parallelism: 3110.5,
    order: "<value>",
  },
  rollbackConfigSwarm: {
    parallelism: 4890.7,
    order: "<value>",
  },
  modeSwarm: {},
  labelsSwarm: {},
  networkSwarm: null,
  replicas: 4046.3,
  createdAt: "1724083716148",
  environmentId: "<id>",
  serverId: "<id>",
  environment: {
    environmentId: "<id>",
    name: "<value>",
    description: "so curry softly braid ick briskly wafer guilt",
    createdAt: "1712967784452",
    env: "<value>",
    projectId: "<id>",
    project: {
      projectId: "<id>",
      name: "<value>",
      description: "duh so now alongside",
      createdAt: "1719356730252",
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
      filePath: "/usr/onto.xlw",
      content: "<value>",
      serviceType: "mariadb",
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
      "coaxingly engage converse anesthetize fat lest bah hm elegantly rundown",
    ipAddress: "f3ff:eccc:76bd:b98f:8ac1:2cbf:32a3:bf38",
    port: 8223.18,
    username: "Berniece.McClure-Bartell",
    appName: "<value>",
    enableDockerCleanup: true,
    createdAt: "1729675297937",
    organizationId: "<id>",
    serverStatus: "active",
    command: "<value>",
    sshKeyId: "<id>",
    metricsConfig: [
      "<value 1>",
      "<value 2>",
      "<value 3>",
    ],
  },
  backups: [],
};
```

## Fields

| Field                                                                                                    | Type                                                                                                     | Required                                                                                                 | Description                                                                                              |
| -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- |
| `postgresId`                                                                                             | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `name`                                                                                                   | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `appName`                                                                                                | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `databaseName`                                                                                           | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `databaseUser`                                                                                           | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `databasePassword`                                                                                       | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `description`                                                                                            | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `dockerImage`                                                                                            | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `command`                                                                                                | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `env`                                                                                                    | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `memoryReservation`                                                                                      | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `externalPort`                                                                                           | *number*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `memoryLimit`                                                                                            | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `cpuReservation`                                                                                         | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `cpuLimit`                                                                                               | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `applicationStatus`                                                                                      | [operations.PostgresStopApplicationStatus](../../models/operations/postgresstopapplicationstatus.md)     | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `healthCheckSwarm`                                                                                       | [operations.PostgresStopHealthCheckSwarm](../../models/operations/postgresstophealthcheckswarm.md)       | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `restartPolicySwarm`                                                                                     | [operations.PostgresStopRestartPolicySwarm](../../models/operations/postgresstoprestartpolicyswarm.md)   | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `placementSwarm`                                                                                         | [operations.PostgresStopPlacementSwarm](../../models/operations/postgresstopplacementswarm.md)           | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `updateConfigSwarm`                                                                                      | [operations.PostgresStopUpdateConfigSwarm](../../models/operations/postgresstopupdateconfigswarm.md)     | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `rollbackConfigSwarm`                                                                                    | [operations.PostgresStopRollbackConfigSwarm](../../models/operations/postgresstoprollbackconfigswarm.md) | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `modeSwarm`                                                                                              | [operations.PostgresStopModeSwarm](../../models/operations/postgresstopmodeswarm.md)                     | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `labelsSwarm`                                                                                            | Record<string, *string*>                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `networkSwarm`                                                                                           | [operations.PostgresStopNetworkSwarm](../../models/operations/postgresstopnetworkswarm.md)[]             | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `replicas`                                                                                               | *number*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `createdAt`                                                                                              | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `environmentId`                                                                                          | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `serverId`                                                                                               | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `environment`                                                                                            | [operations.PostgresStopEnvironment](../../models/operations/postgresstopenvironment.md)                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `mounts`                                                                                                 | [operations.PostgresStopMount](../../models/operations/postgresstopmount.md)[]                           | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `server`                                                                                                 | [operations.PostgresStopServer](../../models/operations/postgresstopserver.md)                           | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `backups`                                                                                                | [operations.PostgresStopBackup](../../models/operations/postgresstopbackup.md)[]                         | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
# RedisStopResponseBody

Successful response

## Example Usage

```typescript
import { RedisStopResponseBody } from "dokploy-sdk/models/operations";

let value: RedisStopResponseBody = {
  redisId: "<id>",
  name: "<value>",
  appName: "<value>",
  description:
    "roundabout bonnet incidentally suburban inculcate precedent buzzing smarten mutate",
  databasePassword: "<value>",
  dockerImage: "<value>",
  command: null,
  env: "<value>",
  memoryReservation: "<value>",
  memoryLimit: "<value>",
  cpuReservation: "<value>",
  cpuLimit: "<value>",
  externalPort: 608.3,
  createdAt: "1730054913527",
  applicationStatus: "error",
  healthCheckSwarm: {},
  restartPolicySwarm: {},
  placementSwarm: {},
  updateConfigSwarm: {
    parallelism: 6282.54,
    order: "<value>",
  },
  rollbackConfigSwarm: null,
  modeSwarm: {},
  labelsSwarm: {},
  networkSwarm: [
    {},
  ],
  replicas: 3518.41,
  environmentId: "<id>",
  serverId: "<id>",
  environment: {
    environmentId: "<id>",
    name: "<value>",
    description: "before off violently eek below but",
    createdAt: "1713774346892",
    env: "<value>",
    projectId: "<id>",
    project: {
      projectId: "<id>",
      name: "<value>",
      description: null,
      createdAt: "1707226745819",
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
      filePath: "/Users/concerning_aha_following.mpeg",
      content: "<value>",
      serviceType: "postgres",
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
    description: "supposing indeed maroon advertisement onto whoa",
    ipAddress: "8fca:5b61:9327:9f4a:7bcd:0284:b9dc:0ddb",
    port: 2443.67,
    username: "Emilio_Little0",
    appName: "<value>",
    enableDockerCleanup: false,
    createdAt: "1734775806865",
    organizationId: "<id>",
    serverStatus: "active",
    command: "<value>",
    sshKeyId: "<id>",
    metricsConfig: {},
  },
};
```

## Fields

| Field                                                                                              | Type                                                                                               | Required                                                                                           | Description                                                                                        |
| -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| `redisId`                                                                                          | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `name`                                                                                             | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `appName`                                                                                          | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `description`                                                                                      | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `databasePassword`                                                                                 | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `dockerImage`                                                                                      | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `command`                                                                                          | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `env`                                                                                              | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `memoryReservation`                                                                                | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `memoryLimit`                                                                                      | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `cpuReservation`                                                                                   | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `cpuLimit`                                                                                         | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `externalPort`                                                                                     | *number*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `createdAt`                                                                                        | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `applicationStatus`                                                                                | [operations.RedisStopApplicationStatus](../../models/operations/redisstopapplicationstatus.md)     | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `healthCheckSwarm`                                                                                 | [operations.RedisStopHealthCheckSwarm](../../models/operations/redisstophealthcheckswarm.md)       | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `restartPolicySwarm`                                                                               | [operations.RedisStopRestartPolicySwarm](../../models/operations/redisstoprestartpolicyswarm.md)   | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `placementSwarm`                                                                                   | [operations.RedisStopPlacementSwarm](../../models/operations/redisstopplacementswarm.md)           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `updateConfigSwarm`                                                                                | [operations.RedisStopUpdateConfigSwarm](../../models/operations/redisstopupdateconfigswarm.md)     | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `rollbackConfigSwarm`                                                                              | [operations.RedisStopRollbackConfigSwarm](../../models/operations/redisstoprollbackconfigswarm.md) | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `modeSwarm`                                                                                        | [operations.RedisStopModeSwarm](../../models/operations/redisstopmodeswarm.md)                     | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `labelsSwarm`                                                                                      | Record<string, *string*>                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `networkSwarm`                                                                                     | [operations.RedisStopNetworkSwarm](../../models/operations/redisstopnetworkswarm.md)[]             | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `replicas`                                                                                         | *number*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `environmentId`                                                                                    | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `serverId`                                                                                         | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `environment`                                                                                      | [operations.RedisStopEnvironment](../../models/operations/redisstopenvironment.md)                 | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `mounts`                                                                                           | [operations.RedisStopMount](../../models/operations/redisstopmount.md)[]                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `server`                                                                                           | [operations.RedisStopServer](../../models/operations/redisstopserver.md)                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
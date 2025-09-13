# RedisStopResponseBody

Successful response

## Example Usage

```typescript
import { RedisStopResponseBody } from "dokploy-sdk/models/operations";

let value: RedisStopResponseBody = {
  appName: "<value>",
  applicationStatus: "error",
  command: "<value>",
  cpuLimit: "<value>",
  cpuReservation: "<value>",
  createdAt: "1711872914461",
  databasePassword: "<value>",
  description:
    "worth meaningfully without excluding reluctantly yahoo soon intermarry forenenst vastly",
  dockerImage: "<value>",
  env: "<value>",
  environment: {
    createdAt: "1712270541650",
    description: "geez merit behind",
    env: "<value>",
    environmentId: "<id>",
    name: "<value>",
    project: {
      createdAt: "1728026772012",
      description: "mmm vastly mid what depart oof reach",
      env: "<value>",
      name: "<value>",
      organizationId: "<id>",
      projectId: "<id>",
    },
    projectId: "<id>",
  },
  environmentId: "<id>",
  externalPort: 6242.3,
  healthCheckSwarm: {},
  labelsSwarm: {
    "key": "<value>",
    "key1": "<value>",
  },
  memoryLimit: "<value>",
  memoryReservation: null,
  modeSwarm: {},
  mounts: [
    {
      applicationId: "<id>",
      composeId: "<id>",
      content: null,
      filePath: null,
      hostPath: "<value>",
      mariadbId: "<id>",
      mongoId: "<id>",
      mountId: "<id>",
      mountPath: "<value>",
      mysqlId: null,
      postgresId: "<id>",
      redisId: "<id>",
      serviceType: "mariadb",
      type: "bind",
      volumeName: "<value>",
    },
  ],
  name: "<value>",
  networkSwarm: [
    {},
  ],
  placementSwarm: {},
  redisId: "<id>",
  replicas: 9682,
  restartPolicySwarm: {},
  rollbackConfigSwarm: {
    order: "<value>",
    parallelism: 7032.43,
  },
  server: {
    appName: "<value>",
    command: "<value>",
    createdAt: "1713774346892",
    description: "miserably straw mushy rich neglected",
    enableDockerCleanup: true,
    ipAddress: "d9f0:3f0b:d3bc:2747:0668:fbac:2df6:f04b",
    metricsConfig: [
      "<value 1>",
      "<value 2>",
    ],
    name: "<value>",
    organizationId: "<id>",
    port: 982.67,
    serverId: "<id>",
    serverStatus: "inactive",
    sshKeyId: "<id>",
    username: "Mable.Bradtke1",
  },
  serverId: "<id>",
  updateConfigSwarm: {
    order: "<value>",
    parallelism: 3720.92,
  },
};
```

## Fields

| Field                                                                                              | Type                                                                                               | Required                                                                                           | Description                                                                                        |
| -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| `appName`                                                                                          | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `applicationStatus`                                                                                | [operations.RedisStopApplicationStatus](../../models/operations/redisstopapplicationstatus.md)     | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `command`                                                                                          | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `cpuLimit`                                                                                         | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `cpuReservation`                                                                                   | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `createdAt`                                                                                        | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `databasePassword`                                                                                 | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `description`                                                                                      | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `dockerImage`                                                                                      | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `env`                                                                                              | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `environment`                                                                                      | [operations.RedisStopEnvironment](../../models/operations/redisstopenvironment.md)                 | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `environmentId`                                                                                    | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `externalPort`                                                                                     | *number*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `healthCheckSwarm`                                                                                 | [operations.RedisStopHealthCheckSwarm](../../models/operations/redisstophealthcheckswarm.md)       | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `labelsSwarm`                                                                                      | Record<string, *string*>                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `memoryLimit`                                                                                      | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `memoryReservation`                                                                                | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `modeSwarm`                                                                                        | [operations.RedisStopModeSwarm](../../models/operations/redisstopmodeswarm.md)                     | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `mounts`                                                                                           | [operations.RedisStopMount](../../models/operations/redisstopmount.md)[]                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `name`                                                                                             | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `networkSwarm`                                                                                     | [operations.RedisStopNetworkSwarm](../../models/operations/redisstopnetworkswarm.md)[]             | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `placementSwarm`                                                                                   | [operations.RedisStopPlacementSwarm](../../models/operations/redisstopplacementswarm.md)           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `redisId`                                                                                          | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `replicas`                                                                                         | *number*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `restartPolicySwarm`                                                                               | [operations.RedisStopRestartPolicySwarm](../../models/operations/redisstoprestartpolicyswarm.md)   | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `rollbackConfigSwarm`                                                                              | [operations.RedisStopRollbackConfigSwarm](../../models/operations/redisstoprollbackconfigswarm.md) | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `server`                                                                                           | [operations.RedisStopServer](../../models/operations/redisstopserver.md)                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `serverId`                                                                                         | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `updateConfigSwarm`                                                                                | [operations.RedisStopUpdateConfigSwarm](../../models/operations/redisstopupdateconfigswarm.md)     | :heavy_check_mark:                                                                                 | N/A                                                                                                |
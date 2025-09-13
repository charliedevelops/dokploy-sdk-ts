# RedisSaveExternalPortResponseBody

Successful response

## Example Usage

```typescript
import { RedisSaveExternalPortResponseBody } from "dokploy-sdk/models/operations";

let value: RedisSaveExternalPortResponseBody = {
  appName: "<value>",
  applicationStatus: "idle",
  command: "<value>",
  cpuLimit: "<value>",
  cpuReservation: "<value>",
  createdAt: "1715232661148",
  databasePassword: "<value>",
  description: null,
  dockerImage: "<value>",
  env: "<value>",
  environment: {
    createdAt: "1709861484506",
    description: "whose instead pendant hastily",
    env: "<value>",
    environmentId: "<id>",
    name: "<value>",
    project: {
      createdAt: "1708174808079",
      description: "agreeable scare violently why spew zowie than",
      env: "<value>",
      name: "<value>",
      organizationId: "<id>",
      projectId: "<id>",
    },
    projectId: "<id>",
  },
  environmentId: "<id>",
  externalPort: 3521.19,
  healthCheckSwarm: {},
  labelsSwarm: {
    "key": "<value>",
    "key1": "<value>",
    "key2": "<value>",
  },
  memoryLimit: "<value>",
  memoryReservation: "<value>",
  modeSwarm: {},
  mounts: [
    {
      applicationId: "<id>",
      composeId: "<id>",
      content: "<value>",
      filePath: "/proc/till.xlsx",
      hostPath: "<value>",
      mariadbId: "<id>",
      mongoId: "<id>",
      mountId: "<id>",
      mountPath: "<value>",
      mysqlId: "<id>",
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
  replicas: 7162.01,
  restartPolicySwarm: {},
  rollbackConfigSwarm: {
    order: "<value>",
    parallelism: 8916.82,
  },
  server: {
    appName: "<value>",
    command: "<value>",
    createdAt: "1713211255890",
    description:
      "spirited boyfriend avaricious nor skateboard depend hmph above",
    enableDockerCleanup: true,
    ipAddress: "ba02:4aed:ff9b:242c:5519:5696:cc0d:331f",
    metricsConfig: "<value>",
    name: "<value>",
    organizationId: "<id>",
    port: 8316.2,
    serverId: "<id>",
    serverStatus: "active",
    sshKeyId: "<id>",
    username: "Melany.Dibbert",
  },
  serverId: "<id>",
  updateConfigSwarm: {
    order: "<value>",
    parallelism: 4544.09,
  },
};
```

## Fields

| Field                                                                                                                      | Type                                                                                                                       | Required                                                                                                                   | Description                                                                                                                |
| -------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------- |
| `appName`                                                                                                                  | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `applicationStatus`                                                                                                        | [operations.RedisSaveExternalPortApplicationStatus](../../models/operations/redissaveexternalportapplicationstatus.md)     | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `command`                                                                                                                  | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `cpuLimit`                                                                                                                 | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `cpuReservation`                                                                                                           | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `createdAt`                                                                                                                | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `databasePassword`                                                                                                         | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `description`                                                                                                              | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `dockerImage`                                                                                                              | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `env`                                                                                                                      | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `environment`                                                                                                              | [operations.RedisSaveExternalPortEnvironment](../../models/operations/redissaveexternalportenvironment.md)                 | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `environmentId`                                                                                                            | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `externalPort`                                                                                                             | *number*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `healthCheckSwarm`                                                                                                         | [operations.RedisSaveExternalPortHealthCheckSwarm](../../models/operations/redissaveexternalporthealthcheckswarm.md)       | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `labelsSwarm`                                                                                                              | Record<string, *string*>                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `memoryLimit`                                                                                                              | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `memoryReservation`                                                                                                        | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `modeSwarm`                                                                                                                | [operations.RedisSaveExternalPortModeSwarm](../../models/operations/redissaveexternalportmodeswarm.md)                     | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `mounts`                                                                                                                   | [operations.RedisSaveExternalPortMount](../../models/operations/redissaveexternalportmount.md)[]                           | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `name`                                                                                                                     | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `networkSwarm`                                                                                                             | [operations.RedisSaveExternalPortNetworkSwarm](../../models/operations/redissaveexternalportnetworkswarm.md)[]             | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `placementSwarm`                                                                                                           | [operations.RedisSaveExternalPortPlacementSwarm](../../models/operations/redissaveexternalportplacementswarm.md)           | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `redisId`                                                                                                                  | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `replicas`                                                                                                                 | *number*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `restartPolicySwarm`                                                                                                       | [operations.RedisSaveExternalPortRestartPolicySwarm](../../models/operations/redissaveexternalportrestartpolicyswarm.md)   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `rollbackConfigSwarm`                                                                                                      | [operations.RedisSaveExternalPortRollbackConfigSwarm](../../models/operations/redissaveexternalportrollbackconfigswarm.md) | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `server`                                                                                                                   | [operations.RedisSaveExternalPortServer](../../models/operations/redissaveexternalportserver.md)                           | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `serverId`                                                                                                                 | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `updateConfigSwarm`                                                                                                        | [operations.RedisSaveExternalPortUpdateConfigSwarm](../../models/operations/redissaveexternalportupdateconfigswarm.md)     | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
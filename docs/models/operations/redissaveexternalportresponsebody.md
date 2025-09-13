# RedisSaveExternalPortResponseBody

Successful response

## Example Usage

```typescript
import { RedisSaveExternalPortResponseBody } from "dokploy-sdk/models/operations";

let value: RedisSaveExternalPortResponseBody = {
  redisId: "<id>",
  name: "<value>",
  appName: "<value>",
  description: "though sunder apparatus uh-huh crackle ah labourer nor by",
  databasePassword: "<value>",
  dockerImage: "<value>",
  command: "<value>",
  env: "<value>",
  memoryReservation: "<value>",
  memoryLimit: "<value>",
  cpuReservation: "<value>",
  cpuLimit: "<value>",
  externalPort: 2590.86,
  createdAt: "1726739702349",
  applicationStatus: "done",
  healthCheckSwarm: {},
  restartPolicySwarm: {},
  placementSwarm: {},
  updateConfigSwarm: {
    parallelism: 6216.91,
    order: "<value>",
  },
  rollbackConfigSwarm: {
    parallelism: 4794.25,
    order: "<value>",
  },
  modeSwarm: {},
  labelsSwarm: {
    "key": "<value>",
    "key1": "<value>",
  },
  networkSwarm: [
    {},
  ],
  replicas: 7859.88,
  environmentId: "<id>",
  serverId: "<id>",
  environment: {
    environmentId: "<id>",
    name: "<value>",
    description: "vanish cork jaywalk",
    createdAt: "1717328351480",
    env: "<value>",
    projectId: "<id>",
    project: {
      projectId: "<id>",
      name: "<value>",
      description: "weird via hence hence",
      createdAt: "1734882822266",
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
      filePath: null,
      content: null,
      serviceType: "compose",
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
    description: "above apud needily after wherever if apud yahoo formation",
    ipAddress: "1.185.136.58",
    port: 3995.55,
    username: "Haleigh_Kutch",
    appName: "<value>",
    enableDockerCleanup: false,
    createdAt: "1713457743805",
    organizationId: "<id>",
    serverStatus: "active",
    command: "<value>",
    sshKeyId: "<id>",
    metricsConfig: 8989.42,
  },
};
```

## Fields

| Field                                                                                                                      | Type                                                                                                                       | Required                                                                                                                   | Description                                                                                                                |
| -------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------- |
| `redisId`                                                                                                                  | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `name`                                                                                                                     | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `appName`                                                                                                                  | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `description`                                                                                                              | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `databasePassword`                                                                                                         | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `dockerImage`                                                                                                              | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `command`                                                                                                                  | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `env`                                                                                                                      | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `memoryReservation`                                                                                                        | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `memoryLimit`                                                                                                              | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `cpuReservation`                                                                                                           | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `cpuLimit`                                                                                                                 | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `externalPort`                                                                                                             | *number*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `createdAt`                                                                                                                | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `applicationStatus`                                                                                                        | [operations.RedisSaveExternalPortApplicationStatus](../../models/operations/redissaveexternalportapplicationstatus.md)     | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `healthCheckSwarm`                                                                                                         | [operations.RedisSaveExternalPortHealthCheckSwarm](../../models/operations/redissaveexternalporthealthcheckswarm.md)       | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `restartPolicySwarm`                                                                                                       | [operations.RedisSaveExternalPortRestartPolicySwarm](../../models/operations/redissaveexternalportrestartpolicyswarm.md)   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `placementSwarm`                                                                                                           | [operations.RedisSaveExternalPortPlacementSwarm](../../models/operations/redissaveexternalportplacementswarm.md)           | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `updateConfigSwarm`                                                                                                        | [operations.RedisSaveExternalPortUpdateConfigSwarm](../../models/operations/redissaveexternalportupdateconfigswarm.md)     | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `rollbackConfigSwarm`                                                                                                      | [operations.RedisSaveExternalPortRollbackConfigSwarm](../../models/operations/redissaveexternalportrollbackconfigswarm.md) | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `modeSwarm`                                                                                                                | [operations.RedisSaveExternalPortModeSwarm](../../models/operations/redissaveexternalportmodeswarm.md)                     | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `labelsSwarm`                                                                                                              | Record<string, *string*>                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `networkSwarm`                                                                                                             | [operations.RedisSaveExternalPortNetworkSwarm](../../models/operations/redissaveexternalportnetworkswarm.md)[]             | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `replicas`                                                                                                                 | *number*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `environmentId`                                                                                                            | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `serverId`                                                                                                                 | *string*                                                                                                                   | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `environment`                                                                                                              | [operations.RedisSaveExternalPortEnvironment](../../models/operations/redissaveexternalportenvironment.md)                 | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `mounts`                                                                                                                   | [operations.RedisSaveExternalPortMount](../../models/operations/redissaveexternalportmount.md)[]                           | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
| `server`                                                                                                                   | [operations.RedisSaveExternalPortServer](../../models/operations/redissaveexternalportserver.md)                           | :heavy_check_mark:                                                                                                         | N/A                                                                                                                        |
# RedisRemoveResponseBody

Successful response

## Example Usage

```typescript
import { RedisRemoveResponseBody } from "dokploy-sdk/models/operations";

let value: RedisRemoveResponseBody = {
  appName: "<value>",
  applicationStatus: "idle",
  command: "<value>",
  cpuLimit: "<value>",
  cpuReservation: null,
  createdAt: "1707741772574",
  databasePassword: "<value>",
  description: "juggernaut for early if ack that under interior interchange",
  dockerImage: "<value>",
  env: "<value>",
  environment: {
    createdAt: "1721819350670",
    description: "prudent meanwhile slipper dream upward vainly disk than",
    env: "<value>",
    environmentId: "<id>",
    name: "<value>",
    project: {
      createdAt: "1709314426668",
      description: "aha versus verbally oh augment whether",
      env: "<value>",
      name: "<value>",
      organizationId: "<id>",
      projectId: "<id>",
    },
    projectId: "<id>",
  },
  environmentId: "<id>",
  externalPort: 1290.77,
  healthCheckSwarm: {},
  labelsSwarm: null,
  memoryLimit: "<value>",
  memoryReservation: "<value>",
  modeSwarm: {},
  mounts: [
    {
      applicationId: null,
      composeId: "<id>",
      content: "<value>",
      filePath: "/usr/src/beyond_dual.rng",
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
  networkSwarm: [],
  placementSwarm: {},
  redisId: "<id>",
  replicas: 1045.07,
  restartPolicySwarm: {},
  rollbackConfigSwarm: {
    order: "<value>",
    parallelism: 195.11,
  },
  server: {
    appName: "<value>",
    command: "<value>",
    createdAt: "1730720308795",
    description: "aw including so unzip against officially character",
    enableDockerCleanup: true,
    ipAddress: "156.138.90.203",
    metricsConfig: [
      "<value 1>",
      "<value 2>",
    ],
    name: "<value>",
    organizationId: "<id>",
    port: 1877.22,
    serverId: "<id>",
    serverStatus: "active",
    sshKeyId: "<id>",
    username: "Gilbert18",
  },
  serverId: "<id>",
  updateConfigSwarm: {
    order: "<value>",
    parallelism: 3752.86,
  },
};
```

## Fields

| Field                                                                                                  | Type                                                                                                   | Required                                                                                               | Description                                                                                            |
| ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ |
| `appName`                                                                                              | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `applicationStatus`                                                                                    | [operations.RedisRemoveApplicationStatus](../../models/operations/redisremoveapplicationstatus.md)     | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `command`                                                                                              | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `cpuLimit`                                                                                             | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `cpuReservation`                                                                                       | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `createdAt`                                                                                            | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `databasePassword`                                                                                     | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `description`                                                                                          | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `dockerImage`                                                                                          | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `env`                                                                                                  | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `environment`                                                                                          | [operations.RedisRemoveEnvironment](../../models/operations/redisremoveenvironment.md)                 | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `environmentId`                                                                                        | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `externalPort`                                                                                         | *number*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `healthCheckSwarm`                                                                                     | [operations.RedisRemoveHealthCheckSwarm](../../models/operations/redisremovehealthcheckswarm.md)       | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `labelsSwarm`                                                                                          | Record<string, *string*>                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `memoryLimit`                                                                                          | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `memoryReservation`                                                                                    | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `modeSwarm`                                                                                            | [operations.RedisRemoveModeSwarm](../../models/operations/redisremovemodeswarm.md)                     | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `mounts`                                                                                               | [operations.RedisRemoveMount](../../models/operations/redisremovemount.md)[]                           | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `name`                                                                                                 | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `networkSwarm`                                                                                         | [operations.RedisRemoveNetworkSwarm](../../models/operations/redisremovenetworkswarm.md)[]             | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `placementSwarm`                                                                                       | [operations.RedisRemovePlacementSwarm](../../models/operations/redisremoveplacementswarm.md)           | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `redisId`                                                                                              | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `replicas`                                                                                             | *number*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `restartPolicySwarm`                                                                                   | [operations.RedisRemoveRestartPolicySwarm](../../models/operations/redisremoverestartpolicyswarm.md)   | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `rollbackConfigSwarm`                                                                                  | [operations.RedisRemoveRollbackConfigSwarm](../../models/operations/redisremoverollbackconfigswarm.md) | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `server`                                                                                               | [operations.RedisRemoveServer](../../models/operations/redisremoveserver.md)                           | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `serverId`                                                                                             | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `updateConfigSwarm`                                                                                    | [operations.RedisRemoveUpdateConfigSwarm](../../models/operations/redisremoveupdateconfigswarm.md)     | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
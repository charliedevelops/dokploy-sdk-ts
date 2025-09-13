# RedisStartResponseBody

Successful response

## Example Usage

```typescript
import { RedisStartResponseBody } from "dokploy-sdk/models/operations";

let value: RedisStartResponseBody = {
  redisId: "<id>",
  name: "<value>",
  appName: "<value>",
  description: "minister beside granular whereas ouch march",
  databasePassword: "<value>",
  dockerImage: "<value>",
  command: "<value>",
  env: "<value>",
  memoryReservation: "<value>",
  memoryLimit: "<value>",
  cpuReservation: "<value>",
  cpuLimit: "<value>",
  externalPort: 4777.66,
  createdAt: "1713690486298",
  applicationStatus: "done",
  healthCheckSwarm: {},
  restartPolicySwarm: {},
  placementSwarm: {},
  updateConfigSwarm: {
    parallelism: 5605.96,
    order: "<value>",
  },
  rollbackConfigSwarm: {
    parallelism: 3729.18,
    order: "<value>",
  },
  modeSwarm: {},
  labelsSwarm: {},
  networkSwarm: [
    {},
  ],
  replicas: 5492.89,
  environmentId: "<id>",
  serverId: "<id>",
  environment: {
    environmentId: "<id>",
    name: "<value>",
    description: "dampen terrible why prohibition gastropod notwithstanding",
    createdAt: "1714514882143",
    env: "<value>",
    projectId: "<id>",
    project: {
      projectId: "<id>",
      name: "<value>",
      description: "oil wisely on who",
      createdAt: "1734550191951",
      organizationId: "<id>",
      env: "<value>",
    },
  },
  mounts: [
    {
      mountId: "<id>",
      type: "file",
      hostPath: "<value>",
      volumeName: "<value>",
      filePath: "/opt/include/with.bz",
      content: "<value>",
      serviceType: "redis",
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
    description: null,
    ipAddress: "43.145.56.137",
    port: 6599.15,
    username: "Francis.Gulgowski76",
    appName: "<value>",
    enableDockerCleanup: true,
    createdAt: "1733493160142",
    organizationId: "<id>",
    serverStatus: "active",
    command: "<value>",
    sshKeyId: "<id>",
    metricsConfig: "null",
  },
};
```

## Fields

| Field                                                                                                | Type                                                                                                 | Required                                                                                             | Description                                                                                          |
| ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- |
| `redisId`                                                                                            | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `name`                                                                                               | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `appName`                                                                                            | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `description`                                                                                        | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `databasePassword`                                                                                   | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `dockerImage`                                                                                        | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `command`                                                                                            | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `env`                                                                                                | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `memoryReservation`                                                                                  | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `memoryLimit`                                                                                        | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `cpuReservation`                                                                                     | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `cpuLimit`                                                                                           | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `externalPort`                                                                                       | *number*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `createdAt`                                                                                          | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `applicationStatus`                                                                                  | [operations.RedisStartApplicationStatus](../../models/operations/redisstartapplicationstatus.md)     | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `healthCheckSwarm`                                                                                   | [operations.RedisStartHealthCheckSwarm](../../models/operations/redisstarthealthcheckswarm.md)       | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `restartPolicySwarm`                                                                                 | [operations.RedisStartRestartPolicySwarm](../../models/operations/redisstartrestartpolicyswarm.md)   | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `placementSwarm`                                                                                     | [operations.RedisStartPlacementSwarm](../../models/operations/redisstartplacementswarm.md)           | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `updateConfigSwarm`                                                                                  | [operations.RedisStartUpdateConfigSwarm](../../models/operations/redisstartupdateconfigswarm.md)     | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `rollbackConfigSwarm`                                                                                | [operations.RedisStartRollbackConfigSwarm](../../models/operations/redisstartrollbackconfigswarm.md) | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `modeSwarm`                                                                                          | [operations.RedisStartModeSwarm](../../models/operations/redisstartmodeswarm.md)                     | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `labelsSwarm`                                                                                        | Record<string, *string*>                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `networkSwarm`                                                                                       | [operations.RedisStartNetworkSwarm](../../models/operations/redisstartnetworkswarm.md)[]             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `replicas`                                                                                           | *number*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `environmentId`                                                                                      | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `serverId`                                                                                           | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `environment`                                                                                        | [operations.RedisStartEnvironment](../../models/operations/redisstartenvironment.md)                 | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `mounts`                                                                                             | [operations.RedisStartMount](../../models/operations/redisstartmount.md)[]                           | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `server`                                                                                             | [operations.RedisStartServer](../../models/operations/redisstartserver.md)                           | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
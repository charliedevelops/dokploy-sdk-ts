# RedisChangeStatusResponseBody

Successful response

## Example Usage

```typescript
import { RedisChangeStatusResponseBody } from "dokploy-sdk/models/operations";

let value: RedisChangeStatusResponseBody = {
  redisId: "<id>",
  name: "<value>",
  appName: "<value>",
  description: "blah dimly about",
  databasePassword: "<value>",
  dockerImage: "<value>",
  command: "<value>",
  env: "<value>",
  memoryReservation: "<value>",
  memoryLimit: "<value>",
  cpuReservation: "<value>",
  cpuLimit: "<value>",
  externalPort: 6782.01,
  createdAt: "1735298939676",
  applicationStatus: "idle",
  healthCheckSwarm: {},
  restartPolicySwarm: null,
  placementSwarm: {},
  updateConfigSwarm: null,
  rollbackConfigSwarm: {
    parallelism: 2498.44,
    order: "<value>",
  },
  modeSwarm: {},
  labelsSwarm: {
    "key": "<value>",
    "key1": "<value>",
  },
  networkSwarm: [],
  replicas: 4886.37,
  environmentId: "<id>",
  serverId: "<id>",
  environment: {
    environmentId: "<id>",
    name: "<value>",
    description: "inwardly yahoo exploration anti likewise suckle",
    createdAt: "1706813093953",
    env: "<value>",
    projectId: "<id>",
    project: {
      projectId: "<id>",
      name: "<value>",
      description: "suspiciously whoever publicity",
      createdAt: "1722511417122",
      organizationId: "<id>",
      env: "<value>",
    },
  },
  mounts: [],
  server: {
    serverId: "<id>",
    name: "<value>",
    description:
      "toward naturally about accidentally fall selfishly cantaloupe treble",
    ipAddress: "2c7d:9e55:eef9:fde8:2fcc:3dd2:f284:e48d",
    port: 4328.61,
    username: "Isai_Reinger",
    appName: "<value>",
    enableDockerCleanup: true,
    createdAt: "1711252328552",
    organizationId: "<id>",
    serverStatus: "inactive",
    command: "<value>",
    sshKeyId: "<id>",
    metricsConfig: "<value>",
  },
};
```

## Fields

| Field                                                                                                                          | Type                                                                                                                           | Required                                                                                                                       | Description                                                                                                                    |
| ------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------ |
| `redisId`                                                                                                                      | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `name`                                                                                                                         | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `appName`                                                                                                                      | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `description`                                                                                                                  | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `databasePassword`                                                                                                             | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `dockerImage`                                                                                                                  | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `command`                                                                                                                      | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `env`                                                                                                                          | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `memoryReservation`                                                                                                            | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `memoryLimit`                                                                                                                  | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `cpuReservation`                                                                                                               | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `cpuLimit`                                                                                                                     | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `externalPort`                                                                                                                 | *number*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `createdAt`                                                                                                                    | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `applicationStatus`                                                                                                            | [operations.RedisChangeStatusApplicationStatusResponse](../../models/operations/redischangestatusapplicationstatusresponse.md) | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `healthCheckSwarm`                                                                                                             | [operations.RedisChangeStatusHealthCheckSwarm](../../models/operations/redischangestatushealthcheckswarm.md)                   | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `restartPolicySwarm`                                                                                                           | [operations.RedisChangeStatusRestartPolicySwarm](../../models/operations/redischangestatusrestartpolicyswarm.md)               | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `placementSwarm`                                                                                                               | [operations.RedisChangeStatusPlacementSwarm](../../models/operations/redischangestatusplacementswarm.md)                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `updateConfigSwarm`                                                                                                            | [operations.RedisChangeStatusUpdateConfigSwarm](../../models/operations/redischangestatusupdateconfigswarm.md)                 | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `rollbackConfigSwarm`                                                                                                          | [operations.RedisChangeStatusRollbackConfigSwarm](../../models/operations/redischangestatusrollbackconfigswarm.md)             | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `modeSwarm`                                                                                                                    | [operations.RedisChangeStatusModeSwarm](../../models/operations/redischangestatusmodeswarm.md)                                 | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `labelsSwarm`                                                                                                                  | Record<string, *string*>                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `networkSwarm`                                                                                                                 | [operations.RedisChangeStatusNetworkSwarm](../../models/operations/redischangestatusnetworkswarm.md)[]                         | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `replicas`                                                                                                                     | *number*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `environmentId`                                                                                                                | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `serverId`                                                                                                                     | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `environment`                                                                                                                  | [operations.RedisChangeStatusEnvironment](../../models/operations/redischangestatusenvironment.md)                             | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `mounts`                                                                                                                       | [operations.RedisChangeStatusMount](../../models/operations/redischangestatusmount.md)[]                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `server`                                                                                                                       | [operations.RedisChangeStatusServer](../../models/operations/redischangestatusserver.md)                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
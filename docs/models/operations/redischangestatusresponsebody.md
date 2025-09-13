# RedisChangeStatusResponseBody

Successful response

## Example Usage

```typescript
import { RedisChangeStatusResponseBody } from "dokploy-sdk/models/operations";

let value: RedisChangeStatusResponseBody = {
  appName: "<value>",
  applicationStatus: "error",
  command: "<value>",
  cpuLimit: "<value>",
  cpuReservation: "<value>",
  createdAt: "1733791754204",
  databasePassword: "<value>",
  description: "um pfft aw as seldom yippee blindly challenge wholly",
  dockerImage: "<value>",
  env: "<value>",
  environment: {
    createdAt: "1731239099390",
    description: "entice precedent ha toward naturally",
    env: "<value>",
    environmentId: "<id>",
    name: "<value>",
    project: {
      createdAt: "1711251662146",
      description:
        "ouch ravioli mysteriously although upsell phooey mixture provided like",
      env: "<value>",
      name: "<value>",
      organizationId: "<id>",
      projectId: "<id>",
    },
    projectId: "<id>",
  },
  environmentId: "<id>",
  externalPort: 736.03,
  healthCheckSwarm: {},
  labelsSwarm: {
    "key": "<value>",
  },
  memoryLimit: "<value>",
  memoryReservation: null,
  modeSwarm: null,
  mounts: [],
  name: "<value>",
  networkSwarm: [],
  placementSwarm: null,
  redisId: "<id>",
  replicas: 1080.63,
  restartPolicySwarm: null,
  rollbackConfigSwarm: {
    order: "<value>",
    parallelism: 408.58,
  },
  server: {
    appName: "<value>",
    command: "<value>",
    createdAt: "1729570501316",
    description: "down hm like heartbeat",
    enableDockerCleanup: false,
    ipAddress: "66.171.163.253",
    metricsConfig: [
      "<value 1>",
      "<value 2>",
      "<value 3>",
    ],
    name: "<value>",
    organizationId: "<id>",
    port: 6074.59,
    serverId: "<id>",
    serverStatus: "inactive",
    sshKeyId: "<id>",
    username: "Brady15",
  },
  serverId: "<id>",
  updateConfigSwarm: {
    order: "<value>",
    parallelism: 9700.12,
  },
};
```

## Fields

| Field                                                                                                                          | Type                                                                                                                           | Required                                                                                                                       | Description                                                                                                                    |
| ------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------ |
| `appName`                                                                                                                      | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `applicationStatus`                                                                                                            | [operations.RedisChangeStatusApplicationStatusResponse](../../models/operations/redischangestatusapplicationstatusresponse.md) | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `command`                                                                                                                      | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `cpuLimit`                                                                                                                     | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `cpuReservation`                                                                                                               | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `createdAt`                                                                                                                    | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `databasePassword`                                                                                                             | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `description`                                                                                                                  | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `dockerImage`                                                                                                                  | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `env`                                                                                                                          | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `environment`                                                                                                                  | [operations.RedisChangeStatusEnvironment](../../models/operations/redischangestatusenvironment.md)                             | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `environmentId`                                                                                                                | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `externalPort`                                                                                                                 | *number*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `healthCheckSwarm`                                                                                                             | [operations.RedisChangeStatusHealthCheckSwarm](../../models/operations/redischangestatushealthcheckswarm.md)                   | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `labelsSwarm`                                                                                                                  | Record<string, *string*>                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `memoryLimit`                                                                                                                  | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `memoryReservation`                                                                                                            | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `modeSwarm`                                                                                                                    | [operations.RedisChangeStatusModeSwarm](../../models/operations/redischangestatusmodeswarm.md)                                 | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `mounts`                                                                                                                       | [operations.RedisChangeStatusMount](../../models/operations/redischangestatusmount.md)[]                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `name`                                                                                                                         | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `networkSwarm`                                                                                                                 | [operations.RedisChangeStatusNetworkSwarm](../../models/operations/redischangestatusnetworkswarm.md)[]                         | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `placementSwarm`                                                                                                               | [operations.RedisChangeStatusPlacementSwarm](../../models/operations/redischangestatusplacementswarm.md)                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `redisId`                                                                                                                      | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `replicas`                                                                                                                     | *number*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `restartPolicySwarm`                                                                                                           | [operations.RedisChangeStatusRestartPolicySwarm](../../models/operations/redischangestatusrestartpolicyswarm.md)               | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `rollbackConfigSwarm`                                                                                                          | [operations.RedisChangeStatusRollbackConfigSwarm](../../models/operations/redischangestatusrollbackconfigswarm.md)             | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `server`                                                                                                                       | [operations.RedisChangeStatusServer](../../models/operations/redischangestatusserver.md)                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `serverId`                                                                                                                     | *string*                                                                                                                       | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
| `updateConfigSwarm`                                                                                                            | [operations.RedisChangeStatusUpdateConfigSwarm](../../models/operations/redischangestatusupdateconfigswarm.md)                 | :heavy_check_mark:                                                                                                             | N/A                                                                                                                            |
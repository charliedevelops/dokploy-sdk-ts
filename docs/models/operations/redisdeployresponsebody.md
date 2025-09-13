# RedisDeployResponseBody

Successful response

## Example Usage

```typescript
import { RedisDeployResponseBody } from "dokploy-sdk/models/operations";

let value: RedisDeployResponseBody = {
  redisId: "<id>",
  name: "<value>",
  appName: "<value>",
  description:
    "consequently eek reassuringly yowza remark atop between next upright representation",
  databasePassword: "<value>",
  dockerImage: "<value>",
  command: "<value>",
  env: "<value>",
  memoryReservation: "<value>",
  memoryLimit: null,
  cpuReservation: "<value>",
  cpuLimit: "<value>",
  externalPort: 9007.04,
  createdAt: "1725244610171",
  applicationStatus: "error",
  healthCheckSwarm: {},
  restartPolicySwarm: null,
  placementSwarm: {},
  updateConfigSwarm: {
    parallelism: 524.62,
    order: "<value>",
  },
  rollbackConfigSwarm: null,
  modeSwarm: {},
  labelsSwarm: {},
  networkSwarm: [],
  replicas: 8186.42,
  environmentId: "<id>",
  serverId: null,
  environment: {
    environmentId: "<id>",
    name: "<value>",
    description: "obscure phooey apud where usable carelessly",
    createdAt: "1726364531617",
    env: "<value>",
    projectId: "<id>",
    project: {
      projectId: "<id>",
      name: "<value>",
      description: null,
      createdAt: "1732134708142",
      organizationId: "<id>",
      env: "<value>",
    },
  },
  mounts: [],
  server: null,
};
```

## Fields

| Field                                                                                                  | Type                                                                                                   | Required                                                                                               | Description                                                                                            |
| ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ |
| `redisId`                                                                                              | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `name`                                                                                                 | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `appName`                                                                                              | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `description`                                                                                          | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `databasePassword`                                                                                     | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `dockerImage`                                                                                          | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `command`                                                                                              | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `env`                                                                                                  | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `memoryReservation`                                                                                    | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `memoryLimit`                                                                                          | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `cpuReservation`                                                                                       | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `cpuLimit`                                                                                             | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `externalPort`                                                                                         | *number*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `createdAt`                                                                                            | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `applicationStatus`                                                                                    | [operations.RedisDeployApplicationStatus](../../models/operations/redisdeployapplicationstatus.md)     | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `healthCheckSwarm`                                                                                     | [operations.RedisDeployHealthCheckSwarm](../../models/operations/redisdeployhealthcheckswarm.md)       | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `restartPolicySwarm`                                                                                   | [operations.RedisDeployRestartPolicySwarm](../../models/operations/redisdeployrestartpolicyswarm.md)   | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `placementSwarm`                                                                                       | [operations.RedisDeployPlacementSwarm](../../models/operations/redisdeployplacementswarm.md)           | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `updateConfigSwarm`                                                                                    | [operations.RedisDeployUpdateConfigSwarm](../../models/operations/redisdeployupdateconfigswarm.md)     | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `rollbackConfigSwarm`                                                                                  | [operations.RedisDeployRollbackConfigSwarm](../../models/operations/redisdeployrollbackconfigswarm.md) | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `modeSwarm`                                                                                            | [operations.RedisDeployModeSwarm](../../models/operations/redisdeploymodeswarm.md)                     | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `labelsSwarm`                                                                                          | Record<string, *string*>                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `networkSwarm`                                                                                         | [operations.RedisDeployNetworkSwarm](../../models/operations/redisdeploynetworkswarm.md)[]             | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `replicas`                                                                                             | *number*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `environmentId`                                                                                        | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `serverId`                                                                                             | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `environment`                                                                                          | [operations.RedisDeployEnvironment](../../models/operations/redisdeployenvironment.md)                 | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `mounts`                                                                                               | [operations.RedisDeployMount](../../models/operations/redisdeploymount.md)[]                           | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `server`                                                                                               | [operations.RedisDeployServer](../../models/operations/redisdeployserver.md)                           | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
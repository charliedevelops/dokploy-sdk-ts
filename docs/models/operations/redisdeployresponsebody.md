# RedisDeployResponseBody

Successful response

## Example Usage

```typescript
import { RedisDeployResponseBody } from "dokploy-sdk/models/operations";

let value: RedisDeployResponseBody = {
  appName: "<value>",
  applicationStatus: "running",
  command: "<value>",
  cpuLimit: "<value>",
  cpuReservation: "<value>",
  createdAt: "1704359773679",
  databasePassword: "<value>",
  description: "pecan fragrant by ah",
  dockerImage: "<value>",
  env: "<value>",
  environment: {
    createdAt: "1726718685623",
    description: "and gee innovation about via",
    env: "<value>",
    environmentId: "<id>",
    name: "<value>",
    project: {
      createdAt: "1704531902593",
      description: "notwithstanding lend pish oh offensively gadzooks hover",
      env: "<value>",
      name: "<value>",
      organizationId: "<id>",
      projectId: "<id>",
    },
    projectId: "<id>",
  },
  environmentId: "<id>",
  externalPort: 798.68,
  healthCheckSwarm: {},
  labelsSwarm: {
    "key": "<value>",
    "key1": "<value>",
    "key2": "<value>",
  },
  memoryLimit: "<value>",
  memoryReservation: "<value>",
  modeSwarm: {},
  mounts: [],
  name: "<value>",
  networkSwarm: null,
  placementSwarm: {},
  redisId: "<id>",
  replicas: 2822.99,
  restartPolicySwarm: null,
  rollbackConfigSwarm: null,
  server: {
    appName: "<value>",
    command: "<value>",
    createdAt: "1735048015441",
    description: "across phew round topsail tensely really",
    enableDockerCleanup: true,
    ipAddress: "44.11.24.180",
    metricsConfig: "<value>",
    name: "<value>",
    organizationId: "<id>",
    port: 4715.65,
    serverId: "<id>",
    serverStatus: "active",
    sshKeyId: "<id>",
    username: "Janice15",
  },
  serverId: "<id>",
  updateConfigSwarm: null,
};
```

## Fields

| Field                                                                                                  | Type                                                                                                   | Required                                                                                               | Description                                                                                            |
| ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ |
| `appName`                                                                                              | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `applicationStatus`                                                                                    | [operations.RedisDeployApplicationStatus](../../models/operations/redisdeployapplicationstatus.md)     | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `command`                                                                                              | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `cpuLimit`                                                                                             | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `cpuReservation`                                                                                       | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `createdAt`                                                                                            | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `databasePassword`                                                                                     | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `description`                                                                                          | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `dockerImage`                                                                                          | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `env`                                                                                                  | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `environment`                                                                                          | [operations.RedisDeployEnvironment](../../models/operations/redisdeployenvironment.md)                 | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `environmentId`                                                                                        | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `externalPort`                                                                                         | *number*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `healthCheckSwarm`                                                                                     | [operations.RedisDeployHealthCheckSwarm](../../models/operations/redisdeployhealthcheckswarm.md)       | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `labelsSwarm`                                                                                          | Record<string, *string*>                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `memoryLimit`                                                                                          | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `memoryReservation`                                                                                    | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `modeSwarm`                                                                                            | [operations.RedisDeployModeSwarm](../../models/operations/redisdeploymodeswarm.md)                     | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `mounts`                                                                                               | [operations.RedisDeployMount](../../models/operations/redisdeploymount.md)[]                           | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `name`                                                                                                 | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `networkSwarm`                                                                                         | [operations.RedisDeployNetworkSwarm](../../models/operations/redisdeploynetworkswarm.md)[]             | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `placementSwarm`                                                                                       | [operations.RedisDeployPlacementSwarm](../../models/operations/redisdeployplacementswarm.md)           | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `redisId`                                                                                              | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `replicas`                                                                                             | *number*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `restartPolicySwarm`                                                                                   | [operations.RedisDeployRestartPolicySwarm](../../models/operations/redisdeployrestartpolicyswarm.md)   | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `rollbackConfigSwarm`                                                                                  | [operations.RedisDeployRollbackConfigSwarm](../../models/operations/redisdeployrollbackconfigswarm.md) | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `server`                                                                                               | [operations.RedisDeployServer](../../models/operations/redisdeployserver.md)                           | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `serverId`                                                                                             | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `updateConfigSwarm`                                                                                    | [operations.RedisDeployUpdateConfigSwarm](../../models/operations/redisdeployupdateconfigswarm.md)     | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
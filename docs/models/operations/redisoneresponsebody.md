# RedisOneResponseBody

Successful response

## Example Usage

```typescript
import { RedisOneResponseBody } from "dokploy-sdk/models/operations";

let value: RedisOneResponseBody = {
  appName: "<value>",
  applicationStatus: "done",
  command: null,
  cpuLimit: "<value>",
  cpuReservation: "<value>",
  createdAt: "1722629352316",
  databasePassword: "<value>",
  description: "huzzah ostrich hence strident drat blah as gadzooks",
  dockerImage: "<value>",
  env: "<value>",
  environment: {
    createdAt: "1732351168449",
    description: null,
    env: "<value>",
    environmentId: "<id>",
    name: "<value>",
    project: {
      createdAt: "1706582335848",
      description: "until shakily inasmuch",
      env: "<value>",
      name: "<value>",
      organizationId: "<id>",
      projectId: "<id>",
    },
    projectId: "<id>",
  },
  environmentId: "<id>",
  externalPort: 6065.08,
  healthCheckSwarm: {},
  labelsSwarm: {},
  memoryLimit: "<value>",
  memoryReservation: "<value>",
  modeSwarm: {},
  mounts: [],
  name: "<value>",
  networkSwarm: [
    {},
  ],
  placementSwarm: {},
  redisId: "<id>",
  replicas: 7322.05,
  restartPolicySwarm: null,
  rollbackConfigSwarm: {
    order: "<value>",
    parallelism: 9547.38,
  },
  server: {
    appName: "<value>",
    command: "<value>",
    createdAt: "1730885963301",
    description:
      "yahoo stir-fry swim puny miskey selfishly if finally floss mortar",
    enableDockerCleanup: false,
    ipAddress: "5aec:3e4b:7a1a:ff8e:4914:e4ec:444e:c5e2",
    metricsConfig: false,
    name: "<value>",
    organizationId: "<id>",
    port: 9099.9,
    serverId: "<id>",
    serverStatus: "inactive",
    sshKeyId: "<id>",
    username: "Richard.Davis25",
  },
  serverId: "<id>",
  updateConfigSwarm: null,
};
```

## Fields

| Field                                                                                            | Type                                                                                             | Required                                                                                         | Description                                                                                      |
| ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ |
| `appName`                                                                                        | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `applicationStatus`                                                                              | [operations.RedisOneApplicationStatus](../../models/operations/redisoneapplicationstatus.md)     | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `command`                                                                                        | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `cpuLimit`                                                                                       | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `cpuReservation`                                                                                 | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `createdAt`                                                                                      | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `databasePassword`                                                                               | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `description`                                                                                    | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `dockerImage`                                                                                    | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `env`                                                                                            | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `environment`                                                                                    | [operations.RedisOneEnvironment](../../models/operations/redisoneenvironment.md)                 | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `environmentId`                                                                                  | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `externalPort`                                                                                   | *number*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `healthCheckSwarm`                                                                               | [operations.RedisOneHealthCheckSwarm](../../models/operations/redisonehealthcheckswarm.md)       | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `labelsSwarm`                                                                                    | Record<string, *string*>                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `memoryLimit`                                                                                    | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `memoryReservation`                                                                              | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `modeSwarm`                                                                                      | [operations.RedisOneModeSwarm](../../models/operations/redisonemodeswarm.md)                     | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `mounts`                                                                                         | [operations.RedisOneMount](../../models/operations/redisonemount.md)[]                           | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `name`                                                                                           | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `networkSwarm`                                                                                   | [operations.RedisOneNetworkSwarm](../../models/operations/redisonenetworkswarm.md)[]             | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `placementSwarm`                                                                                 | [operations.RedisOnePlacementSwarm](../../models/operations/redisoneplacementswarm.md)           | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `redisId`                                                                                        | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `replicas`                                                                                       | *number*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `restartPolicySwarm`                                                                             | [operations.RedisOneRestartPolicySwarm](../../models/operations/redisonerestartpolicyswarm.md)   | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `rollbackConfigSwarm`                                                                            | [operations.RedisOneRollbackConfigSwarm](../../models/operations/redisonerollbackconfigswarm.md) | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `server`                                                                                         | [operations.RedisOneServer](../../models/operations/redisoneserver.md)                           | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `serverId`                                                                                       | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `updateConfigSwarm`                                                                              | [operations.RedisOneUpdateConfigSwarm](../../models/operations/redisoneupdateconfigswarm.md)     | :heavy_check_mark:                                                                               | N/A                                                                                              |
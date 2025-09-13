# RedisOneResponseBody

Successful response

## Example Usage

```typescript
import { RedisOneResponseBody } from "dokploy-sdk/models/operations";

let value: RedisOneResponseBody = {
  redisId: "<id>",
  name: "<value>",
  appName: "<value>",
  description: "talkative thread ascertain",
  databasePassword: "<value>",
  dockerImage: "<value>",
  command: "<value>",
  env: "<value>",
  memoryReservation: "<value>",
  memoryLimit: "<value>",
  cpuReservation: "<value>",
  cpuLimit: "<value>",
  externalPort: 4426.94,
  createdAt: "1716852383728",
  applicationStatus: "error",
  healthCheckSwarm: {},
  restartPolicySwarm: {},
  placementSwarm: {},
  updateConfigSwarm: {
    parallelism: 3302.65,
    order: "<value>",
  },
  rollbackConfigSwarm: {
    parallelism: 8452.26,
    order: "<value>",
  },
  modeSwarm: {},
  labelsSwarm: {},
  networkSwarm: [],
  replicas: 6002.92,
  environmentId: "<id>",
  serverId: "<id>",
  environment: {
    environmentId: "<id>",
    name: "<value>",
    description: "as gadzooks wheel",
    createdAt: "1705740838198",
    env: "<value>",
    projectId: "<id>",
    project: {
      projectId: "<id>",
      name: "<value>",
      description:
        "descent huzzah hmph yak absentmindedly frantically made-up dependency",
      createdAt: "1715523153298",
      organizationId: "<id>",
      env: "<value>",
    },
  },
  mounts: [],
  server: {
    serverId: "<id>",
    name: "<value>",
    description: "uproot narrow deduction since signature",
    ipAddress: "ebec:2eaf:ab19:3f44:f0c6:25d6:0e68:7c48",
    port: 8125.43,
    username: "Rory_Crooks",
    appName: "<value>",
    enableDockerCleanup: true,
    createdAt: "1726823976620",
    organizationId: "<id>",
    serverStatus: "inactive",
    command: "<value>",
    sshKeyId: "<id>",
    metricsConfig: [
      "<value 1>",
      "<value 2>",
    ],
  },
};
```

## Fields

| Field                                                                                            | Type                                                                                             | Required                                                                                         | Description                                                                                      |
| ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ |
| `redisId`                                                                                        | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `name`                                                                                           | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `appName`                                                                                        | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `description`                                                                                    | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `databasePassword`                                                                               | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `dockerImage`                                                                                    | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `command`                                                                                        | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `env`                                                                                            | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `memoryReservation`                                                                              | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `memoryLimit`                                                                                    | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `cpuReservation`                                                                                 | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `cpuLimit`                                                                                       | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `externalPort`                                                                                   | *number*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `createdAt`                                                                                      | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `applicationStatus`                                                                              | [operations.RedisOneApplicationStatus](../../models/operations/redisoneapplicationstatus.md)     | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `healthCheckSwarm`                                                                               | [operations.RedisOneHealthCheckSwarm](../../models/operations/redisonehealthcheckswarm.md)       | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `restartPolicySwarm`                                                                             | [operations.RedisOneRestartPolicySwarm](../../models/operations/redisonerestartpolicyswarm.md)   | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `placementSwarm`                                                                                 | [operations.RedisOnePlacementSwarm](../../models/operations/redisoneplacementswarm.md)           | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `updateConfigSwarm`                                                                              | [operations.RedisOneUpdateConfigSwarm](../../models/operations/redisoneupdateconfigswarm.md)     | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `rollbackConfigSwarm`                                                                            | [operations.RedisOneRollbackConfigSwarm](../../models/operations/redisonerollbackconfigswarm.md) | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `modeSwarm`                                                                                      | [operations.RedisOneModeSwarm](../../models/operations/redisonemodeswarm.md)                     | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `labelsSwarm`                                                                                    | Record<string, *string*>                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `networkSwarm`                                                                                   | [operations.RedisOneNetworkSwarm](../../models/operations/redisonenetworkswarm.md)[]             | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `replicas`                                                                                       | *number*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `environmentId`                                                                                  | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `serverId`                                                                                       | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `environment`                                                                                    | [operations.RedisOneEnvironment](../../models/operations/redisoneenvironment.md)                 | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `mounts`                                                                                         | [operations.RedisOneMount](../../models/operations/redisonemount.md)[]                           | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `server`                                                                                         | [operations.RedisOneServer](../../models/operations/redisoneserver.md)                           | :heavy_check_mark:                                                                               | N/A                                                                                              |
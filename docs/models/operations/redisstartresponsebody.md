# RedisStartResponseBody

Successful response

## Example Usage

```typescript
import { RedisStartResponseBody } from "dokploy-sdk/models/operations";

let value: RedisStartResponseBody = {
  appName: "<value>",
  applicationStatus: "idle",
  command: "<value>",
  cpuLimit: "<value>",
  cpuReservation: "<value>",
  createdAt: "1707837973085",
  databasePassword: "<value>",
  description: "along humidity hopeful hmph along who lumpy",
  dockerImage: "<value>",
  env: "<value>",
  environment: {
    createdAt: "1727685838588",
    description: "marathon notwithstanding untrue speedily",
    env: "<value>",
    environmentId: "<id>",
    name: "<value>",
    project: {
      createdAt: "1707095946259",
      description: "oof cap forenenst brightly bah um phooey",
      env: "<value>",
      name: "<value>",
      organizationId: "<id>",
      projectId: "<id>",
    },
    projectId: "<id>",
  },
  environmentId: "<id>",
  externalPort: null,
  healthCheckSwarm: {},
  labelsSwarm: {
    "key": "<value>",
    "key1": "<value>",
  },
  memoryLimit: "<value>",
  memoryReservation: "<value>",
  modeSwarm: {},
  mounts: [
    {
      applicationId: "<id>",
      composeId: "<id>",
      content: "<value>",
      filePath: "/etc/mail/imaginary_foretell.def",
      hostPath: "<value>",
      mariadbId: "<id>",
      mongoId: "<id>",
      mountId: "<id>",
      mountPath: "<value>",
      mysqlId: "<id>",
      postgresId: "<id>",
      redisId: "<id>",
      serviceType: "application",
      type: "file",
      volumeName: null,
    },
  ],
  name: "<value>",
  networkSwarm: [],
  placementSwarm: {},
  redisId: "<id>",
  replicas: 7467.68,
  restartPolicySwarm: {},
  rollbackConfigSwarm: {
    order: "<value>",
    parallelism: 5609.89,
  },
  server: {
    appName: "<value>",
    command: "<value>",
    createdAt: "1707003856544",
    description:
      "loyalty aside duh briskly burdensome kindly wallop during opposite finally",
    enableDockerCleanup: false,
    ipAddress: "232.229.76.214",
    metricsConfig: [],
    name: "<value>",
    organizationId: "<id>",
    port: 4013.85,
    serverId: "<id>",
    serverStatus: "active",
    sshKeyId: null,
    username: "Theo_Pollich3",
  },
  serverId: "<id>",
  updateConfigSwarm: {
    order: "<value>",
    parallelism: 232.7,
  },
};
```

## Fields

| Field                                                                                                | Type                                                                                                 | Required                                                                                             | Description                                                                                          |
| ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- |
| `appName`                                                                                            | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `applicationStatus`                                                                                  | [operations.RedisStartApplicationStatus](../../models/operations/redisstartapplicationstatus.md)     | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `command`                                                                                            | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `cpuLimit`                                                                                           | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `cpuReservation`                                                                                     | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `createdAt`                                                                                          | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `databasePassword`                                                                                   | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `description`                                                                                        | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `dockerImage`                                                                                        | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `env`                                                                                                | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `environment`                                                                                        | [operations.RedisStartEnvironment](../../models/operations/redisstartenvironment.md)                 | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `environmentId`                                                                                      | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `externalPort`                                                                                       | *number*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `healthCheckSwarm`                                                                                   | [operations.RedisStartHealthCheckSwarm](../../models/operations/redisstarthealthcheckswarm.md)       | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `labelsSwarm`                                                                                        | Record<string, *string*>                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `memoryLimit`                                                                                        | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `memoryReservation`                                                                                  | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `modeSwarm`                                                                                          | [operations.RedisStartModeSwarm](../../models/operations/redisstartmodeswarm.md)                     | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `mounts`                                                                                             | [operations.RedisStartMount](../../models/operations/redisstartmount.md)[]                           | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `name`                                                                                               | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `networkSwarm`                                                                                       | [operations.RedisStartNetworkSwarm](../../models/operations/redisstartnetworkswarm.md)[]             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `placementSwarm`                                                                                     | [operations.RedisStartPlacementSwarm](../../models/operations/redisstartplacementswarm.md)           | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `redisId`                                                                                            | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `replicas`                                                                                           | *number*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `restartPolicySwarm`                                                                                 | [operations.RedisStartRestartPolicySwarm](../../models/operations/redisstartrestartpolicyswarm.md)   | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `rollbackConfigSwarm`                                                                                | [operations.RedisStartRollbackConfigSwarm](../../models/operations/redisstartrollbackconfigswarm.md) | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `server`                                                                                             | [operations.RedisStartServer](../../models/operations/redisstartserver.md)                           | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `serverId`                                                                                           | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `updateConfigSwarm`                                                                                  | [operations.RedisStartUpdateConfigSwarm](../../models/operations/redisstartupdateconfigswarm.md)     | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
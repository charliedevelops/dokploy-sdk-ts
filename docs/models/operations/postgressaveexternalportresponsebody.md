# PostgresSaveExternalPortResponseBody

Successful response

## Example Usage

```typescript
import { PostgresSaveExternalPortResponseBody } from "dokploy-sdk/models/operations";

let value: PostgresSaveExternalPortResponseBody = {
  appName: "<value>",
  applicationStatus: "idle",
  backups: [],
  command: "<value>",
  cpuLimit: "<value>",
  cpuReservation: "<value>",
  createdAt: "1721946435707",
  databaseName: "<value>",
  databasePassword: "<value>",
  databaseUser: "<value>",
  description: "foretell minus ouch yieldingly apropos sew",
  dockerImage: "<value>",
  env: "<value>",
  environment: {
    createdAt: "1704274451432",
    description: "glider sore wound um aha whose",
    env: "<value>",
    environmentId: "<id>",
    name: "<value>",
    project: {
      createdAt: "1716042994530",
      description: "give consequently definite blah repeat ravioli inasmuch",
      env: "<value>",
      name: "<value>",
      organizationId: "<id>",
      projectId: "<id>",
    },
    projectId: "<id>",
  },
  environmentId: "<id>",
  externalPort: 632.07,
  healthCheckSwarm: {},
  labelsSwarm: {},
  memoryLimit: null,
  memoryReservation: "<value>",
  modeSwarm: {},
  mounts: [],
  name: "<value>",
  networkSwarm: [],
  placementSwarm: {},
  postgresId: "<id>",
  replicas: 1714.34,
  restartPolicySwarm: {},
  rollbackConfigSwarm: {
    order: "<value>",
    parallelism: 2523.34,
  },
  server: {
    appName: "<value>",
    command: "<value>",
    createdAt: "1728518850820",
    description: "smuggle er until snowplow futon splurge enormously",
    enableDockerCleanup: false,
    ipAddress: "71.224.4.67",
    metricsConfig: false,
    name: "<value>",
    organizationId: "<id>",
    port: 6462.58,
    serverId: "<id>",
    serverStatus: "inactive",
    sshKeyId: "<id>",
    username: "Noemi38",
  },
  serverId: "<id>",
  updateConfigSwarm: {
    order: "<value>",
    parallelism: 6376.42,
  },
};
```

## Fields

| Field                                                                                                                            | Type                                                                                                                             | Required                                                                                                                         | Description                                                                                                                      |
| -------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------- |
| `appName`                                                                                                                        | *string*                                                                                                                         | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `applicationStatus`                                                                                                              | [operations.PostgresSaveExternalPortApplicationStatus](../../models/operations/postgressaveexternalportapplicationstatus.md)     | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `backups`                                                                                                                        | [operations.PostgresSaveExternalPortBackup](../../models/operations/postgressaveexternalportbackup.md)[]                         | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `command`                                                                                                                        | *string*                                                                                                                         | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `cpuLimit`                                                                                                                       | *string*                                                                                                                         | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `cpuReservation`                                                                                                                 | *string*                                                                                                                         | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `createdAt`                                                                                                                      | *string*                                                                                                                         | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `databaseName`                                                                                                                   | *string*                                                                                                                         | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `databasePassword`                                                                                                               | *string*                                                                                                                         | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `databaseUser`                                                                                                                   | *string*                                                                                                                         | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `description`                                                                                                                    | *string*                                                                                                                         | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `dockerImage`                                                                                                                    | *string*                                                                                                                         | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `env`                                                                                                                            | *string*                                                                                                                         | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `environment`                                                                                                                    | [operations.PostgresSaveExternalPortEnvironment](../../models/operations/postgressaveexternalportenvironment.md)                 | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `environmentId`                                                                                                                  | *string*                                                                                                                         | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `externalPort`                                                                                                                   | *number*                                                                                                                         | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `healthCheckSwarm`                                                                                                               | [operations.PostgresSaveExternalPortHealthCheckSwarm](../../models/operations/postgressaveexternalporthealthcheckswarm.md)       | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `labelsSwarm`                                                                                                                    | Record<string, *string*>                                                                                                         | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `memoryLimit`                                                                                                                    | *string*                                                                                                                         | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `memoryReservation`                                                                                                              | *string*                                                                                                                         | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `modeSwarm`                                                                                                                      | [operations.PostgresSaveExternalPortModeSwarm](../../models/operations/postgressaveexternalportmodeswarm.md)                     | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `mounts`                                                                                                                         | [operations.PostgresSaveExternalPortMount](../../models/operations/postgressaveexternalportmount.md)[]                           | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `name`                                                                                                                           | *string*                                                                                                                         | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `networkSwarm`                                                                                                                   | [operations.PostgresSaveExternalPortNetworkSwarm](../../models/operations/postgressaveexternalportnetworkswarm.md)[]             | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `placementSwarm`                                                                                                                 | [operations.PostgresSaveExternalPortPlacementSwarm](../../models/operations/postgressaveexternalportplacementswarm.md)           | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `postgresId`                                                                                                                     | *string*                                                                                                                         | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `replicas`                                                                                                                       | *number*                                                                                                                         | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `restartPolicySwarm`                                                                                                             | [operations.PostgresSaveExternalPortRestartPolicySwarm](../../models/operations/postgressaveexternalportrestartpolicyswarm.md)   | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `rollbackConfigSwarm`                                                                                                            | [operations.PostgresSaveExternalPortRollbackConfigSwarm](../../models/operations/postgressaveexternalportrollbackconfigswarm.md) | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `server`                                                                                                                         | [operations.PostgresSaveExternalPortServer](../../models/operations/postgressaveexternalportserver.md)                           | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `serverId`                                                                                                                       | *string*                                                                                                                         | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `updateConfigSwarm`                                                                                                              | [operations.PostgresSaveExternalPortUpdateConfigSwarm](../../models/operations/postgressaveexternalportupdateconfigswarm.md)     | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
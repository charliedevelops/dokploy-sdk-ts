# PostgresSaveExternalPortResponseBody

Successful response

## Example Usage

```typescript
import { PostgresSaveExternalPortResponseBody } from "dokploy-sdk/models/operations";

let value: PostgresSaveExternalPortResponseBody = {
  postgresId: "<id>",
  name: "<value>",
  appName: "<value>",
  databaseName: "<value>",
  databaseUser: "<value>",
  databasePassword: "<value>",
  description: null,
  dockerImage: "<value>",
  command: "<value>",
  env: "<value>",
  memoryReservation: "<value>",
  externalPort: 5642.07,
  memoryLimit: "<value>",
  cpuReservation: "<value>",
  cpuLimit: "<value>",
  applicationStatus: "running",
  healthCheckSwarm: {},
  restartPolicySwarm: {},
  placementSwarm: {},
  updateConfigSwarm: {
    parallelism: 3478.67,
    order: "<value>",
  },
  rollbackConfigSwarm: {
    parallelism: 701.44,
    order: "<value>",
  },
  modeSwarm: {},
  labelsSwarm: {
    "key": "<value>",
    "key1": "<value>",
    "key2": "<value>",
  },
  networkSwarm: [
    {},
  ],
  replicas: 7212.36,
  createdAt: "1729282176993",
  environmentId: "<id>",
  serverId: "<id>",
  environment: {
    environmentId: "<id>",
    name: "<value>",
    description: "damaged duh randomize heavily",
    createdAt: "1734292314413",
    env: "<value>",
    projectId: "<id>",
    project: {
      projectId: "<id>",
      name: "<value>",
      description: "clamour aw yahoo including makeover until since adult",
      createdAt: "1734472000190",
      organizationId: "<id>",
      env: "<value>",
    },
  },
  mounts: [],
  server: {
    serverId: "<id>",
    name: "<value>",
    description: "stiff when heating as tightly yuck even parallel",
    ipAddress: "102.122.209.40",
    port: 3079.73,
    username: "Ricky0",
    appName: "<value>",
    enableDockerCleanup: false,
    createdAt: "1733356808635",
    organizationId: "<id>",
    serverStatus: "active",
    command: "<value>",
    sshKeyId: "<id>",
    metricsConfig: {
      "key": "<value>",
      "key1": "<value>",
    },
  },
  backups: [
    {
      backupId: "<id>",
      appName: "<value>",
      schedule: "<value>",
      enabled: false,
      database: "<value>",
      prefix: "<value>",
      serviceName: "<value>",
      destinationId: "<id>",
      keepLatestCount: null,
      backupType: "database",
      databaseType: "mysql",
      composeId: "<id>",
      postgresId: "<id>",
      mariadbId: "<id>",
      mysqlId: "<id>",
      mongoId: null,
      userId: "<id>",
    },
  ],
};
```

## Fields

| Field                                                                                                                            | Type                                                                                                                             | Required                                                                                                                         | Description                                                                                                                      |
| -------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------- |
| `postgresId`                                                                                                                     | *string*                                                                                                                         | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `name`                                                                                                                           | *string*                                                                                                                         | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `appName`                                                                                                                        | *string*                                                                                                                         | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `databaseName`                                                                                                                   | *string*                                                                                                                         | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `databaseUser`                                                                                                                   | *string*                                                                                                                         | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `databasePassword`                                                                                                               | *string*                                                                                                                         | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `description`                                                                                                                    | *string*                                                                                                                         | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `dockerImage`                                                                                                                    | *string*                                                                                                                         | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `command`                                                                                                                        | *string*                                                                                                                         | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `env`                                                                                                                            | *string*                                                                                                                         | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `memoryReservation`                                                                                                              | *string*                                                                                                                         | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `externalPort`                                                                                                                   | *number*                                                                                                                         | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `memoryLimit`                                                                                                                    | *string*                                                                                                                         | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `cpuReservation`                                                                                                                 | *string*                                                                                                                         | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `cpuLimit`                                                                                                                       | *string*                                                                                                                         | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `applicationStatus`                                                                                                              | [operations.PostgresSaveExternalPortApplicationStatus](../../models/operations/postgressaveexternalportapplicationstatus.md)     | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `healthCheckSwarm`                                                                                                               | [operations.PostgresSaveExternalPortHealthCheckSwarm](../../models/operations/postgressaveexternalporthealthcheckswarm.md)       | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `restartPolicySwarm`                                                                                                             | [operations.PostgresSaveExternalPortRestartPolicySwarm](../../models/operations/postgressaveexternalportrestartpolicyswarm.md)   | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `placementSwarm`                                                                                                                 | [operations.PostgresSaveExternalPortPlacementSwarm](../../models/operations/postgressaveexternalportplacementswarm.md)           | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `updateConfigSwarm`                                                                                                              | [operations.PostgresSaveExternalPortUpdateConfigSwarm](../../models/operations/postgressaveexternalportupdateconfigswarm.md)     | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `rollbackConfigSwarm`                                                                                                            | [operations.PostgresSaveExternalPortRollbackConfigSwarm](../../models/operations/postgressaveexternalportrollbackconfigswarm.md) | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `modeSwarm`                                                                                                                      | [operations.PostgresSaveExternalPortModeSwarm](../../models/operations/postgressaveexternalportmodeswarm.md)                     | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `labelsSwarm`                                                                                                                    | Record<string, *string*>                                                                                                         | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `networkSwarm`                                                                                                                   | [operations.PostgresSaveExternalPortNetworkSwarm](../../models/operations/postgressaveexternalportnetworkswarm.md)[]             | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `replicas`                                                                                                                       | *number*                                                                                                                         | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `createdAt`                                                                                                                      | *string*                                                                                                                         | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `environmentId`                                                                                                                  | *string*                                                                                                                         | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `serverId`                                                                                                                       | *string*                                                                                                                         | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `environment`                                                                                                                    | [operations.PostgresSaveExternalPortEnvironment](../../models/operations/postgressaveexternalportenvironment.md)                 | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `mounts`                                                                                                                         | [operations.PostgresSaveExternalPortMount](../../models/operations/postgressaveexternalportmount.md)[]                           | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `server`                                                                                                                         | [operations.PostgresSaveExternalPortServer](../../models/operations/postgressaveexternalportserver.md)                           | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `backups`                                                                                                                        | [operations.PostgresSaveExternalPortBackup](../../models/operations/postgressaveexternalportbackup.md)[]                         | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
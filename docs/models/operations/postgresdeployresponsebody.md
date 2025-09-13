# PostgresDeployResponseBody

Successful response

## Example Usage

```typescript
import { PostgresDeployResponseBody } from "dokploy-sdk/models/operations";

let value: PostgresDeployResponseBody = {
  postgresId: "<id>",
  name: "<value>",
  appName: "<value>",
  databaseName: "<value>",
  databaseUser: "<value>",
  databasePassword: "<value>",
  description:
    "midst shrilly barring lovingly yahoo bludgeon wonderfully sideboard",
  dockerImage: "<value>",
  command: "<value>",
  env: "<value>",
  memoryReservation: "<value>",
  externalPort: null,
  memoryLimit: "<value>",
  cpuReservation: null,
  cpuLimit: "<value>",
  applicationStatus: "done",
  healthCheckSwarm: {},
  restartPolicySwarm: {},
  placementSwarm: {},
  updateConfigSwarm: {
    parallelism: 5541.39,
    order: "<value>",
  },
  rollbackConfigSwarm: {
    parallelism: 7894.81,
    order: "<value>",
  },
  modeSwarm: {},
  labelsSwarm: {},
  networkSwarm: [],
  replicas: 604.49,
  createdAt: "1719283246632",
  environmentId: "<id>",
  serverId: "<id>",
  environment: {
    environmentId: "<id>",
    name: "<value>",
    description: "optimal er fully phew interestingly meanwhile even phew",
    createdAt: "1719461551088",
    env: "<value>",
    projectId: "<id>",
    project: {
      projectId: "<id>",
      name: "<value>",
      description:
        "patiently that in phew drat until great gripping regular nor",
      createdAt: "1735025392039",
      organizationId: "<id>",
      env: "<value>",
    },
  },
  mounts: [],
  server: {
    serverId: "<id>",
    name: "<value>",
    description: "inside saw gosh pish past fooey writhing",
    ipAddress: "110.100.41.238",
    port: 6540.94,
    username: "Betsy_Skiles9",
    appName: "<value>",
    enableDockerCleanup: true,
    createdAt: "1731191954944",
    organizationId: "<id>",
    serverStatus: "inactive",
    command: "<value>",
    sshKeyId: "<id>",
    metricsConfig: [
      "<value 1>",
      "<value 2>",
    ],
  },
  backups: [],
};
```

## Fields

| Field                                                                                                        | Type                                                                                                         | Required                                                                                                     | Description                                                                                                  |
| ------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------ |
| `postgresId`                                                                                                 | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `name`                                                                                                       | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `appName`                                                                                                    | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `databaseName`                                                                                               | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `databaseUser`                                                                                               | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `databasePassword`                                                                                           | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `description`                                                                                                | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `dockerImage`                                                                                                | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `command`                                                                                                    | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `env`                                                                                                        | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `memoryReservation`                                                                                          | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `externalPort`                                                                                               | *number*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `memoryLimit`                                                                                                | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `cpuReservation`                                                                                             | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `cpuLimit`                                                                                                   | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `applicationStatus`                                                                                          | [operations.PostgresDeployApplicationStatus](../../models/operations/postgresdeployapplicationstatus.md)     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `healthCheckSwarm`                                                                                           | [operations.PostgresDeployHealthCheckSwarm](../../models/operations/postgresdeployhealthcheckswarm.md)       | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `restartPolicySwarm`                                                                                         | [operations.PostgresDeployRestartPolicySwarm](../../models/operations/postgresdeployrestartpolicyswarm.md)   | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `placementSwarm`                                                                                             | [operations.PostgresDeployPlacementSwarm](../../models/operations/postgresdeployplacementswarm.md)           | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `updateConfigSwarm`                                                                                          | [operations.PostgresDeployUpdateConfigSwarm](../../models/operations/postgresdeployupdateconfigswarm.md)     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `rollbackConfigSwarm`                                                                                        | [operations.PostgresDeployRollbackConfigSwarm](../../models/operations/postgresdeployrollbackconfigswarm.md) | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `modeSwarm`                                                                                                  | [operations.PostgresDeployModeSwarm](../../models/operations/postgresdeploymodeswarm.md)                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `labelsSwarm`                                                                                                | Record<string, *string*>                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `networkSwarm`                                                                                               | [operations.PostgresDeployNetworkSwarm](../../models/operations/postgresdeploynetworkswarm.md)[]             | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `replicas`                                                                                                   | *number*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `createdAt`                                                                                                  | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `environmentId`                                                                                              | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `serverId`                                                                                                   | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `environment`                                                                                                | [operations.PostgresDeployEnvironment](../../models/operations/postgresdeployenvironment.md)                 | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `mounts`                                                                                                     | [operations.PostgresDeployMount](../../models/operations/postgresdeploymount.md)[]                           | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `server`                                                                                                     | [operations.PostgresDeployServer](../../models/operations/postgresdeployserver.md)                           | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `backups`                                                                                                    | [operations.PostgresDeployBackup](../../models/operations/postgresdeploybackup.md)[]                         | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
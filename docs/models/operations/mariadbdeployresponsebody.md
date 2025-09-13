# MariadbDeployResponseBody

Successful response

## Example Usage

```typescript
import { MariadbDeployResponseBody } from "dokploy-sdk/models/operations";

let value: MariadbDeployResponseBody = {
  mariadbId: "<id>",
  name: "<value>",
  appName: "<value>",
  description: "house why closely out if ack",
  databaseName: "<value>",
  databaseUser: "<value>",
  databasePassword: "<value>",
  databaseRootPassword: "<value>",
  dockerImage: "<value>",
  command: "<value>",
  env: "<value>",
  memoryReservation: "<value>",
  memoryLimit: null,
  cpuReservation: "<value>",
  cpuLimit: "<value>",
  externalPort: 3925.19,
  applicationStatus: "error",
  healthCheckSwarm: {},
  restartPolicySwarm: {},
  placementSwarm: {},
  updateConfigSwarm: {
    parallelism: 5377.72,
    order: "<value>",
  },
  rollbackConfigSwarm: {
    parallelism: 8194.78,
    order: "<value>",
  },
  modeSwarm: {},
  labelsSwarm: {
    "key": "<value>",
    "key1": "<value>",
  },
  networkSwarm: [
    {},
  ],
  replicas: 1568.18,
  createdAt: "1731063207077",
  environmentId: "<id>",
  serverId: "<id>",
  environment: {
    environmentId: "<id>",
    name: "<value>",
    description:
      "within precedent usually times complicated furthermore bakeware markup",
    createdAt: "1732027254082",
    env: "<value>",
    projectId: "<id>",
    project: {
      projectId: "<id>",
      name: "<value>",
      description:
        "deduct guzzle while homely up optimistically instead huzzah",
      createdAt: "1723177725048",
      organizationId: "<id>",
      env: "<value>",
    },
  },
  mounts: [],
  server: {
    serverId: "<id>",
    name: "<value>",
    description: "sardonic morbidity better",
    ipAddress: "252.220.254.88",
    port: 9463.94,
    username: "Mallory.Koepp48",
    appName: "<value>",
    enableDockerCleanup: false,
    createdAt: "1704892633937",
    organizationId: "<id>",
    serverStatus: "inactive",
    command: "<value>",
    sshKeyId: "<id>",
    metricsConfig: [
      "<value 1>",
      "<value 2>",
      "<value 3>",
    ],
  },
  backups: [],
};
```

## Fields

| Field                                                                                                      | Type                                                                                                       | Required                                                                                                   | Description                                                                                                |
| ---------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- |
| `mariadbId`                                                                                                | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `name`                                                                                                     | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `appName`                                                                                                  | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `description`                                                                                              | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `databaseName`                                                                                             | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `databaseUser`                                                                                             | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `databasePassword`                                                                                         | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `databaseRootPassword`                                                                                     | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `dockerImage`                                                                                              | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `command`                                                                                                  | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `env`                                                                                                      | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `memoryReservation`                                                                                        | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `memoryLimit`                                                                                              | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `cpuReservation`                                                                                           | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `cpuLimit`                                                                                                 | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `externalPort`                                                                                             | *number*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `applicationStatus`                                                                                        | [operations.MariadbDeployApplicationStatus](../../models/operations/mariadbdeployapplicationstatus.md)     | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `healthCheckSwarm`                                                                                         | [operations.MariadbDeployHealthCheckSwarm](../../models/operations/mariadbdeployhealthcheckswarm.md)       | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `restartPolicySwarm`                                                                                       | [operations.MariadbDeployRestartPolicySwarm](../../models/operations/mariadbdeployrestartpolicyswarm.md)   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `placementSwarm`                                                                                           | [operations.MariadbDeployPlacementSwarm](../../models/operations/mariadbdeployplacementswarm.md)           | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `updateConfigSwarm`                                                                                        | [operations.MariadbDeployUpdateConfigSwarm](../../models/operations/mariadbdeployupdateconfigswarm.md)     | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `rollbackConfigSwarm`                                                                                      | [operations.MariadbDeployRollbackConfigSwarm](../../models/operations/mariadbdeployrollbackconfigswarm.md) | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `modeSwarm`                                                                                                | [operations.MariadbDeployModeSwarm](../../models/operations/mariadbdeploymodeswarm.md)                     | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `labelsSwarm`                                                                                              | Record<string, *string*>                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `networkSwarm`                                                                                             | [operations.MariadbDeployNetworkSwarm](../../models/operations/mariadbdeploynetworkswarm.md)[]             | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `replicas`                                                                                                 | *number*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `createdAt`                                                                                                | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `environmentId`                                                                                            | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `serverId`                                                                                                 | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `environment`                                                                                              | [operations.MariadbDeployEnvironment](../../models/operations/mariadbdeployenvironment.md)                 | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `mounts`                                                                                                   | [operations.MariadbDeployMount](../../models/operations/mariadbdeploymount.md)[]                           | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `server`                                                                                                   | [operations.MariadbDeployServer](../../models/operations/mariadbdeployserver.md)                           | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `backups`                                                                                                  | [operations.MariadbDeployBackup](../../models/operations/mariadbdeploybackup.md)[]                         | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
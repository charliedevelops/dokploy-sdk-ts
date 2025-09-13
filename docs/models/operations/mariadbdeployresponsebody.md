# MariadbDeployResponseBody

Successful response

## Example Usage

```typescript
import { MariadbDeployResponseBody } from "dokploy-sdk/models/operations";

let value: MariadbDeployResponseBody = {
  appName: "<value>",
  applicationStatus: "idle",
  backups: [],
  command: "<value>",
  cpuLimit: "<value>",
  cpuReservation: "<value>",
  createdAt: "1713331361129",
  databaseName: "<value>",
  databasePassword: "<value>",
  databaseRootPassword: "<value>",
  databaseUser: "<value>",
  description: "along besides management fooey cease",
  dockerImage: "<value>",
  env: "<value>",
  environment: {
    createdAt: "1710520347234",
    description: "developing specific incidentally above er",
    env: "<value>",
    environmentId: "<id>",
    name: "<value>",
    project: {
      createdAt: "1726195672478",
      description: "hello institutionalize browse",
      env: "<value>",
      name: "<value>",
      organizationId: "<id>",
      projectId: "<id>",
    },
    projectId: "<id>",
  },
  environmentId: "<id>",
  externalPort: 6989.39,
  healthCheckSwarm: {},
  labelsSwarm: {
    "key": "<value>",
    "key1": "<value>",
    "key2": "<value>",
  },
  mariadbId: "<id>",
  memoryLimit: "<value>",
  memoryReservation: "<value>",
  modeSwarm: null,
  mounts: [
    {
      applicationId: "<id>",
      composeId: "<id>",
      content: "<value>",
      filePath: "/var/useless.dump",
      hostPath: "<value>",
      mariadbId: "<id>",
      mongoId: "<id>",
      mountId: "<id>",
      mountPath: "<value>",
      mysqlId: "<id>",
      postgresId: "<id>",
      redisId: "<id>",
      serviceType: "postgres",
      type: "file",
      volumeName: "<value>",
    },
  ],
  name: "<value>",
  networkSwarm: [],
  placementSwarm: {},
  replicas: 3196.93,
  restartPolicySwarm: null,
  rollbackConfigSwarm: {
    order: "<value>",
    parallelism: 4550.87,
  },
  server: {
    appName: "<value>",
    command: "<value>",
    createdAt: "1730684156671",
    description: null,
    enableDockerCleanup: true,
    ipAddress: "d4ba:2e67:fbbf:82ad:0fcc:5ae8:b14f:cf7e",
    metricsConfig: [
      "<value 1>",
      "<value 2>",
    ],
    name: "<value>",
    organizationId: "<id>",
    port: 4608.94,
    serverId: "<id>",
    serverStatus: "active",
    sshKeyId: "<id>",
    username: "Caroline_Bailey",
  },
  serverId: "<id>",
  updateConfigSwarm: {
    order: "<value>",
    parallelism: 3265.8,
  },
};
```

## Fields

| Field                                                                                                      | Type                                                                                                       | Required                                                                                                   | Description                                                                                                |
| ---------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- |
| `appName`                                                                                                  | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `applicationStatus`                                                                                        | [operations.MariadbDeployApplicationStatus](../../models/operations/mariadbdeployapplicationstatus.md)     | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `backups`                                                                                                  | [operations.MariadbDeployBackup](../../models/operations/mariadbdeploybackup.md)[]                         | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `command`                                                                                                  | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `cpuLimit`                                                                                                 | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `cpuReservation`                                                                                           | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `createdAt`                                                                                                | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `databaseName`                                                                                             | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `databasePassword`                                                                                         | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `databaseRootPassword`                                                                                     | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `databaseUser`                                                                                             | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `description`                                                                                              | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `dockerImage`                                                                                              | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `env`                                                                                                      | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `environment`                                                                                              | [operations.MariadbDeployEnvironment](../../models/operations/mariadbdeployenvironment.md)                 | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `environmentId`                                                                                            | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `externalPort`                                                                                             | *number*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `healthCheckSwarm`                                                                                         | [operations.MariadbDeployHealthCheckSwarm](../../models/operations/mariadbdeployhealthcheckswarm.md)       | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `labelsSwarm`                                                                                              | Record<string, *string*>                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `mariadbId`                                                                                                | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `memoryLimit`                                                                                              | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `memoryReservation`                                                                                        | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `modeSwarm`                                                                                                | [operations.MariadbDeployModeSwarm](../../models/operations/mariadbdeploymodeswarm.md)                     | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `mounts`                                                                                                   | [operations.MariadbDeployMount](../../models/operations/mariadbdeploymount.md)[]                           | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `name`                                                                                                     | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `networkSwarm`                                                                                             | [operations.MariadbDeployNetworkSwarm](../../models/operations/mariadbdeploynetworkswarm.md)[]             | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `placementSwarm`                                                                                           | [operations.MariadbDeployPlacementSwarm](../../models/operations/mariadbdeployplacementswarm.md)           | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `replicas`                                                                                                 | *number*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `restartPolicySwarm`                                                                                       | [operations.MariadbDeployRestartPolicySwarm](../../models/operations/mariadbdeployrestartpolicyswarm.md)   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `rollbackConfigSwarm`                                                                                      | [operations.MariadbDeployRollbackConfigSwarm](../../models/operations/mariadbdeployrollbackconfigswarm.md) | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `server`                                                                                                   | [operations.MariadbDeployServer](../../models/operations/mariadbdeployserver.md)                           | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `serverId`                                                                                                 | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `updateConfigSwarm`                                                                                        | [operations.MariadbDeployUpdateConfigSwarm](../../models/operations/mariadbdeployupdateconfigswarm.md)     | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
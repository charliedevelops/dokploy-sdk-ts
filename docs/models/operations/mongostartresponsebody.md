# MongoStartResponseBody

Successful response

## Example Usage

```typescript
import { MongoStartResponseBody } from "dokploy-sdk/models/operations";

let value: MongoStartResponseBody = {
  appName: "<value>",
  applicationStatus: "idle",
  backups: [],
  command: null,
  cpuLimit: "<value>",
  cpuReservation: "<value>",
  createdAt: "1719987306136",
  databasePassword: "<value>",
  databaseUser: "<value>",
  description: "good um furiously",
  dockerImage: "<value>",
  env: "<value>",
  environment: {
    createdAt: "1719004974024",
    description: "ah nutritious questionably",
    env: "<value>",
    environmentId: "<id>",
    name: "<value>",
    project: {
      createdAt: "1735427122788",
      description:
        "far-flung pish graduate begonia awful judicious leading pace upright",
      env: "<value>",
      name: "<value>",
      organizationId: "<id>",
      projectId: "<id>",
    },
    projectId: "<id>",
  },
  environmentId: "<id>",
  externalPort: 4047.5,
  healthCheckSwarm: null,
  labelsSwarm: {
    "key": "<value>",
    "key1": "<value>",
    "key2": "<value>",
  },
  memoryLimit: "<value>",
  memoryReservation: "<value>",
  modeSwarm: {},
  mongoId: "<id>",
  mounts: [
    {
      applicationId: "<id>",
      composeId: "<id>",
      content: "<value>",
      filePath: "/var/log/difficult.doc",
      hostPath: "<value>",
      mariadbId: "<id>",
      mongoId: null,
      mountId: "<id>",
      mountPath: "<value>",
      mysqlId: "<id>",
      postgresId: "<id>",
      redisId: "<id>",
      serviceType: "mysql",
      type: "bind",
      volumeName: "<value>",
    },
  ],
  name: "<value>",
  networkSwarm: [],
  placementSwarm: {},
  replicaSets: null,
  replicas: 1685.1,
  restartPolicySwarm: {},
  rollbackConfigSwarm: {
    order: "<value>",
    parallelism: 9294.51,
  },
  server: {
    appName: "<value>",
    command: "<value>",
    createdAt: "1725742705975",
    description: "internalize throbbing quantify wilderness shallow after",
    enableDockerCleanup: true,
    ipAddress: "35a4:11ae:cc85:4dfc:f90f:5794:c3dd:8ee6",
    metricsConfig: [],
    name: "<value>",
    organizationId: "<id>",
    port: 7111.3,
    serverId: "<id>",
    serverStatus: "inactive",
    sshKeyId: "<id>",
    username: "Minnie_Gislason24",
  },
  serverId: "<id>",
  updateConfigSwarm: {
    order: "<value>",
    parallelism: 8292.27,
  },
};
```

## Fields

| Field                                                                                                | Type                                                                                                 | Required                                                                                             | Description                                                                                          |
| ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- |
| `appName`                                                                                            | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `applicationStatus`                                                                                  | [operations.MongoStartApplicationStatus](../../models/operations/mongostartapplicationstatus.md)     | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `backups`                                                                                            | [operations.MongoStartBackup](../../models/operations/mongostartbackup.md)[]                         | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `command`                                                                                            | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `cpuLimit`                                                                                           | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `cpuReservation`                                                                                     | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `createdAt`                                                                                          | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `databasePassword`                                                                                   | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `databaseUser`                                                                                       | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `description`                                                                                        | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `dockerImage`                                                                                        | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `env`                                                                                                | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `environment`                                                                                        | [operations.MongoStartEnvironment](../../models/operations/mongostartenvironment.md)                 | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `environmentId`                                                                                      | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `externalPort`                                                                                       | *number*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `healthCheckSwarm`                                                                                   | [operations.MongoStartHealthCheckSwarm](../../models/operations/mongostarthealthcheckswarm.md)       | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `labelsSwarm`                                                                                        | Record<string, *string*>                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `memoryLimit`                                                                                        | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `memoryReservation`                                                                                  | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `modeSwarm`                                                                                          | [operations.MongoStartModeSwarm](../../models/operations/mongostartmodeswarm.md)                     | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `mongoId`                                                                                            | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `mounts`                                                                                             | [operations.MongoStartMount](../../models/operations/mongostartmount.md)[]                           | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `name`                                                                                               | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `networkSwarm`                                                                                       | [operations.MongoStartNetworkSwarm](../../models/operations/mongostartnetworkswarm.md)[]             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `placementSwarm`                                                                                     | [operations.MongoStartPlacementSwarm](../../models/operations/mongostartplacementswarm.md)           | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `replicaSets`                                                                                        | *boolean*                                                                                            | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `replicas`                                                                                           | *number*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `restartPolicySwarm`                                                                                 | [operations.MongoStartRestartPolicySwarm](../../models/operations/mongostartrestartpolicyswarm.md)   | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `rollbackConfigSwarm`                                                                                | [operations.MongoStartRollbackConfigSwarm](../../models/operations/mongostartrollbackconfigswarm.md) | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `server`                                                                                             | [operations.MongoStartServer](../../models/operations/mongostartserver.md)                           | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `serverId`                                                                                           | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `updateConfigSwarm`                                                                                  | [operations.MongoStartUpdateConfigSwarm](../../models/operations/mongostartupdateconfigswarm.md)     | :heavy_check_mark:                                                                                   | N/A                                                                                                  |